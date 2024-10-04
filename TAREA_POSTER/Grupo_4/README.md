# Security Operations Center (SOC)

### Grupo 4
- Oscar Camargo
- Jaime Zamudio
- Jose Luis Galvis
- Carlos Rodriguez
- Wilfredo Samboni 

### Tabla de Contenido
1. [Forensics](#1-forensics-forense-digital)
2. [Command Center](#2-command-center-centro-de-comando)
3. [Self Assessment](#3-self-assessment-autoevaluación)

## Security Operations Center (SOC)
![SOC](/TAREA_POSTER/Grupo_4/Images/Analisis.jpg)
	
**Security Operations Center (SOC) o centro de operación de seguridad** son un grupo de expertos altamente calificados cuyo trabajo consiste en monitorizar, detectar, analizar, defender e investigar continuamente los sistemas de información de la empresa. 
El **SOC** es esencial si se desea garantizar la seguridad de la infraestructura de TI, minimizar los tiempos de respuesta a incidentes y proteger la organización contra amenazas internas y externas. A través de la gestión eficiente de incidentes y el análisis continuo de amenazas, el SOC ayuda a mantener una postura de ciberseguridad sólida y resiliente.

Dentro de los tipos de SOC tenemos **internos, subcontratados, híbridos o virtuales**.
	
- **Internos**
Son los centros de operaciones de seguridad que son gestionados por miembros de la organización. 
- **Subcontratados o externos**
También se conoce como SOC administrado o centro de operaciones de seguridad como servicio, y son aquellos que son gestionados por un proveedor de seguridad externo.
- **Híbridos**
Son una combinación de SOC interno y externo, donde la organización trabaja en estrecha colaboración con un proveedor de servicios externos.
- **Virtuales**
Son SOC que se gestionan de forma remota mediante herramientas digitales.

### Funciones Principales

1. **Monitoreo Continuo**:
   - _Supervisar la red, sistemas y aplicaciones las 24 horas del día en búsqueda de actividades inusuales o maliciosas._
   - _Utilizar herramientas de monitoreo, como sistemas de detección de intrusos [IDS](https://www.ibm.com/es-es/topics/intrusion-detection-system), [firewall](https://latam.kaspersky.com/resource-center/definitions/firewall) y [herramientas SIEM](https://www.ibm.com/mx-es/topics/siem)._
2. **Gestión de Incidentes de Seguridad**:
   - _Detectar, analizar, responder y mitigar incidentes de ciberseguridad._
   - _Garantizar la rápida identificación y contención de amenazas._
3. **Análisis y Detección de Amenazas**:
   - _Realizar análisis en tiempo real identificando patrones de comportamiento sospechoso._
   - _Proporcionar análisis forense cuando se producen incidentes._
4. **Automatización y Orquestación**:
   - _Automatizar tareas rutinarias y procesos de respuesta a incidentes, como el bloqueo de IPs maliciosas o la contención de malware._
5. **Gestión de Vulnerabilidades**:
   - _Evaluar y priorizar vulnerabilidades en los sistemas de la organización asegurando que se mitiguen antes de ser explotadas._
   - _Realizar escaneos periódicos de vulnerabilidades y pruebas de penetración._
6. **Generación de Informes y Cumplimiento**:
   - _Crear informes periódicos sobre el estado de la seguridad y los incidentes ocurridos._
   - _Asegurar el cumplimiento con regulaciones y normativas de seguridad como [ISO 27001](https://www.iso.org/standard/27001)._
7. **Inteligencia de Amenazas**:
   - _Recopilar, analizar y aplicar información sobre amenazas emergentes buscando mejorar las defensas y reducir el riesgo de ataques futuros._
   - _Mantenerse al día sobre las últimas tendencias y vectores de ataque adaptándose a las estrategias de seguridad._

> [!NOTE]
> Herramientas como [qualys](https://www.qualys.com) permiten identificar, priorizar y remediar vulnerabilidades en redes, dispositivos y aplicaciones, a partir de soluciones [SaaS](https://aws.amazon.com/es/what-is/saas/).
> A través de su enfoque en la automatización y la entrega en tiempo real de información de seguridad, qualys permite abordar varias funciones necesarias de un SOC.
> 
> **Las principales características de Qualys incluyen**:
> - _**Gestión de vulnerabilidades**: Identificación proactiva de vulnerabilidades en sistemas operativos, aplicaciones y configuraciones mediante escaneos tanto locales como remotos._
> - _**Cumplimiento normativo** Herramientas para asegurarse que los sistemas cumplan con los estándares de seguridad y normativas como [PCI-DSS](https://www.cloudflare.com/es-es/learning/privacy/what-is-pci-dss-compliance/), [DORA](https://www.incibe.es/empresas/blog/que-es-el-reglamento-dora) y [GDPR](https://gdpr-info.eu/)._
> - _**Detección de amenazas**: Monitoreo continuo para identificar amenazas emergentes y nuevas vulnerabilidades que puedan afectar a los sistemas de la organización._
> - _**Inventario de activos**: Visibilidad total de los activos de TI, incluyendo dispositivos de red, aplicaciones y servidores._
> - _**Seguridad web y de aplicaciones**: Evaluación de la seguridad de aplicaciones web para identificar problemas de seguridad y malas configuraciones._
> - _**Monitoreo de cumplimiento de políticas**: Revisión de políticas de seguridad en tiempo real para garantizar que los dispositivos cumplan con los requisitos de seguridad internos y externos._

## 1. Forensics (Forense Digital)
![Forense](/TAREA_POSTER/Grupo_4/Images/Forense.jpg)

**Forense Digital** es una disciplina que se centra en la identificación, recolección, análisis y preservación de evidencia digital. Su objetivo es reconstruir los eventos relacionados con una brecha de seguridad, un ataque o cualquier tipo de actividad ilegal en entornos digitales.
Es esencial hacia la investigación de incidentes de ciberseguridad, ya que permite a las organizaciones descubrir las causas de los ataques, mejorar sus defensas y en caso necesario, llevar a cabo acciones legales contra los responsables. También juega un papel clave en la recuperación de sistemas y en la reducción de riesgos futuros.

### Funciones Principales

1. **Identificación de Evidencia**:
   - _Localizar y reconocer archivos, registros y datos relevantes en dispositivos y redes que podrían estar vinculados a incidentes de seguridad._   
2. **Preservación de Evidencia**:
   - _Asegurar la integridad de la evidencia digital mediante la creación de copias forenses, evitando alteraciones que comprometan su validez._
3. **Análisis de Evidencia**:
   - _Examinar la evidencia recopilada con el fin de reconstruir lo que ocurrió, determinar la naturaleza del ataque, cómo se llevó a cabo, y quién fue responsable._   
4. **Recuperación de Datos**:
   - _Extraer datos eliminados, cifrados o dañados que puedan servir como prueba en la investigación._
5. **Análisis de Redes**:
   - _Evaluar el tráfico de red detectando patrones de comportamiento anómalo o identificar fuentes de ataques._
6. **Análisis Forense de Malware**:
   - _Estudiar archivos maliciosos analizando su funcionamiento, sus métodos de infección y el daño causado._
7. **Documentación y Reportes**:
   - _Crear informes detallados sobre el proceso de investigación y los hallazgos, asegurando la cadena de custodia de la evidencia._
8. **Recolección de Logs**:
   - _Examinar los registros (logs) de sistemas, aplicaciones y redes en búsqueda de actividades sospechosas o no autorizadas._

**Ejemplo log**
```   
Sep 25 12:25:32 Monitor kernel: [ 5647.629686] usb 2-6: Detected FT232R
Sep 25 12:25:32 Monitor kernel: [ 5647.629858] ftdi_sio ttyUSB0: Unable to read latency timer: -32
Sep 25 12:25:32 Monitor kernel: [ 5647.630097] usb 2-6: FTDI USB Serial Device converter now attached to ttyUSB0
Sep 25 12:25:32 Monitor kernel: [ 5647.796799] usb 2-6: USB disconnect, device number 6
Sep 25 12:25:32 Monitor kernel: [ 5647.797153] ftdi_sio ttyUSB0: FTDI USB Serial Device converter now disconnected from ttyUSB0
Sep 25 12:25:32 Monitor kernel: [ 5647.797167] ftdi_sio 2-6:1.0: device disconnected
Sep 25 12:25:32 Monitor kernel: [ 5648.047904] usb 2-6: new full-speed USB device number 7 using xhci_hcd
Sep 25 12:25:32 Monitor kernel: [ 5648.180191] usb 2-6: New USB device found, idVendor=0403, idProduct=6001, bcdDevice= 6.00
Sep 25 12:25:32 Monitor kernel: [ 5648.180196] usb 2-6: New USB device strings: Mfr=1, Product=2, SerialNumber=3
Sep 25 12:25:32 Monitor kernel: [ 5648.180197] usb 2-6: Product: USB Serial Converter
Sep 25 12:25:32 Monitor kernel: [ 5648.180199] usb 2-6: Manufacturer: FTDI
Sep 25 12:25:32 Monitor kernel: [ 5648.180199] usb 2-6: SerialNumber: FTB6SPL3
Sep 25 12:25:32 Monitor kernel: [ 5648.181532] ftdi_sio 2-6:1.0: FTDI USB Serial Device converter detected
Sep 25 12:25:32 Monitor kernel: [ 5648.181551] usb 2-6: Detected FT232R
Sep 25 12:25:32 Monitor kernel: [ 5648.181739] ftdi_sio ttyUSB0: Unable to read latency timer: -32
Sep 25 12:25:32 Monitor kernel: [ 5648.181964] usb 2-6: FTDI USB Serial Device converter now attached to ttyUSB0
```
```
[20241001-07:40:21] [INFO ] xrdp_caps_process_pointer: client supports new(color) cursor
[20241001-07:40:21] [INFO ] xrdp_process_offscreen_bmpcache: support level 1 cache size 10485760 MB cache entries 100
[20241001-07:40:21] [INFO ] xrdp_caps_process_codecs: nscodec, codec id 1, properties len 3
[20241001-07:40:21] [WARN ] xrdp_caps_process_codecs: unknown codec id 5
[20241001-07:40:21] [INFO ] xrdp_caps_process_codecs: RemoteFX, codec id 3, properties len 49
[20241001-07:40:21] [INFO ] Loading keymap file /etc/xrdp/km-0000080a.ini
[20241001-07:40:21] [WARN ] local keymap file for 0x0000080a found and doesn't match built in keymap, using local keymap file
[20241001-07:40:28] [INFO ] connecting to sesman ip 127.0.0.1 port 3350
[20241001-07:40:28] [INFO ] xrdp_wm_log_msg: sesman connect ok
[20241001-07:40:28] [INFO ] sesman connect ok
[20241001-07:40:28] [INFO ] sending login info to session manager, please wait...
[20241001-07:40:28] [INFO ] xrdp_wm_log_msg: login successful for display 10
[20241001-07:40:28] [INFO ] login successful for display 10
[20241001-07:40:28] [INFO ] loaded module 'libxup.so' ok, interface size 10296, version 4
[20241001-07:40:28] [INFO ] started connecting
[20241001-07:40:28] [INFO ] lib_mod_connect: connecting via UNIX socket
```
> [!IMPORTANT] 
>
>**Componentes Principales**
>
>1. **Host Forensics (Forense de Hosts)**
>		- _**Adquisición de Memoria y Disco**: Implica la recopilación de datos almacenados en discos duros, memorias RAM y otros sistemas de almacenamiento de dispositivos individuales (computadoras, teléfonos, servidores)._
>			- _El análisis incluye examinar los archivos almacenados, logs y otros artefactos presentes en el sistema operativo de los dispositivos comprometidos._
>
>2. **Network Forensics (Forense de Redes)**
>		- _**Adquisición de Logs, Información de Eventos y [PCAP](https://www.linkedin.com/pulse/network-traffic-analysis-qu%C3%A9-es-un-archivo-pcap-arturo-e-torres/)**: Se encarga de recolectar y analizar los registros de red, datos de eventos y capturas de paquetes PCAP para investigar patrones de tráfico de red que puedan revelar ataques o comportamientos sospechosos._
>			- _El análisis de red ayuda a rastrear cómo los atacantes interactúan con los sistemas y qué datos han podido comprometerse._
>
>3. **Reverse Engineering (Ingeniería Inversa)**
>		- _**Adquisición de Dispositivos, Software o Código**: En casos de análisis más avanzado, la ingeniería inversa se utiliza para desensamblar y analizar código malicioso, dispositivos o software que puedan haber sido manipulados durante un ataque._
>			- _El objetivo es comprender cómo funciona un malware o cualquier otra amenaza para poder neutralizarla y prevenir futuros incidentes._
>
>**Proceso de Forense Digital**
>
>	1. _**Análisis de Activos**: Los equipos de forense analizan los activos (sistemas o redes) comprometidos para determinar qué ocurrió, cómo ocurrió y qué impacto tuvo el incidente._
>	2. _**Mantener la Cadena de Custodia**: Asegurar que la evidencia digital se mantenga de manera segura y sin alteraciones, con una cadena de custodia rigurosa para su posible uso en investigaciones legales._
>	3. _**Garantizar la Integridad del Activo**: Preservar la integridad de los activos involucrados para asegurar que los datos no se vean comprometidos o alterados durante el proceso de investigación._
>
>**Colaboración con el Management y el Command Center**
>	- _El equipo forense provee información crítica sobre Indicadores de Compromiso [IOCs](https://www.cloudflare.com/es-es/learning/security/what-are-indicators-of-compromise/) y resultados de la investigación para apoyar la toma de decisiones en el **Management** y el **Command Center**._
>	- _Esta información es clave para mitigar el impacto de un incidente y planificar acciones correctivas._
>
>**Sistemas Internos y Artefactos de Red**
>	- _**Sistemas Internos**: Incluyen dispositivos como teléfonos, computadoras y servidores donde se lleva a cabo el análisis forense de hosts._
>	- _**Red y Artefactos Relacionados**: Implica el análisis de servidores de logs, infraestructura de red y capturas completas de paquetes (Full PCAP) para determinar el alcance de una intrusión o ataque._



> [!NOTE]  
> - Software como [autopsy](https://www.sleuthkit.org/autopsy/) hacen parte de las herramientas que se pueden utilizar para realizar identificación de evidencia digital, la cual es muy intuitiva y que mediante una [instalación](https://github.com/jaiderospina/autopsy222/) sencilla los resultados son altamente satisfactorios.     
> - [FTK Imager](https://accessdata-ftk-imager.software.informer.com/download/) es una [herramienta](https://www.hackingarticles.in/comprehensive-guide-on-ftk-imager/?trk=public_post_comment-text) de código abierto que se utiliza para crear copias de la evidencia original sin alterarla.

##  2. Command Center (Centro de Comando)
![Code](/TAREA_POSTER/Grupo_4/Images/Code.jpg)

Un **Command Center** (Centro de Comando) es una entidad central que coordina y gestiona la información crítica de una organización. Actúa como el punto de contacto clave para diversos grupos (usuarios, fuerzas del orden, público) y se encarga de recibir, procesar y diseminar información de acuerdo con las necesidades operativas y de seguridad.
Un centro de comando es vital para mantener la continuidad de las operaciones, responder de manera efectiva a incidentes y gestionar cualquier interrupción o emergencia que pueda poner en riesgo a una organización o la seguridad pública.

### Funciones Principales

1. **Monitoreo en Tiempo Real**: 
   - _Supervisar actividades y procesos críticos en tiempo real._
   - _Utilizar sistemas y herramientas avanzadas ya que permite obtener información actualizada y ayuda a tomar decisiones basadas en datos._
2. **Coordinación de Respuestas**:
   - _Coordinar la respuesta a incidentes o emergencias._
   - _Asegurar que los equipos involucrados trabajen de manera conjunta y eficiente._
3. **Gestión de Recursos**:
   - _Asignar y gestionar los recursos necesarios durante un incidente._
   - _Optimizar el uso de personal, herramientas y otras capacidades de la organización las cuales garantizan una respuesta efectiva._
4. **Análisis y Toma de Decisiones**:
   - _Analizar datos provenientes de diferentes fuentes (sensores, cámaras, sistemas de información) los cuales evalúan la situación._
   - _Proporcionar a los tomadores de decisiones la información necesaria las cuales les permite implementar acciones rápidas y precisas._
5. **Comunicación Eficiente**:
   - _Facilitar la comunicación entre diferentes partes interesadas (internas y externas)._
   - _Asegurar que la información crítica fluya de manera rápida y eficiente durante operaciones._
   - _Reportar al ente encargado los incidentes o emergencias presentadas._
6. **Gestión de Crisis**:
   - _Tomar control y liderar durante situaciones de crisis._
   - _Implementar planes de contingencia y coordinar la mitigación de impactos negativos._   

> [!IMPORTANT]     
>**Fuentes de Información para el Command Center**
>
>1. **Usuarios o Help Desk**
>		- _**Reportar Problemas**: Los usuarios o los equipos de soporte técnico [(Help Desk)](https://www.zendesk.es/blog/help-desk/) informan al Command Center sobre cualquier problema relacionado con sistemas, seguridad o infraestructura que necesite atención inmediata._
>2. **Fuerzas del Orden (Law Enforcement)**
>		- _**Notificación a Terceros**: El Command Center notifica a terceros, como proveedores o socios, sobre problemas que puedan afectar su operativa._
>		- _**Reportar Actividades Ilegales**: Se encargan de reportar al Command Center cualquier actividad sospechosa o ilegal que requiera la intervención de las autoridades._
>		- _**Buscar Consejos**: Pueden solicitar la asesoría del Command Center para gestionar situaciones críticas o emergencias._
>3. **Público**
>		- _**Reportes de Estado**: El Command Center proporciona informes de estado a la comunidad o partes interesadas sobre la situación actual de la infraestructura o de las operaciones._
>		- _**Comunicados de Prensa**: Realiza publicaciones oficiales sobre temas de interés público relacionados con la seguridad o emergencias._
>		- _**Grabaciones**: Puede emitir grabaciones de eventos importantes, informes de incidentes o actualizaciones de estado._
>		- _**Concienciación y Divulgación**: El Command Center realiza actividades para crear conciencia pública y divulgar información crítica sobre la situación o riesgos._


## 3. Self Assessment (Autoevaluación)
![Analisis](/TAREA_POSTER/Grupo_4/Images/Analisis.jpg)

**Self Assessment** (Autoevaluación) es un proceso sistemático mediante el cual una organización evalúa su propia postura de seguridad y capacidad para enfrentar amenazas. Este proceso permite identificar áreas de fortaleza y debilidades en sus sistemas de seguridad, brindando información crítica para priorizar acciones correctivas y mejorar la preparación ante posibles ataques..
La autoevaluación es fundamental para mantener una estrategia de ciberseguridad sólida, ya que ayuda a las organizaciones a ajustar sus políticas, procedimientos y tecnologías de manera continua, asegurando una mayor resistencia ante las amenazas cambiantes del entorno digital. Las áreas clave que se analizan en este proceso incluyen la configuración de sistemas, la evaluación de vulnerabilidades, las pruebas de penetración y ejercicios prácticos de respuesta a incidentes.

### Funciones Principales

1. **Evaluación Personal**:
   - _Reflexionar sobre el desempeño en ciertas tareas o áreas._
   - _Identificar logros y reconocer las áreas que necesitan desarrollo o fortalecimiento._

2. **Establecimiento de Metas**:
   - _Definir objetivos claros a corto, mediano y largo plazo con base en los resultados de la autoevaluación._
   - _Alinear las metas personales o profesionales con las necesidades detectadas._

3. **Identificación de Fortalezas y Debilidades**:
   - _Analizar las áreas donde el desempeño es óptimo (fortalezas) y donde se requiere mejorar (debilidades)._
   - _Utilizar esta información para optimizar esfuerzos y estrategias de crecimiento._

4. **Plan de Mejora Continua**:
   - _Elaborar un plan de acción con pasos específicos para mejorar las debilidades y maximizar las fortalezas._
   - _Hacer ajustes y evaluaciones periódicas para verificar el progreso._

5. **Autoconocimiento**:
   - _Facilitar un mayor entendimiento de las habilidades, conocimientos y comportamientos._
   - _Aumentar la conciencia sobre cómo se impacta en el entorno o en el trabajo en equipo._

6. **Auto-motivación**:
   - _Utilizar los resultados de la autoevaluación para motivarse a mejorar y alcanzar nuevas metas._
   - _Celebrar los éxitos y pequeños avances logrados durante el proceso de mejora._

> [!IMPORTANT]   
>El proceso de **Self Assessment** en ciberseguridad se centra en cuatro áreas clave:
>
>1. **Configuration Monitoring (Monitoreo de Configuración)**
> 		- _**Create Baselines**: Establecer configuraciones estándar o puntos de referencia para sistemas._
>		- _**Identify Configuration Changes**: Detectar cambios que puedan alterar el comportamiento normal del sistema._
> 		- _**Maintain Systems**: Asegurar que los sistemas estén actualizados y funcionando correctamente._
>2. **Vulnerability Assessment (Evaluación de Vulnerabilidades)**
> 		- _**Identify Risk and Exposure**: Evaluar las áreas donde la infraestructura está expuesta a riesgos._
>		- _**Scan Systems for Known Vulnerabilities**: Detectar vulnerabilidades conocidas que podrían comprometer los sistemas._
>		- _**Impact of New Vulnerabilities**: Evaluar el impacto de nuevas vulnerabilidades identificadas en el entorno._
>3. **Penetration Testing (Pruebas de Penetración)**
> 		- _**Model Attacker Scenarios**: Simular escenarios de ataque que los atacantes podrían utilizar._
>		- _**Exploit Systems**: Identificar y explotar vulnerabilidades en los sistemas para medir su impacto._
>		- _**Reconnaissance, Organizational Intelligence**: Realizar actividades de reconocimiento y recopilación de información sobre la organización._
>		- _**Deconfliction**: Coordinar esfuerzos para evitar conflictos entre pruebas de seguridad y operaciones._
>4. **Exercises (Ejercicios)**
>		- _**Tabletop Scenarios**: Desarrollar escenarios de simulación para planificar respuestas a incidentes._
>		- _**Model Threats and Events**: Modelar amenazas y eventos potenciales para probar la respuesta de la organización._
>		- _**Train and Assess Staff**: Capacitar y evaluar al personal para mejorar su respuesta ante incidentes de seguridad._
>		- _**DRP/BCP**: Evaluar y probar los planes de recuperación ante desastres [DRP](https://www.proofpoint.com/es/threat-reference/disaster-recovery) y continuidad del negocio [BCP](https://blog.hackmetrix.com/plan-de-continuidad-de-negocio/)._

> [!NOTE]
>Ejemplos de autoevaluación en ciberseguridad, aplicados a diferentes escenarios:
>
>**Evaluación de Configuración de Redes**
>   - _Verificar que se han aplicado reglas de firewall adecuadas._
>   - _Revisar si las configuraciones de red permiten conexiones inseguras._
>   - _Asegurar que las políticas de contraseñas para dispositivos de red cumplen con los requisitos de seguridad._
>
>**Prueba de Penetración Interna**
>   - _Identificar vulnerabilidades como credenciales débiles o configuraciones incorrectas._
>   - _imular escenarios de ataque para evaluar la preparación del equipo de respuesta._
>
>**Evaluación de Vulnerabilidades en Aplicaciones Web**
>   - _Buscar vulnerabilidades conocidas como inyecciones SQL o Cross-Site Scripting [XSS](https://www.welivesecurity.com/la-es/2021/09/28/que-es-ataque-xss-cross-site-scripting/)._
>   - _Revisar la configuración del servidor web para evitar la exposición de información sensible._
>
>**Ejercicio de Simulación de Respuesta a Incidentes**
>   - _Simular un incidente en tiempo real para evaluar cómo responderían los equipos._
>   - _Medir el tiempo de respuesta y la efectividad de las medidas implementadas._
>
>**Evaluación de Continuidad del Negocio**
>   - _Verificar que los backups estén actualizados y accesibles._
>   - _Evaluar el tiempo de recuperación ante incidentes [RTO y RPO](https://winempresas.pe/blog/que-es-y-para-que-sirven-el-rto-y-rpo)._
>
>**Revisión de Cumplimiento de Normativas**
>   - _Verificar que los sistemas que almacenan información financiera están correctamente cifrados._
>   - _Asegurar que los registros de auditoría se mantengan adecuadamente._

> [!TIP]
>**Que es un CISO**
>
>[![CISO](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D2qRH78b61rQ)](https://www.youtube.com/watch?v=2qRH78b61rQ)   
 
 ## Referencias
 
- https://gobiernodigital.mintic.gov.co/692/articles-150511_G8_Controles_Seguridad.pdf
- https://threat-modeling.com/ciso-security-mind-map-2024/
- https://www.ibm.com/es-es/topics/intrusion-detection-system
- https://latam.kaspersky.com/resource-center/definitions/firewall
- https://latam.kaspersky.com/resource-center/definitions/firewall
- https://www.iso.org/standard/27001
- https://www.qualys.com/
- https://www.cloudflare.com/es-es/learning/privacy/what-is-pci-dss-compliance/
- https://gdpr-info.eu/
- https://www.sleuthkit.org/autopsy/
- https://aws.amazon.com/es/what-is/saas/
- https://www.incibe.es/empresas/blog/que-es-el-reglamento-dora
- https://unsplash.com/es