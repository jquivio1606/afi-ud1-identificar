# IDENTIFICAR ANTES DE TOCAR
## Lista de comprobación


Con lo que has leído, construye la lista de comprobación que llevarías a una escena real: 
lo que tienes que mirar, preguntar y decidir para no dejarte ninguna fuente atrás. 

la norma y el apartado de los que sale, por ejemplo «RFC 3227 §2.1». 

Debería tener entre 15 y 25 puntos y caber en dos caras de A4. 

### Al llegar

- Asegurar físicamente el lugar para evitar el acceso no autorizado (NIST SP 800-86 §3.1.2; ENFSI §8.2)

- Confirmar el alcance de la intervención. ¿Qué dispositivos, personas, cuentas y espacios puedo examinar legalmente? ¿Hay restricciones de privacidad? (RFC 3227 §2.3–2.4; NIST SP 800-86 §3.1.1; ENFSI §8.2)

- Identificar a las personas involucradas y documentar qué hicieron y observaron. (RFC 3227 §3.2)

- Localizar los sistemas involucrados en el incidente, las posibles fuentes de datos. (NIST SP 800-86 §3.1.1)

- Comprobar si existen fuentes de evidencia fuera del lugar físico, como servicios en la nube, copias de seguridad, registros remotos o dispositivos de terceros, y anotar dónde están y quién tiene acceso. (NIST SP 800-86 §3.1.1)

- Fotografiar el lugar de los hechos, los equipos, las conexiones, las pantallas visibles, los periféricos y su disposición. (NIST SP 800-86 §3.1.2; ENFSI §8.2)


### Antes de tocar

- Evitar pérdida de datos:  (RFC 3227 §2; ENFSI §8.2)
    - Registrar si los equipos/evidencias están encendidos, apagados, bloqueados o en suspensión, y no modificarlos.
    - Evaluar los riesgos de pérdida o alteración de datos al desconectar el dispositivo de la red o corriente eléctrica.
    - Evaluar cómo evitar modificaciones externas como borrado remoto o la activación de un malware.

- Registrar y etiquetar los elementos recogidos, indicando su ubicación, responsable, fecha y hora. (ENFSI §8.2)

- Preparar herramientas adecuadas y fiables, y que modifiquen lo menos posible las pruebas. (RFC 3227 §5; NIST SP 800-86 §3; §3.1.2; ENFSI §9.6)

- Anotar el identificador único de cada elemento y mantener la cadena de custodia, registrando quién lo recoge y quién lo recibe. (RFC 3227 §4.1)

### Al decidir qué se adquiere

- Evaluar si el examen se iniciará como un análisis completo o si se basará en un método de elaboración de informes por fases. (ENFSI §9.5)

- Determinar qué fuentes son relevantes para el incidente y justificar cuáles se adquirirán. (NIST SP 800-86 §3.1.1–3.1.2)

- Hacer una copia del original y trabajar sobre las copias. (RFC 3227 §2; NIST SP 800-86 §3.2)

- Documentar el orden en que se van a examinar las fuentes de evidencia. (RFC 3227 §3.2; NIST SP 800-86 §3.1.2)

- Registrar todos los datos de red, cortafuegos, servidores, sistemas de monitorización y logs que puedan sobrescribirse. (RFC 3227 §2.1; NIST SP 800-86 §3.1.1)

- Preparar los formularios necesarios antes de iniciar la adquisición: identificación de evidencias, registro de actuaciones, adquisición y verificación de integridad, e historial de cadena de custodia. (RFC 3227 §3.2; §4.1)


### ¿En qué orden?

- Si el sistema está encendido, o conectado a la corriente, a la red u otro sitio, valorar primero los datos volátiles que pueden desaparecer al desconectarlo. (RFC 3227 §2.1; ENFSI §9.6)

- Si no está encendido, priorizar por valor probatorio, volatilidad y esfuerzo de adquisición. (RFC 3227 §2.1; NIST SP 800-86 §3.1.2)
