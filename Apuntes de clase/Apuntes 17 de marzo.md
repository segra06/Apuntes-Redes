# Almacenamiento persistente

- La forma de transmitir datos digitales más usada es la electrónica, sin olvidar que existe el magnetismo.
- It is often more cost effective, especially for applications where a high data rate or cost per bit transported is the key factor.

# Cables

- Cable coaxial, años 70, la calidad del cobre y del equipo era bastante mala, nace la era de lo electrónico... El problema es que un alto voltaje podía quemar los equipos, ahí es donde nace este cable, por eso el grosor del cobre, tiene 3 capas antes del cobre, una de esas capas es la maya de aluminio. El color negro funciona como aislante de la luz. Por dentro posee una capa blanca de pvc mpas resistente, resiste hasta 90 grados.
  Las primeras computadoras conectadas en red utilizaban cable coaxial. Varios cientos de metros.

- Importa la capa física con enlace, dependiendo del largo del cable debe de pensar en la resistencia.
  Nace el primer cable transoceanico, de cobre. Comunicaba New York y Londres.

- Con geles y cremas dieléctricas para repeler el agua.

- **Cables telefónicos**: Cable de cobre con chaqueta. Posee una cabecilla que tiene una guía con canales pequeños que llevan hasta las cuchillas. Nace el RJ11, este es el conector. Para estos cables nace la idea de 4 cables, uno izquierdo y derecho para cada lado de la llamada, con el problema de que se pasaban los electrones de un lado a otro, creandose **crosstalk** que es que se pasan de un lado a otro. El tipo de cable se llama Par Prensado o TP. Este minimiza, no elimina que los e se pasen de cable. A día de hoy solo se utiliza uno de estos dos cables trenzados, el otro está muerto. El límite son 100m.
  ![alt text](/Apuntes%20de%20clase/Imágenes/stp.png)

- Según las necesidades de datos, se cambia tanto el cable, ahora tiene 4 y 4 y la cabecilla pasa de RJ11 a RJ45:
  ![alt text](/Apuntes%20de%20clase/Imágenes/rj.png)

**Colores de los cables**: Un buen manejo de los cables funciona para estandarizar lo colores. La EIA 568 A/B

**Multiplexor**: Con un solo medio se pueden conectar varios dispositivos. Para esta parte nace la Anto negociación para saber el orden de los cables, sin embargo pueden o no tener de esta.

En el contexto de cables de red, straight-through y crossover son dos tipos de configuraciones de cableado que se utilizan para conectar dispositivos en una red. La diferencia radica en cómo están ordenados los cables dentro del conector RJ45 en cada extremo.

patch cord se traduce como cable de parcheo o simplemente cable de red. Es un cable corto, generalmente con conectores RJ45 en ambos extremos, que se utiliza para conectar dispositivos de red, como computadoras, switches, routers o paneles de parcheo (patch panels).

# Laser

Un **láser** (Light Amplification by Stimulated Emission of Radiation) es un dispositivo que emite luz coherente, monocromática y altamente concentrada mediante un proceso de amplificación óptica basado en la emisión estimulada de radiación.

### Características principales:

- **Coherencia**: Los fotones emitidos están en fase, lo que permite que la luz sea altamente direccional.
- **Monocromaticidad**: La luz tiene una sola longitud de onda (color).
- **Alta intensidad**: La energía está concentrada en un haz estrecho.

### Usos en telecomunicaciones:

- Transmisión de datos a través de fibras ópticas.
- Comunicación de alta velocidad y larga distancia.
- Aplicaciones en redes ópticas y láseres de semiconductores para enlaces de datos.

Recordar que los espejos son vitales para todo esto. LED.

## Medios no guiados

Los medios no guiados son aquellos que no requieren un medio físico para la transmisión de datos, ya que utilizan el espacio libre como canal de comunicación. Estos medios son esenciales para las comunicaciones inalámbricas.

### Tipos principales:

1. **Ondas de radio**:
  - Utilizadas en redes Wi-Fi, Bluetooth, y comunicaciones móviles.
  - Pueden cubrir largas distancias dependiendo de la frecuencia y potencia de transmisión.
  - Sensibles a interferencias y obstáculos físicos.

2. **Microondas**:
  - Utilizadas en enlaces punto a punto y comunicaciones satelitales.
  - Requieren una línea de vista directa entre los transmisores y receptores.
  - Alta capacidad de transmisión de datos.

3. **Infrarrojo**:
  - Utilizado en controles remotos y comunicaciones de corto alcance.
  - Requiere línea de vista directa y no atraviesa obstáculos.

4. **Láser**:
  - Utilizado para enlaces ópticos inalámbricos.
  - Alta velocidad de transmisión, pero requiere alineación precisa y es sensible a condiciones climáticas.

### Ventajas:
- No requieren infraestructura física como cables.
- Flexibilidad para establecer conexiones en áreas remotas o de difícil acceso.

### Desventajas:
- Mayor susceptibilidad a interferencias y condiciones ambientales.
- Limitaciones en la seguridad debido a la naturaleza abierta del medio.

Estos medios son fundamentales en la era de las comunicaciones inalámbricas, permitiendo la conectividad en una amplia gama de aplicaciones.

# Categorías del UTP
