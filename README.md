# Proyecto Reserva de Canchas Online

## Curso
Ingenieria de Software Agil 1

## Docentes
* Fabiana Pedrini
* Alejo Pereira

## Estudiantes

* Agustina Serrón - 264641
* Brahian Peña - 267633
* Daniela Waldeck - 193254
* Federico Mendez - 223255
* Nicolas Bruno - 172648
* Vicente Bermudez - 214831

## Indice
- [Marco de Trabajo](#marco-de-trabajo)
  * [Roles y Responsabilidades](#roles-y-responsabilidades)
  * [Eventos / Ceremonias](#eventos--ceremonias)
  * [Artefactos](#artefactos)
  * [Adaptaciones](#adaptaciones)
  * [Definición de Ready (DoR)](#definicion-de-ready-dor)
  * [Definición de Done (DoD)](#definicion-de-done-dod)
  * [Escala de Estimación](#escala-de-estimacion)
  * [Estrategia de Branching](#estrategia-de-branching)
- [Iteración 1](#iteracion-1)
  * [Objetivo de la Iteración](#objetivo-de-la-iteracion)
  * [Desarrollo de la Iteración](#desarrollo-de-la-iteracion)
    + [Fecha de Inicio](#fecha-de-inicio)
    + [Fecha de Fin](#fecha-de-fin)
    + [Minuta Sprint Planning](#minuta-sprint-planning)
    + [Daily Scrum Meetings](#daily-scrum-meetings)
  * [Resultados Claves](#resultados-claves)
    + [Identificación del problema a resolver](#identificacion-del-problema-a-resolver)
    + [Definición del problema/solución](#definicion-del-problemasolucion)
  * [Análisis del Proceso de la Iteración](#analisis-del-proceso-de-la-iteracion)
    + [Registro de Horas](#registro-de-horas)
    + [Minuta Retrospective Meeting - 05/05](#minuta-retrospective-meeting---0505)
    + [Resultado](#resultado)
- [Iteración 2](#iteracion-2)
  * [Objetivo de la Iteración](#objetivo-de-la-iteracion-1)
  * [Desarrollo de la Iteración](#desarrollo-de-la-iteracion-1)
    + [Fecha de Inicio](#fecha-de-inicio-1)
    + [Fecha de Fin](#fecha-de-fin-1)
    + [Minuta Sprint Planning](#minuta-sprint-planning-1)
    + [Daily Scrum Meetings](#daily-scrum-meetings-1)
  * [Resultados Claves](#resultados-claves-1)
    + [Prototipado](#prototipado)
  * [Sprint Review](#sprint-review)
    + [Sesiones de Usability Testing](#sesiones-de-usability-testing)
    + [Inspección y adaptación del producto](#inspeccion-y-adaptacion-del-producto)
  * [Análisis del Proceso de la Iteración](#analisis-del-proceso-de-la-iteracion-1)
    + [Burndown Chart](#burndown-chart)
    + [Velocidad](#velocidad)
    + [Registro de Horas](#registro-de-horas-1)
  * [Minuta Retrospective Meeting - 19/05](#minuta-retrospective-meeting---1905)
    + [Resultado](#resultado-1)
- [Iteración 3](#iteracion-3)
  * [Objetivo de la Iteración](#objetivo-de-la-iteracion-2)
  * [Desarrollo de la Iteración](#desarrollo-de-la-iteracion-2)
    + [Fecha de Inicio](#fecha-de-inicio-2)
    + [Fecha de Fin](#fecha-de-fin-2)
    + [Minuta Sprint Planning](#minuta-sprint-planning-2)
    + [Daily Scrum Meetings](#daily-scrum-meetings-2)
  * [Resultados Claves](#resultados-claves-2)
    + [Prototipado](#prototipado-1)
  * [Sprint Review](#sprint-review-1)
    + [Sesiones de Usability Testing](#sesiones-de-usability-testing-1)
    + [Inspección y adaptación del producto](#inspeccion-y-adaptacion-del-producto-1)
  * [Análisis del Proceso de la Iteración](#analisis-del-proceso-de-la-iteracion-2)
    + [Burndown Chart](#burndown-chart-1)
    + [Velocidad](#velocidad-1)
    + [Registro de Horas](#registro-de-horas-2)
  * [Minuta Retrospective Meeting - 02/06](#minuta-retrospective-meeting---0206)
    + [Resultado](#resultado-2)

# Marco de Trabajo

El framework de gestión a utilizar es Scrum, el cual se ajusta muy bien al problema planteado, ya que es un marco de trabajo ágil que se enfoca en la entrega de valor al cliente de manera iterativa e incremental. Scrum permite una mayor flexibilidad y adaptabilidad a los cambios y requisitos del proyecto, y ofrece un enfoque colaborativo y transparente en la gestión de proyectos. Sin embargo, se realizarán algunas adaptaciones para adecuarlo al proyecto.

## Roles y Responsabilidades
* **Product Owner (Vicente Bermúdez)**: Es responsable de maximizar el valor del producto, ayudando a definir y priorizar el backlog del producto en colaboración con los stakeholders, participar en la planificación del sprint y asegurar la comunicación clara de la visión del producto. Además, debe tomar decisiones sobre el producto.

* **Scrum Master (Brahian Peña)**: Su función principal es facilitar el proceso Scrum y asegurarse de que se sigan los principios y prácticas adecuadas. Sus responsabilidades incluyen facilitar las reuniones y eventos de Scrum, eliminar obstáculos o impedimentos que puedan afectar al equipo, promover la autoorganización del equipo de desarrollo y apoyar al Product Owner en la gestión del backlog del producto y en el cumplimiento de los objetivos del proyecto.

* **Desarrolladores (Federico Méndez, Agustina Serrón, Nicolás Bruno, Daniela Waldeck, Brahian Peña)**: Es responsable de desarrollar los incrementos del producto. Sus responsabilidades incluyen implementar, probar y entregar los incrementos del producto durante cada sprint, autoorganizarse y colaborar para decidir cómo llevar a cabo el trabajo y mantener la calidad del producto mediante prácticas ágiles.

## Eventos / Ceremonias
Para alcanzar los objetivos del proyecto, realizaremos los siguientes eventos en cada iteración:
* **Sprint Planning Meeting**: La reunión de planificación del sprint es una ceremonia en la que el equipo de Scrum define el trabajo a realizar durante el próximo sprint. Se lleva a cabo al comienzo del sprint y generalmente tiene una duración de 1 a 4 horas, dependiendo de la duración del sprint. Durante esta reunión, el Product Owner presenta los elementos prioritarios del backlog del producto y el equipo de desarrollo selecciona los elementos que se comprometerá a completar durante el sprint. Se establecen los objetivos del sprint y se define el plan de acción para lograrlos.
    La planning meeting se realizará en una video llamada (en lo posible) el día que comienza el sprint.
    
* **Daily Scrum Meeting**: Su objetivo es que el equipo de desarrollo se sincronice y coordine en torno a las tareas del sprint. En la reunión, los miembros del equipo responden a tres preguntas clave: ¿Qué hice ayer?, ¿Qué haré hoy? y ¿Hay algún impedimento o bloqueo? Se enfoca en la comunicación efectiva y la identificación temprana de problemas para facilitar la colaboración y la toma de decisiones.
    La meeting se realizará mediante WhatsApp, dos veces a la semana.
    

* **Sprint Review Meeting**: La revisión del sprint es una ceremonia que se realiza al finalizar cada sprint y tiene como objetivo principal revisar y evaluar el trabajo completado durante el sprint. Durante esta reunión, el equipo de desarrollo presenta los incrementos del producto que se han construido y se recopilan los comentarios y la retroalimentación de los stakeholders. Se analiza si los resultados alcanzados cumplen con los criterios de aceptación y se pueden adaptar los elementos del backlog del producto en función de las nuevas necesidades o requisitos identificados. La revisión del sprint es una oportunidad para demostrar el progreso y recibir comentarios valiosos para la planificación futura.


* **Sprint Retrospective Meeting**: La retrospectiva del sprint es una ceremonia que se realiza al finalizar cada sprint con el objetivo de reflexionar sobre el proceso de trabajo y buscar oportunidades de mejora. Durante esta reunión, el equipo de Scrum examina lo que ha funcionado bien, lo que no ha funcionado y las posibles áreas de mejora. Se utilizan técnicas y herramientas colaborativas, como la herramienta MetroRetro, para facilitar la discusión y la generación de ideas. Al final de la retrospectiva, se identifican acciones concretas (action items) que se implementarán en el próximo sprint para abordar los problemas identificados y mejorar el proceso de trabajo en general.
    
Para más detalles de la cadencia de realización de estos eventos, ver la sección de adaptaciones.

## Artefactos
Aparte de las ceremonias, también definimos los siguientes artefactos:

* **Backlog del producto**: Lista de nuevas funciones, mejoras, correcciones de errores, tareas o requisitos de trabajo necesarios. Se obtendrá a partir de fuentes como interacciones con los stakeholders, los análisis de la competencia, las demandas del mercado y los análisis empresariales en general. Este será actualizado a medida que se obtenga nueva información.

* **Backlog del sprint**: Es un conjunto de tareas del backlog del producto que se seleccionaron para desarrollarse durante la siguiente iteración. Estos son creados para planificar las entregas de cara a los futuros incrementos y detallar el trabajo necesario para concebir el incremento.

* **Incremento del producto**: Esto será la entrega al cliente que tiene lugar al completar las tareas del backlog del producto durante un sprint. A su vez, incluye los incrementos de todos los sprints anteriores.
    
    
## Adaptaciones

* En este caso, tanto el Scrum Master como el Product Owner, también tendrán doble rol como Desarrollador, debido a que la cantidad de integrantes del equipo es acotada.
* Daily Scrum Meeting se realizará Martes y Jueves de manera asíncrona (vía WhatsApp), ya que no se trabajará todos los días en el proyecto. 
En base a un action item generado en la retrospective de la primera iteración, se decició modificar la cadencia de este evento y realizarlo los días Lunes y Jueves.

* La Sprint Review Meeting se llevará a cabo en dos partes:
    1. Meeting para demostrar el incremento al equipo liderada por el Product Owner y el Scrum Master.
    2. Validación con los stakeholders (usuarios) de manera personal.

    La primera iteración no tendrá review.
* La Sprint Retrospective será una meeting de treinta minutos - siendo posible extenderla a máximo una hora. En ella los primeros quince minutos serán para pensar los temas a tratar y luego los quince (máximo cuarenta y cinco) minutos restantes serán para discutirlos.

## Definición de Ready (DoR)
Una tarea está lista para ser trabajada cuando:
* La tarea debe estar claramente definida y descrita en el Product Backlog.
* La tarea debe estar priorizada en el Product Backlog y haber sido aceptada por el Product Owner.
* La tarea debe ser lo suficientemente pequeña para ser completada en un Sprint.
* Los criterios de aceptación de la tarea deben ser definidos y acordados por el equipo de desarrollo.
* Todos los recursos y materiales necesarios para completar la tarea deben estar disponibles.
* Los riesgos y dependencias asociados con la tarea deben ser identificados y resueltos o mitigados en lo posible.
* El equipo de desarrollo debe tener un entendimiento común de la tarea y de cómo se relaciona con el MVP final del proyecto.

## Definición de Done (DoD)
El incremento está completo cuando:
* Se ha desarrollado y probado adecuadamente.
* Ha sido revisado y aprobada por el Scrum Master y el Product Owner.
* Se ha integrado en el producto completo de forma adecuada.
* Los prototipos deben seguir las mejores prácticas de diseño de interfaz de usuario y ser fáciles de usar para las distintas franjas etarias de población.
* Los prototipos deben ser compatibles con dispositivos móviles (iOS y Android) y seguir las guías de interfaz de usuario de cada plataforma.
* Los prototipos deben estar en un estado que permita su evaluación y revisión por parte de los stakeholders y el equipo.
* Cumple con los requisitos definidos en el Product Backlog.
* Se ha creado toda la documentación necesaria en el documento compartido en [HackMD](https://hackmd.io/) (el cual luego sera agregado al repositorio de GIT).

## Escala de Estimación
Para estimar las tareas utilizaremos el método póker, preguntándole a cada miembro del equipo qué número de la escala de Fibonacci le asigna a cada tarea del Backlog en relación a su nivel de dificultad. 

Los miembros que elijan números altos y bajos (con respecto a lo que estimó el resto del equipo) deberan exponer las razones de su elección. Luego, si es necesario, se vuelve a estimar según las nuevas percepciones discutidas hasta llegar a un consenso.

Se utilizará la extensión de Azure Devops: Planning Poker.

## Estrategia de Branching
Tendremos una rama por cada iteración y una rama por cada tarea dentro de la misma (las ramas por tarea no aplican para la primera iteración).
Una vez que la tarea cumpla con la definición de hecho se integrará a la rama de la iteración correspondiente. Al final de la iteración se integrará la misma a la rama main. Se puede ver como una adaptación de GitFlow.

# Iteración 1

## Objetivo de la Iteración
El objetivo de esta iteración es identificar y definir el problema a resolver.

## Desarrollo de la Iteración

### Fecha de Inicio
17/04/2023

### Fecha de Fin
05/05/2023

### Minuta Sprint Planning

#### Fecha
17/04/2023.
#### Hora
17:30.
#### Duración
Dos horas.

#### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

#### Agenda

1. Objetivos de la reunión
2. Revisión del Product Backlog
3. Establecimiento del Objetivo del Sprint
4. Selección de elementos del Product Backlog para el Sprint
5. Estimación de los elementos seleccionados
6. Asignación de tareas a los miembros del equipo
7. Planificación de la reunión diaria
8. Cierre de la reunión

#### Desarrollo

##### Objetivos de la reunión
El Scrum Master junto al Product Owner presentaron los objetivos de la reunión los cuales fueron revisar el Product Backlog, seleccionar los elementos que se incluirían en el Sprint, estimarlos y asignarlos. También se estableció el objetivo del sprint.

##### Revisión del Product Backlog
El Product Owner presentó el Product Backlog. El equipo hizo preguntas y discutió los elementos más importantes.

##### Establecimiento del Objetivo del Sprint
El equipo definió y discutió el objetivo del Sprint, siendo el resultado: Identificar y definir el problema a resolver.

##### Selección, Estimación y Asignación de Elementos del Product Backlog para el Sprint:
El equipo seleccionó los elementos del Product Backlog que se incluirán en el Sprint. Los estimó utilizando la escala planteada en el marco de trabajo. Luego se asignaron, asegurándose que cada tarea tenga un responsable. El resultado es el siguiente:
<img class="img-fluid" src="https://i.imgur.com/tH8uXbs.png" width="740" height="340">



##### Planificación de la Reunión Diaria
El equipo acordó el horario de la reunión diaria, el formato y el canal por la que se realizará.

##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

### Daily Scrum Meetings

#### Minuta Daily Scrum - 18/04

##### Fecha
18/04/2023.

##### Hora
18:00.

##### Duración
Asíncrona.

##### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

##### Agenda

1. Revisión del estado actual del equipo
2. Cierre de Reunión

#### Desarrollo

##### Revisión del Estado Actual del Equipo
El Scrum Master a la hora indicada solicitó los estados actuales de cada uno de los integrantes del equipo. Los mismos fueron los siguientes:
![](https://i.imgur.com/C8VfFrA.png)

##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

#### Otras Reuniones
Para ver los estados de los integrantes del equipo en el resto de Daily Scrum Meetings, dirigerse al directorio *Iteracion 1/Anexos/Dailies*.

## Resultados Claves

### Identificación del problema a resolver

#### Identificación de interesados
1. Jugadores: Personas de cualquier edad que realicen actividades deportivas. 
2. Dueños de canchas: Aquellas personas que tienen canchas aptas para actividades deportivas (las funcionalidades para estos están por fuera del alcance del proyecto).


#### Lista de funcionalidades por interesado
##### Funcionalidades generales (para jugadores y dueños de cancha)
* Login usuario
* Registrar usuario
* Editar usuario
* Restablecer Contraseña

##### Jugadores
* Buscar canchas para reservar utilizando filtros.
* Buscar canchas para reservar a través de la búsqueda en el mapa.
* Mostrar la distancia en el mapa entre el usuario y la cancha deportiva a reservar.
* Invitar a un usuario a una reserva realizada.
* Lista de canchas favoritas para el usuario.
* Reservar cancha.
* Visualización de cupos restantes en reserva de cancha
* Recibir notificación cuando el partido aleatorio ha sido confirmado luego de llegar al cupo.
* Recibir notificación cuando el horario reservado no está disponible.
* Recibir notificación cuando la cancha reservada ha sido confirmada por un Dueño.
* Recibir notificación cuando la cancha reservada ha sido cancelada por un Dueño.
* Recibir notificación cuando otro jugador me ha invitado a un partido en cierto horario.
* Recibir notificación cuando un jugador que he invitado ha aceptado mi invitación.
* Dividir tarifa de la cancha.
* Pagar el total de la tarifa de la cancha.
* Pagar la parte que me corresponde de la tarifa.
* Ver pagos en mi cancha reservada
* Visualización de una cancha seleccionada.
* Ver las reservas que hice previamente.
* Cancelar una reserva que hice previamente.
* Unirme a partido creado de forma aleatoria


#### Estudio de competidores


**Nombre del competidor:** QuieroJugar

**Descripción breve del competidor:** QuieroJugar es una aplicación que concentra canchas deportivas y ofrece a los complejos un software completo de gestión. Para los usuarios es una manera fácil de encontrar hora, reservar y señar directo desde la app. Disponible para iOS y Android. Funciona únicamente para Uruguay.

**Características y funcionalidades ofrecidas por el competidor:** 
* Siendo usuario
-Poder reservar canchas de diversos deportes
-Poder ver características de la cancha a reservar
-Búsqueda de lugares para entrenar
-Tener un panel para gestionar las reservas del usuario
* Siendo dueño de una cancha
-Poder poner la cancha a disposición para posibles usuarios
-Tener un panel para gestionar reservas


**Experiencia del usuario al utilizar la aplicación del competidor:** tiene una calificación de 4.8 estrellas en Play Store. Es una aplicación con una buena performance, no se detectaron errores.





##### Al comienzo de la aplicación puedo elegir entre dos tipos de usuario: usuario o admin


<img class="img-fluid" src=https://i.imgur.com/W71yvww.jpg width="400" height="600">

<img class="img-fluid" src=https://i.imgur.com/HuYbvpD.jpg width="400" height="600">

<img class="img-fluid" src=https://i.imgur.com/3xJk4vl.jpg width="400" height="600">


##### Si entro a una de las opciones de canchas disponibles (color verde) me aparece la siguiente información 

<img class="img-fluid" src=https://i.imgur.com/M7mJKw2.jpg width="400" height="600">


##### Si el icono aparece en color rojo, es porque la cancha no está disponible

<img class="img-fluid" src=https://i.imgur.com/TmMctKM.jpg width="400" height="600">
<img class="img-fluid" src=https://i.imgur.com/s3uUK8K.jpg width="400" height="600">


##### También ofrece la posibilidad de encontrar lugares para entrenar

<img class="img-fluid" src=https://i.imgur.com/Awd8Bmy.jpg width="400" height="600">

##### Cada usuario tiene su propio perfil 

<img class="img-fluid" src=https://i.imgur.com/1aTVsge.jpg width="400" height="600">


##### Otras funcionalidades 

<img class="img-fluid" src=https://i.imgur.com/fgLNLDW.jpg width="400" height="600">
<img class="img-fluid" src=https://i.imgur.com/WGq1EFg.jpg width="400" height="600">


---------



**Nombre del competidor:** Canchea

**Descripción breve del competidor:** Canchea, es una página web (https://canchea.com.uy/) que permite reservar canchas de : Fútbol 5,7,11 , Básquet 5 y Tenis. Funciona solo para Uruguay.

**Características y funcionalidades ofrecidas por el competidor:** 
* Siendo usuario
-Poder reservar canchas de Fútbol 5,7,11 , Basquet 5 y Tenis
-Tener un panel para gestionar las reservas del usuario
-Ver campeonatos disponibles
* Siendo dueño de una cancha
-Poder poner la cancha a disposición para posibles usuarios



**Experiencia del usuario al utilizar la página** 
Al ser una página web no parece ser tan práctica como una aplicación. Está restringida para algunos deportes solamente. La performance no es muy buena, generando que se enlentezca la página al momento de uso.




##### Página principal
![](https://i.imgur.com/DV571bV.png)
##### La página ofrece estas 3 opciones : registrarse como usuario, ver campeonatos disponibles, sumar un centro deportivo
![](https://i.imgur.com/ESIZQ4t.png)

##### Registro de nuevos usuarios
![](https://i.imgur.com/jEt17Ox.png)

##### Lista de campeonatos
![](https://i.imgur.com/OcHDQwT.png)
##### Ingreso de nuevo centro
![](https://i.imgur.com/LmjJkTH.png)


---------


#### Estudio de otras aplicaciones similares

**Nombre de la aplicación:** Playtomic

**Descripción breve:** Playtomic es una aplicación española, enfocada específicamente en Tenis y Padel. Tiene una versión web (https://playtomic.io/) aparte de la versión móvil para Android e iOS

**Características más destacables para nuestro proyecto:** 
* Siendo usuario
-Permite hacer una reserva individualmente, y luego volver la partida pública, es decir, habilitar a otros jugadores a que se sumen a la partida para jugar .
-En estas partidas públicas, la tarifa se divide entre los participantes, y no es posible sumarse a una partida sin abonar el monto correspondiente. Si el partido no se completa y no se inscriben la cantidad de jugadores necesarios antes de un tiempo límite, el sistema lo cancela automáticamente y devuelve el importe a cada jugador inscrito antes de la cancelación.
-Sistema de niveles o ranking. Cada jugador al inscribirse en la aplicación debe llenar un formulario donde detalla su nivel actual de juego. Una vez que se es miembro de la comunidad, cada partida que se juegue (que se defina como competitiva) afectará al puntaje del jugador, haciendo que suba o baje su nivel, dependiendo del resultado, y del nivel del rival. Esto permite a los demás usuarios buscar rivales con niveles competitivos similares, lo cual debería ayudar a que las partidas sean más parejas, y por lo tanto más interesantes.

##### Partidas públicas
![](https://i.imgur.com/tdoPbJD.png)

##### Sistema de niveles
![](https://i.imgur.com/xdCZUGy.png)


**Experiencia del usuario:** Tiene más de 1 millón de descargas en Play Store. Es una aplicación con una buena performance y un diseño muy cuidado, no se detectaron errores.

---------

**Nombre de la aplicación:** Timpik

**Descripción breve:** Playtomic es una aplicación española, con versiones tanto web (https://www.timpik.com/) como móvil para Android e iOS, y maneja una gama muy amplia de deportes.

**Características más destacables para nuestro proyecto:** 
* Siendo usuario
-Además de la posibilidad de crear partidas públicas, a las que los jugadores pueden unirse, permite crear "Clubes", lo que serían comunidades de jugadores, donde estos pueden compartir su disponibilidad y permite crear eventos públicos pero solo dentro del alcance del club, a diferencia de los eventos netamente públicos, que son visibles para todos los miembros de la aplicación.
-Amonestaciones y normas. En cada partida pública, el organizador define las normas. Los jugadores que incumplan con las normas definidas, serán sancionados de la siguiente manera:
Tarjeta amarilla: Si has llegado tarde, creas conflictos, te has borrado horas antes... (Dos tarjetas amarillas implican una tarjeta roja)
Tarjeta Roja: Has dejado tirado a tus compañeros y no has ido al partido.... Durante los próximos 3 partidos la inscripción en los partidos no será instantánea y tendrá que ser aprobada por el organizador del evento.
Este sistema de amonestaciones puede ser útil para bannear jugadores que no respeten las normas y que por lo tanto afectan la experiencia de los demás jugadores.

##### Partidas públicas
![](https://i.imgur.com/MQWFB5F.png)

##### Ejemplos de normas de los eventos
![](https://i.imgur.com/c0mlsFi.png)
![](https://i.imgur.com/hgrj8fw.png)

---------
#### Conclusiones del estudio de competidores y otras aplicaciones similares

Dentro de las opciones disponibles en Uruguay, es claro que el competidor principal es QuieroJugar, por ser el único con versión móvil, el más conocido y el que tiene una gama mayor de deportes y actividades disponibles. El diseño no parece ser un fuerte en ninguna de los dos competidores analizados.
Por otra parte, estudiando aplicaciones similares extranjeras, queda evidente que en otros territorios estas aplicaciones agregan una buena parte de "red social", que permite que se generen partidas entre miembros de la red. También estas aplicaciones extranjeras agregan la cuestión del seguimiento de los resultados y de los niveles de cada jugador, lo que enriquece las partidas públicas, al generar un desafío para quienes participan, que buscan subir su puntaje.



| Funcionalidad                                                              | QuieroJugar | Canchea | Playtomic | Timpik |
| -------------------------------------------------------------------------- | ----------- | ------- | --------- | ------ |
| Tener un perfil personal en la aplicación                                  | sí          | sí      | sí        | sí     |
| Poder visualizar canchas de diferentes deportes                            | sí          | algunos | algunos   | sí     |
| Reservar canchas                                                           | sí          | sí      | sí        | sí     |
| Crear partidas públicas                                                    | no          | no      | sí        | sí     |
| Sistema de niveles o ranking para los usuarios                             | no          | no      | sí        | no     |
| Poder ver campeonatos futuros                                              | no          | sí      | no        | no     |
| Pagos integrados                                                                         |       no     |      no   |       no    |    no   |
| Poder visualizar en un mapa las canchas disponibles y asi ver su ubicación | sí          | sí      | sí         | sí      |
| La aplicación esta diponible solo en Uruguay                               | sí          | sí      | no         | no      |
| Plataforma de funcionamiento                                               | Android/IOS | WEB     | Android/IOS y WEB         | Android/IOS y WEB        |



#### Segmentación del mercado
Para conocer más a nuestro público y posibles interesados realizamos encuestas y entrevistas.

##### Encuestas
Aprovechamos la instancia de la encuesta para validar algunas funcionalidades de nuestra app y reconocer nuevas oportunidades. Además tener una perspectiva más clara sobre quiénes serán los usuarios, sus edades, la frecuencia con que utilizarán la aplicación y que tipos de deportes realizan.
![](https://i.imgur.com/RIlifYM.png)
![](https://i.imgur.com/VXxDId4.png)
![](https://i.imgur.com/G2BMvEa.png)
![](https://i.imgur.com/bXqyilw.png)
![](https://i.imgur.com/hnN8QHE.png)
![](https://i.imgur.com/EHmrP0Z.png)
![](https://i.imgur.com/pOpGziu.png)
![](https://i.imgur.com/5Yx7iBT.png)
![](https://i.imgur.com/rdkFNHg.png)
![](https://i.imgur.com/qgzbvjo.png)
![](https://i.imgur.com/i1MYL5x.png)
Por más información consultar el documento .csv dentro de la carpeta Anexos que resume las respuestas obtenidas en la encuesta.

Dado que dejamos abierta la respuesta a la pregunta: "qué funcionalidades no podrían faltar en una App de reserva de cancha?", algunos de los encuestados se tomaron el trabajo de dejar sugerencias, entre ellas quisiéramos destacar:
- Fotos de estado de la cancha proporcionadas por usuarios
- Compartir ubicación de la cancha
- Pagos integrados
- Recordatorio de reserva
- Descuentos por reserva anticipada
- Lista de espera si está ocupada la cancha
- Recompensas para usuarios frecuentes
- Gestión de la reserva recurrente para repetir dia y hora
- Clasificaciones de los equipos rivales

A la hora de diseñar y prototipar la aplicación podremos basarnos en estos aspectos para asegurarnos de presentar esa información de forma clara y útil.

Evaluaremos técnicamente la posibilidad de incorporar la integración de pagos y división de tarifa en nuestra app ya que como se puede ver en las encuestas, la gran mayoría de los encuestados evaluó como muy útil esa funcionalidad y más de la mitad de ellos consideraron que el momento de pago suponía una problemática.
##### Entrevistas
Se llevaron a cabo dos entrevistas con el fin de validar la problemática y las funcionalidades que podrían ayudar al usuario al momento de utilizar la aplicación.

Se prepararon 10 preguntas que se realizaron a dos personas, las cuales se mencionan a continuación: 
1. ¿Qué deportes practicas con mayor frecuencia?
2. ¿Cómo buscas y reservas canchas deportivas actualmente? ¿Qué dificultades has enfrentado al hacerlo?
3. ¿Qué características consideras importantes al buscar y reservar canchas deportivas?
4. ¿Cómo te gustaría que una aplicación móvil te ayudará a buscar y reservar canchas deportivas?
5. ¿De qué ámbito son generalmente las personas que participan de los partidos? ¿Con amigos, compañeros de trabajo, amigos de amigos?
6. ¿Has tenido dificultades para encontrar suficientes personas para realizar el partido? Si es así, ¿cómo lo has resuelto?
7. ¿Qué te parece la idea de jugar con personas desconocidas para poder completar los equipos?
8. ¿Te gustaría unirte a un partido y jugar con personas desconocidas?
9. ¿Qué características te parecería importante que ofrezca una aplicación móvil para la organización de los partidos?
10. ¿Qué tipos de avisos te gustaría recibir de una aplicación móvil relacionada con la reserva y organización de actividades deportivas?


A continuación se detallan las respuestas de ambas entrevistas realizadas. 

Respuestas primera entrevista:
1. Principalmente fútbol y a veces basquetbol
2. Al principio buscaba por internet o google maps, y luego una vez que ya se había reservado en varios lugares ya tengo, por llamarlo de alguna como una agenda de las canchas que son opciones para reservar. La dificultad es que no siempre están disponibles, en esos casos me comunico con varias canchas y ello conlleva a que consuma mucho tiempo reservar.
3. Lo más importante es el horario disponible y ubicación. Otras características a tener en cuenta es el precio y estado de la cancha.
4. Que me muestre un mapa con las canchas, fotos del lugar y en qué horario está disponible. También que pueda ingresar un rango de hora y me muestre solo las disponibles para esa hora.
5. Generalmente son amigos o compañeros de trabajo.
6. Si he tenido dificultad, en esos casos cada persona que va a jugar pregunta en sus otros círculos de personas con el cual habitualmente practica deporte.
7. No me parece una mala idea ya que ayudaría mucho a la hora de completar los equipos, especialmente cuando te faltan pocas personas.
8. Si me gustaría ya que a veces no es fácil coincidir con la disponibilidad horaria de cada uno de los grupos de personas que habitualmente uno juega. También me sucede cuando quiero jugar al basquetbol que al ser un deporte que lo practica menos gente es más difícil de conseguir suficientes personas para armar un partido.
9. Que sea fácil de usar, que tenga los horarios de disponibilidad de cada cancha actualizados y que se pueda pagar por la aplicación.
10. Me parece que seria de gran ayuda recibir notificaciones en los siguientes casos:
- Cuando se haya confirmado la reserva.
- Cuando se cancela por alguna razón.
- En caso de que se quiera sumar a una persona aleatoria recibir la notificación de que hay alguien interesado en jugar, lo mismo pero a la inversa o sea si yo quiero jugar con gente aleatoria que me notifiquen que hay partidos disponibles de ese tipo.

Respuestas segunda entrevista: 
1. Handball y fútbol.
2. Busco por Internet y reservo por teléfono. La mayor dificultad que me aparece es perder mucho tiempo llamando para encontrar cancha. A veces perder la posibilidad porque no atienden el teléfono o WhatsApp.
3. Saber las condiciones de la cancha a nivel estructural, tener facilidad de tener los horarios disponibles a la vista momento a momento y no tener que llamar a cada rato para reconfirmar si sigue disponible la cancha a la hr que quiero. Tener a disposición los precios por hr y modo de pago para poder comparar con mayor facilidad.  Y la distancia a la que está la cancha.
4. Me gustaría que tuviera un calendario con horarios, locación, precio, fotos del lugar y reseñas para tener todo eso en cuenta a la hr de reservar un lugar. Y que sea más fácil comparar y lograr conseguir la mejor opción de acuerdo a las características que queramos de la cancha.
5. Amigos y/o compañeros de trabajo.
6. Sí, hemos tenido dificultades. Ahí intentamos cada uno escribir en distintos grupos de amigos y conocidos si hay alguien disponible. En algunos casos hemos tenido que suspender por falta de gente. 
7. Me parece una idea práctica que solucionaría los problemas.
8. Me considero una persona extrovertida así que sí,  me gustaría. Me parece divertido conocer personas nuevas y además hacer una actividad que me divierte. 
9. Características de los jugadores,  posiciones en las que juega, reseñas de otras personas con las que haya jugado, especificar si ha dejado plantado a otras personas en partidos, es decir que haya un ítem para puntuar la puntualidad, responsabilidad y concurrencia a los compromisos deportivos que se anote por la app. Deporte que le interesa y disponibilidad horaria y zona en la que puede jugar. 
10. Promociones de alquileres de canchas. Avisos de partidos que se estén armando cerca de mi zona.


---------
### Definición del problema/solución

Crear una aplicación móvil para ayudar al usuario a reservar canchas para realizar actividades deportivas.

#### Propuesta de Valor y Diferenciador de nuestra propuesta
Nuestra solución ofrece a los usuarios la posibilidad de reservar canchas para actividades deportivas de una manera más práctica y social. Con nuestra aplicación, los usuarios pueden crear partidas públicas a las que otros usuarios pueden unirse, y dividir el costo de la reserva entre todos los participantes. Estas características son una gran ventaja en comparación con las aplicaciones existentes en el mercado, ya que no ofrecen estas opciones.

La creación de partidas públicas permite a los usuarios ampliar su círculo de contactos deportivos y encontrar nuevos compañeros para jugar y compartir el costo de la reserva de canchas. Esto es particularmente beneficioso para aquellos que no tienen un equipo o grupo de amigos para practicar deportes de manera regular, ya que les brinda la oportunidad de unirse a partidas públicas y conocer a otros jugadores con intereses similares.

Además, la opción de dividir el costo de la reserva entre todos los participantes es una gran ventaja en comparación con las aplicaciones existentes, ya que el pago de las reservas es muchas veces la parte más compleja de la logística de estos eventos. Esto hace que el deporte sea más disfrutable para los usuarios, al dejar de lado una tarea engorrosa y los incentiva a reservar canchas y jugar con más frecuencia.

En resumen, nuestra aplicación móvil ofrece una propuesta de valor diferenciada al permitir a los usuarios no solo hacer lo que nuestros competidores directos hoy ofrecen, sino además crear partidas públicas y dividir el costo de la reserva entre los participantes, lo que la convierte en una opción atractiva para los usuarios que buscan una solución más completa y útil que las aplicaciones de reservas de canchas deportivas existentes en el mercado.

#### Product Backlog
A continuación podemos ver el backlog del producto, el cual se encuentra priorizado, la escala utilizada es:

- **1: Prioridad más alta**: Implementar función o solucionar lo más pronto posible. El producto no puede ser enviado sin una resolución exitosa.
- **2: Prioridad media**: El producto no puede ser enviado sin una resolución exitosa, pero no necesita ser abordado de inmediato.
- **3: Prioridad baja**: La implementación o solución es opcional según los recursos, tiempo y riesgo. Si el producto se envía sin una resolución exitosa, documentar el problema en las notas de la versión como problemas conocidos.
- **4: Prioridad más baja**: Registra un problema que básicamente no afecta el uso (como un pequeño error tipográfico).

Es la recomendada por Azure Devops.

![](https://hackmd.io/_uploads/S1IofyX42.png)


#### Épicas
1. Notificación
2. Reserva de cancha
3. Visualización de cancha
4. Pagos
5. Producto
6. Gestion de usuario

#### Story map
En base a las historias de usuario, epicas, prioridades definidas y la cantidad de sprints que tenemos para trabajar, creamos el siguiente story map:

<img class="img-fluid" src=https://hackmd.io/_uploads/SkjPW3GEh.png />

Como se puede observar, dedicamos la primera iteración a relevar y documentar, luego la segunda y tercera a prototipado y adaptación. La ultima iteración consolidaria el trabajo de documentación y creación del video de demostración.
Pre-definir esto nos permite tener claro los objetivos de los sprints al comienzo de estos, y también saber de antemano cuales son las historias que se deberian completar en el mismo.

#### Historias de usuario
A continuación se presentan algunos ejemplos de las tareas creadas. Por la lista completa de tareas, revisar la sección de product backlog.

![](https://hackmd.io/_uploads/B1Vj1b7En.png)
-
![](https://hackmd.io/_uploads/Hk26y-QV3.png)
-
![](https://hackmd.io/_uploads/SygcxZQN3.png)
-
![](https://hackmd.io/_uploads/HJPBlb7V2.png)


## Análisis del Proceso de la Iteración

### Registro de Horas

| Integrante | Horas | Descripción General |
| -------- | -------- | -------- |
| Agustina Serrón     | 10     |Planning + Descripción de competidores + Documentación + Creación de escenarios + Retro     |
| Brahian Peña     | 11     | Planning + Documentación + Gestion de Herramientas y Tareas  + Retro |
| Daniela Waldeck     | 8,5     | Encuestas + Documentación + Planning + Retro    |
| Federico Mendez     | 8,5     | Planning + Análisis de competidores + Propuesta de valor     |
| Nicolas Bruno     | 8     | Entrevistas + Documentación + Planning + Retro      |
| Vicente Bermudez     | 8     | Planning + Retro + Definición de user stories     |


### Minuta Retrospective Meeting - 05/05

#### Fecha
05/05/2023.
#### Hora
18:00.
#### Duración
Una hora.

#### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

#### Agenda

1. Invitar a participantes.
2. Introducir el objetivo de la meeting.
3. Introducir el tablero a utilizar.
4. Dar tiempo a los participantes para escribir tarjetas con puntos a analizar.
5. Presentar puntos.
6. Agrupar.
7. Tomar action items.

#### Desarrollo

##### Comienzo de la Reunión
Durante los minutos iniciales se cubrieron los puntos 1, 2 y 3 de la agenda.

##### Establecer Puntos a Analizar
Luego, los participantes tuvieron 15 minutos para pensar y escribir los puntos que consideraron que son relevantes.

##### Presentación y Agrupado
Después, los participantes presentan los puntos que escribieron. Luego, entre todos se agrupan los mismos. A continuación se muestra el resultado de esto:

![](https://hackmd.io/_uploads/S1zZogQVh.png)

![](https://hackmd.io/_uploads/BylSoe7V3.png)
![](https://hackmd.io/_uploads/SJB8slXVh.png)
![](https://hackmd.io/_uploads/ryA8ieQEh.png)
![](https://hackmd.io/_uploads/S1zOjeXNn.png)

##### Action Items
Para finalizar, el equipo discutió y acordó crear los siguientes action items:
![](https://hackmd.io/_uploads/S1S83eXE3.png)

##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

### Resultado
Como resultado de la Retrospective Meeting, se identificarón los siguientes action items y su posible motivación:


| Action Item | Motivación | Entra en el backlog? |
| -------- | -------- | -------- |
| Registrar horas por tareas en Google Sheet compartida     |Tener un control más granular sobre las horas trabajadas, para así poder tomar analiticas    |NO (es algo operativo) |
| Acordar metas entre nosotros en planning meeting     | Se detectó que se "fué" dejando trabajó hacia el final del sprint, generando más carga. Por lo que se desea acordar una meta con respecto a esto     | NO (es algo operativo)|
| Mover Dailies a Lunes y Jueves    | Poco tiempo entre dailies    | NO (es algo operativo) |

# Iteración 2


## Objetivo de la Iteración
Prototipar las funcionalidades prioritarias de la aplicación en base a lo relevado en la iteración anterior para validar la solución.

## Desarrollo de la Iteración

### Fecha de Inicio
06/05/2023

### Fecha de Fin
19/05/2023

### Minuta Sprint Planning

#### Fecha
07/05/2023.
#### Hora
10:00.
#### Duración
Dos horas.

#### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

#### Agenda

1. Objetivos de la reunión
2. Revisión del Product Backlog
3. Establecimiento del Objetivo del Sprint
4. Selección de elementos del Product Backlog para el Sprint
5. Estimación de los elementos seleccionados
6. Asignación de tareas a los miembros del equipo
7. Cierre de la reunión

#### Desarrollo

##### Objetivos de la reunión
El Scrum Master junto al Product Owner presentaron los objetivos de la reunión los cuales fueron revisar el Product Backlog, seleccionar los elementos que se incluirían en el Sprint, estimarlos y asignarlos. También se estableció el objetivo del sprint.

##### Revisión del Product Backlog
El Product Owner presentó el Product Backlog. El equipo hizo preguntas y discutió los elementos más importantes.

##### Establecimiento del Objetivo del Sprint
El equipo definió y discutió el objetivo del Sprint, siendo el resultado: Prototipar las funcionalidades prioritarias de la aplicación en base a lo relevado en la iteración anterior.

##### Selección, Estimación y Asignación de Elementos del Product Backlog para el Sprint:
El equipo seleccionó los elementos del Product Backlog que se incluirán en el Sprint (en base a las prioridades definas en el sprint anterior). Los estimó utilizando la escala planteada en el marco de trabajo. Luego se asignaron, asegurándose que cada tarea tenga un responsable. El resultado es el siguiente:

![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/3f72ef1e-b8ef-4feb-a25d-96fd4fb964c2)


##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

### Daily Scrum Meetings

#### Minuta Daily Scrum - 08/05

##### Fecha
08/05/2023.
##### Hora
18:30.
##### Duración
Asíncrona.

#### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

#### Agenda

1. Revisión del estado actual del equipo
2. Cierre de Reunión

##### Desarrollo

###### Revisión del Estado Actual del Equipo
El Scrum Master a la hora indicada solicitó los estados actuales de cada uno de los integrantes del equipo. Los mismos fueron los siguientes:
![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/f57c067e-8236-42bb-83cb-81107126dc38)


###### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

#### Otras Reuniones
Para ver los estados de los integrantes del equipo en el resto de reuniones, dirigerse al directorio *Iteracion 2/Anexos/Dailies*.


## Resultados Claves
### Prototipado
El prototipo fue realizado con la herramienta Framer. Puede verse y probarse el flujo en este [enlace](https://framer.com/projects/JugaYa--nNnNNOIE7PTzeyIXFQ1i-esMev?node=wLLptzZWw&preview=1).
Presentamos a continuación algunas capturas del mismo:

|  |  | |
| -------- | -------- | -------- |
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/d155bbab-7880-4494-b228-fae0e8d229eb) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/8d25862c-1ebf-4587-9290-e63aedb3d5a3) |![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/c6039af8-620f-4074-b98e-85a4f4c2accc) 
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/e0f9d5ec-3c2a-4efc-a14c-dc7a5be1cd58) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/3110dfc6-e8e4-45e4-88cb-9a5dc29eed19) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/cf4059f9-6fdf-47d9-bc42-9fbca7d90b79) 
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/186f7057-9ec4-4dc7-8027-32f05536a1f0)  | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/a3a2eed0-54da-43d3-a17a-afeff4d42c12) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/e8f5643c-a0c5-4f98-912b-98ecece9543f)
 | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/fa53d147-f6af-4004-b738-fb8c231e0d0d) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/31c67d0a-ae94-4436-a7a7-0ad643dab86a) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/1065a1bd-4299-422e-86ea-8641fb65173f)
 | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/9feacdd2-0b33-4209-a6b7-62e804190626) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/fa3b69b6-55fc-493f-8c0b-b8d456386ce9) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/da089c43-9358-4e14-907f-19c810948504)
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/330d78de-aeb8-47e0-9f7e-b5defa33a4c2) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/437651e7-811d-4ae8-87bd-a90c0c5f6bd9) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/a0ef2c60-14cb-4a07-8269-a12466cbd457)
 | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/72584de6-b1fc-4dec-9e2c-f1d10fe5135e) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/293af112-5af8-4713-9f71-b6fdc75e3ef0) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/18d8c3ca-db54-4a9b-b5a7-0f68e68aff54)
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/17f9ae05-33be-4b92-b963-0a4da0d860a1) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/54c8f1dd-aa1a-4fd8-800a-eac9923d2a80) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/364276f9-0b34-48c7-9c67-6aa70544a0e2)
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/a8889f48-8f8b-4749-b0a3-530ea39433f8) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/e902cab5-8519-4cd7-8b7f-9417d7b8da43) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/d0cd38b5-8dfb-4f75-850b-b2107b80e12f)
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/b97ab5ab-54ee-4853-9124-3fc33d9f2733) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/4020bfcc-4bab-4996-bb19-1bb59f6b48fe) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/bacd01b3-058b-491b-b6cd-90594c73bd92)
| ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/2cf5b4c9-058e-458f-a88e-c3a3b66e1ff5) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/c13a1235-41b5-4a99-9f5c-1f76ad589633) | ![image](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/2f77b036-7c08-4e1a-8875-9883776c23fe) | 


## Sprint Review
Pudimos completar en este sprint todas las user stories que nos habíamos propuesto. Todas las user stories se encuentran en la columna Done.

![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/1c557cc6-dde0-4515-866d-09b86d43ae43)

Como aprendizaje, cometimos el error de no crear tasks para nuestras user stories y por lo tanto el board del sprint no refleja el progreso. Esto nos dimos cuenta al final del sprint (hasta ahora estábamos trabajándolo en la sección de boards). Generamos un action item para resolver esto en el siguiente sprint (ver en la sección correspondiente a la retrospective meeting).

![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/4d0cedb8-6b1a-4e0e-9c97-b16616d36a5d)

### Sesiones de Usability Testing
Se le pidió a los usuarios que realicen una reserva de una cancha de fútbol 5 para la fecha 20 de Mayo a las 14:30hs. La misma debía ser para su grupo de amigos e invitar a uno de ellos. Luego de reservada se les solicitó que accedieran a las notificaciones, desplegaran una de ellas y por último regresaran al menú principal y cerraran sesión.

| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 59     | El usuario optó por crear una nueva reserva. No pudo resolver sin ayuda la selección de reserva con amigos, no entendió (mirando la pantalla) cuál era la diferencia entre ambas opciones y le confundía la iconografía utilizada. Le tomó unos segundos darse cuenta cómo regresar a la pantalla de inicio luego de visualizar las notificaciones. | No se entienden los tipos de reserva (público/privado). Quizás debería ser "comunidad"/"amigos", reserva "abierta"/"cerrada" o "privado"/"público" e indicarlo con un candado o "reservá con tu equipo"/"reservá con otros jugadores".    |
| 24     | El usuario optó por crear una nueva reserva. El único paso, que si bien pudo resolverlo sin ayuda, necesito unos segundos para pensar fue a la hora de elegir el departamento y la zona.     | Agregar un ícono indicativo de dropdown (flechita hacia abajo) en la selección de departamento y zona.   |
| 20     | El usuario optó por visualizar las canchas al comienzo, luego de registrarse y acceder a la aplicación correctamente. A la hora de ver ubicaciones no le quedaba claro que su ubicación era el punto de color violeta.  Después de esto volvió para atrás y selecciono: reservar cancha. A la hora de poner la fecha intento escribir en el recuadro y no abrir el panel de selección. Luego de eso continuo a la siguiente pantalla, esperaba que se viera algo para elegir la hora pero se ve primero la selección de la zona. En el listado de canchas le quedo la duda si la plata que aparecía era por hora, tampoco entendió muy bien la parte de las distancias (ej 3km, pensó que eran tamaños). Cuando termino la reserva y el pago no le quedó muy claro que tendría que hacer con el código de reserva.| Cambiar el color del punto de: "usted esta aquí", por otro color que no se mimetice por ejemplo: verde. Sería bueno que después que selecciono: mañana, tarde, noche ya me aparezcan los horarios.  Agregar en el listado de canchas un icono de ubicación en donde está la distancia. Estaría bueno agregar otras características de las canchas como: pasto sintético o no , piso de hormigón, etc. Le parece importante que en un futuro lleguen a aparecer varias canchas.
| 28    | El usuario optó por crear una nueva reserva. En dos partes no logro continuar, primero en la selección de horas, ya que le parecía complicado si el horario no existía y quería pasar a otro momento por ejemplo la mañana (debería volver hacia atrás). La otra parte fue en la selección el tipo de partido, no entendía que era publico y que era privado. A lo ultimo quiso ver sus reservar y no encontró como.      | No queda claro lo de los días y hora, pondría el selector de fecha y las opciones de mañana tarde noche en esa pantalla arriba. En el tipo de partido, se podría poner una ayuda que explique que es cada tipo. En el código de reserva, estaría bueno poner un botón de compartir el código. Agregar botón de ver mis reservas y una pantalla para esto.  |
| 21    | El usuario pudo hacer la reserva exitosamente. Sin embargo, tuvo dificultad para entender que era un partido público y privado. No se entendió la utilidad del código de reserva. | Devuelta, no queda claro qué es un partido público y qué es un partido privado. Debemos cambiar la terminología.  Para el código de reserva, sería útil incluir un boton de "copiar" y también darle un mayor uso. | 


Se le pidió a los usuarios que realicen una reserva en la cancha más cercana, para la fecha 20 de Mayo a las 14:30hs. La misma debía ser para su grupo de amigos e invitar a uno de ellos. Debìa completar la reserva y el pago y volver al inicio.

| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 42     | No tuvo mayores inconvenientes con la aplicación y logró el objetivo pedido sin necesidad de ayuda externa | Le pareció sencillo y fácil de usar. Le gustaría que hubieran filtros en Ver canchas cerca, en caso de que la cancha que se muestra no cumpla con sus expectativas. No le quedó claro el horario de cierre de la cancha (02:30 es AM o PM). Le gustaría que la campana de notificaciones le diga cuántas notificaciones tiene para leer. No le pareció claro que el logo era el botón de Home.
| 22     | Al comienzo le costo encontrar cual era el boton correcto para reservar la cancha mas cercana, si el de reservar cancha o el de ver canchas cerca. Luego de esto pudo completar la reserva sin problemas | Estaria bueno tener una pantalla para poder ver mis reservas y cuales son las canchas mas reservadas por el usuario (algo como favoritos).
| 30     | No tuvo mayores inconvenientes con la aplicación y logró el objetivo pedido sin necesidad de ayuda externa |  La aplicación en sí fue fácil de navegar y pude encontrar rápidamente la opción para reservar una cancha. Me hubiera gustado tener la opción de utilizar diferentes métodos de pago, ya que la aplicación solo permitía tarjetas de crédito. Sería beneficioso incluir opciones adicionales como transferencias bancarias para mayor comodidad y flexibilidad.
| 21     | El usuario tuvo una experiencia sin complicaciones con la aplicación y logró alcanzar su objetivo. Desde el inicio hasta el final, todo el proceso de reserva fue fluido y sin obstáculos significativos. |  Estaria bueno que los usuarios de la aplicación compartan reseñas y calificaciones sobre las canchas reservadas esto brindaría a otros usuarios una referencia adicional al seleccionar una cancha.


Se le pidió a los usuarios que realicen una reserva de las canchas destacadas, para la fecha 20 de Mayo a las 14:30hs. La misma debía ser para su grupo de amigos e invitar a uno de ellos. Debìa completar la reserva y el pago y volver al inicio.
| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 31     | No tuvo problemas en el uso de la aplicacion y pudo reservar cancha sin requerir asistencia externa, a excepción de que no le quedó claro inicialmente para qué eran los casos de el partido público y privado. | Le pareció muy intuitivo y fácil de usar. El flujo para reservar es facil de entender, esto llevo a que en pocos minutos pudiera reservar una cancha.


### Inspección y adaptación del producto
En las sesiones de prueba de usabilidad con usuarios detectamos algunas mejoras que podrían hacerse a nuestro producto entre ellas:
- Mejorar la pantalla de selección de partido público o privado.
- Agregar una flecha que indique que la selección de departamento y zona son dropdowns.
- Dar un uso al código de reserva (ej. compartir).
- Ver reservas (aunque ya era algo que teníamos planificado en el backlog).
- Agregar nuevos métodos de pago como : transferencia bancaria.
- Generar una instancia en donde los usuarios puedan calificar las canchas y agregar reseñas.  

Aparte de los comentarios recibidos, encontramos algunos errores en el prototipo como ser:
- Un loop en el back de seleccionar deporte y seleccionar fecha.
- Algunos íconos de la vista de notificaciones que quedan ocultos en la vista de presentación.

Aprovechamos la instancia de sprint review para discutir posibles soluciones a estos comentarios y errores encontrados. Decidimos incluir nuevas tareas en el próximo sprint para atacar estos puntos. Las mismas serán definidas y refinadas previo a la próxima sprint planning. 

## Análisis del Proceso de la Iteración

### Burndown Chart
![](https://hackmd.io/_uploads/SkpEd3P82.png)
En el gráfico se observa que las tareas fueron agregadas a la iteración luego del comienzo de la misma.
También aparenta que todas fueron completadas el último día y esto refleja exactamente un error que cometimos como equipo durante el desarrollo del sprint por inexperiencia en la herramienta.

Durante el sprint, actualizamos el estado de las tareas pasándolas de To Do a Doing y luego a For Review. Luego en la sprint Review, analizamos las tareas realizadas y las movimos a Done. Es por esto que el gráfico no refleja el avance del equipo durante la iteración.

### Velocidad
La velocidad promedio estimada para el sprint 2 fué de 25 story points (en base al primer sprint, sin contar los puntos asignados a los tickets operativos - ej: Documentación). Como podemos ver, se completaron, 32 puntos, más de lo que fué estimado.

![](https://hackmd.io/_uploads/HkSxqRDIn.png)



### Registro de Horas

Color naranja: Ingeniería (Total 31h)

Esta categoría se refiere al tiempo dedicado a actividades de desarrollo, programación y diseño técnico. En este caso fue el tiempo que se realizaron tareas de prototipado.


Color azul: Gestión (Total 29.9h)

Esta categoría abarca actividades relacionadas con la planificación, coordinación, comunicación y seguimiento del proyecto. Esto incluye reuniones, elaboración de documentación y demos con los clientes. 

En general, el equipo parece haber asignado un equilibrio razonable entre las horas dedicadas a la ingeniería y la gestión. Es esencial que los equipos de Scrum dediquen tiempo tanto a las tareas técnicas como a las actividades de gestión para asegurar un desarrollo efectivo del proyecto. 

Con esta distribución de horas, no vemos grandes diferencias en las actividades y tareas por roles, se ve que todos los integrantes fueron parte del desarrollo y de las actividades de gestión como lo es la documentación. 

#### Referencias
Color naranja: Ingeniería
Color azul: Gestión

![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/f9b706dd-2006-4989-8c63-bea629a14e35)
![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/fb2ea505-bfd4-4ffd-beb0-4a5e0bb02c83)
![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/67212148-e66f-4ad6-9ad9-cf80d4bf5b14)
![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/a33047b7-6a2c-44bd-a902-aceab7db5881)
![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/579eb0ed-9ee2-4c32-bb39-c2c614deda52)
![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/b1f7839c-5e47-4a98-9f1a-1735080a46bf)


## Minuta Retrospective Meeting - 19/05

#### Fecha
19/05/2023.
#### Hora
18:00.
#### Duración
Una hora.

#### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

#### Agenda

1. Invitar a participantes.
2. Introducir el objetivo de la meeting.
4. Dar tiempo a los participantes para escribir tarjetas con puntos a analizar.
5. Presentar puntos.
6. Agrupar.
7. Tomar action items.

#### Desarrollo

##### Comienzo de la Reunión
Durante los minutos iniciales se cubrieron los puntos 1 y 2 de la agenda.

##### Establecer Puntos a Analizar
Luego, los participantes tuvieron 15 minutos para pensar y escribir los puntos que consideraron que son relevantes.

##### Presentación y Agrupado
Después, los participantes presentan los puntos que escribieron. Luego, entre todos se agrupan los mismos. A continuación se muestra el resultado de esto:

![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/bde49ac4-d58e-4ffb-8d33-0998d79d8696)


##### Action Items
Para finalizar, el equipo discutió y acordó crear los siguientes action items:

![](https://github.com/vincentes/Equipo3-B.P-A.S-V.B-F.M-N.B-D.W/assets/11695552/c376eb4f-1dfd-46d2-a471-6a59027f4ca0)

##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

### Resultado
Como resultado de la Retrospective Meeting, se identificarón los siguientes action items y su posible motivación:

| Action Item | Motivación | Entra en el backlog? |
| -------- | -------- | -------- |
| Revision de la letra para Sprint que viene + revision planilla     | Asegurarnos de que la entrega cumpla con los requisitos.     | No     |
| Arreglar burndown charts. Definir como arreglar.     | Tuvimos un problema que no definimos tasks en las user stories y por lo tanto no pudimos completarlas en el sprint. Entendemos que esto puede generar problemas en la visualización de los burndown charts que tenemos que generar en las próximas iteraciones.     | No     |



# Iteración 3

## Objetivo de la Iteración
Continuar el prototipado de funcionalidades y corregir los problemas que se introdujeron junto a los prototipos de la iteración anterior.

## Desarrollo de la Iteración

### Fecha de Inicio
20/05/2023

### Fecha de Fin
02/06/2023

### Minuta Sprint Planning

#### Fecha
22/05/2023.
#### Hora
18:00.
#### Duración
Una hora y media.

#### Participantes
Brahian Peña, Vicente Bermúdez, Daniela Waldeck, Agustina Serrón, Federico Méndez, Nicolas Bruno.

#### Agenda

1. Objetivos de la reunión
2. Revisión del Product Backlog
3. Establecimiento del Objetivo del Sprint
4. Selección de elementos del Product Backlog para el Sprint
5. Estimación de los elementos seleccionados
6. Asignación de tareas a los miembros del equipo
7. Cierre de la reunión

#### Desarrollo

##### Objetivos de la reunión
El Scrum Master junto al Product Owner presentaron los objetivos de la reunión, los cuales fueron: revisar el Product Backlog, seleccionar los elementos que se incluirían en el Sprint, estimarlos y asignarlos. También se estableció el objetivo del sprint.

##### Revisión del Product Backlog
El Product Owner presentó el Product Backlog. El equipo hizo preguntas y discutió los elementos más importantes.

##### Establecimiento del Objetivo del Sprint
El equipo discutió y definió el objetivo del Sprint, siendo el resultado: Continuar el prototipado de funcionalidades y corregir los problemas que se introdujeron junto a los prototipos de la iteración anterior.

##### Selección, Estimación y Asignación de Elementos del Product Backlog para el Sprint:
El equipo seleccionó los elementos del Product Backlog que se incluirán en el Sprint (en base a las prioridades definidas en el sprint anterior). Los estimó utilizando la escala planteada en el marco de trabajo. Luego se asignaron, asegurándose que cada tarea tenga un responsable. El resultado es el siguiente:

![](https://hackmd.io/_uploads/HJ-ua9zUn.png)

##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

### Daily Scrum Meetings

#### Minuta Daily Scrum - 22/05

##### Fecha
22/05/2023.

##### Hora
18:30.

##### Duración
Asíncrona.

##### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

##### Agenda

1. Revisión del estado actual del equipo
2. Cierre de Reunión

#### Desarrollo

##### Revisión del Estado Actual del Equipo
El Scrum Master a la hora indicada solicitó los estados actuales de cada uno de los integrantes del equipo. Los mismos fueron los siguientes:
![](https://hackmd.io/_uploads/rkyiknI83.png)


##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

#### Otras Reuniones
Para ver los estados de los integrantes del equipo en el resto de Daily Scrum Meetings, dirigerse al directorio *Iteracion 3/Anexos/Dailies*.


## Resultados Claves
### Prototipado
El prototipo continua siendo trabajado sobre la herramienta Framer. Puede verse y probarse el flujo en este [enlace](https://framer.com/projects/JugaYa--nNnNNOIE7PTzeyIXFQ1i-esMev?node=wLLptzZWw&preview=1).
Presentamos a continuación algunas capturas de las nuevas pantallas y pantallas modificadas (en comparación a la iteración dos):

|  |  | |
| -------- | -------- | -------- |
|![](https://hackmd.io/_uploads/r18plzLLh.jpg)|![](https://hackmd.io/_uploads/B1vRlMII2.jpg)|![](https://hackmd.io/_uploads/HkugbMILh.jpg)|
|![](https://hackmd.io/_uploads/HyMM-fI82.jpg)|![](https://hackmd.io/_uploads/HyyXWzILn.jpg)|![](https://hackmd.io/_uploads/HJb4-fI82.jpg)|
|![](https://hackmd.io/_uploads/SJAr-M8Uh.jpg)|![](https://hackmd.io/_uploads/rkBZQRvU2.png)|![](https://hackmd.io/_uploads/HkjQm0vLh.png)|
|![](https://hackmd.io/_uploads/HJ50_y_In.png)|![](https://hackmd.io/_uploads/SJ36u1d82.png)|![](https://hackmd.io/_uploads/SykRw1d8h.png)|
|![](https://hackmd.io/_uploads/HyJj_kOL2.png)|![](https://hackmd.io/_uploads/H1FjOydLh.png)|![](https://hackmd.io/_uploads/By7f51_L3.png)|
|![](https://hackmd.io/_uploads/BJOrExdU3.png)|![](https://hackmd.io/_uploads/r18sXedU2.png)|![](https://hackmd.io/_uploads/S1k1EldUh.png)|
|![](https://hackmd.io/_uploads/H1Y2ExuU2.png)|![](https://hackmd.io/_uploads/S1tQBguIn.png)





## Sprint Review

### Sesiones de Usability Testing
Se le pidió a los usuarios que exploren la lista de canchas disponibles y elijan una que deseen guardar como favorita. Después de seleccionarla, se les pide que la añadan a sus favoritos. A continuación, se les solicita que creen un partido compartido e inviten a algunos amigos. Por último, se les pide que revisen sus reservas actuales, así como que actualicen sus datos personales en su perfil.

| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 24     | El usuario ingresó al listado de canchas y marcó una como favorita. Luego optó por crear una nueva reserva. Pudo seguir el flujo correctamente. Se le tuvo que explicar que no puede invitar más amigos porque es solo una demostración. | Tener una "lista de amigos", los cuales se pueden invitar directamente, sin tener que ingresar su correo electrónico.|
| 23     | El usuario pudo realizar la reserva correctamente. Siguió el flujo de pago "Pagar Mi Parte", el cual encontró ideal para los casos en que no se maneja dinero en efectivo.   | Le gustaria que las notificación se oculten una vez las confirma. O que se marquen con algún icono como "ya leidas".  |
| 30     | El usuario logro ingresar una cancha como favorita. El proceso de añadir la cancha a sus favoritos fue fluido y sin problemas. Luego, creó un partido compartido e intentó invitar a algunos amigos. Ademas reviso su perfil  |  Sería deseable poder editar mi foto de perfil y decir que datos pueden ver los otros usuarios
|  20    | El usuario completo correctamente los pedidos sin mayores dificultades |  Sería deseable que en el perfil se puedan agregar preferencias deportivas, como por ejemplo en que deportes estoy interesado. Tener notificaciones de aviso cuando falte un dia para realizarse el partido.

Se solicito a los usuarios que luego de estar logueados, se unan a un partido con desconocidos y paguen su parte correspondiente.


| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 28     | El usuario seleccionó el partido de Fúbol. Pudo unirse a la reserva y pagar su parte con éxito.     | Sería deseable que antes de decidir pagar, la aplicación te informe sobre el costo adicional que tiene (Impuestos).    |
| 24     | Pudo hacer el flujo completo sin ayuda.     | Le gusta poder ver todos los datos y jugadores anotados hasta el momento. En cierto punto intentó volver al Home pero no reconoció el ícono de la app como link directo a esa pantalla.
| 33     | Completó la prueba sin problemas.     | No le quedó claro si el número que se muestra en la pantalla previa es la cantidad de anotados o el límite de jugadores

Se le solicitó a los usuarios que eliminen una de sus reservas.

| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 56     | El usuario reconoció que para visualizar sus reservas debía acceder a Mis Reservas. Una vez en la página intento hacer click sobre la reserva sin obtener respuesta, luego reconoció el ícono de basura y al presionarlo se desplegó una nueva página para confirmar su cancelación. El usuario aceptó y terminó.     | No hay mucha diferencia entre el botón de cancelar la reserva y volver a mis reservas. Quizás el de cancelar debería tener color rojo de fondo y el otro ser solamente texto o botón sin relleno y solo borde.     |
| 42     | El proceso se completó sin dificultades     | Le gustó que tenga doble confirmación antes de borrar la reserva para evitar errores     |
| 31     | Se completó la tarea correctamente, sin ninguna dificultad.     | El usuario identificó rápidamente el icono para poder eliminar la reserva. También consideró positivo que existiera una confirmación, ya que brinda mayor seguridad de que la cancelación sea la correcta y no sea accidental al presionar el botón de cancelar.     |

Se le solicita al usuario que elimine una cancha de su lista de favoritos.
| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 31     | El usuario completo la tarea correctamente.     | Una vez que el usuario inicia sesión, en la pantalla principal deduce que su lista de favoritos se encuentra en su perfil. Una vez dentro, de manera sencilla, visualiza su lista de favoritos y desmarca una cancha como favorita. Intuitivamente ve que la cancha ha sido eliminada exitosamente.     |

Se le solicita al usuario que edite los datos del perfil y verifique que el mail se haya modificado

| Edad | Descripción | Comentarios |
| -------- | -------- | -------- |
| 30     | El usuario completo la tarea correctamente.     | El usuario identifica de manera rápida la ubicación de los datos de su perfil. Una vez dentro de la pantalla correspondiente, realiza los cambios deseados en los datos y luego confirma que su dirección de correo electrónico ha sido ingresada correctamente.     |

### Inspección y adaptación del producto
En las sesiones de prueba de usabilidad con usuarios detectamos algunas mejoras que podrían hacerse a nuestro producto entre ellas:
- Tener una lista de amigos, para luego poder invitarlos a los partidos.
- Notificaciones se deberian ocultar cuando se toca sobre ella.
- Editar foto de perfil.
- Mostrar si un dato del perfil es público o privado.
- Agregar preferencias deportivas como información de usuario.
- Otras notificaciones de aviso.
- Mostrar costo de impuestos antes de pagar.
- Agregar nuevos métodos de pago como: transferencia bancaria.
- Generar una instancia en donde los usuarios puedan calificar las canchas y agregar reseñas.

Aprovechamos la instancia de sprint review para discutir posibles soluciones a estos comentarios. Decidimos que como los mismos son mejoras sobre la aplicación base, estos quedan por fuera del alcance del proyecto.


## Análisis del Proceso de la Iteración

### Burndown Chart
![](https://hackmd.io/_uploads/HyqlQ3vLh.png)

Podemos observar en el gráfico que si bien la iteración comenzó el día Sábado 20 de Mayo, las tareas fueron definidas el Lunes siguiente. Esto explica que la grafica comienza en 0 y luego sube hasta alcanzar 49, cantidad total de story points en esta iteración.

La mayor cantidad de trabajo se realizó en el fin de semana y se alcanzó a completar el total del alcance de la iteración días previos a su finalización. Esto ocurrió porque destinamos algunos días a documentar y realizar demos con usuarios y estos aspectos no estaban incluídos como historias de usuario en el sprint.

Durante este sprint, el equipo fue moviendo las tareas a Done en la medida que eran completadas. Este cambio en la forma de trabajo del equipo respecto a la iteración 2 fue el resultado de la aplicación de un Action Item que surgió en la última retrospective.

### Velocidad
La velocidad promedio estimada para el sprint 3 fue de 28 story points (en base al promedio calculado entre el sprint 1 - 25 story points - y el sprint 2 - 32 story points). Como podemos ver, se completaron, 49 puntos, más de lo que fué estimado.

![](https://hackmd.io/_uploads/HyIJqRDIn.png)

Se tiene que la velocidad promedio estimada para el sprint 4 va a ser de 35 story points.


### Registro de Horas

#### Referencias
Color naranja: Ingeniería (Total 21h)

Esta categoría se refiere al tiempo dedicado a actividades de desarrollo, programación y diseño técnico. En este caso fue el tiempo que se realizaron tareas de prototipado.


Color azul: Gestión (Total 26h)

Esta categoría abarca actividades relacionadas con la planificación, coordinación, comunicación y seguimiento del proyecto. Esto incluye reuniones, elaboración de documentación y demos con los clientes. 

En general, el equipo parece tener un equilibrio razonable entre las horas asignadas a la ingeniería y las dedicadas a la gestión. 

La distribución vista de horas y trabajo es similar a la de la iteración 2.



![](https://hackmd.io/_uploads/SyjKnWIU2.jpg)
![](https://hackmd.io/_uploads/rJ2q3-IUn.jpg)
![](https://hackmd.io/_uploads/rk4ZabU8n.jpg)
![](https://hackmd.io/_uploads/HJi96-I8n.jpg)
![](https://hackmd.io/_uploads/H1KXA-L83.jpg)
![](https://hackmd.io/_uploads/HJ7vyAU83.png)


## Minuta Retrospective Meeting - 02/06

#### Fecha
02/06/2023.
#### Hora
18:00.
#### Duración
Media hora.

#### Participantes
Brahian Peña, Vicente Bermudez, Daniela Waldeck, Agustina Serrón, Federico Mendez, Nicolas Bruno.

#### Agenda

1. Invitar a participantes.
2. Introducir el objetivo de la meeting.
4. Dar tiempo a los participantes para escribir tarjetas con puntos a analizar.
5. Presentar puntos.
6. Agrupar.
7. Tomar action items.

#### Desarrollo

##### Comienzo de la Reunión
Durante los minutos iniciales se cubrieron los puntos 1 y 2 de la agenda.

##### Establecer Puntos a Analizar
Luego, los participantes tuvieron 15 minutos para pensar y escribir los puntos que consideraron que son relevantes.

##### Presentación y Agrupado
Después, los participantes presentan los puntos que escribieron. Luego, entre todos se agrupan los mismos. A continuación se muestra el resultado de esto:
![](https://hackmd.io/_uploads/SygEkedUn.png)

| What is slowing us down? | What is driving us forwards? |
| -------- | -------- |
| ![](https://hackmd.io/_uploads/HJ6Bkgu82.png)| ![](https://hackmd.io/_uploads/r11wkeOU2.png)


##### Action Items
Para finalizar, el equipo discutió y se acordó no crear ningún action item, ya que no se pueden tomar acciones desde nuestro lado para trabajar los puntos que nos podrian estar deteniendo.

##### Cierre de la Reunión
El Scrum Master cerró la reunión y se puso a disposición por cualquier cosa que el equipo pueda precisar.

### Resultado
Como se mencionó arriba, no hay ningún action item para cubrir.

