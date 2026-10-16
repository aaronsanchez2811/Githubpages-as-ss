# Guia basica sobre http

## ¿Que es http?
HTTP (Hypertext Transfer Protocol) es el protocolo de comunicación usado para la transmisión de datos para la **World Wide Web**. La cual permite a los navegadores web accerder a páginas, imágenes, videos y otros contenidos.

## Características Principales
* **Modelo Cliente-Servidor:** El cliente (normalmente un navegador) realiza una serie de peticiones y el servidor cuando la recibe la procesa y devuelve la respuesta correspondiente a la petición.
* **Sin Estado:** Cada petición es independiente de las demás. El servidor no retiene información de las solicitudes pasadas de un mismo cliente (para hacer esto se utilizan otras herramientas, como son cookies o tokens).
* **Capa de transporte:** Funciona típicamente sobre **TCP** (Transmission Control Protocol).
* **Puerto predeterminado:** Utiliza el puerto **80** por defecto (mientras que su versión segura, **HTTPS**, utiliza el puerto **443** y añade cifrado SSL/TLS).

---

## Estructura de una Transacción

### 1. Métodos HTTP (Verbos)
Indican la acción que se desea realizar sobre el recurso:
* **GET:** Solicita la representación de un recurso específico.
* **POST:** Envía datos para ser procesados a un recurso determinado (crea un nuevo recurso).
* **PUT:** Actualiza un recurso existente o lo crea si no existe.
* **DELETE:** Elimina un recurso específico.

### 2. Códigos de Estado (Status Codes)
Indican el resultado de la petición realizada al servidor:
* **2xx (Éxito):** La petición fue recibida, comprendida y aceptada correctamente (ej. `200 OK`).
* **3xx (Redirección):** Se requieren acciones adicionales para completar la solicitud (ej. `301 Moved Permanently`).
* **4xx (Error del cliente):** La solicitud contiene sintaxis errónea o no se puede procesar (ej. `404 Not Found`).
* **5xx (Error del servidor):** El servidor falló al intentar procesar una solicitud aparentemente válida (ej. `500 Internal Server Error`). 
