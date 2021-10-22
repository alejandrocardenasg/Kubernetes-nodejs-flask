# Kubernetes-nodejs-flask
Despliegue de Deployments y Services para las aplicaciones de NodeJS y Flask del proyecto "SISTEMA DE APOYO A LA EVALUACIÓN REMOTA DE FACTORES DE RIESGOS ERGONÓMICOS EN UN PUESTO DE OFICINA EN TELETRABAJO"

# Descripción

En este repositorio se implementan los archivos respectivos para implementar los deployments and service de las siguientes aplicaciones:
* https://github.com/alejandrocardenasg/Flask-api-procesamiento
* https://github.com/alejandrocardenasg/NodeJS-Application

Las imagenes respectivas se encuentran en el siguiente repositorio de DockerHub:
* https://hub.docker.com/repository/docker/cardenasgg/flask-api-processing
* https://hub.docker.com/repository/docker/cardenasgg/nodejs-gcp

Se debe implementar primeramente los deployments y servicios de FlaskAPP y obtener la IP del balanceador de carga asiganado para colocarlo de parámetro en las variables de entorno de la App de NodeJS.

# Autores

* Alejandro Cárdenas Galeano
* María Lucía Quintero Vidales
