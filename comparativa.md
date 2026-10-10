# IDENTIFICAR ANTES DE TOCAR
## Tabla comparativa

|    | RFC 3227| NIST SP 800-86| Manual de buenas prácticas de ENFSI|
|---|---|---|---|
| **Qué consideran 'identificación'**| Enumerar los sistemas involucrados en el incidente y determinar qué  evidencias relevantes y admisibles se pueden recopilar. <br><br>Identificar también a las personas involucradas y documentar qué hicieron y observaron.| Reconocer las posibles fuentes de datos y recopilar la información relevante.<br><br>También tener en cuenta la disponibilidad de los datos, quién es su propietario y las restricciones legales para obtenerlos, además de buscar fuentes alternativas si no es posible acceder a la principal.|Localizar las evidencias digitales, priorizando las que puedan contener información relevante. <br><br>Registrar y etiquetar los elementos recogidos, indicando su ubicación, responsable, fecha y hora. <br><br>Evaluar el estado de los dispositivos y los riesgos de pérdida o alteración de datos.|
| **Fuentes de evidencia**|  - Registros y caché.<br><br>- Tabla de enrutamiento, caché ARP, tabla de procesos, estadísticas del kernel y memoria.<br><br> - Sistemas de archivos temporales. <br><br>- Disco.<br><br> - Datos de registro y monitorización remota relevantes para el sistema investigado.<br><br>- Configuración física y topología de red. <br><br>- Medios de archivo.|  - Equipos informáticos: ordenadores, servidores, portátiles y dispositivos de almacenamiento en red. <br><br>- Soportes de almacenamiento: CD, DVD, memorias USB, tarjetas de memoria y discos magnéticos y ópticos. <br><br>- Dispositivos portátiles: móviles, PDA, cámaras y grabadoras y reproductores de audio. <br><br>- Red y aplicaciones: registros de red, de proveedores de Internet (ISP) y de uso de aplicaciones.<br><br> - Registros de la organización: auditoría, registros centralizados, copias de seguridad y herramientas de seguridad.|En el manual no hay un apartado específico que las clasifique, pero a lo largo de los puntos 8 y 9 hace referencia a: <br><br> - Equipos informáticos y configuraciones de redes.<br><br> - Capturas de pantalla y datos físicos y lógicos recopilados en la escena.<br><br> - Memoria volátil y datos dinámicos de sistemas activos que pueden perderse al apagar los dispositivos. <br><br>- Sistemas de archivos y bloques lógicos (LBA) y físicos. <br><br>- Archivos y sistemas remotos como páginas web. <br><br>- Equipos de radiofrecuencia o infrarrojos. <br><br>- Sistemas embebidos y circuitos integrados|
| **Criterio de prioridades**| Propone seguir el orden de volatilidad, recopilando primero las evidencias más volátiles y después las menos volátiles. |1. Valor probable: utilidad de la fuente para investigar el incidente. <br><br>2. Volatilidad: posibilidad de que los datos desaparezcan o se modifiquen; se recopilan primero los más volátiles. <br><br>3. Esfuerzo necesario: tiempo, recursos, coste y dificultad de adquisición. |1. La volatilidad de los datos que se pretenden adquirir. <br><br>2. La antigüedad y el estado del elemento presentado. <br><br>3. La eliminación automática de datos no asignados por parte del sistema. <br><br>4. El nivel de seguridad aplicado por el usuario original.|


## ¿En qué coinciden?

Las tres normas coinciden en que es importante identificar las fuentes de información y recoger las evidencias que puedan ser útiles para la investigación. Además, las fuentes de evidencia que contemplan son bastante similares. 

También tienen en cuenta la volatilidad de los datos, ya que algunos pueden perderse o modificarse si no se recogen a tiempo, por lo que es importante tenerlo en cuenta desde el principio.


## Diferencias
Tanto RFC 3227 como NIST SP 800-86 tienen en cuenta a las personas involucradas y la información que pueden aportar a la investigación. En cambio, el manual ENFSI hace más hincapié en la localización de las evidencias, su registro, su estado y la documentación de la escena.

Otra diferencia importante está en los criterios de prioridad. El NIST, aunque también le da importancia a la volatilidad, coloca en primer lugar el valor probable de la fuente para la investigación, mientras que los otros dos sí lo ponen en primer lugar. El manual ENFSI, además de considerar la volatilidad, tiene en cuenta factores como la antigüedad, el estado del elemento y el riesgo de pérdida de datos.

En general, el manual ENFSI profundiza en las precauciones necesarias para evitar que las evidencias se estropeen, pierdan su utilidad o desaparezcan, incluso por acciones remotas. NIST SP 800-86 ofrece una visión amplia de las fuentes de evidencia y de los criterios para seleccionarlas, mientras que RFC 3227 presenta de forma más esquemática el proceso de recopilación y el orden de volatilidad. 

En conjunto, las tres referencias se complementan, ya que cada una se centra más en unos aspectos que en otros, lo que ayuda a tener una visión más completa a la hora de identificar las evidencias.


