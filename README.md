# moodle-rusben

El primer paso despues de descargar el moodle siguiendo el siguiente manual. (colocar manual rusben)

![Foto](1.png)

El siguiente paso es crear un directoria para guardar los datos del moodle.

![Foto](2.png)

Despues de eso nos aparecera una pantalla en la que deberemos darle a continuar.

![Foto](3.png)

Despues llegaremos a una pantalla en la que no podremos avanzar, para arreglarlo nos tenemos que meter en la termminal i entrar al directorio /etc/php/8.3/apache 2 i descargaremos nano php.ini

![Foto](4.png)

![Foto](5.png)

Una vez echo esto nos llevara al siguiente menu en el que tendremos que pulsar control W i buscar max_input_var.

![Foto](6.png)

Una vez echo eso hay que cambiar el 0 por 5001 i quitar las ; delante de "max" despues pulsamos control o i pulsamos enter.


![Foto](7.png)

ponemos el comando para reiniciar el apache.


