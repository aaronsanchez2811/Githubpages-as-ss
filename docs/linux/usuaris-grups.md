Cada persona que fa servir l'ordinador té el seu usuari, amb una contrasenya i una carpeta pròpia a /home. L'usuari root és l'administrador i pot fer qualsevol canvi.

## Els grups

Un grup ajunta diversos usuaris perquè tinguin els mateixos permisos. Per exemple, si la *maria*, el *joan* i l'*anna* són al grup alumnes, tots tres poden entrar a la mateixa carpeta.

![imatgepermisos](https://linuxhandbook.com/content/images/2020/06/Group-Management-Linux.jpg)
## Comandes

| Comanda | Per a què serveix |
|---|---|
| useradd | Crear un usuari |
| passwd | Posar la contrasenya |
| groupadd | Crear un grup |
| usermod -aG | Afegir un usuari a un grup |

bash
sudo useradd -m sergi
sudo passwd sergi
sudo groupadd alumnes
sudo usermod -aG alumnes sergi


## On es guarda

- Els usuaris, a /etc/passwd.
- Les contrasenyes xifrades, a /etc/shadow.
- Els grups, a /etc/group.
