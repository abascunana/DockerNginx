# DockerNginx

Para desplegar un contenedor en docker con html personalizado se inicia este comando que básicamente inicia un servidor de nginx en puerto 8080 le pone de nombre web y hace un volumen que enlaza el directorio del contenedor docker /usr/share/nginx/html y el directorio local /home/dam1/nginx (en mi caso).

![](images/image6.png)

En el directorio local tiene que haber el html personalizado con nombre de index.html.

![](images/image2.png)

Al iniciarlo se podrá ir a localhost:8080 y ver el resultado.

![](images/image1.png)

Se puede editar el archivo html y se verá reflejado en el servidor web

![](images/image4.png)

![](images/image7.png)

![](images/image5.png)

![](images/image3.png)
