<img src=Img/logo.png width="150" height="100"> <h1> **Instalación Docker** </h1>
<h2> 
    Requisitos del sistema
</h2>

Para realizar la instalación, vamos a necesitar ya tener previamente insalado en nuestro SO Windows el servidor WSL 2 y aqui se necesitaran otros requisitos

* Windows 11 de 64 bits: Home o Pro versión 21H2 o superior, o Enterprise o Education versión 21H2 o superior.

* Windows 10 de 64 bits: Home o Pro 21H1 (compilación 19043) o superior, o Enterprise o Education 20H2 (compilación 19042) o superior.

* Habilite la función WSL 2 en Windows. Para obtener instrucciones detalladas, consulte la documentación de Microsoft .

* Se requieren los siguientes requisitos previos de hardware para ejecutar correctamente WSL 2 en Windows 10 o Windows 11:

    * Procesador de 64 bits con traducción de direcciones de segundo nivel (SLAT) 

    * RAM del sistema de 4GB

    * El soporte de virtualización de hardware a nivel de BIOS debe estar habilitado en la configuración del BIOS. Para obtener más información, consulte Virtualización .

    * Descargue e instale el paquete de actualización del kernel de Linux .

<body>
    <h2> 
     <p style="color:blue";>Install Docker Desktop on Windows</p>
    </h2>
    <h3>
     <p style="color:blue";>Instalación interactiva</p>
    </h3>

</body>
En este proceso de instalación vamos a realizarla interactivamente por medio del paso a paso que nos provee la interfaz del instalador de Docker; los pasos que seguiremos los revisaremos a continuación:

 * Para empezar con la instalación debemos decargar el [ejecutable de Docker][1.1] y abrimos:

    ![img1](Img/screen1.png)

* Para esta instalacion interactiva marcamos la casilla para que se pueda añadir un acceso directo al escritorio.
    ![img2](Img/screen2.png)

* En este momento empieza el unpacking file de Docker
    ![img3](Img/screen3.png)

* como se puede apreciar la instalacion tiene pocos pasos, y no se demora en desempaquetar los archivos de docker.

    le pide cerrar para completar completar la instalación. 
    ![img4](Img/screen4.png)

* teniendo en cuenta, la marca del check que hizo anteriormente, le queda anclado el acceso directo para poder abrirlo rapidamente
    ![img5](Img/screen5.jpg)

* se abrira una ventana en el navegador para loguearnos y poder autentificar la cuenta con el Docker que acabamos de instalar, si no tenemos una cuenta docker, damos clic en el boton para registrarnos ([sing in][1.2])
    ![img6](Img/screen6.png)

* Aqui crearemos nuestra cuenta docker para poder ingresar a la gran cadena de ventajas que nos brinda Docker
    ![imgn](Img/sceen.png)

* En este paso, simplemente tendras que clasificarte en el plan que deseas escoger, ya sea personal, profesional, Un quipo o de negocio.
![img8](Img/screen8.png)

* Finalmente, al momento de ejecutar el acceso directo de Docker Desktop accederemos a nuestra cuenta docker y podremos utilizar normalmente la herramienta. 
    ![img10](Img/screen10.png)

[1.1]:https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe

[1.2]:https://hub.docker.com/


# Mas recursos

* [Docker Documents][1.3]

[1.3]:https://docs.docker.com/desktop/install/windows-install/