# Game Project

Para correr el juego debes seguir las siguientes instrucciones en la terminal:
```sh
~/project-py
cd game
python3 main.py
```
# App Project

```sh
git clone
~/project-py
cd app
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```
Resumen del proyecto:

El desarrollo de este proyecto se lleva a cabo en Python, utilizando un entorno local. Para la gestión de las dependencias, se emplea PIP (Python Install Package). Esta herramienta permite instalar y administrar de forma eficiente las bibliotecas y herramientas necesarias para el proyecto, evitando conflictos entre módulos y sus diferentes versiones.

Adicionalmente, se implementa el uso de entornos virtuales para aislar cada proyecto, garantizando que las dependencias específicas de cada uno no interfieran entre sí.

Al momento de llevar el proyecto a un entorno de producción en servidores en la nube, surge la necesidad de aislar la versión de Python utilizada. Para ello, el proyecto encapsula las aplicaciones en contenedores Docker.

Esta encapsulación permite empaquetar la aplicación junto con todas sus dependencias en un entorno autosuficiente y portable, facilitando su implementación y distribución en diferentes entornos, asegurando que la versión de Python utilizada se mantenga constante y no dependa del entorno de ejecución.

Project summary:

The development of this project is carried out in Python, using a local environment. To manage dependencies, PIP (Python Install Package) is used. This tool allows you to efficiently install and manage the libraries and tools necessary for the project, avoiding conflicts between modules and their different versions.

Additionally, the use of virtual environments is implemented to isolate each project, guaranteeing that the specific dependencies of each one do not interfere with each other.

When bringing the project to a production environment on cloud servers, the need arises to isolate the version of Python used. To do this, the project encapsulates the applications in Docker containers.

This encapsulation allows the application to be packaged together with all its dependencies in a self-sufficient and portable environment, facilitating its implementation and distribution in different environments, ensuring that the version of Python used remains constant and does not depend on the execution environment.