# Zabbix
## _Sistema de Monitorización de Redes, Docker Compose :whale2:_

Zabbix es un Sistema de Monitorización de Redes creado por Alexei Vladishev. Está diseñado para monitorizar y registrar el estado de varios servicios de red, Servidores, y hardware de red.

## Caracteristicas
 - Verificar la disponibilidad y nivel de respuesta de varios servicios como por ejemplo servicios web o de correo.
 - Permite obtener estadísticas cómo carga de una CPU, uso de disco, ancho de banda de la red.
 - Permite monitorizar servicios a través de protocolos como SNMP, TCP, ICMP o SSH y telnet.

## Herramientas :globe_with_meridians:
* Docker :whale2:
* Postgresql :elephant:
* Zabbix
* Nginx

## Installation

Debe tener instalador Docker :whale2: y Docker Compose en el sistema.

```sh
git clone https://github.com/JhonnyVeraCervantes/Zabbix-with-Docker-Compose.git
```
```sh
cd Zabbix-with-Docker-Compose
```
```sh
docker-compose up -d
```

## Docker :whale2:

Zabbix es muy fácil de instalar e implementar en un contenedor Docker.
De forma predeterminada, Docker expondrá el puerto 8080, así que cámbielo dentro del Dockerfile si es necesario. Cuando esté listo, simplemente use el Dockerfile para construir la imagen.
Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:8000
```
# Zabbix - Compose
```sh
USER=Admin
PASSWORD=zabbix
```
#### ¿Hablamos?☕️


<a href="https://www.linkedin.com/in/jhonnyvera/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="George Vera" height="30" width="40" /></a>


<a href="mailto:george.vera.tic@gmail.com " target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg" alt="George Vera" height="30" width="40" /></a>
</p>

