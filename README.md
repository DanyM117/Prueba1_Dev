# Prueba1_Dev
Repositorio para el ejercicio de prueba 1 de DevSecOps.

Aquí se hostea el codigo fuente para la primer prueba dev de los ejercicios.

Se utilizó docker y docker hub para la build de la imagen de la aplicación.

El repositorio publico en docker hub es: https://hub.docker.com/r/danym117/prueba1-dev

Se intuye que ya se tiene docker instalado en la maquina host.

# Instrucciones

Como el repositorio de docker hub es publico bastaría con ejecutar el siguiente comando en la terminal:

```docker run -p 8080:8080 danym117/prueba1-dev:latest```

Una vez hecho eso ya estaría corriendo el servidor nginx y el backend en un contenedor y podemos ver la respuesta ya sea visitando el link http://localhost:8080/ o con el comando ```curl http://localhost:8080/``` en una nueva terminal para ver el Hello World