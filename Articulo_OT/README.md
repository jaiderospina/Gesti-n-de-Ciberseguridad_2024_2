# Resumen


## Principle 2: Knowledge of the business is crucial

El Principio 2: El conocimiento del negocio es crucial resalta la importancia de que una organización tenga un entendimiento profundo de sus propios procesos para fortalecer su ciberseguridad, especialmente en el ámbito de la tecnología operacional (OT). Este principio se enfoca en dos aspectos clave:

* Conocer los sistemas vitales: Es fundamental que las organizaciones identifiquen qué sistemas son cruciales para continuar brindando sus servicios esenciales. Esto implica comprender cómo funcionan los sistemas OT, cómo interactúan con el resto de la infraestructura, y qué partes del negocio dependen de ellos para operar.

* Contexto del negocio: El personal encargado de diseñar, operar y mantener los sistemas OT debe estar familiarizado con el contexto de negocio en el que estos sistemas operan. Esto incluye no solo los aspectos técnicos, sino también la relación de estos sistemas con los procesos físicos y su importancia para la entrega de servicios a los clientes.

## Ejemplos para ilustrar este principio:
* Industria de generación eléctrica: Para garantizar la seguridad y eficiencia de un generador eléctrico, no basta con entender el funcionamiento de sus componentes técnicos. Los ingenieros y el personal de seguridad deben conocer los procesos empresariales que dependen de la generación de electricidad, como el suministro continuo de energía a hospitales o instalaciones críticas.

* Plantas de tratamiento de agua: Si hay un fallo en el sistema de control OT, el equipo debe saber qué procesos son prioritarios, como asegurar el flujo de agua potable, lo cual es vital para la seguridad pública.

  
## Principales características:
* Comprensión integral de los sistemas: Se debe entender completamente qué partes del sistema OT son críticas y cómo están conectadas.
* Relación entre OT y el negocio: Es vital que los equipos de ciberseguridad y OT trabajen alineados con los objetivos del negocio.
* Identificación de riesgos y dependencias: Se debe tener un panorama claro de qué sistemas y procesos pueden verse afectados en caso de un incidente cibernético.
* Cuanto más conocimiento tenga una empresa sobre sí misma, mejor podrá protegerse, prepararse y responder ante incidentes cibernéticos.
* La comprensión, visibilidad e informes sobre los riesgos cibernéticos, especialmente en sistemas OT (Tecnología Operacional), deben estar presentes en los niveles más altos de la organización.
  
## Requisitos para organizaciones de infraestructura crítica:
1. Identificar sistemas vitales que permitan la continuidad de los servicios esenciales.
2. Comprender el proceso del sistema OT y la importancia de cada parte del proceso.
3. Crear una arquitectura de defensa que proteja los sistemas y procesos vitales de otras redes internas y externas.
4. Garantizar que el personal responsable de OT entienda el contexto empresarial del sistema OT, la planta física conectada y cómo se entregan los servicios a los interesados.
5. Comprender las dependencias de los sistemas vitales y cómo se conectan con sistemas externos al sistema OT.
## Ejemplos e implicaciones:
1. Es fundamental saber qué necesita ser protegido: identificar los elementos esenciales para la continuidad del negocio.
2. Es necesario comprender los sistemas y procesos, que incluyen: diagramas de ingeniería, listas de activos, diagramas de redes, quién puede conectarse y desde dónde, procedimientos de recuperación, proveedores, servicios y equipos.
3. Se requiere tanto pensamiento de arriba hacia abajo (separar OT de IT) como de abajo hacia arriba (descubrir el conjunto mínimo de equipos OT críticos).
* Ejemplo: Para generar electricidad, el mínimo podría ser un generador, un controlador y un suministro de combustible.
##Implicaciones para la ciberseguridad:
1. El conocimiento de los sistemas esenciales debe guiar la implementación de controles de ciberseguridad en capas.
2. Los planes y guías de respuesta a incidentes OT deben integrarse con los planes de crisis, continuidad del negocio y reporte de incidentes cibernéticos.
3. Involucrar a ingenieros de procesos en la creación de planes y guías, y en cualquier proceso de investigación o recuperación.
4. Proporcionar un paquete de información a terceros antes o durante su contratación, que incluya contactos, convenciones de nombres, herramientas y restricciones.
5. Estos planes, guías y paquetes de terceros deben ser actualizados y protegidos regularmente debido a su valor frente a los adversarios.
## Aspectos físicos y visuales en OT:
1. Utilizar codificación de colores en cables, marcar dispositivos permitidos en el entorno OT de manera visible.
2. Solo los dispositivos autorizados deben estar conectados al entorno OT, garantizando que solo se introduzca código autorizado.
3. Las señales visuales ayudan a proteger el entorno y permiten tomar decisiones rápidas y correctas durante eventos cibernéticos.
4. Importancia del contexto empresarial en OT:
5. Comprender el contexto empresarial del sistema OT es crucial para evaluar el impacto de interrupciones y compromisos de ciberseguridad.
6. Esto es vital para definir las prioridades de recuperación durante un incidente crítico.
7. Las relaciones entre personal de ciberseguridad de OT y responsables de la planta física son clave tanto para proyectos de mejora cibernética como para la respuesta a eventos cibernéticos.




## Principle 5: The supply chain must be secure



## Acciones recomendadas para una cadena de suministro segura:
### Auditorías regulares de los proveedores:

* Las organizaciones deben realizar auditorías de seguridad periódicas a todos los proveedores que tengan acceso a sus sistemas OT o que suministren dispositivos que se integren en la infraestructura crítica. Estas auditorías deben verificar que los proveedores sigan las mejores prácticas de ciberseguridad y que cualquier acceso remoto esté adecuadamente controlado y registrado.

### Seguridad de firmware y actualizaciones:

* Es esencial que cualquier actualización de firmware o software provenga de fuentes verificadas y esté firmada criptográficamente. Las organizaciones también deben establecer procesos para verificar que los proveedores sigan este enfoque antes de permitir cualquier actualización en los sistemas OT.

## Ejemplos e implicaciones:
* Proveedores de energía: En una compañía eléctrica, puede haber múltiples proveedores de pequeñas plantas generadoras o equipos de almacenamiento de energía. Si uno de estos pequeños proveedores tiene una debilidad en su red OT, podría convertirse en un punto de acceso para un ciberatacante. Desde la perspectiva de seguridad, cualquier conexión a estos proveedores, independientemente de su tamaño, debe ser tratada como crítica, y deben aplicarse los mismos controles de seguridad rigurosos que se aplicarían a conexiones más grandes.

* Un consultor externo en una planta química: Si una planta química utiliza un sistema de control que requiere acceso frecuente de un consultor externo para tareas de mantenimiento, cada vez que el consultor se conecte de forma remota, existe un riesgo de que esa conexión pueda ser interceptada o comprometida. Para mitigar este riesgo, la planta debe implementar protocolos estrictos de autenticación multifactor y segmentar adecuadamente las redes OT de manera que el acceso del consultor esté limitado solo a las áreas necesarias.
