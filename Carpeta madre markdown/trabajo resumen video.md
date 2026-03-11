
# Semana 8 – Conceptos de Internet (CS50)

## Conceptos básicos de Internet
Internet es una red mundial de computadoras conectadas entre sí.  
La información no viaja completa de una vez, sino que se divide en **paquetes de datos** que se envían a través de diferentes rutas.

Los **routers** son dispositivos que se encargan de dirigir esos paquetes hacia su destino, de manera similar a cómo una persona pasa un mensaje a otra.  
Si una ruta falla, los paquetes pueden tomar **otro camino**, lo que hace que Internet sea un sistema bastante resistente.

---

## TCP/IP
El funcionamiento de Internet depende principalmente de dos protocolos.

### IP (Internet Protocol)
El protocolo IP asigna una **dirección única** a cada dispositivo conectado a la red.  
Estas direcciones funcionan como una dirección de casa.

Ejemplo de IPv4:

`1.2.3.4`

También existe **IPv6**, creado para soportar una mayor cantidad de dispositivos conectados.

### TCP (Transmission Control Protocol)
TCP se encarga de asegurar que los datos lleguen correctamente.

Para lograrlo:

- Divide la información en paquetes
- Les asigna **números de secuencia**
- Verifica que todos los paquetes lleguen

Además usa **puertos** para identificar servicios distintos.

Ejemplos:

- Puerto **80** → páginas web (HTTP)  
- Puerto **443** → páginas web seguras (HTTPS)

---

## DNS y DHCP

### DNS (Domain Name System)
Los humanos recuerdan nombres fácilmente, pero las computadoras trabajan con números.

El **DNS** traduce los **nombres de dominio** a direcciones IP.

Ejemplo:

`harvard.edu → dirección IP`

Gracias a esto no necesitamos memorizar números.

### DHCP
El protocolo **DHCP** configura automáticamente los dispositivos cuando se conectan a una red.

Puede asignar:

- Dirección IP
- Servidor DNS
- Otros datos de red

Esto hace que conectarse a Internet sea mucho más sencillo.

---

## HTTP
El **HTTP (HyperText Transfer Protocol)** es el protocolo que permite que los navegadores pidan páginas web a los servidores.

La versión segura es **HTTPS**, que cifra la información para proteger los datos.

### Partes de una URL

Ejemplo:

`https://www.harvard.edu/ruta`

- **https** → protocolo  
- **www** → subdominio  
- **harvard.edu** → dominio  
- **/ruta** → ubicación específica dentro del sitio

### Métodos de solicitud

- **GET** → solicitar información  
- **POST** → enviar información al servidor

---

## Códigos de estado HTTP

Cuando un navegador hace una solicitud, el servidor responde con un **código de estado**.

Algunos ejemplos:

- **200** → solicitud exitosa  
- **301** → recurso movido permanentemente  
- **404** → página no encontrada  

Los navegadores permiten ver estas respuestas usando las **herramientas de desarrollador**.

---

## HTML
El **HTML (HyperText Markup Language)** es el lenguaje utilizado para estructurar el contenido de las páginas web.

Se basa en **etiquetas (tags)** que organizan el contenido.

Algunas etiquetas básicas:

- `<html>` → estructura principal  
- `<head>` → información de la página  
- `<title>` → título mostrado en la pestaña  
- `<body>` → contenido visible

Los archivos HTML pueden visualizarse en el navegador y también pueden servirse usando un **servidor HTTP local**.

---

## Idea principal
Internet funciona gracias a la combinación de varios sistemas y protocolos que permiten que los dispositivos se identifiquen, se comuniquen y envíen información entre sí para mostrar contenido en la web.
```
