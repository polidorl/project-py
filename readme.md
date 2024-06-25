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

Este proyecto se desarrolla en Python,se crea en un entorno local,
Se instalan dependencias con PIP,Python Install Package, gestor de paquetes estandar
para Python, se aislan proyectos en entornos virtuales evitando conflictos entre modulos y sus diferentes versiones.Cuando llevas el proyecto a produccion, a servidores en la nube, nos encontramos que debemos aislar la version de Python, por lo que el proyecto encapsula las aplicaciones en contenedores de Docker.

El desarrollo de este proyecto se lleva a cabo en Python, utilizando un entorno local. Para la gestión de las dependencias, se emplea PIP (Python Install Package). Esta herramienta permite instalar y administrar de forma eficiente las bibliotecas y herramientas necesarias para el proyecto, evitando conflictos entre módulos y sus diferentes versiones.

Adicionalmente, se implementa el uso de entornos virtuales para aislar cada proyecto, garantizando que las dependencias específicas de cada uno no interfieran entre sí.

Al momento de llevar el proyecto a un entorno de producción en servidores en la nube, surge la necesidad de aislar la versión de Python utilizada. Para ello, el proyecto encapsula las aplicaciones en contenedores Docker.

Esta encapsulación permite empaquetar la aplicación junto con todas sus dependencias en un entorno autosuficiente y portable, facilitando su implementación y distribución en diferentes entornos, asegurando que la versión de Python utilizada se mantenga constante y no dependa del entorno de ejecución.