# Instrucciones para ejecutar este proyecto


Clonar el proyecto y cambiar de rama
git clone https://github.com/coder-live-class/django-coderhouse-project.git

cd django-coderhouse-project

git checkout class_21
Crear y activar entorno virtual (Windows)
C:\>python -m venv c:\ruta\al\entorno\virtual
C:\>c:\ruta\al\entorno\virtual\scripts\activate.bat
Crear y activar entorno virtual (Linux)
python3 -m venv venv
source venv/bin/activate
Instalar Django
pip install Django
Crear base de datos con los Modelos (hacer migraciones y migrar)
python manage.py makemigrations app_coder

python manage.py migrate
Crear super-usuario
python manage.py createsuperuser
Ejecutar proyecto
python manage.py runserver
