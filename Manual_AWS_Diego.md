# Como realiza una instalacion instancia en AWS

Para poder crear una instancia en AWS, tendremos que acceder a la pagina de AWS,
una vez en la página principal, en el pequeño menu que nos aparece a la izquierda
buscaremos Contenidos.

![cap1](./imagenes/cap1.png)

Una vez dentro de Contenidos, nos apareceran varias opciones y buscaremos,
"Laboratorio para el alumnado de AWS Academy" que en este caso solo tendremos 
una opcion.

![cap2](./imagenes/cap2.png)

En esta pantalla, lo que tendremos que hacer sera simplemente en parte superior 
derecha "Start Lab" y esperaremos a que se ponga en verde el boton rojo que sale
en la parte central superior un poco a la izquierda.

![cap3](./imagenes/cap3.png)

Una vez en verde, haremos click encima AWS.

![cap4](./imagenes/cap4.png)

Una vez en la página de inicio de la consola, tendremos que acceder a EC2.

![cap5](./imagenes/cap5.png)

Cuando ya estemos dentro de EC2 en el listado en la parte izquierda de la pantalla
encontramos "Instancias", accederemos a ellas.

![cap6](./imagenes/cap6.png)

Para lanzar una instancia, deberemos de hacer click encima de lanzar instancia en
la parte superior derecha.

![cap7](./imagenes/cap7.png)

Tendreos que elegir un nombre para la instancia que vamos a crear a continuacion.

![cap8](./imagenes/cap7-8.png)

Seleccionaremos la opcion de Windows.

![cap9](./imagenes/cap8.png)

El tipo de instancia crearemos la medium, que tendremos más recursos para dicha instancia
pero nos costaria más.

![cap10](./imagenes/cap9.png)

Tendremos que crear un nuevo par de claves.

![cap11](./imagenes/cap10.png)

Seleccionamos el nombre de el par de claves, el tipo RSA, y en formato .pem

![cap12](./imagenes/cap11.png)

En configuraciones de red, en este caso la dejaremos en predeterminado.

![cap13](./imagenes/cap12.png)

Lo mismo con la configuracion de almacenamiento.

![cap14](./imagenes/cap13.png)

Lanzaremos la instancia, para finalizar el proceso.

![cap15](./imagenes/cap14.png)

Una vez creada la instancia, podremos ver que se ha creado pero no podremos acceder
a el ya que esta recien creada dicha instancia y nos tendremos que esperar un par
de minutos

![cap16](./imagenes/cap15.png)

Cuando pasan 2 minutos probamos a actualizar y podremos ver que ya esta disponible
para probar a conectarnos.

![cap17](./imagenes/cap16.png)

Para conectarnos seleccionamos la instancia a la que queremos conectarnos, y en la esquina 
superior derecha hacemos click encima de conectar.

![cap18](./imagenes/cap17.png)

Cuando nos conectamos a la instancia seleccionamos "Cliente de RDP".

![cap19](./imagenes/cap18.png)

Tendremos que descargar el archivo de escritorio remoto

![cap20](./imagenes/cap19.png)

Una vez descargado el escritorio remoto, tendremos que obtener la contraseña.

![cap21](./imagenes/cap20.png)

Tenemos que subir el archivo que se nos haya creado anteriormente cuando creamos
la contraseña para que se nos descifre y poder acceder a el escritorio remoto.

![cap22](./imagenes/cap21.png)

Intentaremos acceder a el escritorio remoto y pondremos la contraseña descifrada.

![cap23](./imagenes/cap22.png)

Nos saldria un aviso y lo aceptaremos.
Y ya podremos acceder finalmente a la instancia.

![cap24](./imagenes/cap23.png)
![cap25](./imagenes/cap24.png)
