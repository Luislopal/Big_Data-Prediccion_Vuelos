## Autores
 * Luis Alberto López Álvarez
 * Álvaro de Rojas Maraver

## Ficheros README
Existen 2 ficheros README incluidos en los directorios del proyecto, uno de ellos para el despliegue de la aplicación utilizando scripts de Python (sin contenedores) y el segundo de ellos para el despliegue de la misma utilizando Docker.

## Trabajo realizado
- Lograr el funcionamiento de la práctica sin realizar modificaciones.

## Mejoras realizadas
1. Entrenar el modelo con Apache Airflow y descripción de su arquitectura.
2. Ejecución del job de predicción con Spark Submit en vez de IntelliJ.
3. Automatización del despliegue del proyecto utilizando tecnologías vistas en clase como Vagrant que es empleado como IaaC proporcionando la imagen del sistema operativo y el aprovisionamiento base de la máquina virtual sobre la que se han desplegado todos los servicios descritos utilizando scripts de Python.

## Mejoras intentadas
1. Dockerizar cada uno de los servicios que componen la arquitectura completa. (mejora no operativa)
2. Desplegar el escenario completo usando Docker Compose. (mejora no operativa)
