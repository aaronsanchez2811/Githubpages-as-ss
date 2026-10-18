## Què és

El DNS (Domain Name System) és el sistema que tradueix els noms de les webs a adreces IP. Els ordinadors es comuniquen amb números, com 142.250.184.4, però a les persones ens és més fàcil recordar un nom com google.com.

![imatgedns](https://ayudaleyprotecciondatos.es/wp-content/uploads/2020/10/dns-domain-name-system-server.jpg)

## Com funciona

Quan escrius una adreça al navegador, l'ordinador pregunta a un servidor DNS quina IP té aquell nom. El servidor li retorna la IP i, a partir d'aquí, el navegador ja es pot connectar a la web.

Si el servidor no sap la resposta, la va demanant a altres servidors fins que la troba. Per no haver de repetir tot aquest procés cada vegada, l'ordinador guarda les respostes durant un temps a la memòria cau.

## Tipus de registres

Cada domini té uns registres que diuen on ha d'anar cada cosa. El registre A indica la IP d'un nom, el registre MX indica quin servidor rep el correu, i el registre CNAME fa que un nom apunti a un altre.

## Ordres útils

Per consultar la IP d'un domini es pot fer servir l'ordre nslookup, per exemple nslookup google.com. A Linux també hi ha l'ordre dig, que dona informació més detallada.
