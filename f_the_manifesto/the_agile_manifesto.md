## The Agile  Manifesto {#the-agile-manifesto}

En 2001 se reunieron 17 personas representantes de varias de estas formas alternativas de desarrollar software. Unieron a todas ellas bajo el paraguas Agile Software Development como una estrategia para de llegar al _mainstream_ (Mayoría temprana en la curva de adopción de innovaciones).

La estrategia, además del nombre común, consistió en publicar un Manifesto que consiste en 4 valores y 12 principios.

Podemos decir que la estrategia fue exitosa. El Desarrollo Ágil de Software es hoy referencia obligada, aunque no todos los desarrollos la utilicen.

Pero junto con el éxito, la estrategia tuvo sus costos.

Para pasar de los _Innovadores_ y _Early Adopters_ a la _Mayoría temprana_ se debe cambiar el foco de la innovación. Se busca mejorar la usabilidad. Debe ser fácil de implementar, de mantener. Buscamos tener lenguajes comunes, simplificar. Porque el limitante es llegar a personas y organizaciones menos propensas a soportar los inconvenientes (_glitches)_ de las nuevas tecnologías. Ver sobre esto el libro _Crossing the Chasm_ y los trabajos de Diego Fontdevila sobre Usabilidad en la adopción de prácticas.

Durante la etapa de de _Mayoría temprana_ la escalabilidad de la innovación es el principal limitante. ¿Cuán rápido podemos brindar el producto/servicio? En este caso, ¿cuán rápido pueden adoptar agilidad las personas, los equipos, las organizaciones? En esta instancia buscamos tener soluciones estandarizadas, FAQ. Ver sobre esto el libro _Inside the Tornado_.

El costo de esta simplificación y estandarización es que, como comunidad de práctica, nos hemos vuelto dogmáticos y menos innovadores.

Veo esto más notorio con los Valores del Manifesto. Algunas personas de la comunidad contestan refiriendo a los valores como si estos fueran inamovibles y absolutos. &quot;Si hacemos un proceso automático para… Hey, valoramos Individuos e interacciones sobre procesos y herramientas&quot;.

Una forma de sacarnos el dogmatismo es aceptar que todas nuestras creencias pueden ser criticadas con el objeto de entenderlas y quizás encontrar limitaciones o alternativas. Analizaré a continuación los valores, con esa mirada crítica. Ver el [http://alistair.cockburn.us/oath+of+non-allegiance](http://alistair.cockburn.us/oath+of+non-allegiance).

Nota: siempre podemos releer cambiando la definición de las palabras, para acomodarlo a que signifique lo que queremos que signifique: &quot;cuando decimos software funcionando queremos decir valor de negocio&quot;, &quot;cuando decimos contrato queremos decir acuerdo&quot;, … Cada uno es libre de autoengañarse.

### Lenguaje usado en los valores {#lenguaje-usado-en-los-valores}

En este análisis usaré los niveles de Tribal Leaderhip. Si no los conoces, la forma más rápida de entender lo que que sigue es ver el video [https://www.ted.com/talks/david_logan_on_tribal_leadership](https://www.ted.com/talks/david_logan_on_tribal_leadership)

En las comunicaciones masivas, como es el caso del Agile Manifesto, es común y deseable que se hable el lenguaje de varios niveles de Tribal Leadership, para llegar a la mayor cantidad de personas.

Tanto el nombre elegido (... Manifesto) como en parte del texto sobre la historia del Agile Manifesto ([http://agilemanifesto.org/history.html](http://agilemanifesto.org/history.html)) puede notarse lenguaje **Nivel 5**, queremos cambiar el mundo.

El foco en valores (es lo primero que se lee) podría entenderse como lenguaje **Nivel 4**, ya que surgió de la charla interna y es lo común de este grupo, que se siente superior a otros, las _Dilbertesque corporations_. Pero para los que leen el Manifesto, los valores no necesariamente son los de su equipo o grupo, son los valores de otro grupo. Trabajar bajo valores impuestos desde fuera nos lleva a lenguaje **Nivel 3** (los que imponen sus valores) y **Nivel 2** (los que reciben los valores impuestos).

Como comentó Brian Marick en el keynote de Ágiles 2009, para algunos la llegada de la agilidad a sus organizaciones solo significó que su trabajo sea menos horribles (_My work suck less_), cuando los firmantes esperaban transformar el ámbito de trabajo para hacerlo disfrutable. Veo esto en comentarios de la comunidad contra el opresor de turno (PMI, CMMi, los jefes, las corporaciones, las picadoras de carne, &lt;completar con tu monstruo opresor&gt;) que nos obligan a hacer las cosas mal y nos hacen sufrir en el trabajo. Esto es lenguaje **Nivel 2**.

La forma en que están escritos los valores (Valoramos …. Sobre ….), muy presente también en la historia del Agile Manifesto, facilita la mentalidad de nosotros somos mejores que ellos (lenguaje **Nivel 3**).

Además, esa forma se volvió obsoleta en cuanto la agilidad se volvió _mainstream_. Cada vez más personas, equipos y organizaciones llegan a la agilidad sin haber pasado ni por PMI, ni por CMMi ni por RUP.

### Individuos e interacciones sobre procesos y herramientas {#individuos-e-interacciones-sobre-procesos-y-herramientas}

Aquí usaré el concepto de Arful e Industrial making, podés ver una desripción breve [http://softwareagil.blogspot.com.ar/2009/07/artful-making.html](http://softwareagil.blogspot.com.ar/2009/07/artful-making.html)

Las personas que participaron en la escritura del Manifesto se pensaban en el equipo de desarrollo de software, siendo obligados a trabajar con maneras apropiadas a una situación de Industrial making, cuando ellos se veían más cercanos a una situación apropiada a Artful making. Aceptaban la necesidad de procesos y herramientas, dado que siempre hay al menos un poco de ambos.

Pero los que tomaron el Manifesto (no los firmantes originales) llevaron esto a extremos dogmáticos. Balancemos:

*   Brian Marick (Ágiles 2009 y otros lugares [arxta.net/](http://arxta.net/)): Habló del Retro-futurism (entre otras cosas), para rescatar las herramientas como parte imprescindible de la agilidad.
*   Continuous Delivery (libro 2010, [continuousdelivery.com](https://continuousdelivery.com/)): El proceso y la mejora de procesos son importantes. Todo el tiempo que tome desde que confirmamos el cambio en el código (_commit stage_) hasta que el usuario utilice el producto es desperdicio (_waste_) y debe ser eliminado por medio de mejora continua. Corresponde a la parte de la derecha de la Figura 1.
*   Lean Startup (libro 2011, [theleanstartup.com](http://theleanstartup.com/)): Aún la parte más creativa (la izquierda de la Figura 1) puede ser mejorada con procesos y métricas.
*   Tuckman (1963): Los equipos, antes de ser de alto rendimiento (_Performing_), pasan por la etapa de acuerdos en sus procesos (_Norming_).

Un punto central, a veces perdido de vista, en este balance entre individuos y procesos, es la diferencia entre:

*   Un proceso propuesto (o impuesto) desde fuera, como un objetivo a cumplir definido por &quot;los que saben&quot;, que no son del equipo.
*   Un proceso definido por el equipo tomado la forma en que hacemos el trabajo actualmente, como base para los experimentos de mejora del mismo equipo para avanzar hacia un objetivo desafiante, con tiempos definidos por el equipo (si querés profundizar, buscá Toyota Kata).

### Software funcionando sobre documentación extensiva {#software-funcionando-sobre-documentaci-n-extensiva}

Este valor parece especialmente apuntado a contrastar con CMMi / PMI / RUP. Esta comparación es anacrónica y ha perdido relevancia. Tanto CMMi, PMI y RUP se han ocupado en acercarse a Agile todo lo posible.

Pero analicemos cada parte con más profundidad:

*   Software funcionando: ¿Es nuestro principal objetivo? ¿Cuál es el valor de lo que hacemos? Nos podemos preguntar si el software está siendo usado, el nivel de satisfacción del cliente con la experiencia completa, cual es el impacto de negocio logrado. Ejemplo: En el primer equipo en el que participé desarrollando ágilmente pasamos por un cambio enorme, de estar desarrollando un año sin un producto entregado, a desarrollar en 6 semanas y luego cada 15 días, un incremento de producto. Pero el resultado neto para la empresa fue el mismo, no se vendió ni una licencia del producto.
*   Documentación extensiva: ¿Es un problema la documentación extensiva? Prefiero cambiar la pregunta ¿Cuál es el valor de la documentación y cuáles son los problemas relacionados con la documentación? La documentación puede ser usada para comunicación dentro del equipo, comunicación con el equipo futuro (para operar, mantener y evolucionar) o para terceros (clientes, entes reguladores). Los problemas de la documentación: el costo de generar, usar, mantener y que luego se desactualice fácilmente. Para cada uno de los usos habituales de la documentación, busquemos formas de resolverlos, tal que permitan minimizar los problemas. En relación al costo de mantenimiento, buscamos lograr que el costo del cambio en el software implique un cambio acotado en la documentación, no dependiente del tamaño total. Es una condición necesaria para el desarrollo iterativo e incremental (costo de reconfiguración en Artful making). Ejemplos de esto es tener documentación ejecutable (potencialmente escrita antes que el software), corriendo en ambientes de Integración continua. Esto permite que la documentación desactualizada se detecte rápidamente. Tiene otros beneficios, para profundizar, ver el libro Specification by Example de Gojko Adzic.Otro ejemplo, queremos que el costo de operación del software sea bajo y se mantenga así a lo largo del ciclo de vida, el uso y la evolución, del sistema. Entonces en vez de documentar el proceso de instalación, conviene automatizar la creación de ambientes (provisioning) y la instalación y configuración del software.

### Colaboración con el cliente sobre negociación contractual {#colaboraci-n-con-el-cliente-sobre-negociaci-n-contractual}

Este valor asume que tenemos un cliente con quien colaborar o resolver nuestras diferencias consultando el contrato. Nuevamente, está pensado desde el punto de vista de un equipo de desarrollo de software, mientras que el cliente es alguien externo (o que se comporta como un externo) que paga por el trabajo del equipo.

Hay varias cosas que no me gustan de este valor:

*   Resaltar sólo la colaboración con el cliente. Esperaría que la colaboración se dé internamente en el equipo y con cualquier otra persona o grupo con los que interactúa el equipo.
*   No siempre tenemos a un cliente conocido. El proceso completo de creación de software incluye la ideación y descubrimiento del producto que cubrirá las necesidades de un segmento (Lean Startup, Design Thinking). Cuando aún estamos descubriendo quiénes serán nuestros clientes ¿que significaría colaborar con ellos?
*   No siempre tenemos un contrato con el cliente/usuario. En proyectos open source tenemos donaciones, en startups y en la organización de un evento, tenemos un equipo que tiene acuerdo internos, pero el que paga llega cuando mucho del trabajo ya está hecho. En estos contextos, este valor se vuelve irrelevante.

### Respuesta ante el cambio sobre seguir un plan {#respuesta-ante-el-cambio-sobre-seguir-un-plan}

¿Dónde está nuestro proyecto, en el espacio Caótico, Complejo, Complicado o Obvio? (estoy usando la terminología de Cynefin). En este valor se asume que estamos en el espacio de lo complejo. Refleja el Inspeccionar y Adaptar. Esto puede ser correcto en muchos casos, pero no siempre. Por ejemplo, en la forma de proceso que indicamos en la Figura 1, esperaría que el proceso de despliegue sea predecible y según el plan. Que la forma de desplegar sea Obvia. El problema de los bordes caóticos entre Obvio y Caótico me llevan a pensar en antifragilidad y herramientas como _Chaos Monkey_. No en Inspeccionar y Adaptar.

Por otro lado, ¿qué es un plan?

Ejemplo Scrum: Si digo que planifico mi iteración (sprint) es Planificación, Dailies, Revisión y Retrospectiva, ¿qué pasa cuando, por algún problema, no tenemos un incremento de funcionalidad? ¿Respondemos ante el cambio postergando o suspendiendo la Revisión? ¿Alargamos el sprint?

Ejemplo de Open Space Technology, una forma de organizar eventos, tiene fijó la apertura y le mercado de ideas, una definición de tiempo de cada sesión y el horario de una sesión de cierre. Pero no tiene definido los oradores/ facilitadores de cada sesión. Si cumplimos con el horario de cierre, a pesar que alguna de las últimas sesiones no finalizó, ¿No estamos respondiendo al cambio?

Este valor está llamando la atención sobre una forma rígida de definir los planes al inicio y seguirlos sin cambios.

Pero eso es una mala aplicación de la idea del plan. También podríamos decir que &quot;Preferimos preparar nuestro plan para que incorporar los cambios no sean catastróficos&quot;.

### Lo que no está en los valores {#lo-que-no-est-en-los-valores}

Además de lo ya comentado, algunas practicantes encontraron que en los valores no se hace referencia a la calidad de lo construido. Se disparó entonces el movimiento de Artesanos del software (_Craftmanship_).

La visión del artesano orgulloso de su trabajo suele expresarse con lenguaje **Nivel 3**. Llevado a equipo y lenguaje **Nivel 4**, esto sería la mejora continua y los equipos de alto rendimiento.

En ambos casos, hay principios relacionados a la calidad técnica y la mejora continua en el Manifesto, pero no en los valores.