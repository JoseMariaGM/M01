# **Que es y que permite.**

Este comando nos ayuda el la administracion y gestión de nuestro espacio en el disco duro. Hay un máximo de 4 particiones por disco.
Con este comando se puede crear , eliminar , cambiar, copiar y mover particiones.

# **Comandos de FDISK**

-*fdisk* -l -> Nos permite ver todas las particicones.

-*p* -> Para ver la tabla de particiones del sistema.

-*m* -> Para saber los comandos fdisk , ayuda y opciones de aplicación para nuestro disco.

-*fdisk -s* -> Comprobar el tamaño de la partición.

-*n* -> Para crear una partición (new). En esta despeus de querer crearla nos sale lo siguiente: e (extendida), p (primaria) y t
(swap).

-*delete* -> Borrar una partición

-*w* -> Guardar cambios

-*mkfs.ext4 /sdb5/dev/* -> Formateo de la partición 

             |
             |---> Tipo de formato partición.
