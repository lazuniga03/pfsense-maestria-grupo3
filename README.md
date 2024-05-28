![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/8133f468-04e7-4a66-bcc1-15cb70ecab2c) ![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/f385eb05-fb30-461a-9a17-b5ae8c681686)

# pfsense-maestria-grupo3
proceso de dimensionamiento de características para la maquina virtual, instalación y configuración de políticas
Descripción General:
Para instalar el firewall se considera los requerimientos mínimos del sistema de 8Gb de almacenamiento, 1Gb min de RAM y 2 tarjetas de red (para WAN y LAN) (ver Figura 1 y 2)
Se descarga desde la página oficial :
https://www.pfsense.org/ 
Al momento de virtualizar se sigue los siguientes pasos:

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/72722099-5493-46e2-9621-d76ea68a2711)

Figura 1 Localización de almacenamiento del Firewall

 ![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/24b6690c-97a8-4c99-82b6-a3a29f3689ed)


Figura 2 Configuración LAN de tarjetas de red
 

Aceptación de términos de y condiciones (ver Figura 3)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/66a69458-3431-4efb-b73f-509a940fcdc4)

Figura 3 Términos y condiciones a aceptar para instalar pfsense


Se da click en install (ver Figura 4)

 ![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/b4aa41f3-f711-40a9-ba43-ceeda9d63115)

Figura 4 ventana de instalación de pfsense
 
Se da una partición de manera automática ZFS (ver Figura 105)
Figura 105 Selección de tipo de partición de disco

 

Confirmación de escritura de partición de disco (ver Figura 106)
Figura 106 Ventana de aceptación para partición de disco
 
Reinicio de servicios tras la instalación de pfsense
Figura 107 Ventana de instalación finalizada con éxito
 
En la Figura 108 se observa la pantalla inicial del menú de configuración del firewall pfsense y se observa las IP de accesos de red WAN y LAN 
Figura 108 Menú de pfsense

 
Pantalla de acceso WEB en la Figura 109 desde la red LAN por la Gateway 192.168.1.1 con las credenciales por default
Usuario: admin
Contraseña: pfsense

Después del primer acceso se cambian inmediatamente las credenciales 
Figura 109 ventana de inicio por https y red LAN

 

Ventana de bienvenida y cambio de contraseña por primera vez de usuario admin en la Figura 110
Figura 110 Cambio de contraseña de usuario admin
 
Información general del firewall pfsense (ver Figura 111)
Figura 111 Nombre y dominio del firewall pfsense
 
Configuración de red LAN (Gateway) en la Figura 112
Figura 112 red LAN configurada en el wizard
 
En la Figura 113 se observa la configuración de Wizard de configuración rápida del Firewall
Figura 113 Configuración exitosa de wizard 

 

Verificación de actualizaciones del firewall (ver Figura 114)
Figura 114 Ventana de actualización del firewall pfsense
 
Por seguridad se habilita solo ese acceso por https y por un puerto distinto al 443 (https) en este caso 448 como se observa en la Figura 115
Figura 115 Desactivación de acceso http y cambio de puerto
 
Por tema de seguridad se recomienda desactivar el usuario admin y configurar un nuevo usuario para acceder, en este caso se crea el usuario “admin” y se recomienda el uso de contraseñas robustas de mínimo 8 caracteres considerando: 
Letras mayúsculas
Letras minúsculas
Números
Caracteres especiales (ver Figura 116)
Figura 116 creación de nuevo usuario para acceso al firewall


 
Desactivación del usuario admin (ver Figura 117)
Figura 117 Desactivación del usuario admin

 
Estatus de los usuarios habilitados para acceder al firewall (ver Figura 118)
Figura 118 usuarios habilitados y deshabilitados para acceso al firewall
 
