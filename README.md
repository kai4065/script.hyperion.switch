
hyperion-switch
========

Toggle on/off hyperion in OpenELEC with an addon.



DESCRIPCIÓN:

Sistema para apagar los Leds controlados por [Hyperion](https://github.com/tvdzwan/hyperion) en una Raspberry Pi desde el menu de Kodi y desde el mando a distancia de tu TV.
El sistema ha sido probado en OpeneELEC 4, 5, 6, 7, LibreELEC 7 y 8.

INSTRUCCIONES:

Despues de instalar hyperion segun las [instrucciones para LibreELEC](https://hyperion-project.org/wiki/Installation-on-LibreElec), instalar el addon [desde el zip](https://github.com/bite-your-idols/script.hyperion.switch/releases/latest).
Podemos modificar el archivo "remote.xml" para añadir un acceso directo al encendido/apagado desde tu propio mando a distancia. Elegis el boton y le asignais el codigo:
```
XBMC.System.Exec("/storage/.kodi/addons/script.hyperion.switch/bin/switch.sh")`
```

> Si no te funciona el script prueba a darle permisos de ejecucion y lectura al archivo /storage/.kodi/addons/script.hyperion.switch-master/bin/switch.sh


+ información: http://www.elotrolado.net/hilo_hilo-oficial-movimiento-ambilight-eol_1036973
