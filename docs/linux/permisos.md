## Els permisos a Linux

A Linux, cada fitxer té un propietari. Els permisos serveixen per decidir qui pot obrir, canviar o fer servir aquell fitxer.

Hi ha tres permisos: llegir (r), escriure (w) i executar (x). Es donen a tres tipus d’usuaris diferents: el propietari, el seu grup i la resta.

Per veure els permisos d’un fitxer s’utilitza l’ordre ls -l. Per exemple, -rw-r--r-- vol dir que el propietari el pot llegir i modificar, i que els altres només el poden llegir.

Per canviar els permisos s’utilitza l’ordre chmod. Per exemple, chmod u+x script.sh dona permís d’execució al propietari, i així pot executar l’script.
