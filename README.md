# Linux Essentials

Este repositorio contiene una recopilación de comandos esenciales y apuntes relacionados con Linux. Aquí encontrarás información útil sobre la línea de comandos, administración del sistema, herramientas y conceptos fundamentales de Linux. 

El objetivo es proporcionar una referencia rápida y práctica para usuarios de Linux de todos los niveles de experiencia. Siéntete libre de explorar, contribuir y aprender junto con nosotros en este viaje de dominio de Linux.

## Red

### Listado de interfaces de red

A continuación se muestran los comandos para ver las interfaces de red utilizando `ifconfig` y `ip`.

#### Utilizando ifconfig

Abre una terminal y ejecuta el siguiente comando:

`ifconfig -a`

Esto mostrará una lista de las interfaces de red disponibles en tu sistema.

#### Utilizando ip

Abre una terminal y ejecuta el siguiente comando:

`ip link show`

Esto mostrará una lista de las interfaces de red disponibles en tu sistema, junto con su estado y detalles asociados.

En ambos casos, las interfaces de red estarán etiquetadas con nombres como "ethX" para las interfaces Ethernet y "wlanX" para las interfaces inalámbricas, donde "X" es un número que identifica cada interfaz.

Recuerda que algunos sistemas pueden utilizar nombres de interfaz diferentes, como "enpXsY" para Ethernet y "wlpXsY" para Wi-Fi, dependiendo de la versión de Ubuntu y la configuración de tu sistema.
