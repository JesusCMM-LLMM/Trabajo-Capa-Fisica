
# Capa Física (1) - Modelo OSI
 
## ¿Qué es el modelo OSI?
 
El modelo Open Systems Interconnection (OSI) es un marco conceptual desarrollado por la Organización Internacional para la Estandarización (ISO) que estandariza las funciones de un sistema de comunicación en siete capas. Cada capa tiene una función específica y está diseñada para interactuar con la superior e inferior, permitiendo la interoperabilidad entre diferentes tecnologías y sistemas.
 
## Función de la capa física
 
La capa física (Capa 1) es la primera capa del modelo OSI y se encarga de la transmisión de datos en bruto desde el emisor hasta el receptor a través de medios físicos. Es responsable de convertir los bits digitales en señales físicas y enviarlas a través de medios como cables de cobre, fibra óptica o mediante ondas de radio.
 
En resumen, la capa física define los mecanismos eléctricos, mecánicos y de procedimiento para activar, mantener y desactivar conexiones físicas entre dispositivos de red.
 
### Principales funciones de la capa física:
- **Codificación de datos**: Transformar bits en señales eléctricas, ópticas o de radiofrecuencia que pueden ser transmitidas a través de un medio físico.
- **Transmisión y recepción de datos**: Enviar y recibir secuencias de bits a través de los medios de transmisión.
- **Sincronización de bits**: Asegurar que el emisor y el receptor estén sincronizados, es decir, que ambos sepan cuándo comienza y termina una transmisión de datos.
- **Especificaciones del medio físico**: Definir las características del cableado, conectores, interfaces y demás hardware que se utiliza para la transmisión de datos.
- **Topologías de red**: Determinar la disposición física de los nodos en una red (bus, estrella, anillo, etc.).
 
## Componentes de la capa física
 
### Medios de transmisión
 
La capa física utiliza diferentes medios para transmitir los datos, y cada medio tiene sus propias características y limitaciones:
 
- **Cables de cobre (par trenzado y coaxial)**: Los cables de cobre son uno de los medios más comunes en la transmisión de datos, usados principalmente en redes de área local (LAN). El cable de par trenzado (UTP/STP) se utiliza para Ethernet, mientras que el cable coaxial se usaba en redes más antiguas y sistemas de televisión por cable.
 
- **Fibra óptica**: La fibra óptica utiliza pulsos de luz para transmitir datos y ofrece una mayor velocidad y capacidad que los cables de cobre. Es ideal para largas distancias y entornos que requieren alta capacidad de ancho de banda.
 
- **Medios inalámbricos**: Las ondas de radio, microondas y señales infrarrojas son utilizadas en redes inalámbricas, como Wi-Fi y Bluetooth, para transmitir datos a través del aire. Estos medios son menos confiables que los cables en términos de interferencia, pero ofrecen mayor flexibilidad y movilidad.
 
### Señalización
 
La señalización en la capa física puede ser de diferentes tipos, dependiendo del medio y la tecnología:
 
- **Señalización analógica**: Se utiliza en tecnologías más antiguas, como la telefonía analógica, donde las señales son ondas continuas que varían en amplitud, frecuencia o fase.
 
- **Señalización digital**: En las redes modernas, la señalización digital convierte los datos en pulsos discretos (unos y ceros) que se transmiten a través del medio físico. Esta es la señalización dominante en redes Ethernet.
 
### Especificaciones de la capa física
 
La capa física también define las características mecánicas y eléctricas del medio de transmisión, tales como:
 
- **Voltaje y corriente**: Define los niveles de voltaje y la cantidad de corriente que se utiliza para representar los bits (1s y 0s) en las conexiones por cable.
 
- **Velocidad de transmisión**: Define la cantidad de bits por segundo (bps) que pueden ser transmitidos a través del medio. Las velocidades de transmisión varían según el medio, con Ethernet a 10 Mbps, Fast Ethernet a 100 Mbps, Gigabit Ethernet a 1 Gbps, etc.
 
- **Distancia máxima**: Cada medio tiene una distancia máxima de transmisión antes de que la señal se degrade y sea necesario un repetidor o amplificador.
 
### Estándares de la capa física
 
Hay varios estándares que especifican cómo funciona la capa física en diferentes tecnologías de red. Algunos de los más comunes son:
 
- **Ethernet (IEEE 802.3)**: Define la capa física y de enlace de datos para redes LAN cableadas.
 
- **Wi-Fi (IEEE 802.11)**: Define la capa física y de enlace de datos para redes inalámbricas.
 
- **Bluetooth (IEEE 802.15)**: Define los estándares de la capa física para redes de área personal inalámbricas (PAN).
 
- **USB (Universal Serial Bus)**: Define los estándares para conexiones físicas entre dispositivos periféricos y computadoras.
 
## Proceso de transmisión de datos
 
Para que los datos puedan viajar a través de la red, deben ser convertidos en una secuencia de bits y luego en señales físicas. El proceso es el siguiente:
 
1. **Codificación**: Los datos se transforman en una secuencia de unos y ceros.
2. **Señalización**: La secuencia de bits se convierte en una señal eléctrica, óptica o inalámbrica.
3. **Transmisión**: La señal viaja a través del medio físico.
4. **Recepción**: El dispositivo receptor captura la señal, la convierte nuevamente en bits y la pasa a la capa de enlace de datos.
 