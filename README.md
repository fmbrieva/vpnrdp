# vpnrdp
LiveCD para realizar conexiones seguras sobre redes públicas mediante VPN a escritorios corporativos remotos utilizando el protocolo RDP.
(OpenSource para ayudar a los departamentos de IT en la crisis del COVID-19)

[**Presentación del proyecto**](https://github.com/digitaliza-aapp/vpnrdp/blob/master/Vpnrdp%20Digitalizaaapp%20V00r01-18.webm?raw=yes) Vídeo de presentación

## Opciones de funcionamiento

  <img src="imagenes/VPNRDP_Opciones.png" >
 
## Descarga ISO

- [**vpnrdp_kiosk_v02r09.1x.iso**](https://drive.google.com/file/d/1r7vO/view?usp=sharing) (7/12/2020) LiveCD vpnrdp_kiosk versión v02r09.1x (amd64 64bits) 
- [**vpnrdp_kiosk_v02r09.1x.iso.hexhash**](https://github.com/digitaliza-aapp/vpnrdp/blob/master/vpnrdp_kiosk_v02r09.1x.iso.hexhash?raw=yes) (7/12/2020) Huella Digital versión v02r09.1x
- [**Guía de configuración (pdf)**](https://github.com/digitaliza-aapp/vpnrdp/blob/master/vpnrdp_kiosk_v00r02.pdf?raw=yes) Guía de configuración

## Imagen persistente

Imagen preparada para trabajar en modo persistente.

- [**v02r09.1x_kiosk_amd64.img**](https://drive.google.com/file/d/1hJf0i1TLtslUuo_3QQYFp5fC8nvZ6tUw/view?usp=sharing) (7/12/2020) Imagen vpnrdp_kiosk versión v02r09.1x (amd64 64bits) 
- [**v02r09.1x_kiosk_amd64.img.hexhash**](https://github.com/digitaliza-aapp/vpnrdp/blob/master/v02r09.1x_kiosk_amd64.img.hexhash?raw=yes) (7/12/2020) Huella Digital imagen vpnrdp_kiosk versión v02r09.1x

Nota:  Para copiar la imagen a un pendrive puede utilizar programas como Rufus (https://rufus.ie/)

## Pasos a realizar para acceder al escritorio remoto:

 (Para una información más detallada consultar la `Guía de configuración`)
 
  <img src="imagenes/VPNRDP_Pasos.png" width="50%"  >
    
  1. Arrancar la imagen desde USB o DVD
  2. Conectar un USB al equipo con el certificado (p12 ó pfx)
  3. Ejecutar el script para instalar el certificado `haciendo doble clic sobre el icono`
  4. Abrir OpenFortiGUI `haciendo doble clic sobre el icono` y poner las credenciales (usuario/contraseña) y acceder a la VPN
  5. Abrir Remmina `haciendo doble clic sobre el icono` y poner las credenciales para acceder al escritorio remoto (IP,usuario,contraseña y dominio)
  
## Contacto

Para hacer sugerencias ó reportar incidencias puede enviar un correo electrónico a digitaliza.aapp@gmail.com  

## Créditos

El LiveCD vpnrdp utiliza componentes Open Source. A continuación puede encontrar un enlace a los proyectos. Reconocemos y agradecemos a los desarrolladores su contribución al código abierto.

This application uses Open Source components. You can find a link to their projects, we acknowledge and are grateful to these developers for their contributions to open source.

- [**LiveCD vpnrdp**](https://github.com/digitaliza-aapp/vpnrdp/blob/master/README.md) LiveCD - Conexión a escritorios mediante VPN y RDP
- [**Xubuntu**](https://xubuntu.org/)	Distribución Linux ligera basada en Ubuntu + Escritorio ligero XFCE
- [**OpenFortiGUI**](https://github.com/theinvisible/openfortigui) VPN-GUI para conexiones a Fortigate basado en
openfortivpn
- [**Remmina**](https://remmina.org/)	Cliente de escritorio remoto
- [**Firefox**](http://mozilla.org) Navegador Web
- [**FreeRDP**](https://github.com/FreeRDP/FreeRDP) Implementación protocolo RDP
- [**XFreeRDP-GUI**](https://github.com/wyllianbs/xfreerdp-gui) Entorno gráfico para FreeRDP
- [**Clamav**](https://www.clamav.net/downloads) Antivirus Open Source
- [**Docky**](https://launchpad.net/docky) Lanzador de aplicaciones
- [**Mkusb**](https://launchpad.net/~mkusb/+archive/ubuntu/ppa) Herramienta para crear unidades de arranque USB
- [**SystemBack**](https://sourceforge.net/projects/systemback/) Simple system backup and restore

## Ausencia de garantías
EL LIVECD VPNRDP SE PROVEE EN SU ESTADO ACTUAL Y SIN GARANTÍAS DE NINGÚN TIPO. NO SE OFRECE DE MANERA EXPLÍCITA, IMPLÍCITA, NI JURADA GARANTÍAS, AFIRMACIONES NI DECLARACIONES DE NINGÚN TIPO CON RESPECTO AL LIVECD VPNRDP

## Descargo de responsabilidad
Usted recibe el LIVECD VPNRDP de forma gratuita. POR CONSIGUIENTE, USTED RECONOCE Y ACEPTA QUE EL PERSONAL QUE HA PARTICIPADO EN EL PROYECTO NO TENDRÁ RESPONSABILIDAD ALGUNA QUE SURJA DEL USO DEL LIVECD O SE RELACIONE CON DICHO USO. SU ÚNICO DERECHO O RECURSO LEGAL ANTE CUALQUIER PROBLEMA O DISCONFORMIDAD CON EL LIVECD VPNRDP ES DEJAR DE USARLO DE INMEDIATO. 

## Disclaiming warranty
LIVECD VPNRDP IS PROVIDED IN ITS CURRENT STATUS AND WITHOUT WARRANTIES OF ANY KIND. NO WARRANTIES, CLAIMS, OR STATEMENTS OF ANY KIND WITH REGARD TO
THE LIVECD VPNRDP ARE PROVIDED EXPLICIT, IMPLIED, OR SWORN.

## Limiting liability
You receive LIVECD VPNRDP for free. ACCORDINGLY, YOU ACKNOWLEDGE AND AGREE THAT THE PERSONNEL WHO HAVE PARTICIPATED IN THE PROJECT SHALL HAVE NO LIABILITY ARISING FROM THE USE OF THE LIVECD OR RELATING TO SUCH USE. YOUR SOLE RIGHT OR LEGAL REMEDY FOR ANY PROBLEM OR DISPUTE WITH THE LIVECD VPNRDP IS TO  STOP USING IT IMMEDIATELY.
