# Spark
Apache Spark es un motor de análisis unificado para el procesamiento de datos a gran escala.
## correr spark dentro de un contenedor de Docker

### Descargar la imagen
~~~
docker pull jupyter/all-spark-notebook
~~~
### Correr Spark con un notebook de jupyter dentro de un contenedor de docker
~~~
docker run -d -p 8888:8888 jupyter/all-spark-notebook start-notebook.sh --NotebookApp.token=''
~~~
