<h1>eleccion de imagen</h1>

Conociendo ya que es un archivo yaml procedemos a elegir una imagen disponible en [Docker-Hub][1.1] que sera la que utilizaremos para nuestra base de datos, esta la agregaremos posterior mente a un archivo de configuracion yaml de Docker-Compose en un servidor.

En esta oportunidad utilizaremos como imagen [postgres][1.2].

<img src="img/img1.jpg" weith=100 heigth=100>

Donde se encuentra marcado es la instruccion para poder descargar la imagen en con ayuda de nuestro ejecutable.

<img src="img/img2.png " weith=100 heigth=100>

A continuacion le daremos un volumen a nuestra base de datos para que se guarden los datos que usaremos, y esto ayudara que aunque se nos elimine el contenedor los datos no se borraran puesto que quedan almacenados en una parte que nuestro disco duro.

Ya que tenemos nuestra imagen descargada, nos aseguramos que se este instalada correctamente, de la siguiente forma.

<img src="img/img3.png">



[1.1]:https://hub.docker.com/
[1.2]:https://hub.docker.com/_/postgres