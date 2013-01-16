HoneyDark
=========
Es un archivo OVF echo en Vmware vCloud 5.1 el cual contiene la estructura las VMs y el software necesario para correr 
tu propia DarkNet o HoneyNet o las 2 a la vez, con los software de analisis de trafico necesarios.

EL OVF se compone de 4 VMs , cual una vez imporado el OVF dentro de vmware las VMs son las siguientes

Servidor Pfsense:
IP:192.168.3.51
user : admin
Pass : 1q2w3e

HoneyDark::
IP:192.168.3.53
user: HoneyDark
pass: 1q2w3e

OSSIM 4.1:
Datos de acceso a la interfaz Web.
IP:192.168.3.50
user: admin
Pass: 1q2w3e

Evidencias:
IP:192.168.3.52
user: evidencias
pass: 1q2w3e

La red se llama Netproperties y su rango es 192.168.3.0/24.

El diseño inicial esta echo para uso de pequeños grupos pero la conceptualización puede ser usada para redes mas grandes 
o mayores cargas de trafico.

Para mas información http://bl4ckd4wn.blogspot.com/2013/01/honeydark-opensource.html
o twitter : @Bl4ckD4wn

Saludos
