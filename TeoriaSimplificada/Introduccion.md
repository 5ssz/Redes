# Introducción a las redes
## Que es una red de ordenadores?
- Dispositivos conectados entre sí que pueden compartir recursos e intercambiar datos.
- Utilizan una serie de reglas (llamados protocolos de comunicaciones) para transmitir esta información.

## Usos de red de ordenadores
- Para compartir recursos (archivos, impresoras, bases de datos...)
- Para comunicar personas (correos, chats, IM...)

## Que necesitamos para hacerla funcionar?
- Conexión física para la transmisión de datos entre el emisor y receptor
- Protocolos de comunicación conocidos por los extremos para poderse entender (software y hardware)

## Tipos de conexiones ("medios")
- Guiados (cable de cobre, fibra óptica, cable coaxial...)
- No guiados (Wi-Fi, Bluethoot, IR, radio...)

Los medios guiados suelen ser más rápidos, seguros y menos propensos a interficies. Los medios no guiados, en cambio, son más cómodos para el
usuario y para el instalador y mantenedor

## Interficie de red
- Dispositivo electrónico que comunica el ordenador con el medio de red
- Puede ser una tarjeta de expansión agregada al ordenador o venir incorporada en la placa base

## Alcance de redes
- LAN (Local Area Network): Los dispositivos se encuentran conectados en una zona delimitada y el administrador tiene el control total. Su versión inalámbrica es la WLAN (Wireless Local Area Network).
- WAN (Wide Area Network): Encontramos los dispositivos en una zona extensa.

## Tipos de Topologías
- Topología punto a punto
- Topologías multipunto
  - Topología de bus
  - Topología de anillo
  - Topología en estrella
  - Topología en estrella extendida
  - Topología jerárquica
  - Topología en malla

## Tipos de arquitecturas
- **Cliente-Servidor:** Múltiples clientes hacen peticiones a uno o más servidores con tal de abrir ciertos recursos compartidos permanentemente por estos (ficheros, impresoras, etc). Un ejemplo es la WWW.
- **Peer-to-peer (P2P):** Todos los nodos hacen de clientes y servidores a la vez entre sí. Ejemplo: `BitTorrent`
- **Cluster:** Todos los nodos trabajan en grupo para ofrecerse al resto de la red como un único nodo
