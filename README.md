# moodle-rusben

El primer paso despues de descargar el moodle siguiendo el siguiente manual. (colocar manual rusben)

![Foto](1.png)

El siguiente paso es crear un directorio para guardar los datos del moodle.

![Foto](2.png)

Despues de eso nos aparecera una pantalla en la que deberemos darle a continuar.

![Foto](3.png)

Despues llegaremos a una pantalla en la que no podremos avanzar, para arreglarlo nos tenemos que meter en la termminal i entrar al directorio /etc/php/8.3/apache 2 y escribiremos "nano php.ini"

![Foto](4.png)

![Foto](5.png)

Una vez echo esto nos llevara al siguiente menu en el que tendremos que pulsar control W i buscar max_input_var.

![Foto](6.png)

Una vez echo eso hay que cambiar el 0 por 5001 i quitar las ; delante de "max" despues pulsamos control o y pulsamos enter.


![Foto](7.png)

Ponemos el comando para reiniciar el apache.

![Foto](8.png)

Después de esto la instalacion ya estaria completada, simplemente tenemos que avanzar entre las diferentes panatallas que no apareceran rellenando los datos.


![Foto](9.png)

![Foto](10.png)

![Foto](11.png)

![Foto](12.png)

![Foto](13.png)

Hasta llegar a esta pantalla la cual es la ultima y significa que todo ha salido a la perfección.


![Foto](14.png)

## 1(A). Cambiar nombre, correo y avatar.

Para cambiar el nombre o cualquier cosa de nuestro perfil tenemos que darle al circulo de arriba a la izquierda darle a perfil i darle a editar hay se puede cambiar el correo electronico, el nombre, el avatar etc.  

![Foto](15.png)

![Foto](17.png)

![Foto](18.png)

![Foto](19.png)

## 1(B). Cambiar nombre del sitio.

Administración del sitio > ajustes de la pagina principal del sitio.

![Foto](20.png)

![Foto](21.png)

![Foto](22.png)

## 1(C). Franja horaria.

Administración del sitio > Ubicacion

![Foto](20.png)

![Foto](23.png)

## 1(D). Cambiar idioma.
Administración del sitio > idioma > ajustes de idioma
Para insttalar lo mismo pero en vez de entrar en ajustes hay que entrar en paquetes de idioma

![Foto](20.png)

![Foto](24.png)

![Foto](25.png)

![Foto](26.png)

## 1(E).Politica de contraseñas.
Administración del sitio > seguridad > politicas de seguridad del sitio

![Foto](20.png)

![Foto](27.png)

![Foto](28.png)

## 2.Crear cursos.

![Foto](29.png)

![Foto](30.png)

![Foto](31.png)

![Foto](32.png)

![Foto](33.png)


## 3.Modificar cursos.

![Foto](34.png)


## 4. creacion de usuarios

## (A) Crea manualment un usuari anomenat Bob que ha de fer servir el mètode d'autenticació manual

Administracion del sitio > cuentas > crear nuevo usuario 

![Foto](20.png)

![Foto](35.png)

![Foto](36.png)

![Foto](37.png)

![Foto](38.png)

## B) Genera deu alumnes que ho seran dels dos cursos A i B .

![Foto](39.png)

![Foto](40.png)

## (C) Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció

![Foto](41.png)


## 5. Ara matricula aquests usuaris als diferents cursos.
