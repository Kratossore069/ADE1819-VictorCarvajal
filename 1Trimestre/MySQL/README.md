# U1_A2 - Instalación de MySQL Server en Ubuntu

## 1.- Instalar MySQL Server desde el gestor de paquetes.

![](./img/img1.PNG)

> Es mejor primero actualizar antes de instalar el server.

![](./img/img1.PNG)

 > Procedemos a instalar el servidor.

 Reiniciamos la máquina para asegurar la instalación.

 ![](./img/img4.PNG)

 > Seguimos todos los pasos detallados en la última foto por si
 tuviéramos problemas a la hora de entrar.

![](./img/img5.PNG)

> Estos son los pasos que hay que seguir si no tenemos manera de entrar
con la contraseña del admin.

Vemos que podemos entrar, por lo que está instalado.

## 2.-Instalar MySQL Cliente desde el gestor de paquetes.

![](./img/img9.PNG)

## 3.- Indicar que versión estable instala desde el repositorio.

![](./img/img6.PNG)

## 4.- Reiniciar el demonio mysqld, que arranca el núcleo de SGBD. Probar que este corriendo el proceso con: ps aux | grep mysql.

![](./img/img7.PNG)

## 5.- Configuración de la seguridad post-instalación (ejecutar mysql_secure_installation)

![](./img/img8.PNG)

## 6.- Probar la conexión al servidor, utilizando el programa cliente mysql y con el usuario root

![](./img/img10.PNG)

## 7.- Instalar MYSQL Workbench

![](./img/img11.PNG)

## 8.- Instalar el PHPMYAdmin sobre Apache

Para ello primero debemos actualizar con **apt-get update**

![](./img/img18.PNG)

Luego instalamos el Apache.

![](./img/19.PNG)

Para saber que se ha instalado correctamente, accedemos a nuestro navegador y ponemos **localhost**

![](./img/img20.PNG)

Hecho todo esto, ya podemos instalar el phpmyadmin.

![](./img/img13.PNG)

![](./img/img14.PNG)

> Le damos que no porque vamos a configurarlo nosotros mismos.

![](./img/img21.PNG)

> Vemos que funciona.

## 9.- Además explicar lo siguiente, en base a la distribución linux instalada:

* Directorio de instalación base

![](./img/img15.PNG)

> Usando el comando **ps aux | grep mysql** podemos observar que el directorio es **/usr/sbin/mysqld**


* Directorio del servicio o proceso demonio

**/etc/init.d/mysql**

* Directorio de datos. Explicar lo que se encuentra en dicho directorio respecto a las bases de datos del servidor.

![](./img/img16.PNG)

**/var/lib/mysql**. En este directorio se almacenan todas las configuraciones de nuestro programa.

* Fichero de configuración del servidor y su ubicación.

![](./img/img17.PNG)

**/etc/mysql/my.cnf**

* ¿Quién es el usuario propietario de la instalación ?

**mysql**

* Aplicar el lenguaje de los mensajes de error  a español, modificando la configuración (indicar el directorio donde se aloja el fichero en español).

![](./img/img22.PNG)
