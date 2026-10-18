Els usuaris i grups a Linux

A Linux, cada persona que fa servir l’ordinador té el seu propi usuari, amb una contrasenya i una carpeta personal dins de /home. A més, hi ha l’usuari root, que és l’administrador i pot fer qualsevol canvi al sistema.

Els grups ajunten diversos usuaris perquè tinguin els mateixos permisos. Si tots els alumnes d’una classe estan al mateix grup, es pot fer que tots puguin entrar a la mateixa carpeta sense haver de configurar-ho un per un.

Un usuari nou es crea amb l’ordre useradd, i la contrasenya se li posa amb passwd. Els grups es creen amb groupadd, i amb usermod -aG s’hi afegeixen usuaris: usermod -aG alumnes maria posa la maria dins del grup alumnes.

Si vols saber a quins grups pertany un usuari, pots fer servir l’ordre groups. L’ordre id també ho mostra, juntament amb el número que identifica l’usuari.
