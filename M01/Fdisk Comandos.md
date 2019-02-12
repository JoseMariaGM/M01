**fdisk -l** : Para ver todas las particions existentes.
**n** : Nueva partición -> "e"(xtended partition) - "p"(rimary partition) -> Enter -> +100GB
**d** : Borrar partición -> w : Para guardar
**t** : Cambiar formato de partición (t-> 82 -> Linux swap)
**mkfs.ext4** /dev/sda4** : Formatear partición a ext4
**Partición primária** : "a" -> 1-9 -> p -> "Nombre_Partición  * "
