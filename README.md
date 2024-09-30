




![image](https://github.com/user-attachments/assets/b9b459e6-c079-44f8-9bf8-c729b67f8c18)





# Trabajo-Capa-Fisica
¿Cúal es la capa física del sistem OSI?
La capa física es la responsable de los equipos físicos y la que posibilita la transferencia de datos, como cables y routers instalados en la red.

¿Qué funciones desempeña la capa física?
La tarea principal de la capa física es la conexión física entre dos unidades dentro de una red. La capa física se encarga de establecer e interrumpir la conexión y supervisa su funcionamiento durante la transmisión de información. El elemento más importante de esta transmisión son los bits como unidad más pequeña de información.

Además de la transmisión propiamente dicha, el physical layer también regula la estructura de los bits, su valor y sus distintos métodos de transmisión. Los datos se transmiten bit a bit, se procesan, se consolidan y se cambian si es necesario. Durante el proceso, la capa física no distingue entre los bits de información y los bits de control y no corrige errores.
La capa física se limita a establecer la conexión física, a transmitir todos los datos como un flujo en forma de bits y a garantizar la correcta desconexión al final de la transmisión. Además, el physical layer asume algunas funciones administrativas manejando voltajes e impulsos elécttricos y comprobando en qué dirección va la transmisión. 

¿Qué servicios presta la capa física?
La capa física proporciona información a las demás capas para permitir una conexión fluida. La información puede ser, por ejemplo, en forma de señales de radio, señales luminosas o señales eléctricas. La elección del hardware adecuado para una red y la decisión del tipo de red adecuado también están estrechamente relacionados con la capa física.
Los parámetros que se definen en la capa física también influyen en las demás capas. Entre ellos, la elección del medio de transmisión, la función de cada línea, la velocidad de transmisión y el ya mencionado sentido de transmisión, que puede ser simplex (en una dirección), half duplex (alternando entre ambas direcciones) o full duplex (simultáneamente en ambas direcciones).

¿Qué componentes corresponden al physical layer?
Son varios los componentes de hardware que garantizan el cumplimiento de las especificaciones de la capa física. A grandes rasgos, los componentes se pueden dividir en pasivos y activos, por lo que algunos de ellos también pueden tener una influencia directa en la siguiente capa. 

El siguiente hardware forma parte de los componentes pasivos:

- Resistencias de terminación
- Antenas
- Tomas de corriente
- Cables
- Conectores
- Conectores en T

Entre los componentes activos de la capa física se encuentran los siguientes:

- Hubs
- Tarjetas de red
- Repetidores
- Transceptores
- Amplificadores

  Importancia de la capa física en el diseño de redes
  
La capa física del modelo OSI es clave en toda esta infraestructura de redes y puede que a estas alturas del artículo tengas bastante claro los motivos. A modo de resumen, aquí la importancia en el diseño:

Es el pilar fundamental para que se produzca la transmisión de datos en el resto de las capas del modelo OSI.
Es la facilitadora para transformar las señales físicas en información binaria que atraviese el esto del sistema.
Los materiales de la capa física son determinantes para influir en el ancho de banda y la calidad de la señal.
La capa física también es crucial para escalar la amplitud de la señal o la red.
Es una de las claves para solucionar problemas de red y realizar ajustes para optimizar la transmisión de la señal con cableado, ubicación o materiales.

¿Qué tecnologías se fundamentan en la capa física?
Son muchas las tecnologías que ofrecen una capa física y funcionan según los principios del modelo OSI. Entre ellas se encuentran las siguientes:

- 1-Wire: un protocolo de comunicaciones en serie (transmisión y recepción) que también puede utilizarse como fuente de alimentación.
- 2-Bluetooth: el estándar del sector para la transmisión de datos a corta distancia.
- 3- DSL: varios estándares de capa física para la transferencia de datos a través de líneas de cobre a altas velocidades de transmisión.
- 4- E-carrier: sistema de portadora para la transmisión digital simultánea de diferentes llamadas telefónicas.
- 5- Ethernet: la transmisión de datos por cable dentro de una red de área local (LAN, Local Area Network).
- 6- FireWire: una antigua interfaz en serie con una alta velocidad de transmisión de datos.
- 7- GMS: una norma estandarizada de radiocomunicación móvil para redes de radiocomunicación móvil digital.
- 8- IEEE 802.15.4: un estándar para la transmisión en redes WPAN.
- 9- IrDA: asociación de empresas para la normalización de receptores de infrarrojos.
- 10-ISDN: norma internacional para las redes de telecomunicaciones digitales.
- 11- PCI Express: norma para conectar dispositivos periféricos a un procesador principal.
- 12- SONET/SDH: una técnica de multiplexación para la transmisión síncrona mediante fibra óptica.
- 13- USB: sistema de transferencia de datos entre ordenadores y dispositivos externos.
- 14- Wifi: dispositivos y redes WLAN según la norma IEEE 802.11.
- 15- X10: un protocolo para la automatización de edificios mediante señales de conmutación.

  Componentes de la Tarjeta de Red 
  
A continuación, se presentan los componentes comunes de una tarjeta de red:

- 1. Controlador de red (Network Controller): Es el corazón de la tarjeta de red, responsable de gestionar la comunicación entre la computadora y la red. Es un chip especializado que ejecuta protocolos de red como TCP/IP, Ethernet, Wi-Fi, etc.

- 2. Interfaz de red física (Physical Layer Interface): Es el componente que se encarga de la conexión física con la red, como por ejemplo, el conector RJ-45 para Ethernet o el conector Wi-Fi para redes inalámbricas.

- 3. Buffer de paquetes (Packet Buffer): Es un área de memoria que almacena los paquetes de datos en tránsito entre la computadora y la red. Esto ayuda a mejorar el rendimiento y reducir la latencia en la comunicación.

- 4. DMA (Direct Memory Access) Controller: Es un circuito que permite al controlador de red acceder directamente a la memoria principal de la computadora, sin necesidad de involucrar al procesador principal. Esto mejora el rendimiento y reduce la carga de trabajo del procesador.

- 5. Interruptor (Interrupt): Es un circuito que envía señales al procesador principal cuando se produce un evento en la tarjeta de red, como la recepción de un paquete o la pérdida de conexión.

- 6. LED (Light Emitting Diode): Son luces indicadoras que se utilizan para mostrar el estado de la conexión, como por ejemplo, la luz verde para indicar que la tarjeta está funcionando correctamente o la luz roja para indicar problemas de conexión.

- 7. Chipsets: Son conjuntos de circuitos integrados que trabajan juntos para proporcionar funcionalidades específicas, como por ejemplo, el chipset Ethernet para manejar la comunicación Ethernet.

- 8. Componentes de soporte: Incluyen componentes como resistores, condensadores, inductores y otros elementos pasivos que se utilizan para estabilizar la señal y proteger los circuitos electrónicos.

Es importante destacar que los componentes específicos pueden variar dependiendo del tipo de tarjeta de red (Ethernet, Wi-Fi, Token Ring, etc.) y del fabricante. Además, algunas tarjetas de red pueden incluir componentes adicionales, como por ejemplo, un controlador de seguridad o un firmware para gestionar la autenticación y autorización en la red.

SEÑALIZACION Y CODIFICACION FISICA . REPRESENTACION DE BITS
SEÑALIZACION DE BIT PARA LOS MEDIOS

Eventualmente todas las comunicaciones desde la red humana se convierten en digitos binarios que se transportan individualmente atravez de los medios fisicos. La capa fisica representa cada uno de los bits de la trama como una señal. cada señal ubicada en los medios cuenta con un plazo especifico de tiempo para ocupar los medios. esto se denomina tiempo de bit.cada extremo de la transmision mantiene su propio reloj. Las señales se procesan mediante el dispositivo receptor y se vuelven a enviar para representarlas como bits.

MODOS DE SEÑALIZACION

Los bits se representan en el medioal cambiar una o mas de las iguientes caracteristicas de la señal

- Amplitud
- Frecuencia
- Fase

La naturaleza de los metodos reales que representan los bit en el medio dependera del mètodo de señalizacion que se utilice. algunos mètodos pueden utilizar un atributo de señal para representar un unico '0' o un unico'1'
Por ejemplo: NRZ mètodo sin retorno acero; un '0' puede representarce mediante un nivel de voltaje en los medios durante el tiempo de bit y un '1' mediante el voltae diferente

Tmbien existen mètodos de señalizacion que utilizan transiciones, o la ausencia de las mismas, para indicar un nivel logico.

El mètodo de señalizacion utilizado debe ser compatible con un estandar para que el receptor pueda detectar las señales y decodificarlas

SEÑALIZACION NRZ

El stream de bits se transmite como una secuencia de valores de voltaje; un valor de bajo voltaje representa un '0'lògico y un valor de alto voltaje representa un '1' lògico.
Este mètodo simple de señalizaciòn solo es adecuado para enlace de datos de velocidad lenta, no utiliza el ancho de banda de manera eficiente y es susceptible a la interferncia electromagnetica. Ademas los limites entre bits individuales pueden perderce al transmitir en forma consecutiva secuencias largas de '1' o '0'.

CODIFICACION MANCHESTER

En lugar de representar bits como impulsos de valores simples de voltajes.
por ejemplo : una transicion desde un voltaje bajo a uno alto representa el valor de bit de 1. una transicion de un voltaje alto a uno bajo representa el valor de bit de 0.
se debe realizar una transicion de voltaje en medio de cada tiempo de bit.la direccion sera ascendente o descendente . seguridad al sincronizar. no es eficiente par ser utilizada en señalizaciones superiores (ETHERNET).

CODIFICACION. AGRUPACION DE BITS

Al utilizar el paso de codificacion antes de ubicar las señales en los medios, mejoramos la eficiencia mediante una transmicion de datos de mayor velocidad; la velocida corrompe datos. pero al utiliza la codificacion detectamos errores de manera eficiente.
la capa fisica del dispositivo de reddebe ser capaz de detectar señales legitimas de datos e ignorar señales aleatorias sin datos que tambien pueden encontrarce en el medio fisico. el stream de señales que se transmite necesita iniciarcede tal forma que el receptor reconozca el inicio y el final de la trama.

PATRONES DE SEÑALES

Una forma de detectar tramas es iniciar cada trama con un patron de señales que represente los bits que la capa fisica reconoce como un indicador del comienzo de una trama. otro patron de bits señalara el final de la trama. los bits de datos validos de una trama deben aguparse en una trama; de lo contrario los bits de datos se recibiran sin ningun contextopara darle significado a la capas superiores del modelo de la red

GRUPOS DE CODIGOS

Las tècnicas de codificacion utilizan patrones de bits denominados simbolos. es posible que la capa fisica utilice un conjunto de simbolos codificados denominados grupos de codigos para representar la informacion de control o datos codificados.
un grupo de codigo es una secuencia de consecutiva de bits de codigo que se interpretan y asignan como patrones de bits de datos.

ventajas
- Reduccion de nivel de error en los bits
- Limitacion de la energia efectiva transmitida a los medios
- Ayuda para distinguir los bitsde datos de los bits de control
- Mejoras en la deteccion de errores en los medios

REDUCCION DE ERRORES EN EL NIVEL DE BITS

Este paso requiere la sincronizacion de los tiempos entre el receptor y el transmisor; los grupos de codigos se diseñan para que los simbolos obliguen la introduccion de un amplio numero de transacciones de bits en los medios para sincronizar estos tiempos

MEDIOS FISICOS: CONEXION DE LA COMUNICACION

Los estandares para los medios de cobre se definen segun lo siguiente

- Tipo de cableado de cobre utilizado
- Ancho de banda de la comunicacion
- Tipo de conectores utilizados
- Diagrama de pines y codigos de colores de las conexiones a los medios
- distancia maxima de los medios

MEDIOS DE COBRE

El medio mas utilizado para las comunicaciones de datos es el cableado que utiliza alambres de cobre para señalizar bits de control y datos entre los dispositivos de red.
El tipo de medio de cobre elegido seespecifica por el estandar de la capa fisica necesario para enlazar las capas de enlace de dos o mas dispositivos de red.
estos cables pueden utilizarce para para conectar los nodos de una LAN a los dispositivos intermedios como router o switches. tambien para dispositivos WAN a un proveedor de servicios de datos.
INTERFERENCIA SEÑAL EXTERNA

Los datos se transmiten en cables de cobrecomo impulsos electricos.
Los tipos de cable con blindage o trenzado de pares de alambre estan diseñados para minimizar la degradacion de señales debido a ruido electronico, lo cual puede estar limitada por

- seleccion de tipo o categoriade cable mas adecuadopara proteger las señales de datosen un entorno de networking determinado
- Dseño de una infraestructurade cables para evitarlas fuentes de interfercncia posiblesy conocidas
- Utilizacion de tecnicas del cableado que incluyen el manejo y la terminacion apropiada de los cables

CABLE PAR TRENZDO NO BLINDADO (UTP)

Se utiliza en las LAN ETHERNET . consiste en 4 pares de alambre codificados por color que han sido trenzados y cubiertos por un revestimiento de plastico flexible. E l trenzado cancela las señales no deseadas

ESTANDARES DE CABLEADO UTP

El cableado utp que se encuentra comunmente en el trabajo , las escuelas, los hogares , cumple con los estandares estipulados en conjunto por la asociacion de industrias de las telecomunicaciones (TIA) y la Asociacion de industrias electronicas (EIA). (TIA\EIA)568A Etipula los estandares de cableado para las instalaciones LAN y es el estandar de mayor uso en entornos de cableado LAN.
elementos definidos

- tipos de cables
- longitudes de los cables
- conectores
- terminacion de los cables
- mètodos para realizar pruebas de cables

TIPOS DE CABLE UTP

UTP tiene una terminacion de conectore RJ45
- cable directo de ethernet
- cruzado de ethernet
- consola

OTROS CABLES DE COBRE

- coaxial
-par trenzado bindado

CABLE COAXIAL
Consiste en un conector de cobre rodeado con una capa de aislante flexible.

USO DE CABLE COAXIAL
es el medio de uso mas frecuente para transportar señales elevadas de radiofrecuencia mediante cableado, especialmente señales de television por cable.

CABLE DE PAR TRENZADO BLINDADO
El cable stp cubre todo el grupo de alambres dentro del cable al igual que los pares de alambres individuales.stp ofrece una mejor proteccion contra el ruido que el cableado utp pero a un precio mayor

SEGURIDA DE LOS MEDIOS DE COBRE

PELIGRO POR ELECTRICIDAD
Los alambres de cobre puedes conducir la electricidad de manera no deseada. Un dispositivo de red defectuoso podria conducir la corriente al shasis de otros dispositivos de red. para evitar esto y toros es necesario instalar correctamente el cableado segun especificaciones relevantes y los codigos de edificacion
MEDIOS DE FIBRA

Utiliza fibras de plastico o de vidrio para enviar los impulsos de luz desde el origen hacia el destino. Los bits se codifican en la fibra como impulsos de luz; puede generar velocidades superiores de ancho de banda para transmitir datos sin procesar

COMPARACION ENTRE CABLEADO DE COBRE Y FIBRA OPTICA

La fibra optica es inmune a la interferencia electromagnetica y no conduce corriente electrica no deseada cuando existe y problema de conexion a tierra.las fibras pueden utilizarce en longitudes mucho mayores que el cobre. la fibra es mas costosa y se requiere mejor teminacion de la misma

PRODUCCION Y DETECCION DE SEÑALES OPTICAS

lazer odiodos de emision de luz.La luz del lazer transmitida atravez del cableado de fibra optica puede dañar el ojo humano, se debe tener precaucion y evitar mirar dentro del extremo de una fibra optica activa.

FIBRA MULTIMODO Y MONO MODO

- MONOMODO: transporta un solo rayo de luz, generalmente emitido desde un laser
- MULTIMODO: utiliza emisores LED que no generan una unica ola de luz coherente

MEDIOS INALAMBRICOS

Transpot¡rtan señales electromagneticas mediante frecuencias de microondas y radiofrecuencias que representan los digitos binarios de las comunicaciones de datos.como medio de red no se limita a conductores o canaletas

TIPOS DE REDES INALAMBRICAS

Los 4 estandares comunes de comunicacion de datos que se aplican a los medios inalambricos son

- IEEE Estandar 802.11: tecnologia LAN inalambrica
- IEEE Estandar 802.16 utiliza una tecnologia punto amultipunto para generar un acceso de ancho de banda inalambrico
- IEEE Estandar 802.15: red area persoanl inalambrica
- sistema global para comunicaciones moviles (GSM)

LAN INALAMBRICA

Requiere de los dispositivos de red

- PUNTO DE ACCESO INALAMBRICO(AP):concntra las señales inalambricas de los usuarios y se conecta atravez de un cable de cobre, ala infraestructura de red existente basada en cobre, como ethernet
- ADAPTADORES NIC INALAMBRICOS: Proporciona capacidad de comunicacion inalambrica a cada host de la red

CONECTORES DE MEDIOS

CONECTORES COMUNES DE MEDIOS DE COBRE

El conector RJ45 definido por ISO 8877 se utiliza para diferentes especificaciones de la capa fisica en las que se incluye ethernet. otra especificacion EIA-TIA568 describe los codigos de elcolor de los cables para colocar pines a las asignaciones conexion cruzada y ethernet

TERMINACION CORRECTA DEL CONECTOR

Cada vez que se termina un cableado de cobre existe la posibilidad de que se pierda la señal y de que se genere ruido en el circuito de comunicacion. es fundamental que todas las terminaciones de medios de cobre sean de calidad superior para garantizar un funcionamiento optimo con tecnologias de rede actuales y futuras.

CONECTORES COMUNES DE FIBRA OPTICA

PUNTA RECTA (ST): utilizado con fibra multimodo
CONECTOR SUSCRIPTOR(SC): conector que utiliza un mecanismo de doble efecto para asegurar al insercion positiva, se utiliza con fibra monomodo
CONECTOR LUCENT (LC): conector pequeño que esta adquiriendo popularidad en su uso con fibra monomodo


