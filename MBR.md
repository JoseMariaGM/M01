# ¿QUE CONTIENE EL MBR? (Master boot record)

**Que es el MBR?**

Un registro de arranque principal, conocido también como registro de arranque maestro,  es el primer sector de un dispositivo de almacenamiento de datos, como un disco duro. A veces, se emplea para el arranque del sistema operativo, otras veces es usado para almacenar una tabla de particiones y, en ocasiones, se usa sólo para identificar un dispositivo de disco individual.

**Partes del MBR**


Tabla de particiones (64 bytes) **->** 4 registros que definen cada una de las particiones primarias.

Código máquina (446 bytes) **->** Es el gestor de arranque del PC. Este es un sisema de códigos que actuan como conjunto de instrucciones determinando así acciones a tomar para la máquina.

Firma de unidad de arrancable (2 bytes) **->** Número identificador para un disco duro almacenado en la MBR ("55hAAh" en hexadecimal).


