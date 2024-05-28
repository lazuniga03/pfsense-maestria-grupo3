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

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/66a69458-3431-4efb-b73f-509a940fcdc4)

Figura 2 Configuración LAN de tarjetas de red
 
Aceptación de términos de y condiciones (ver Figura 3)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/b4aa41f3-f711-40a9-ba43-ceeda9d63115)

Figura 3 Términos y condiciones a aceptar para instalar pfsense

Se da click en install (ver Figura 4)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/ff998ebb-5995-4209-ad02-f3c6eb10bd7f)

Figura 4 ventana de instalación de pfsense
 
Se da una partición de manera automática ZFS (ver Figura 5)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/c90a66e4-884d-455b-8667-ae85bd6d9ba8)

Figura 5 Selección de tipo de partición de disco

 Confirmación de escritura de partición de disco (ver Figura 6)

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/ff34bea4-e3ac-449e-8a92-3d2b94b5e4fa)

Figura 6 Ventana de aceptación para partición de disco
 
Reinicio de servicios tras la instalación de pfsense

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/54cd48a5-2319-424d-b190-a9a4ecc6167f)

Figura 7 Ventana de instalación finalizada con éxito
 
En la Figura 8 se observa la pantalla inicial del menú de configuración del firewall pfsense y se observa las IP de accesos de red WAN y LAN 

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/7ffdf421-2ce2-429f-9886-7c07361ebf8b)

Figura 8 Menú de pfsense

 
Pantalla de acceso WEB en la Figura 9 desde la red LAN por la Gateway 192.168.1.1 con las credenciales por default

Usuario: admin

Contraseña: pfsense

Después del primer acceso se cambian inmediatamente las credenciales 

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/c9dca292-c9e0-41ec-bd11-8df60486af38)

Figura 9 ventana de inicio por https y red LAN

Ventana de bienvenida y cambio de contraseña por primera vez de usuario admin en la Figura 10

![image](https://github.com/lazuniga03/pfsense-maestria-grupo3/assets/144503813/be17df1f-8acb-478a-9337-77452b16e8a7)

Figura 10 Cambio de contraseña de usuario admin
 
