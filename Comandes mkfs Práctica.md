*Comandos Mkfs Práctica.*


**kpartx -a /dev/loop0** -> Para entrar al disco.

**ls /dev/mapper/loop0p1** -> Para encontrar primera partición ( la cual es el Boot Manager de 100KiB)

**mkfs.ntfs /dev/mapper/loop0p1** -> Para formatear la partición 1 y transformarla en "NTFS".

- Este apartado no se puede hacer por que para transformar una partición en "NTFS" debe ser de un mínimo de 2 MiB y esta es de 
100 KiB.

**ls /dev/mapper/loop0p2** -> Para buscar la partición de 70 MiB creada.

**mkfs.ntfs /dev/mapper/loop0p2** ->Para formatear la partición 2 y transformarla en "NTFS".

**ls /dev/mapper/loop0p5** -> Para encontrar la partición 5 de 5MiB de la SWAP antes creada.

**mkswap /dev/mapper/loop0p5** -> Para formatear la partición 5 de la extended ya creada y convertirla en "SWAP".

**ls /dev/mapper/loop0p6** -> Para encontrar la partición 6 de la extended de 100 MiB.

**mkfs.ext4 /dev/mapper/loop0p6** -> Para formatear la partición 6 de 100MiB de la extended y transformarla en ext4 ( / ).

**ls /dev/mapper/loop0p7** -> Para encontrar la partición 7 de 100 MiB de la extended.

**mkfs.ext4 /dev/mapper/loop0p7** -> Para formatear la partición 7 de 100MiB de la extended y transformarla en ext4 ( / )






