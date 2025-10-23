[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/B_vZRp3W)
# Entrega 1: Fundamentos de Docker: Debian, Nginx y NextCloud

## Parte A

1. Instala docker en una máquina y configúralo para que se pueda usar con un usuario sin privilegios.
2. Ejecuta un contenedor a partir de la imagen `hello-word`. Comprueba que nos devuelve la salida adecuada. Comprueba que no se está ejecutando. Lista los contenedores que están parado. Borra el contenedor.
3. Crea un contenedor interactivo desde una imagen debian. Instala un paquete (por ejemplo `nano`). Sal de la terminal, ¿sigue el contenedor corriendo? ¿Por qué?. Vuelve a iniciar el contenedor y accede de nuevo a él de forma interactiva. ¿Sigue instalado el `nano`?. Sal del contenedor, y bórralo. Crea un nuevo contenedor interactivo desde la misma imagen. ¿Tiene el `nano` instalado?
4. Crea un contenedor demonio con un servidor nginx, usando la imagen oficial de nginx. Al crear el contenedor, ¿has tenido que indicar algún comando para que lo ejecute? Accede al navegador web y comprueba que el servidor esta funcionando. Muestra los logs del contenedor.
5. Crea un contenedor con la aplicación Nextcloud, mirando la [documentación en docker Hub](https://hub.docker.com/_/nextcloud), para personalizar el nombre de la base de datos sqlite que va a utilizar.

Sube y documenta, sin abusar de las IAs, en este mismo repositorio los pantallazos que consideres relevantes en cada uno de los cinco puntos anteriores.

## Parte B

Vamos a entregar el ejercicio 4 con algunas modificaciones. Crearemos un contenedor demonio a partir de la imagen `nginx`, el contenedor se debe llamar `servidor_web` y se debe acceder a él utilizando el puerto 8181 del ordenador donde tengas instalado docker.

Sube y documenta, sin abusar de las IAs, en este mismo repositorio los siguientes pantallazos:

1. Pantallazo donde se vea la creación del contenedor y podamos comprobar que el contenedor está funcionando.
2. Pantallazo donde se vea el acceso al servidor web utilizando un navegador web (recuerda que tienes que acceder a la ip del ordenador donde tengas instalado docker)
3. Pantallazo donde se vean las imágenes que tienes en tu registro local.
4. Pantallazo donde se vea como se elimina el contenedor (recuerda que antes debe estar parado el contenedor).

## Entrega

- 23 de octubre a las 23:59 h.
- Tendremos la penalización de siempre si sufrimos un retraso en la entrega.
