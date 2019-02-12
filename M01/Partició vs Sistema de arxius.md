Una **Partició** és el que podría dir-se un armari i el **Sistema d'arxius** serien els calaixos on guardarem les coses.

Les particions estàn dins d'un disc físic, però aquestes actuen com un disc independent cadascuna, encara que estiguin al mateix disc.
Hi ha diferents esquemes de particions per la distribució de particions en un disc. Els més coneguts són l'MBR i GPT.
Tipus de particions: 

- *Partició primària:* Divisions crudes del disc. Solament hi poden haver 4 primàries o 3 primàries i 1 extended ,
si es MBR el sistema de particions, si és GPT, serien ilimitats el nom de particions possibles.

- *Partició extendida*: És una partició que actúa com una primària, serveix per contenir múltiples lògiques en el seu interior. Aquesta 
es va crear per eliminar la limitació de 4 particions máximes en un sòl disc dur.

- *Partició lógica* : És el tipus de partició que pot haver-hi en una extended, tan sigui una sola partició , com altres més, el màxim són
32 particions lògiques en total. A Linux té com a màxim 15, incloent-hi les 4 primàries.


Els sistemes d'arxius són els encarregats d'asignar l'espai als arxius, l'adminitració de l'espai lliure, del accès a dades reguardades...
Aquest dóna informació  guardada en un disc dur. Els sistemes d'arxius estàn repartits en sectors a tot el disc, aquests sectors són 
usualment d'uns 512 bytes cadascun (clusters). 
Però , com s'organitza el sistema d'arxius? Amb el seu propi software. Usualment tots els Sistemes Operatius tenen el seu propi  
sistema d'arxius.

Per poder contenir dades , les particions han de poseeir un sistema d'arxius. Existeixen múltiples sistemes d'arxius amb diferents 
capacitats com :
FAT , NTFS , FAT32, ETX2, EXT3, ETX4, Btrfs, FedFS, ReiserFS, Reiser4 i altres.

