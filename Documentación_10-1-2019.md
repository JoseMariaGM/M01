Atualmente estoy haciendo una instalación de un ISO de Debian 
versión 9.5.0 dentro de una partición de 52 gigabytes.
He hecho que la partición utilizada se formatee para el nuevo Debian,
y también hacer que la swap se desactive.

He montado la partición como "/" , y actualmente tiene el GRUB.

Al haber acabado la instalación, arrancamos desde la BIOS con
Pendrive que tenga una live de Fedora para así poder modificar 
la ruta del GRUB con los siguientes comandos.

 - mkdir_/mnt/disc/
 - mount_/dev/sda6_/mnt/disc
 - grub2-install_--boot-directory-=/mnt/disc/boot_/dev/sda

A partir de aquí, cierro y vuelvo a entrar al Fedora del ordenador,
abro una terminal, hago "mount_/dev/sda6_/mnt/disc
Después de esto hago vi_/boot/grub2/grub.cfg

Se pone la entrada de Debian y se elimina lo que sobra dentro del
grub.cfg


