# IDENTIFICAR ANTES DE TOCAR
## Lista de comprobación

### Al llegar

1. Asegurar físicamente el lugar para evitar el acceso no autorizado (NIST SP 800-86 §3.1.2; ENFSI §8.2)

2. Confirmar el alcance de la intervención. ¿Qué dispositivos, personas, cuentas y espacios puedo examinar legalmente? ¿Hay restricciones de privacidad? (RFC 3227 §2.3–2.4; NIST SP 800-86 §3.1.1; ENFSI §8.2)

3. Identificar a las personas involucradas y documentar qué hicieron y observaron. (RFC 3227 §3.2)

4. Localizar los sistemas involucrados en el incidente, las posibles fuentes de datos. (NIST SP 800-86 §3.1.1)

5. Comprobar si existen fuentes de evidencia fuera del lugar físico, como servicios en la nube, copias de seguridad, registros remotos o dispositivos de terceros, y anotar dónde están y quién tiene acceso. (NIST SP 800-86 §3.1.1)

6. Fotografiar el lugar de los hechos, los equipos, las conexiones, las pantallas visibles, los periféricos y su disposición. (NIST SP 800-86 §3.1.2; ENFSI §8.2)


### Antes de tocar

7. Evitar pérdida de datos:  (RFC 3227 §2; ENFSI §8.2)
    - Registrar si los equipos/evidencias están encendidos, apagados, bloqueados o en suspensión, y no modificarlos.
    - Evaluar los riesgos de pérdida o alteración de datos al desconectar el dispositivo de la red o corriente eléctrica.
    - Evaluar cómo evitar modificaciones externas como borrado remoto o la activación de un malware.

8. Registrar y etiquetar los elementos recogidos, indicando su ubicación, responsable, fecha y hora. (ENFSI §8.2)

9. Preparar herramientas adecuadas y fiables, y que modifiquen lo menos posible las pruebas. (RFC 3227 §5; NIST SP 800-86 §3; §3.1.2; ENFSI §9.6)

10. Anotar el identificador único de cada elemento y mantener la cadena de custodia, registrando quién lo recoge y quién lo recibe. (RFC 3227 §4.1)

### Al decidir qué se adquiere

11. Evaluar si el examen se iniciará como un análisis completo o si se basará en un método de elaboración de informes por fases. (ENFSI §9.5)

12. Determinar qué fuentes son relevantes para el incidente y justificar cuáles se adquirirán. (NIST SP 800-86 §3.1.1–3.1.2)

13. Hacer una copia del original y trabajar sobre las copias. (RFC 3227 §2; NIST SP 800-86 §3.2)

14. Documentar el orden en que se van a examinar las fuentes de evidencia. (RFC 3227 §3.2; NIST SP 800-86 §3.1.2)

15. Registrar todos los datos de red, cortafuegos, servidores, sistemas de monitorización y logs que puedan sobrescribirse. (RFC 3227 §2.1; NIST SP 800-86 §3.1.1)

16. Preparar los formularios necesarios antes de iniciar la adquisición: identificación de evidencias, registro de actuaciones, adquisición y verificación de integridad, e historial de cadena de custodia. (RFC 3227 §3.2; §4.1)


### ¿En qué orden?

- Si el sistema está encendido, o conectado a la corriente, a la red u otro sitio, valorar primero los datos volátiles que pueden desaparecer al desconectarlo. (RFC 3227 §2.1; ENFSI §9.6)

- Si no está encendido, priorizar por valor probatorio, volatilidad y esfuerzo de adquisición. (RFC 3227 §2.1; NIST SP 800-86 §3.1.2)
