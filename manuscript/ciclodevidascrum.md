# Ciclo de vida de SCRUM

SCRUM es un marco de trabajo que nos ayuda a administrar un proyecto de desarrollo, brinda una base que ayuda a las empresas a administrar sus proyectos, no implica implementar cabios drasticos al modo de trabajo de la empresa, si no quepuede aplicar cambios poco a poco.

La siguiente imagen se puede observar una representacion grafica del ciclo de vida de SCRUM.

![Ciclo de vida de SCRUM](images/ciclodevidascrum.jpg)

Los principales elementos de la metodología SCRUM son lo siguientes:

1. El Equipo Scrum 
 * El propietario del producto (Product Owner)
  * El Equipo de Desarrollo (Developers) 
 * El Scrum Master
2. Eventos de SCRUM 
 * La iteración (Sprint). El Sprint es el periodo de tiempo en el cual los desarrolladores trabajan sobre las historias de usuario y las tareas. Las cuales se comprometieron a terminar para la “Revisión del Sprint”. Estás HU son las representadas en el “Product Backlog”
 * Planificación de la iteración (Sprint Planning). Se realiza una junta en la cual se seleccionan las historias de usuario que se va a comprometer el equipo de desarrollo a entregar en el Sprint planificado. Dependiendo de la productividad del equipo se puede especificar un número de historias a realizar por Sprint.
 * Reunión diaria de SCRUM (Daily Scrum). Scrum sugiere que se realice una reunión diaria no mayor a quince minutos y de pie (para que no se prolongue), en la cual participan todos los desarrolladores involucrados en el proyecto, y por turnos cada uno contesta tres preguntas:

* ¿En qué historia de usuario estoy trabajando? 
* ¿Qué voy a hacer hoy en esa o en otra historia de usuario?
* ¿Qué me lo podría impedir?

Uno de los fines de realizar esta reuniones diarias, es asegurar el avance en las historias de usuario, e identificar si algún desarrollador enfrenta un problema o una situación que no puede resolver, expresando esto frente a sus compañeros, alguno podría dar una sugerencia para resolverlo o incluso colaborar en la resolución del problema, impidiendo así que hubiera atrasos.

 * Revisión de la iteración (Sprint Review). Es una junta en la que participan todos los involucrados en el proyecto:  El propietario del producto (Product Owner), el equipo de desarrollo (Developers) y el Scrum Master, en esta junta se le muestra al propietario del producto los avances que se tuvieron en la selección de las historias de usuario, también las HU que no se alcanzaron a terminar y se explica el motivo. Esta junta también sirve para realizar el nuevo compromiso del siguiente Sprint.
Dependiendo de la empresa la fecha del Sprint puede ser semanal, cada dos semanas o cada 3 semanas, no se recomienda que sean de más de 4 semanas, ya que podría representar retraso en el desarrollo de las HU.

* Retrospectiva del Sprint (Sprint). Después de la junta del Sprint, se realiza una pequeña junta en la cual se discuten los nuevos requerimientos, los cambios (en caso de que existan) o lo que hay que eliminar o modificar en el avance entregado al cliente.

3. Artefactos de Scrum 
 * Product Backlog. Aquí se encuentran todas las historias de usuario con las que cuenta el proyecto.
 * Sprint Backlog. Se encuentran las HU que fueron seleccionadas para realizar en el periodo de 2 semanas (según el modo de trabajar de la empresa) y que serán mostradas al cliente.
 * Incremento 

4. Transparencia de Artefacto 
 * Definición de "Hecho” (Done)

Explicación del Ciclo:

A continuación se mencionan más a fondo las acciones que se llevan a cabo dentro del ciclo de vida de SCRUM, según la experiencia que se ha tenido en el estudio de este marco de trabajo:

1.- Redacción de historias de usuario. 
2.- Estimación de historias de usuario.
3.- Priorización por valor y riesgo
4.- Product backlog
5.- Junta de planeación del Sprint
6.- Sprint
7.- Junta de revisión del Sprint
8.- Retrospectiva del Sprint

![Ciclo de vida de SCRUM](ciclodevidascrumpuntos.jpg)

En este [enlace][1] podras encontrar la guia oficial de SCRUM.

[1]: http://www.scrumguides.org/

## Historias de usuario

Una historia de usuario es la representacion de un requerimiento, lo que en los metodos tradicionales seria la realizacion de casos de uso de manera detallada.

Una HU representa una requeriemiento con valor importante para el desarrollo del sistema, se define como una breve descripcion de una necesidad del usuario y las pruebas que determinan la finalizacion de la historia descrita de una manera entendible para cualquier usuario del sistema. Las HU son redactadas sobre papel pequeño (fichas bibliograficas por ejemolo) esto facilita la administracion de los requerimientos sin la necesidad de realizar gran cantidad de documentos, de la misma forma, facilita la realizacion del cambio al sistema.

__Caracteristicas de las HU__

Según Bill Wake las caracteristicas de una buena historia de usuario deben de cubrir el acronimo en ingles __INVEST__

* __I__ndependientes: Las HU deben ser independientes unas de otras, si existen dos historias dependientes una de otra, se recimienda unirlas pero considerar dividirlas de tal manera que pudieran generarse mas HU pero independientes.

* __N__egociables: Se debe discutir con el cliente el alcance de cada HU, y debera quedar especificado en la validacion de cada una.

* __V__aloradas por los clientes (valiosas): El cliente debera determinar el valor que cada una de ellas representa. El valor que el cliente puede determinar para una HU no es el mismo que le podria dar un desarrollador, por lo cual, debera existir una charla para llegar a un acuerdo y terminar el sistema a tiempo. Pero sin olvidar que lo mas importante es la opinion del cliente.

* __E__stimables: Cada HU debera es estimada segun la complejidad y la experiencia de los desarrolladores, al finalizar, la suma de la estimacion de cada una determinara el total de tiempo de desarrollo del sistema.

* Pequeña__S__: Debera evitarse tener historias largas ya que eso dificulta determinar la estimacion.

* Verificables / comprobables (__T__est): Ya que las HU son requerimientos funcionales, son verificables. 

## Como redactar una HU

A continuaciÓn se describira y mostrara como redactar una HU

Yo como <tipo de usuario>, quiero o necesito <función> para <descripción del porque>

__Ejemplo:__

__Yo como__ "socio tecnologico" __quiero__ "conectarme a la plataforma" __para__ "dar de alta los cursos a través de una API".

__Ejercico:__ En la siguiente [liga][2] se encuentra la convocatoria para el desarrollo de una aplicación web que vincule a los funcionarios públicos con las plataformas de capacitación de empresas del sector de TIC, de la pagina llamada "Retos publicos". La cual ayudara para la realizacion de:

[2]: https://docs.google.com/document/d/1p6snXndUkm9QY8v33035KwgORgxFeG7o88xhv7gPNJw/edit#


* Redaccion de historias de usuario.
* Valoracion de importancia por parte del cliente de la historias de usuario.
* Estimacion de las historias de husuario.
