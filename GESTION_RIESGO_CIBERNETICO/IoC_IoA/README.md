## IoC   VS   IoA

Diiferencias y similitudes entre los Indicadores de Compromiso (IoC) y los Indicadores de Ataque (IoA):

| **Aspecto**               | **Indicadores de Compromiso (IoC)**                   | **Indicadores de Ataque (IoA)**                         | **Similitudes**                                               |
|---------------------------|-------------------------------------------------------|---------------------------------------------------------|--------------------------------------------------------------|
| **Definición**            | Evidencias forenses que indican que un sistema ha sido comprometido. | Señales que muestran que un ataque está ocurriendo o está a punto de ocurrir. | Ambos son utilizados para detectar y responder a amenazas.   |
| **Ejemplos**              | - Hashes de archivos maliciosos<br>- Direcciones IP maliciosas<br>- Dominios maliciosos | - Comportamiento anómalo del usuario<br>- Intentos de escalación de privilegios<br>- Acceso no autorizado a datos sensibles | Ambos se basan en la recopilación de datos y el análisis de patrones. |
| **Enfoque Temporal**      | Generalmente después del compromiso                   | Durante o antes del ataque                               | Ambos buscan mejorar la seguridad y minimizar el impacto de los ataques. |
| **Uso Principal**         | Respuesta a incidentes y análisis forense             | Prevención y detección en tiempo real                    | Ambos son componentes clave en una estrategia de ciberseguridad. |
| **Objetivo**              | Identificar la presencia de una amenaza pasada o actual | Identificar señales tempranas de un ataque potencial     | Ambos contribuyen a la identificación y mitigación de amenazas. |
| **Recolección**           | Basado en artefactos y rastros dejados por atacantes  | Basado en patrones de comportamiento y actividad sospechosa | Ambos requieren herramientas y técnicas avanzadas para su identificación. |
| **Relevancia**            | Crítica para entender la extensión y el impacto de un compromiso | Crítica para la prevención y respuesta proactiva a ataques | Ambos son esenciales para la protección integral de la red. |

## Pirámide del dolor.


La Pirámide del Dolor es un concepto desarrollado por David J. Bianco, que ayuda a comprender el impacto relativo de diferentes tipos de indicadores de compromiso (IoC) en la capacidad de un atacante para operar dentro de una red. La pirámide ilustra cómo ciertos tipos de indicadores son más difíciles de cambiar o evadir por los atacantes, y cómo la detección y respuesta a estos indicadores pueden infligir diferentes niveles de "dolor" a los atacantes.

### Niveles de la Pirámide del Dolor

1. **Hashes de Ficheros (File Hash Values)**
   - **Descripción**: Identificadores únicos generados a partir del contenido de archivos, como hashes MD5 o SHA-256.
   - **Dificultad para Atacantes**: Baja. Los atacantes pueden modificar el contenido del archivo ligeramente para generar un hash diferente (técnica conocida como hashing).
   - **Impacto**: Los hashes son fáciles de evadir y proporcionan poco dolor a los atacantes.

2. **Direcciones IP (IP Addresses)**
   - **Descripción**: Direcciones de origen y destino del tráfico de red.
   - **Dificultad para Atacantes**: Baja. Los atacantes pueden cambiar las direcciones IP utilizando proxies, VPNs o botnets.
   - **Impacto**: Cambiar las direcciones IP es relativamente fácil para los atacantes, causando un impacto moderado.

3. **Dominios y URLs (Domain Names and URLs)**
   - **Descripción**: Nombres de dominio y URLs utilizados en la comunicación de los atacantes.
   - **Dificultad para Atacantes**: Moderada. Los atacantes pueden registrar nuevos dominios, pero esto requiere más esfuerzo y recursos.
   - **Impacto**: Forzar a los atacantes a cambiar sus dominios y URLs aumenta el dolor, ya que implica más trabajo y gastos.

4. **Artefactos de Red (Network Artifacts)**
   - **Descripción**: Características y patrones de tráfico de red, como protocolos utilizados, puertos específicos o características de la comunicación.
   - **Dificultad para Atacantes**: Alta. Cambiar los patrones de tráfico y características de la comunicación es más complejo y puede requerir una reconfiguración significativa.
   - **Impacto**: Causar cambios en los artefactos de red inflige un dolor considerable a los atacantes.

5. **Artefactos de Huella Digital del Host (Host Artifacts)**
   - **Descripción**: Rastros dejados en los sistemas de destino, como archivos creados, claves de registro modificadas o procesos ejecutados.
   - **Dificultad para Atacantes**: Muy alta. Modificar consistentemente los artefactos del host es difícil y puede comprometer la funcionalidad del malware.
   - **Impacto**: Cambiar los artefactos de huella digital del host causa un gran dolor a los atacantes.

6. **Herramientas de Atacantes (Tools)**
   - **Descripción**: Herramientas específicas y programas utilizados por los atacantes, como exploits y kits de herramientas.
   - **Dificultad para Atacantes**: Muy alta. Cambiar herramientas implica un rediseño significativo o la adopción de nuevas herramientas, lo cual es costoso y consume tiempo.
   - **Impacto**: Obligar a los atacantes a cambiar sus herramientas impone un dolor significativo.

7. **Tácticas, Técnicas y Procedimientos (TTPs)**
   - **Descripción**: Métodos y estrategias utilizados por los atacantes, incluyendo su modus operandi y estrategias de ataque.
   - **Dificultad para Atacantes**: Máxima. Cambiar tácticas, técnicas y procedimientos requiere una reestructuración fundamental de cómo operan los atacantes.
   - **Impacto**: Infligir cambios en los TTPs impone el mayor dolor posible a los atacantes, ya que afecta directamente su capacidad para operar eficientemente.

### Resumen

La Pirámide del Dolor de David Bianco destaca la importancia de centrarse en indicadores de mayor impacto en la capacidad operativa de los atacantes. Al detectar y responder a niveles más altos de la pirámide, las organizaciones pueden infligir un dolor significativo a los atacantes, dificultando sus operaciones y aumentando sus costos y esfuerzos. Este enfoque estratégico permite una defensa cibernética más eficaz y proactiva.
