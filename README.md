# Poyecto_Practica
## Monitor de Red Local

Herramienta sencilla para diagnosticar y supervisar una red local: detecta los equipos conectados, comprueba su conectividad y registra los resultados.

Objetivos
1. Descubrir los dispositivos activos dentro de una LAN.
2. Medir la disponibilidad de cada equipo mediante un ping.
3. Generar un informe con las direcciones IP y las direcciones MAC.

# Instalación

Instala las herramientas de red necesarias y comprueba la conectividad:

bash
sudo apt install nmap net-tools -y && ping -c 4 192.168.1.1

https://nmap.org/man/es/index.html

# Estado del proyecto

Tareas realizadas

 Diseño del esquema de red y asignación de direcciones IP.
 Configuración del script de escaneo de hosts con nmap.

Tareas pendientes

 Añadir de la red.
 Crear un informe automático con los equipos detectados.
Autor Ian Simón Piñeiro