¿Cómo funciona docker?

`docekr run [OPCIONES] IMAGEN[:TAG|@DIGEST][COMANDO][ARGUMENTOS]`

Crear un contenedor

`docker container run --name my_container_name -v $(pwd):/usr/share/nginx/html -d -p 83:80 nginx:alpine`

pwd = working directory

-v: volumens

-d : run in background

-p : exposing a port

83:80 Puerto host machine : Puerto del contenedor
