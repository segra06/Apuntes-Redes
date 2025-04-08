## Static Channel Allocation
  - Dinamic Channel Allocation (DCA): Asignación de canales de forma dinámica, en función de la demanda. Se utiliza en sistemas donde la carga de tráfico varía significativamente.

## Assumptions for DCA
- Trafico independiente: El tráfico de cada usuario es independiente de los demás.
- Canal independiente: Cada canal es independiente y no afecta a los demás.
- Colisiones observadas: Las colisiones son observadas por todos los usuarios.
## Multiple Access Protocols
- ALOHA: Protocolo de acceso aleatorio donde los usuarios transmiten sin coordinación. Si hay colisión, esperan un tiempo aleatorio antes de volver a intentar.
- CSMA (Carrier Sense Multiple Access): Protocolo que escucha el canal antes de transmitir. Si el canal está ocupado, espera hasta que esté libre.
- Collision free protocols: Protocolos que evitan colisiones mediante la asignación de canales o el uso de técnicas de acceso controlado.
## Carrier Sense Multiple Access (CSMA)
- CSMA/CD (Collision Detection): Detecta colisiones durante la transmisión y retransmite después de un tiempo aleatorio. Llama a todo como perdida de paquetes. 

- Persistent and Non-persistent CSMA: Diferentes enfoques para manejar el acceso al canal. En el persistente, los usuarios esperan hasta que el canal esté libre, mientras que en el no persistente, esperan un tiempo aleatorio antes de volver a intentar.
## Collision Free Protocols
- Bit Map: Asigna un bit a cada usuario para indicar si tiene permiso para transmitir. Si el bit está en 1, el usuario puede transmitir; si está en 0, no puede.
- Token passing: Un token se pasa entre los usuarios. Solo el usuario que tiene el token puede transmitir. Si no hay tráfico, el token se pasa al siguiente usuario. Virtualmente se crea un circuito entre los usuarios para hacer llegar el token a quien se desea.
- Binary Contdown: Un protocolo que utiliza un contador binario para coordinar el acceso al canal. Cada usuario cuenta hacia abajo y transmite cuando su contador llega a cero.

## Limited Contention Protocols
- Combina las ventajas de los protocolos de acceso aleatorio y los protocolos de acceso controlado. Utiliza un enfoque de contención limitada para reducir la probabilidad de colisiones y mejorar la eficiencia del canal.

# Ethernet

## Classic Ethernet MAC Sublayer Protocol
El protocolo de la subcapa MAC de Ethernet clásico define cómo los dispositivos en una red Ethernet comparten el medio de transmisión. Utiliza el protocolo **CSMA/CD (Carrier Sense Multiple Access with Collision Detection)** para gestionar el acceso al canal. Sus características principales son:

- **Carrier Sense**: Los dispositivos escuchan el canal antes de transmitir para asegurarse de que esté libre.
- **Multiple Access**: Varios dispositivos comparten el mismo medio de transmisión.
- **Collision Detection**: Si dos dispositivos transmiten al mismo tiempo, se detecta la colisión y ambos detienen la transmisión. Luego, esperan un tiempo aleatorio antes de volver a intentarlo.

### Ventajas
- Simplicidad en la implementación.
- Bajo costo para redes pequeñas o medianas.

### Desventajas
- La eficiencia disminuye a medida que aumenta el número de dispositivos en la red.
- No es adecuado para redes de alta demanda debido a las colisiones frecuentes.

Este protocolo fue la base de las primeras redes Ethernet y sigue siendo relevante para comprender los fundamentos de las redes modernas.

## 10-Gigabit Ethernet
El estándar de **10-Gigabit Ethernet** fue desarrollado para ofrecer velocidades 1000 veces mayores que el Ethernet original. Este estándar es utilizado principalmente en centros de datos, conexiones de alta velocidad entre routers, switches y servidores, así como en redes metropolitanas basadas en Ethernet y fibra óptica.

# Wireless LANs

Las redes LAN inalámbricas (Wireless LANs) son cada vez más populares y se utilizan en hogares, oficinas, cafeterías, bibliotecas, aeropuertos y otros lugares públicos para conectar dispositivos como PCs, laptops, tablets y smartphones a Internet. También permiten la comunicación directa entre dispositivos cercanos sin necesidad de usar Internet.

## Estándar 802.11
El estándar **802.11** ha sido el principal estándar para redes inalámbricas durante más de dos décadas. Proporciona las bases para la transmisión inalámbrica, incluyendo:

- **Capa física**: Técnicas de transmisión por radio.
- **Capa MAC**: Protocolo para gestionar el acceso al medio compartido.
- **Estructura de tramas**: Define cómo se envían y reciben los datos.
- **Servicios**: Incluyen autenticación, asociación y gestión de conexiones.

El estándar 802.11 ha evolucionado con el tiempo para soportar mayores velocidades y capacidades, siendo clave en la conectividad moderna. Para más detalles, se pueden consultar las publicaciones oficiales del IEEE.