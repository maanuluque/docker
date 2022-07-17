Primero, se crea el repositorio mediante el HUB de docker. En este caso, se crea con el nombre ejercicio 2 (mluquemeijide/ejercicio2)

Comandos ejecutados:
```
docker pull nicopaez/pingapp:3.0.0
docker login -u mluquemeijide --password-stdin
docker tag nicopaez/pingapp:3.0.0 mluquemeijide/ejercicio2
docker push mluquemeijide/ejercicio2
```
Para descargar la imagen:
```
docker pull mluquemeijide/ejercicio2
```
