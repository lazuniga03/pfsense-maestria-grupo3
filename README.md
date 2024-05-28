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
 
Se da una partición de manera automática ZFS (ver Figura 5)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/b0091a83-5ed3-4cfc-a525-64fdabcb96fc)

Figura 5 Selección de tipo de partición de disco

 Confirmación de escritura de partición de disco (ver Figura 6)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/677f80f8-2bc0-4e1b-b6e7-f1e6dfff831d)

Figura 6 Ventana de aceptación para partición de disco
 
Reinicio de servicios tras la instalación de pfsense

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/323d66c6-3dbc-4f67-a444-216ecc793a68)

Figura 7 Ventana de instalación finalizada con éxito
 
En la Figura 8 se observa la pantalla inicial del menú de configuración del firewall pfsense y se observa las IP de accesos de red WAN y LAN 

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/e36ef19d-613f-4e16-ad59-9e2f0d68ebe5)

Figura 8 Menú de pfsense

 
Pantalla de acceso WEB en la Figura 9 desde la red LAN por la Gateway 192.168.1.1 con las credenciales por default

Usuario: admin

Contraseña: pfsense

Después del primer acceso se cambian inmediatamente las credenciales 

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/be5d1ea7-0185-4b59-8b5f-53df1cda4ec1)

Figura 9 ventana de inicio por https y red LAN

Ventana de bienvenida y cambio de contraseña por primera vez de usuario admin en la Figura 10

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/afe6b289-e504-4a8e-bd30-e19dee512628)

Figura 10 Cambio de contraseña de usuario admin
 
