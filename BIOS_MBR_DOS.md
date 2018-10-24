**BIOS MBR DOS**
    |
    |     *Antiguo* -> **BIOS MBR DOS** -> Admite hasta un máximo de 2 TB por cada partición existente.
    |     *Actual* -> **UEFI GPT** -> Admite hasta un máximo de 18 exabytes, que este es equivalente a 18,8 millones de TB.
    |
    |
    V
**Reglas MBR**

-Tiene un máximo de **4 particiones primarias**. ---> Una de estas puede ser extended.
-Una **extended** puede tener "n lógicas"
-Una de ellas obligatoriamente debe ser **"Activa"**---> Una Activa no puede ser extended y al revés.
                                            |
                                            |
                                            |
                                            |---> En *Windows* si no es "Activa" el PC no arrancará
*UEFI/GPT*->Ni primarias ni activas tiene.<-|---> En *Linux* esta no es obligatoria como en Windows, no es del todo necesaria.
                                   
                                   
**Boot Manager** --> Gestor de arranque de Windows.
**GRUB** --> Gestor de arranque de Linux

Para cambiar a *MBR* se debe entra en la *BIOS* y poner el *Modo Legacy*, y si queremos ponerlo al revés, de *GPT*
cambiamos al modo a *UEFI*.
