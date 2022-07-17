Primeros hacemos un pull de la imagen oficial de nginx:
```
docker pull nginx
```

Luego ejecutamos:
```
docker run --name docker-nginx -p 80:80 -v ~/../../mnt/c/Users/Manuel/Desktop/docker/ejercicio1:/usr/share
/nginx/html -d nginx
```
