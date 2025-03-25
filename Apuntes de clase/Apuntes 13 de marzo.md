# Redes en computadores

- Qué es una red? y por qué es una red?

- Una red son dos dispositivos conectados.

# Acceso a la información

- Buscadores en la web y celulares inteligentes muestran información desde varios sitios web.

- ¿Que hace una aplicación una aplicación web?
  
  - Una aplicación web es un software que se ejecuta en un servidor y se accede a través de un navegador web mediante una red, como Internet o una intranet. Estas aplicaciones permiten a los usuarios interactuar con contenido o servicios en línea sin necesidad de instalar software adicional en sus dispositivos.

- Modelo cliente-servidor:

  - Historicamente el acceso a recursos de información era más cara que a día de hoy, quienes accedían a los recursos lo hacían de manera remota, por eso el nombre servidor, sevía a los solicitantes de información en estos sistemas tan costosos.
  - Aún después de 50 años se sigue usando, en especial para web.
  - Dos maquinas que están conectadas.
  - Modelo: cliente hace solicitud, la pasa por la red, el servidor recibe, transforma, devuelve mediante la red y el cliente la recibe.
  - Podríamos tener una red de puros clientes sirviendose a sí mismos. (Utopía)

- Persona a Persona
  - Mensajes instantaneos.
  - Twitters multi persona.
  - Redes sociales y sus respectivas aplicaciones.
  - Docs, commits, checkout. Al final todo es lo mismo pero el uso transforma el recurso.
- Comercio electrónico

  - Es importante ver la imágen de la tabla de negocios:

    - B2C: Negocio y cliente.
    - B2B: Negocio y Negocio. (Transportar cosas tipo aliexpress)
    - G2C Estado y cliente.(Pagarle cosas al estado como matricula o impuestos)
    - C2C: Cliente y Cliente (Cosas de segunda mano)
    - P2P: Peer to Peer (Compartido, Torrents o así, muy dirigido a la ilegalididad)

- Entretenimiento

  - Sistemas IPTV.
  - Aplicaciones de Streaming.
  - Videojuegos online.
  - Mundos Virtuales.

- El internet de las cosas (IoT)

  - Aunque la finalidad de diversos productos no tenga que ver con el internet, muchos productos poseen internet de manera obicua, o sea, para que no parezca que está ahí.
  - Cosas tan locas como la pintura.

- Tipos de redes:

  - Móviles.
  - Data-Center.
  - De Tránsito.(Pasar info de un lado a otro lo más rápido posible)
  - Redes Empresariales. (Recursos de las empresas, lo más privado posible.)
  - De la casa.()
  - Ley de Melcalfe (Tarea investigar)
  - Broadband access network.

- Acceso móvil e inalambircas.

  - Portatil es distinto de inalambrico, una laptop dependiendo de su almacenamiento puede ser wireless.
  - Redes de pago, transferencias, el solo hecho de tener un datáfono.
  - NFC (Near Field Communication)
  - Sensores con redes, como las cámaras de detección de movimiento o los sensores de ropa.

- Contenido de distribuidores de red

  - Redes de data center.
  - Redes de tránsito. (Cómo llegan los datos desde aquí a tiktok?).

- Personal Area Nerworks

  - PAN (Personal Area Networks).
  - Un celular es actor tanto en mi PAN y el internet.
  - Area local, en teoría, comparten un medio, por ejemplo las compus del lab comparten, mediante el cable, un servidor.

- Red de area metropolitana (MAN).

  - Ya no se utiliza mucho, lo más sencillo es pensar en los clientes de Claro o Kolbi.

- ## Red de area extensa (WAN)

  - Unión de varias MAN que al unirse se transforman en una WAN.

- Ejemplos de Red
  - Internet
    - La ARPANET.
    - NSFNET.
    - La arquitectura de internet.
  - Redes móviles
  - Redes WIFI.
- Clases de ISP.
- Multiples paths, investigar.

# Las 7 capas

- Cada capa se encarga de algo y le da paso a la siguiente.

# Protocol Layering

![alt text](/Apuntes%20de%20clase/Imágenes/image.png)

- En esta imagen se observa que lo que el usuario envía mediante un protocolo, el que recibe debe de recibirlo y pasarlo por el proceso en inversa.
- Es importante recalcar los servicios orientados a conexión. Por ejemplo si usted necesita que se mantenga un orden.
- Los servicios no orientados a la conexión, no es necesario que se mantenga información del proceso por ejemplo.
- El profesor menciona que en distintas capas pueden haber diversas reglas o bloqueos, no es lo mejor pero al fin y al cabo así se dan.  
  ![alt text](/Apuntes%20de%20clase/Imágenes/image-1.png)

# Servicios

- # Primitivos:

  ![alt text](/Apuntes%20de%20clase/Imágenes/image-2.png)

- Ejemplo gráfico de que ambos lados necesitan implementar la misma versión, los mismos pasos y el mismo protocolo:
  ![alt text](/Apuntes%20de%20clase/Imágenes/image-3.png)

# Modelo OSI

- 7 capas.
- Posee tres conceptos centrales:
  - servicios.
  - interfaz.
  - protocolos.
- Es necesario aprenderse el nombre de las capas, SÍ.
- Posee un intermediario, un tipo operadora que tiene varias salidas, también notese que por Layer puede haber una cosa física y por parte del que recibe puede tener otra forma física, por ejemplo si son wifi o por cable.  
  ![alt text](/Apuntes%20de%20clase/Imágenes/image-4.png)
- Nadie pudo implementarlo por diversos problemas, pero es el santo grial al que aspiramos llegar. Una de las razones fue la política pues se desarrollaba en Europa.

# TCP/IP

![alt text](/Apuntes%20de%20clase/Imágenes/image-5.png)

- Posee 5 capas, no posee apartado físico.

- Es el que se usa mayormente a día de hoy, aprenderse los números de capa igual, por ejemplo la capa 7 sigue siendo aplicación. Importante que capa 3 sigue siendo red o internet, da igual decir cuálquiera.

![alt text](/Apuntes%20de%20clase/Imágenes/image-6.png)


- Se vuelve el standard y open source.
- Surgen problemas como quién dicta los estándares, o quién dice qué paises las respetan.
- WIFI Alliance.
- ONF
- Dos categorías de estándars:

  - De facto.
  - De jure.

- ISO (International standards Organization)
- Nace el IAB como descendiente de ARPANET o sea, gobierno.


- 