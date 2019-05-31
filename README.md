# Paquete DEB vx-dga-l-scripts

Paquete que instala los scripts básicos para personalización del entorno Vitalinux DGA

# Usuarios/Equipos Destinatarios

Paquete obligatorio para los equipos Vitalinux DGA. Añade funcionalidades extra para el sistema:
* Instalar drivers pdi
* Obtener información interesante: datos del equipo, comprobar etiquetas
* Configurar diferentes parámetros: nombre, etiquetas del equipo, dock y pie...
* Atajos: reiniciar, cerrar sesión.... 
* Script para habilitar o desabilitar tanto el touchpad como el touch screen

# Aspectos Interesantes
```
Ninguno en concreoto
```
# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```
En el caso de que no desees crear el paquete DEB a partir del código fuente, ya que no más a modificarlo ni introducir ninguna mejora, puedes obtener el paquete DEB aquí:

[Listado de Paquetes del Proyecto de Software Libre](http://migasfree.educa.aragon.es/repo/Lubuntu-14.04/STORES/base/)

# Como Instalar el paquete generado vx-dga-l-scripts*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-scripts*.deb
```
