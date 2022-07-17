Primero, hacemos un pull de las imagenes del ejercicio:

docker pull nicopaez/passwordapi-java:java8-alpine
docker pull nicopaez/passwordapi-java:java8-fabric.

Luego, ejecutamos el comando docker inspect [image_ID] para ver la cantidad y que layers esta utilizando la imagen.

Primero, vemos que java8-fabric cuenta con 9 layers mientras que java8-alpine cuenta con 4.
Comparando los SHA256, vemos que efectivamente comparten un layer. 
