# F * * * the Manifesto

Por Juan Gabardini, @jgabardini

Etiquetas: artful, lean, agile manifesto

Hace +20 años que se definió Scrum y +15 desde el Agile Manifesto. Es tiempo de dejar atrás algunas soluciones a problemas que ya no existen y repensar lo que queremos lograr, y como, en el contexto actual.

Este texto es una ampliación a presentación que di en Ágiles 2015 [http://www.slideshare.net/jgabardini/f-the-manifesto-54574475](http://www.slideshare.net/jgabardini/f-the-manifesto-54574475)

## De dónde venimos: Agile y su contexto

En los '70 y '80 el software creció en complejidad y tamaño hasta convertirse el principal componente de costo en el desarrollo de sistemas, por sobre el hardware.

Pero las formas de construir software no evolucionaron de manera acorde a la creciente complejidad.

A inicios de los '90, el desarrollo de software se había transformado en el cuello de botella. Esto se refleja en la aparición del CHAOS Report (1994) y los intentos por resolverlo, como CMM (1993), las herramientas CASE (Computer-aided Software Engineering) y RUP (1996).

En esos momentos, la metáfora de construcción de software predominante eran los procesos de manufactura y la línea de montaje. Las formas de resolver la *Crisis del Software *estaban alineados con esa metáfora: control estadístico y mejora de procesos (CMM y luego CMMi), automatización/robotización (CASE, RUP y lo intentos de generación automática de código).

En ese contexto surgieron varias alternativas, que buscaron resolver la *Crisis del Software* desde otro lado: Scrum (1995), Crystal (1992-1997), Extreme Programming (1996) y otras. Estas formas alternativas tuvieron éxito entre los innovadores y los *early adopters*. Nota: ver la curva de adopción de innovaciones en [http://softwareagil.blogspot.com.ar/2015/11/difusion-de-las-innovaciones.html](http://softwareagil.blogspot.com.ar/2015/11/difusion-de-las-innovaciones.html) 

## The Agile  Manifesto

En 2001 se reunieron 17 personas representantes de varias de estas formas alternativas de desarrollar software. Unieron a todas ellas bajo el paraguas Agile Software Development como una estrategia para de llegar al *mainstream *(Mayoría temprana en la curva de adopción de innovaciones).

La estrategia, además del nombre común, consistió en publicar un Manifesto que consiste en 4 valores y 12 principios.

Podemos decir que la estrategia fue exitosa. El Desarrollo Ágil de Software es hoy referencia obligada, aunque no todos los desarrollos la utilicen.

Pero junto con el éxito, la estrategia tuvo sus costos.

Para pasar de los *Innovadores* y *Early Adopters* a la *Mayoría temprana* se debe cambiar el foco de la innovación. Se busca mejorar la usabilidad. Debe ser fácil de implementar, de mantener. Buscamos tener lenguajes comunes, simplificar. Porque el limitante es llegar a personas y organizaciones menos propensas a soportar los inconvenientes (*glitches)* de las nuevas tecnologías. Ver sobre esto el libro *Crossing the Chasm* y los trabajos de Diego Fontdevila sobre Usabilidad en la adopción de prácticas.

Durante la etapa de de *Mayoría temprana *la escalabilidad de la innovación es el principal limitante. ¿Cuán rápido podemos brindar el producto/servicio? En este caso, ¿cuán rápido pueden adoptar agilidad las personas, los equipos, las organizaciones? En esta instancia buscamos tener soluciones estandarizadas, FAQ. Ver sobre esto el libro *Inside the Tornado*.

El costo de esta simplificación y estandarización es que, como comunidad de práctica, nos hemos vuelto dogmáticos y menos innovadores.

Veo esto más notorio con los Valores del Manifesto. Algunas personas de la comunidad contestan refiriendo a los valores como si estos fueran inamovibles y absolutos. "Si hacemos un proceso automático para… Hey, valoramos Individuos e interacciones sobre procesos y herramientas".

Una forma de sacarnos el dogmatismo es aceptar que todas nuestras creencias pueden ser criticadas con el objeto de entenderlas y quizás encontrar limitaciones o alternativas. Analizaré a continuación los valores, con esa mirada crítica. Ver el [http://alistair.cockburn.us/oath+of+non-allegiance](http://alistair.cockburn.us/oath+of+non-allegiance).

Nota: siempre podemos releer cambiando la definición de las palabras, para acomodarlo a que signifique lo que queremos que signifique: "cuando decimos software funcionando queremos decir valor de negocio", "cuando decimos contrato queremos decir acuerdo", … Cada uno es libre de autoengañarse. 

### Lenguaje usado en los valores

En este análisis usaré los niveles de Tribal Leaderhip. Si no los conoces, la forma más rápida de entender lo que que sigue es ver el video [https://www.ted.com/talks/david_logan_on_tribal_leadership](https://www.ted.com/talks/david_logan_on_tribal_leadership)

En las comunicaciones masivas, como es el caso del Agile Manifesto, es común y deseable que se hable el lenguaje de varios niveles de Tribal Leadership, para llegar a la mayor cantidad de personas.

Tanto el nombre elegido (... Manifesto) como en parte del texto sobre la historia del Agile Manifesto ([http://agilemanifesto.org/history.html](http://agilemanifesto.org/history.html)) puede notarse lenguaje **Nivel 5**, queremos cambiar el mundo.

El foco en valores (es lo primero que se lee) podría entenderse como lenguaje **Nivel 4**, ya que surgió de la charla interna y es lo común de este grupo, que se siente superior a otros, las *Dilbertesque corporations*. Pero para los que leen el Manifesto, los valores no necesariamente son los de su equipo o grupo, son los valores de otro grupo. Trabajar bajo valores impuestos desde fuera nos lleva a lenguaje **Nivel 3** (los que imponen sus valores) y **Nivel 2** (los que reciben los valores impuestos).

Como comentó Brian Marick en el keynote de Ágiles 2009, para algunos la llegada de la agilidad a sus organizaciones solo significó que su trabajo sea menos horribles (*My work suck less*), cuando los firmantes esperaban transformar el ámbito de trabajo para hacerlo disfrutable. Veo esto en comentarios de la comunidad contra el opresor de turno (PMI, CMMi, los jefes, las corporaciones, las picadoras de carne, <completar con tu monstruo opresor>) que nos obligan a hacer las cosas mal y nos hacen sufrir en el trabajo. Esto es lenguaje **Nivel 2**.

La forma en que están escritos los valores (Valoramos …. Sobre ….), muy presente también en la historia del Agile Manifesto, facilita la mentalidad de nosotros somos mejores que ellos (lenguaje **Nivel 3**). 

Además, esa forma se volvió obsoleta en cuanto la agilidad se volvió *mainstream*. Cada vez más personas, equipos y organizaciones llegan a la agilidad sin haber pasado ni por PMI, ni por CMMi ni por RUP.

### Individuos e interacciones sobre procesos y herramientas

Aquí usaré el concepto de Arful e Industrial making, podés ver una desripción breve [http://softwareagil.blogspot.com.ar/2009/07/artful-making.html](http://softwareagil.blogspot.com.ar/2009/07/artful-making.html)

Las personas que participaron en la escritura del Manifesto se pensaban en el equipo de desarrollo de software, siendo obligados a trabajar con maneras apropiadas a una situación de Industrial making, cuando ellos se veían más cercanos a una situación apropiada a Artful making. Aceptaban la necesidad de procesos y herramientas, dado que siempre hay al menos un poco de ambos.

Pero los que tomaron el Manifesto (no los firmantes originales) llevaron esto a extremos dogmáticos. Balancemos:

* Brian Marick (Ágiles 2009 y otros lugares [arxta.net/](http://arxta.net/)): Habló del Retro-futurism (entre otras cosas), para rescatar las herramientas como parte imprescindible de la agilidad.

* Continuous Delivery (libro 2010, [continuousdelivery.com](https://continuousdelivery.com/)): El proceso y la mejora de procesos son importantes. Todo el tiempo que tome desde que confirmamos el cambio en el código (*commit stage*) hasta que el usuario utilice el producto es desperdicio (*waste*) y debe ser eliminado por medio de mejora continua. Corresponde a la parte de la derecha de la Figura 1.

* Lean Startup (libro 2011, [theleanstartup.com](http://theleanstartup.com/)): Aún la parte más creativa (la izquierda de la Figura 1) puede ser mejorada con procesos y métricas.

* Tuckman (1963): Los equipos, antes de ser de alto rendimiento (*Performing*), pasan por la etapa de acuerdos en sus procesos (*Norming*).

Un punto central, a veces perdido de vista, en este balance entre individuos y procesos, es la diferencia entre:

* Un proceso propuesto (o impuesto) desde fuera, como un objetivo a cumplir definido por "los que saben", que no son del equipo.

* Un proceso definido por el equipo tomado la forma en que hacemos el trabajo actualmente, como base para los experimentos de mejora del mismo equipo para avanzar hacia un objetivo desafiante, con tiempos definidos por el equipo (si querés profundizar, buscá Toyota Kata).

### Software funcionando sobre documentación extensiva

Este valor parece especialmente apuntado a contrastar con CMMi / PMI / RUP. Esta comparación es anacrónica y ha perdido relevancia. Tanto CMMi, PMI y RUP se han ocupado en acercarse a Agile todo lo posible.

Pero analicemos cada parte con más profundidad:

* Software funcionando: ¿Es nuestro principal objetivo? ¿Cuál es el valor de lo que hacemos? Nos podemos preguntar si el software está siendo usado, el nivel de satisfacción del cliente con la experiencia completa, cual es el impacto de negocio logrado. 
Ejemplo: En el primer equipo en el que participé desarrollando ágilmente pasamos por un cambio enorme, de estar desarrollando un año sin un producto entregado, a desarrollar en 6 semanas y luego cada 15 días, un incremento de producto. Pero el resultado neto para la empresa fue el mismo, no se vendió ni una licencia del producto.

* Documentación extensiva: ¿Es un problema la documentación extensiva? Prefiero cambiar la pregunta ¿Cuál es el valor de la documentación y cuáles son los problemas relacionados con la documentación? La documentación puede ser usada para comunicación dentro del equipo, comunicación con el equipo futuro (para operar, mantener y evolucionar) o para terceros (clientes, entes reguladores). Los problemas de la documentación: el costo de generar, usar, mantener y que luego se desactualice fácilmente. Para cada uno de los usos habituales de la documentación, busquemos formas de resolverlos, tal que permitan minimizar los problemas. 
En relación al costo de mantenimiento, buscamos lograr que el costo del cambio en el software implique un cambio acotado en la documentación, no dependiente del tamaño total. Es una condición necesaria para el desarrollo iterativo e incremental (costo de reconfiguración en Artful making). Ejemplos de esto es tener documentación ejecutable (potencialmente escrita antes que el software), corriendo en ambientes de Integración continua. Esto permite que la documentación desactualizada se detecte rápidamente. Tiene otros beneficios, para profundizar, ver el libro Specification by Example de Gojko Adzic.
Otro ejemplo, queremos que el costo de operación del software sea bajo y se mantenga así a lo largo del ciclo de vida, el uso y la evolución, del sistema. Entonces en vez de documentar el proceso de instalación, conviene automatizar la creación de ambientes (provisioning) y la instalación y configuración del software. 

### Colaboración con el cliente sobre negociación contractual

Este valor asume que tenemos un cliente con quien colaborar o resolver nuestras diferencias consultando el contrato. Nuevamente, está pensado desde el punto de vista de un equipo de desarrollo de software, mientras que el cliente es alguien externo (o que se comporta como un externo) que paga por el trabajo del equipo.

Hay varias cosas que no me gustan de este valor:

* Resaltar sólo la colaboración con el cliente. Esperaría que la colaboración se dé internamente en el equipo y con cualquier otra persona o grupo con los que interactúa el equipo.

* No siempre tenemos a un cliente conocido. El proceso completo de creación de software incluye la ideación y descubrimiento del producto que cubrirá las necesidades de un segmento (Lean Startup, Design Thinking). Cuando aún estamos descubriendo quiénes serán nuestros clientes ¿que significaría colaborar con ellos?

* No siempre tenemos un contrato con el cliente/usuario. En proyectos open source tenemos donaciones, en startups y en la organización de un evento, tenemos un equipo que tiene acuerdo internos, pero el que paga llega cuando mucho del trabajo ya está hecho. En estos contextos, este valor se vuelve irrelevante.

### Respuesta ante el cambio sobre seguir un plan

¿Dónde está nuestro proyecto,  en el espacio Caótico, Complejo, Complicado o Obvio? (estoy usando la terminología de Cynefin). En este valor se asume que estamos en el espacio de lo complejo. Refleja el Inspeccionar y Adaptar. Esto puede ser correcto en muchos casos, pero no siempre. Por ejemplo, en la forma de proceso que indicamos en la Figura 1, esperaría que el proceso de despliegue sea predecible y según el plan. Que la forma de desplegar sea Obvia. El problema de los bordes caóticos entre Obvio y Caótico me llevan a pensar en antifragilidad y herramientas como *Chaos Monkey*. No en Inspeccionar y Adaptar.

Por otro lado, ¿qué es un plan? 

Ejemplo Scrum: Si digo que planifico mi iteración (sprint) es Planificación, Dailies, Revisión y Retrospectiva, ¿qué pasa cuando, por algún problema, no tenemos un incremento de funcionalidad? ¿Respondemos ante el cambio postergando o suspendiendo la Revisión? ¿Alargamos el sprint?

Ejemplo de Open Space Technology, una forma de organizar eventos, tiene fijó la apertura y le mercado de ideas, una definición de tiempo de cada sesión y el horario de una sesión de cierre. Pero no tiene definido los oradores/ facilitadores de cada sesión. Si cumplimos con el horario de cierre, a pesar que alguna de las últimas sesiones no finalizó, ¿No estamos respondiendo al cambio?

Este valor está llamando la atención sobre una forma rígida de definir los planes al inicio y seguirlos sin cambios. 

Pero eso es una mala aplicación de la idea del plan. También podríamos decir que "Preferimos preparar nuestro plan para que incorporar los cambios no sean catastróficos".

### Lo que no está en los valores

Además de lo ya comentado, algunas practicantes encontraron que en los valores no se hace referencia a la calidad de lo construido. Se disparó entonces el movimiento de Artesanos del software (*Craftmanship*).

La visión del artesano orgulloso de su trabajo suele expresarse con lenguaje **Nivel 3**. Llevado a equipo y lenguaje **Nivel 4**, esto sería la mejora continua y los equipos de alto rendimiento. 

En ambos casos, hay principios relacionados a la calidad técnica y la mejora continua en el Manifesto, pero no en los valores.

## ¿Y si lo mejoramos?

El Agile Manifesto fue sumamente exitoso y equipo que gana no se toca. Por ello, pasaron muchos años antes que se sintiera la necesidad de replantear los acuerdos, como comunidad. Y es difícil de lograr un nuevo acuerdo, que sume una masa crítica de voluntades, quizás por eso tardaron tanto en surgir nuevas propuestas. Comento a continuación, sólo como disparadores de la discusión, algunas de las ideas que conozco al respecto. Hay puntos en común, algunos evidentes (como Experimentation y Experimenta y aprende rápido) y otros más sutiles, como el foco en la forma de aprendizaje presente en la propuesta de Kokoro y la propuesta de ir a Modern Agile sin pasar por las formas históricas.

### Navigating Complexity

Propuesto por Tobias Mayer y Alan Cyment, alrededor de la metáfora entre los sistemas Orgánicos y Mecánicos, plantea los siguientes valores: 

* *Dreaming*

* *Fractality*

* *Oscillantion*

* *Experimentation*

Puenden ver una presentación aquí: [https://www.slideshare.net/PhiliyLander/navigating-complexity-london-2016](https://www.slideshare.net/PhiliyLander/navigating-complexity-london-2016)

### Heart of Agile y Kororo

Propuesto por Alistair Cockburn, plantea que cada person que pasó por los estados de Shu -  Ha - Ri, al llegar a Ri tiene contacto con la esencia, el cetro, de la disciplina (kokoro). Cuanto trata de explicarla, transmitirla, a los que inician el camino (Shu) necesariamente la simplifica. Cada maestro de la disciplina puede llegar a una simplificación distinta. 

En Heart of Agile, el kokoro de Agile según Alistair, él busca que el principiante pueda tener una guía clara de qué hacer y por ello propone acciones: 

* *Collaborate *

* *Deliver *

* *Reflect*

* *Improve*

Heart of Agile: [http://alistair.cockburn.us/HeartOfAgile](http://alistair.cockburn.us/HeartOfAgile)

Sobre la idea del maesto que enseña: [http://alistair.cockburn.us/Shu,+Play,+Kokoro+are+3+doorways+into+a+skill](http://alistair.cockburn.us/Shu,+Play,+Kokoro+are+3+doorways+into+a+skill)

### Modern Agile

Propuesto por Joshua Kerievsky, resultado de talleres comunitarios. A partir del brainstorming original se fueron agrupando hasta llegar a cuatro principios. Entiendo de las presentaciones de Joshua que las organizaciones siguieron "descubriendo formas mejores de desarrollar software", y que no hay justificativos para pasar por las técnicas que eran útiles hace 20 años, podemos ir directamente a las actuales. Plantea los siguientes principios

* Haz que las personas sean geniales

* Entrega valor continuamente

* Haz de la seguridad un prerrequisito

* Experimenta y aprende rápido

Creo que es el que más material tiene en este momento, descripción, presentaciones, videos, traducciones: http://modernagile.org/ 

## Conclusión

Estamos entrando en una zona de turbulencias, como comunidad, donde la referencia de quienes somos o qué hacemos no es tan clara. Sin embargo, creo que cada una de las propuestas tiene valor y podemos, cada uno, empezar probando con cualquiera de ellas, ver si nos sentimos cómodos/ si es útil. Sobre esa experiencia, quizás decante en un nuevo consenso. ¡Y si no al menos no desperdiciamos tiempo discutiendo cual es "la correcta"!

