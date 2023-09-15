# Entornos de Desarrollo - 01 - Desarrollo de Software
Tema 01. Desarrollo de Software. 1DAW. Curso 2023/2024.

![imagen](https://raw.githubusercontent.com/joseluisgs/EntornosDesarrollo-00-2022-2023/master/images/entornos.png)

- [Entornos de Desarrollo - 01 - Desarrollo de Software](#entornos-de-desarrollo---01---desarrollo-de-software)
  - [Contenidos](#contenidos)
  - [Desarrollo de Software](#desarrollo-de-software)
    - [Fases del desarrollo del Software](#fases-del-desarrollo-del-software)
  - [Ciclos de Vida y Modelos de Desarrollo de Software](#ciclos-de-vida-y-modelos-de-desarrollo-de-software)
  - [Metodologías Ágiles](#metodologías-ágiles)
  - [Referencias](#referencias)
  - [Autor](#autor)
    - [Contacto](#contacto)
  - [Licencia de uso](#licencia-de-uso)

## Contenidos
1. Desarrollo de Software
2. Ciclos de Vida y Modelos de Desarrollo de Software
3. Metodologías Ágiles

## Desarrollo de Software
Entendemos por Desarrollo de Software todo el proceso que ocurre desde que se concibe una idea hasta que un programa está implementado en el ordenador y funcionando. 

Ingeniera del software: se define como la ciencia y el arte de especificar, diseñar y desarrollar programas, documentación y procedimientos operativos.

El proceso de desarrollo, que en un principio puede parecer una tarea simple, consta de una serie de pasos de obligado cumplimiento, pues sólo así podremos garantizar que los programas creados son eficientes, fiables, seguros y responden a las necesidades de los usuarios finales (aquellos que van a utilizar el programa). 

Como veremos con más detenimiento a lo largo de la unidad, el desarrollo de software es un proceso que conlleva una serie de pasos. Genéricamente, estos pasos son los siguientes: 

### Fases del desarrollo del Software
- Planificación: en esta fase se establecen los objetivos del proyecto, se define el alcance del mismo y se realiza un estudio de viabilidad y costes.
- Análisis del problema: Consiste en ver y comprender **qué** tarea se quiere resolver. Es imprescindible partir de una especificación de requisitos lo más exacta y detallada posible. El proceso de comprensión y simplificación del mundo real se llama análisis del problema y lo que se obtiene tras el análisis es el modelo.	
- Diseño de una solución: Consiste en **cómo** se va a resolver el problema, suele consistir en dividir el problema principal en problemas más sencillos cuya combinación resuelve la tarea final.
- Codificación: Una vez definidos los algoritmos, los traducimos al lenguaje de programación que tengamos que usar. Un lenguaje de programación es un conjunto de símbolos y reglas sintácticas especialmente diseñado para transmitir ordenes al ordenador (C, Java, Pascal…).
- Pruebas: Servirán para corregir posibles errores, tendremos dos tipos de errores: 
    - Sintácticos: Producidos por un mal uso del lenguaje.
    - Semánticos: Lo que está equivocado es la solución que yo he ideado.

- Despliegue: una vez que el programa está terminado, se debe instalar en el ordenador o infraestructura del usuario final.

- Mantenimiento: Hay tres tipos:
    - Correctivo: Sirve para corregir posibles errores o fallos del programa.
    - Perfectivo: Se usa para perfeccionarlo.
    - Adaptativo: Sirve para adaptarlo a nuevas situaciones.

## Ciclos de Vida y Modelos de Desarrollo de Software
- Modelo en cascada. Consiste en dividir el proceso de desarrollo en fases, cada una de las cuales se ejecuta una vez que la anterior ha finalizado. El modelo en cascada es un modelo secuencial, es decir, las fases se ejecutan una tras otra. El modelo de desarrollo en cascada, también conocido como el modelo de cascada, es un proceso de desarrollo de software que fue introducido por el Dr. Winston W. Royce en 1970. Este modelo es lineal y secuencial, con cada fase del proceso de desarrollo fluyendo, como una cascada, hacia la siguiente. Las fases del modelo de cascada son las siguientes:

1. **Requisitos**: Durante esta fase, se recogen y documentan los requisitos del sistema y del software. Los requisitos del sistema son una descripción de lo que el sistema debe hacer, mientras que los requisitos del software detallan cómo el software debe funcionar para cumplir con los requisitos del sistema.

2. **Diseño**: En esta fase, se desarrolla un plan detallado para la implementación del software. Esto incluye la arquitectura del sistema, la selección de los algoritmos y estructuras de datos, y la interfaz de usuario.

3. **Implementación**: Durante esta fase, se escribe el código del software siguiendo el diseño. Este es el paso en el que los programadores realmente crean el software.

4. **Pruebas**: En esta fase, se realiza una serie de pruebas para identificar y corregir errores en el software. Esto puede incluir pruebas unitarias, pruebas de integración y pruebas de sistema.

5. **Despliegue**: Una vez que el software ha pasado las pruebas, se despliega para su uso. Esto puede implicar la instalación del software en los sistemas de los usuarios y la formación de los usuarios sobre cómo utilizarlo.

6. **Mantenimiento**: Después del despliegue, el software necesita ser mantenido. Esto puede implicar la corrección de errores que no se descubrieron durante la fase de pruebas, la adición de nuevas funcionalidades o la mejora de las existentes, y la actualización del software para mantenerlo compatible con los sistemas operativos y el hardware más recientes.

Es importante mencionar que el modelo de cascada ha sido criticado por su rigidez. En la práctica, las fases del desarrollo de software a menudo se superponen, y los requisitos pueden cambiar durante el desarrollo. Por este motivo, muchos equipos de desarrollo de software utilizan enfoques más flexibles, como el desarrollo ágil.
  - Sin realimentación: es el modelo de vida clásico del software. Es prácticamente imposible que se pueda utilizar, ya que requiere conocer de antemano todos los requisitos del sistema. Sólo es aplicable a pequeños desarrollos, ya que las etapas pasan de una a otra sin retorno posible. (se presupone que no habrá errores ni variaciones del software). 
  - Con realimentación: es uno de los modelos más utilizados. Proviene del modelo anterior, pero se introduce una realimentación entre etapas, de forma que podamos volver atrás en cualquier momento para corregir, modificar o depurar algún aspecto. No obstante, si se prevén muchos cambios durante el desarrollo no es el modelo más idóneo. Es el modelo perfecto si el proyecto es rígido (pocos cambios, poco evolutivo) y los requisitos están claros. 
- Modelo evolutivo. tiene en cuenta la naturaleza cambiante y evolutiva del software. La idea detrás de este modelo es el desarrollo de una implantación del sistema inicial, exponerla a los comentarios del usuario, refinarla en N versiones hasta que se desarrolle el sistema adecuado. Una ventaja de este modelo es que se obtiene una rápida realimentación del usuario, ya que las actividades de especificación, desarrollo y pruebas se ejecutan en cada iteración. El modelo en espiral es un tipo de modelo de desarrollo de software que fue introducido por Barry Boehm en 1986. Este modelo combina elementos de diseño y prototipado en etapas para el proceso de software, con el fin de combinar ventajas de desarrollo de software de arriba hacia abajo y de abajo hacia arriba.

El modelo en espiral es un modelo evolutivo e iterativo, lo que significa que el software se desarrolla en incrementos iterativos en lugar de en una sola pasada. Este modelo también se centra en la gestión de riesgos en cada fase del proceso de desarrollo.

El modelo en espiral consta de cuatro fases principales:

1. **Determinación de objetivos**: En esta fase, se identifican los objetivos para la iteración actual. Esto puede incluir el desarrollo de nuevas características, la mejora de las existentes, o la corrección de errores. Se identifican y documentan los requisitos para estos objetivos.

2. **Análisis de riesgos**: En esta fase, se identifican y evalúan los riesgos potenciales que podrían afectar a la iteración actual. Esto puede incluir riesgos técnicos, como la posibilidad de que una característica no funcione como se esperaba, y riesgos de gestión, como la posibilidad de que el proyecto se retrase.

3. **Desarrollo y validación**: En esta fase, se desarrolla y prueba el software. Esto puede implicar la creación de un prototipo para validar los requisitos y el diseño, y luego la implementación y prueba del software.

4. **Planificación**: En esta fase, se revisa el proyecto y se planifica la próxima iteración. Esto puede implicar la revisión de los resultados de la iteración actual, la evaluación de los riesgos y la planificación de los objetivos para la próxima iteración.

Estas cuatro fases se repiten en cada iteración del proyecto, con el software evolucionando y mejorando con cada iteración. Esto permite un desarrollo más flexible y adaptable, ya que los cambios pueden incorporarse en cada iteración en lugar de tener que ser planificados desde el principio. Distinguimos dos variantes: 
    - Modelo Iterativo Incremental. Está basado en el modelo en cascada con realimentación, donde las fases se repiten y refinan, y van propagando su mejora a las fases siguientes. 
    - Modelo en Espiral. Es una combinación del modelo anterior con el modelo en cascada. En él, el software se va construyendo repetidamente en forma de versiones que son cada vez mejores, debido a que incrementan la funcionalidad en cada versión. Es un modelo bastante complejo. 

## Metodologías Ágiles
Las metodologías ágiles son un conjunto de metodologías de desarrollo de software que se basan en el desarrollo iterativo e incremental, donde los requisitos y soluciones evolucionan con el tiempo según la necesidad del proyecto.
Además, las metodologías ágiles promueven el trabajo en equipo, la colaboración con el cliente y la adaptación al cambio. Los equipos de desarrollo ágil se autoorganizan y se organizan de forma planificada y regular. Todos los equipos de desarrollo ágil deben seguir los cuatro valores y los doce principios del [Manifiesto Ágil](https://agilemanifesto.org/iso/es/manifesto.html).

## Referencias
- https://intelequia.com/blog/post/2083/ciclo-de-vida-del-software-todo-lo-que-necesitas-saber
- https://www.monografias.com/docs114/modelos-desarrollo/modelos-desarrollo

## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/JoseLuisGS_)

[![Twitter](https://img.shields.io/twitter/follow/JoseLuisGS_?style=social)](https://twitter.com/JoseLuisGS_)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)
[![GitHub](https://img.shields.io/github/stars/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto

<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
 <a href="https://joseluisgs.dev" target="_blank">
        <img src="https://joseluisgs.github.io/img/favicon.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://distreau.com/github.svg" 
    height="30">
    </a> &nbsp;&nbsp;
        <a href="https://twitter.com/JoseLuisGS_" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://g.dev/joseluisgs" target="_blank">
        <img loading="lazy" src="https://googlediscovery.com/wp-content/uploads/google-developers.png" 
    height="30">
    </a>  &nbsp;&nbsp;
<a href="https://www.youtube.com/@joseluisgs" target="_blank">
        <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" 
    height="30">
    </a>  
</p>

## Licencia de uso

Este repositorio y todo su contenido está licenciado bajo licencia **Creative Commons**, si desea saber más, vea
la [LICENSE](https://joseluisgs.dev/docs/license/). Por favor si compartes, usas o modificas este proyecto cita a su
autor, y usa las mismas condiciones para su uso docente, formativo o educativo y no comercial.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
JoseLuisGS</span>
by <a xmlns:cc="http://creativecommons.org/ns#" href="https://joseluisgs.dev/" property="cc:attributionName" rel="cc:attributionURL">
José Luis González Sánchez</a> is licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License</a>.<br />Creado a partir de la obra
en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/joseluisgs" rel="dct:source">https://github.com/joseluisgs</a>.