# ArqCliente-Servidor
# README - Proyecto de Flask

Este es un proyecto de Flask que incluye pasos para configurar el entorno y ejecutar la aplicación. La aplicación utiliza una base de datos SQLite y consta de dos archivos principales: `create_db.py` y `main.py`.

## Requisitos previos

Asegúrate de tener Python instalado en tu sistema. Puedes descargar Python desde [python.org](https://www.python.org/downloads/).

## Instalación de Flask

Para ejecutar este proyecto, primero debes instalar Flask. Puedes hacerlo utilizando pip, el gestor de paquetes de Python. Abre una terminal y ejecuta el siguiente comando:

```bash
pip install Flask
```

## Creación de la base de datos

Antes de ejecutar la aplicación, necesitas crear la base de datos. Utiliza el script `create_db.py` para hacerlo. Abre una terminal en la carpeta del proyecto y ejecuta el siguiente comando:

```bash
python create_db.py
```

Esto creará una base de datos SQLite llamada `mydatabase.db` con las tablas necesarias para la aplicación.

## Ejecución de la aplicación

Una vez que la base de datos esté creada, puedes ejecutar la aplicación. Utiliza el archivo `main.py` para iniciar el servidor Flask. Ejecuta el siguiente comando en la terminal:

```bash
python main.py
```
