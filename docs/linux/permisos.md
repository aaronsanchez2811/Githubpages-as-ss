## Permisos Linux
Cada fitxer té tres permisos que es donen per separat al propietari, al grup i a la resta:

- r (lectura) per veure'l.
- w (escriptura) per modificar-lo.
- x (execució) per executar-lo.

![imatgepermisos](https://www.comunicare.es/wp-content/uploads/2022/05/linux.jpg)
## Veure'ls i canviar-los

## Comandes
ls -l  mostra la informació del fitxer   
chmod 755  Canviar els permisos del fitxer
-rwxr-xr-- L’usuari propietari pot llegir, escriure i executar. El grup pot llegir i executar. La resta només pot llegir

En números, r val 4, w val 2 i x val 1. Per això 755 vol dir que el propietari ho té tot i la resta només pot llegir i executar.
