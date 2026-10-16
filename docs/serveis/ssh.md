# Guía Básica: Protocolo SSH

## ¿Qué es SSH?
SSH (**Secure Shell** o Intérprete de Comandos Seguro) es un protocolo de red criptográfico que permite a los usuarios acceder, controlar y modificar servidores remotos de forma **segura** a través de una red no segura (como Internet). Proporciona un canal seguro sobre una red insegura mediante cifrado fuerte.

---

## Características Principales
* **Cifrado Fuerte:** Todos los datos transmitidos (incluyendo nombres de usuario, contraseñas y comandos) están completamente cifrados, impidiendo ataques de interceptación (*sniffing*).
* **Autenticación Robusta:** Permite la autenticación basada en contraseñas tradicionales y, de forma preferida, mediante pares de claves criptográficas (pública y privada).
* **Puerto predeterminado:** Utiliza por defecto el puerto **22**.
* **Reemplazo seguro:** Sustituyó a protocolos antiguos e inseguros como Telnet, rlogin y rsh.

---

## Usos Principales
* **Administración remota:** Conexión a la terminal de servidores Linux/Unix para ejecutar comandos de forma interactiva.
* **Transferencia segura de archivos:** Utilizado como base para protocolos como **SFTP** (Secure File Transfer Protocol) y **SCP** (Secure Copy Protocol).
* **Túneles y Reenvío de Puertos:** Permite redirigir tráfico de red de forma segura a través de la conexión SSH (port forwarding).

## Como utilizarlo

Para utilizar el servicio ssh como cliente, tenemos que ejecutar el siguiente comando:

```bash
ssh usuari@direcciónservidor -p <puerto>
```