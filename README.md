# holbertonschool-network

# holbertonschool-network

Modelo OSI

¿Qué es el Modelo OSI?

El Modelo OSI (Interconexión de Sistemas Abiertos) es un marco conceptual que ayuda a entender cómo interactúan los diferentes protocolos de red. Divide el proceso de comunicación en redes en capas, de manera que cada capa maneja una parte específica de la comunicación sin depender de los detalles de las otras capas.

¿Cuántas Capas Tiene?

El Modelo OSI tiene siete capas. Estas capas garantizan que los datos puedan ser enviados de un dispositivo a otro de manera confiable y eficiente.

¿Cómo Está Organizado?

Las capas del Modelo OSI, de arriba hacia abajo, son:

Capa de Aplicación: Donde los usuarios interactúan con los servicios de red (por ejemplo, navegadores web).

Capa de Presentación: Traduce formatos de datos (por ejemplo, cifrado, codificación).

Capa de Sesión: Gestiona las sesiones entre dispositivos (por ejemplo, apertura y cierre de conexiones).

Capa de Transporte: Garantiza la transferencia confiable de datos (por ejemplo, TCP/UDP).

Capa de Red: Maneja el direccionamiento y el enrutamiento (por ejemplo, direcciones IP).

Capa de Enlace de Datos: Controla la transferencia de datos entre dispositivos en la misma red.

Capa Física: Se encarga de la transmisión física de los datos (por ejemplo, cables, switches).

¿Qué es una LAN?

Uso Típico

Una LAN (Red de Área Local) conecta dispositivos dentro de un área geográfica limitada, como un hogar, oficina o escuela. Se usa comúnmente para compartir recursos como impresoras, archivos y conexiones a internet.

Tamaño Geográfico Típico

Una LAN generalmente cubre un área geográfica pequeña, como un edificio o un campus.

¿Qué es una WAN?

Uso Típico

Una WAN (Red de Área Amplia) conecta dispositivos en un área geográfica extensa. El ejemplo más común de una WAN es internet.

Tamaño Geográfico Típico

Una WAN puede cubrir ciudades, países o incluso continentes.

¿Qué es Internet?

Internet es una red global de computadoras interconectadas que utilizan protocolos estandarizados para comunicarse. Es, esencialmente, una WAN masiva que conecta millones de redes privadas, públicas, académicas, comerciales y gubernamentales.

¿Qué es una Dirección IP?

Una dirección IP (Protocolo de Internet) es un identificador único asignado a cada dispositivo conectado a una red. Permite que los dispositivos se encuentren y se comuniquen entre sí.

¿Cuáles Son los 2 Tipos de Direcciones IP?

IPv4: Formato de dirección de 32 bits, escrito como cuatro números separados por puntos (por ejemplo, 192.168.1.1).

IPv6: Formato de dirección de 128 bits, escrito como ocho grupos de cuatro dígitos hexadecimales (por ejemplo, 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

¿Qué es Localhost?

Localhost se refiere al dispositivo que estás usando en ese momento. Es una forma de referirse a la interfaz de red de tu propia computadora. La dirección IP para localhost suele ser 127.0.0.1.

¿Qué es una Subred?

Una subred (subnetwork) es una parte más pequeña y segmentada de una red más grande. Las subredes ayudan a reducir el tráfico y aumentar la seguridad agrupando lógicamente los dispositivos dentro de una red.

¿Por Qué se Creó IPv6?

IPv6 se creó para solucionar la escasez de direcciones IPv4. Con el formato de 32 bits de IPv4, el número total de direcciones posibles es de aproximadamente 4.3 mil millones, lo cual no fue suficiente a medida que aumentó la cantidad de dispositivos conectados a internet. IPv6 proporciona un conjunto mucho más grande de direcciones.

TCP/UDP

¿Cuáles Son los 2 Principales Protocolos de Transferencia de Datos para IP?

Los dos principales protocolos son:

TCP (Protocolo de Control de Transmisión)

UDP (Protocolo de Datagrama de Usuario)

¿Cuál es la Principal Diferencia entre TCP y UDP?

TCP: Garantiza la entrega confiable, ordenada y verificada de los datos. Se utiliza para aplicaciones donde la precisión es crucial, como la navegación web y el correo electrónico.

UDP: Es más rápido pero menos confiable. Se utiliza para aplicaciones en tiempo real como transmisión de video y juegos en línea, donde la velocidad es más importante que la precisión.

¿Qué es un Puerto?

Un puerto es un número que identifica un proceso o servicio específico en un dispositivo. Ayuda a dirigir el tráfico de red entrante y saliente al servicio correcto.

Números de Puertos Importantes para Memorizar

SSH: Puerto 22

HTTP: Puerto 80

HTTPS: Puerto 443

¿Qué Herramienta/Protocolo se Usa Frecuentemente para Verificar si un Dispositivo Está Conectado a una Red?

El comando Ping se usa comúnmente para probar si un dispositivo es accesible en una red. Envía un pequeño paquete de datos al dispositivo objetivo y espera una respuesta, lo que indica conectividad.

