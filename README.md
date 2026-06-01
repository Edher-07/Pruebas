# Pruebas
Ejercicios de Aplicaciones Web con Python 3,SQLite3 y Web.py

# Demo_webapp
Pruebas y demostraciones 

## 1. Crear un entorno virtual
Crear el entorno virtual para la instalación de las librerías necesarias para el proyecto.

````shell
python3 -m venv .venv
````

## 2. Crear el archivo .gitignore
Cree el archivo **.gitignore** para configurar los recursos que no necesitamos que se sincronicen con el repositorio.

````shell
*.pyc
_pycache_/
.venv/
````

## 3. Activar el  vital environment
Activar el  **virtual environment** para realizar la instalación de las librerías necesarias

````shell
source .venv/bin/activate
````

## 4. Actualizar **PIP**
Actualizar el instalador de paquetes de Python **PIP**.

````shell
pip install --upgrade pip
````

## 5. Crear el archivo **runtime.txt**
Cree el archivo **runtime.txt** con la versión utilizada de python3.

````shell
python3 -V > runtime.txt
````

## 6. Instalar el micro-framework **web.py**
Instalar el micro-framework **web.py** en el ambiente virtual

````shell
pip install web.py
````

## 7. Crear el archivo **requirements.txt**
Cree el archivo **requirements.txt** con las versiones de las librerías instaladas en el ambiente virtual.

````shell
pip freeze > requirements.txt
````

## 8. Indexar el contenido del repositorio
Indexar todo el contenido del repositorio para incluir todos los archivos nuevos y las modificaciones al código.

````shell
git add .
````

## 9. Crear un **commit** o punto de control
Crear un punto de control (**commit**) con los cambios realizados al proyecto.

````shell
git commit -m "CREATED configuración del ambiente virtual"
````

## 10. Realizar un **push** hacía el repositorio 

Realizar un **push** hacía el repositorio para sincronizar  los cambios realizados en el proyecto.

````shell
git push -u origin main
````
