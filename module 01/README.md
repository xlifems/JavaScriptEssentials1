#  Introducción a JavaScript y la Programación Informática

## Acerca de JavaScript

Temas en la sección:

  1. [¿Cómo comunicarse con la computadora?](#type)
  1. [¿Qué es JS?](#references)
  1. [JS – Ventajas y Limitaciones](#objects)
  1. [¿Dónde se usa JS hoy?](#arrays) 

## Introducción
¿Quieres aprender a programar en JavaScript? ¡Genial!

Este curso será un viaje bastante largo, pero si llegas hasta el final, podrás leer, comprender y, por supuesto, escribir aplicaciones y programas en JavaScript. Estas nuevas habilidades pueden ayudarte en tu trabajo actual o permitirte alcanzar nuevas oportunidades profesionales en un mercado de TI en constante crecimiento. Comencemos esta aventura sin más preámbulos y descubramos qué es JavaScript.

## ¿Cómo comunicarse con la computadora?
Comencemos con algo obvio: las computadoras están en todas partes. Es casi seguro que estás leyendo este curso en una computadora; tu teléfono es una computadora. Encontrarás computadoras en televisores y otros electrodomésticos. Estamos rodeados de computadoras. Las computadoras se utilizan en la ciencia, la medicina, los bancos y los negocios. Sospechamos que hoy en día sería difícil encontrar algún ámbito de la vida en el que las computadoras no participen activamente.

Usamos computadoras principalmente porque son capaces de realizar ciertas tareas incomparablemente más rápido y con mayor precisión que las personas. Sin embargo, las computadoras no pueden adivinar qué tipo de tareas tenemos en mente o cómo ayudarnos a realizarlas. Tenemos que decirles eso. ¿Cómo? Es mejor hacerlo de forma similar a cuando se pasa información a otras personas, es decir, utilizando un lenguaje que sea comprensible para ambas partes. Usando dicho lenguaje, escribimos un programa, una solución formal a nuestro problema, que puede ser ejecutada por la computadora.

Desafortunadamente, un lenguaje que es directamente entendible por una computadora sería absolutamente ilegible para un ser humano normal. Sería una secuencia de instrucciones extrañas, escritas en forma numérica, refiriéndose a componentes informáticos que ni siquiera sabíamos que existían (y hablando francamente, no necesariamente tenemos que saberlo). Esta forma de comunicación, que data de los comienzos de la informática, hoy en día se usa muy raramente y solo en situaciones muy específicas.

Entonces, para ayudar en la comunicación con las computadoras, se inventaron los lenguajes de programación que son algo similares a los lenguajes naturales (es decir, los que se usan para la comunicación entre personas). Hay miles de lenguajes de programación, y difieren en propósito (aparte de los lenguajes de propósito general, hay muchos especializados, por ejemplo, lenguajes diseñados solo para cálculos estadísticos), nivel de abstracción (en términos simples: cuanto mayor sea el nivel del lenguaje , menos necesitamos saber sobre el hardware en el que se ejecuta el programa), facilidad de uso, efectividad de los programas escritos en ellos, etc.

## JavaScript como lenguaje interpretado
JavaScript es un típico lenguaje interpretado. Si ejecutamos un código escrito en JavaScript en un navegador web, como está sucediendo en la página que estamos leyendo actualmente (sí, sí, hay elementos escritos en JavaScript en esta página también), el intérprete será el Motor JavaScript integrado en el navegador. Esta no es la única forma de ejecutar código JavaScript.

Tal vez hayas oído hablar de node.js. También es un intérprete, pero se instala de manera independiente a los navegadores, en un entorno en el sistema operativo de la computadora (puede ser macOS, Windows o Linux). El uso de node.js te permite escribir programas en JavaScript que, por ejemplo, convertirán tu computadora en un servidor.

Al comienzo de este párrafo, simplificamos un poco las cosas. JavaScript es un lenguaje interpretado, de eso no hay duda. Y, de hecho, ejecutar un programa escrito en JavaScript parece como si estuviéramos ejecutando nuestro código fuente (es decir, el código que escribimos) paso a paso. Sin embargo, puedes llegar a encontrar información sobre este lenguaje, y sobre intérpretes, que son un poco diferentes.

La mayoría de los motores de JavaScript modernos utilizan la técnica Compilación Just In Time - Justo a Tiempo (Compilación JIT). Esta técnica consiste en compilar fragmentos de código durante la ejecución del programa (más de una sola instrucción) y permite aumentar su rendimiento. Sin embargo, desde el punto de vista del usuario, dicho cambio es prácticamente imperceptible: sigue pareciendo que solo el intérprete está ejecutando el código fuente, instrucción por instrucción.

Independientemente del lenguaje que elijas, algunas cosas permanecen igual mientras escribes el programa. En primer lugar, una etapa importante, y probablemente la más difícil, de este proceso es definir correctamente el problema que queremos resolver. Solo entonces tratamos de encontrar la solución óptima, que finalmente presentaremos en forma de un programa escrito en el lenguaje elegido.

Entonces, antes de comenzar a explicarle algo a la computadora, en otras palabras, escribir un programa, debes comprender exactamente qué deseas lograr y cómo deseas lograrlo. En segundo lugar, la solución que proponemos y escribimos en forma de programa debe ser 100% precisa: la computadora no puede adivinar nada.

Un ejemplo simple de un campo ligeramente diferente: en algún momento de tu vida, probablemente compraste un mueble que requería ensamblaje. Montarlo es un problema con el que el comprador, ha tenido que cargar. Para que pueda hacer frente a esta tarea, obtiene un conjunto de instrucciones que lo guiarán a través de todo el proceso. Está actuando como intérprete en este punto, utilizando un programa que le permitirá completar la tarea. El éxito de tu misión depende de la calidad de estas instrucciones, de que sean precisas, y de que no provengan de otro mueble. Al final, puede resultar que no hayas construido los muebles de tus sueños, sino una construcción surrealista de otra dimensión.

Para que las instrucciones sean buenas, quien las desarrolle debe saber exactamente qué deben ilustrar, en qué orden deben realizar ciertas acciones, en qué etapas es más fácil confundirse, etc. Por supuesto, deben saber qué efecto se va a lograr al final.

## Algunas palabras más sobre JavaScript
Como mencionamos antes, JavaScript es un lenguaje de programación interpretado. Como la mayoría de los lenguajes interpretados, también es un lenguaje de alto nivel (es decir, relativamente fácil de entender para las personas y que nos separa de los detalles del hardware).

A principios de los 90, todas las páginas web eran estáticas. Las cosas cambiaron en 1995 cuando la corporación Netscape contrató a Brendan Eich y le encargó que desarrollara un nuevo lenguaje para su producto, el navegador web Netscape Navigator. El nuevo lenguaje se llamó LiveScript, pero poco después se cambió su nombre a JavaScript. Su tarea principal era agregar dinámicas a los sitios web, lo que permitiría, por ejemplo, una interacción más compleja con el usuario. Y así comenzó la carrera de JavaScript.

Programación del lado del cliente y del lado del servidor
El uso de JavaScript en los sitios web, que con el tiempo se ha vuelto cada vez más complejo y, a menudo, contiene una lógica muy sofisticada, se denomina programación del lado del cliente. El código a ejecutar se carga junto con la página en el navegador, del lado del usuario, y el intérprete que forma parte del navegador web permite su ejecución.

Hoy en día, JavaScript es el único lenguaje compatible con todos los principales navegadores web, y aproximadamente el 95 % de las páginas web de todo el mundo incorporan código JavaScript en ellas. Desde el principio, las páginas web utilizaron JavaScript en el lado del cliente para agregar interactividad y cambiar dinámicamente el contenido.

Ahora es mucho más que eso, ya que JavaScript ofrece muchos frameworks sobre los cuales podemos construir aplicaciones web y redes sociales enormes y complejas (probablemente hayas escuchado los nombres de frameworks como React o Angular).

Todo esto puede funcionar en una variedad de equipos, desde estaciones de trabajo de alto rendimiento hasta simples teléfonos inteligentes. Gracias al poder de JavaScript, podemos pedir comida, jugar en el navegador, ver películas en plataformas de transmisión y estar en contacto constante con las personas importantes para nosotros. JavaScript es tan popular que continuamente se dedica más y más esfuerzo a usarlo, no solo como una solución del lado del cliente.

Con el tiempo, JavaScript comenzó a aparecer en otras áreas, como en la programación de lado del servidor de aplicaciones web complejas, también llamadas back-end. Estos programas se ejecutan en servidores, procesando datos (por ejemplo, de bases de datos), que después del procesamiento estarán disponibles en el lado del cliente. La flexibilidad de este lenguaje y su relativa sencillez lo han hecho mucho más aplicable, por ejemplo, en aplicaciones móviles, o incluso en la programación de UAVs - Vehículo Volador No Tripulado (algunos drones ejecutan programas escritos en este lenguaje).

## ¿Es este el lenguaje de programación perfecto? - Desventajas
Decimos que JavaScript es un lenguaje maduro, lo que significa que la mayoría de las funciones ya están implementadas y son estables, y probablemente no veremos grandes cambios en el lenguaje. Desde 2015, muchos aspectos de JavaScript han cambiado y se han agregado muchas características nuevas. Muchos de estos cambios se introdujeron para facilitar la migración a JavaScript para los programadores que conocen otros lenguajes populares, de los cuales JavaScript originalmente difería bastante en ciertos aspectos, como el manejo de objetos. Todavía podemos usar el lenguaje de la manera antigua, pero se recomienda usar el JavaScript moderno.

No existen soluciones ideales, por lo que no existen buenos lenguajes de programación para todas las aplicaciones. Cada uno de ellos tiene sus propias limitaciones, y JavaScript no es diferente. A pesar de su popularidad y éxito, JavaScript no es un lenguaje de programación perfecto. Debido a su naturaleza, no es adecuado para ciertas aplicaciones. Por ejemplo, no tiene sentido usarlo para escribir programas que requieran cálculos matemáticos avanzados o un rendimiento muy alto.

Algunas limitaciones se deben al propio concepto del lenguaje, pero la gran mayoría están relacionadas con la plataforma en la que lo usamos. Esto es especialmente visible cuando se escribe código para ser ejecutado en un navegador, que como dijimos anteriormente se denomina del lado del cliente. En tal situación, la funcionalidad de JavaScript está limitada por el hecho de que los navegadores, por razones de seguridad, ejecutan código de secuencia de comandos en un entorno sandbox (un entorno separado del mundo exterior), que no permite acceso a archivos y recursos locales (es decir, aquellos archivos que están en la computadora donde se inicia el navegador).

Otro inconveniente es que como el código no está compilado, entra en el navegador de la misma forma, o muy similar, a la que lo escribimos nosotros. ¿Por qué es esto una desventaja? Esto se debe a que todos pueden ver nuestra solución en una forma fácil de leer y usarla (ya sea en fragmentos o incluso en su totalidad) sin nuestro permiso.

Algo de ayuda aquí puede ser la ofuscación del código, que consiste en transformar nuestro script listo en una forma un poco menos legible (por ejemplo, generando nombres aleatorios cortos de variables y funciones, eliminando los signos de final de línea, etc.), pero el simple hecho es que si alguien quiere robar nuestro código JavaScript, es muy poco lo que podemos hacer para detenerlo.

## ¿Es este el lenguaje de programación perfecto? - Ventajas
Por otro lado, JavaScript tiene muchas ventajas sobre otros lenguajes de programación, y una de las más grandes es una comunidad muy activa y solidaria. Es fácil encontrar soluciones a problemas comunes y encontrar ayuda en general. Esto también significa que se desarrollan activamente herramientas que funcionan con JavaScript.

Otra gran ventaja es una gran cantidad de frameworks y librerías listas para usarse que brindan la mayoría de las funcionalidades y características comúnmente requeridas. El lenguaje en sí es relativamente fácil de aprender y nos permite centrarnos en el trabajo en lugar de luchar con la sintaxis (es decir, la forma de construir las instrucciones que componen el código de nuestro programa).

Además, JavaScript no requiere que compres herramientas costosas para trabajar con él, y las herramientas realmente buenas ya están integradas dentro de tu navegador web. Por último, pero no menos importante, los grandes jugadores como Google, Facebook y Mozilla apoyan activamente las herramientas de JavaScript y su desarrollo.

Sin embargo, lo que es una ventaja para unos puede resultar una desventaja para otros. Un ejemplo de esto es el manejo dinámico de los tipos de datos en JavaScript. Consiste en que podemos almacenar datos de cualquier tipo en una variable (una variable es un contenedor en el que almacenamos los datos que utilizaremos).

Por ejemplo, durante la ejecución del programa, podemos almacenar el número 10 en una variable, y en el siguiente paso usar la misma variable para almacenar la cadena "abc" (borrando el valor anterior automáticamente. No te preocupes si no entiendes en este momento, porque cubriremos todos estos términos más adelante).

Por lo general, esto es muy conveniente, pero varias personas han encontrado que esta característica del lenguaje es una desventaja. En su opinión, facilita que un programador cometa errores en ciertas situaciones. Al agregar manejo estático de los tipos de datos, donde una variable solo puede contener un tipo de dato (por ejemplo, números) durante la ejecución del programa, se creo un nuevo lenguaje llamado <b>TypeScript</b>.

Recuerda también que si aprendes a programar en un lenguaje, normalmente te será mucho más fácil aprender el siguiente, que por alguna razón puede ser mejor para resolver un problema en particular.

Pero comencemos ahora con JavaScript, que, debido a su sintaxis flexible y simple, es perfecto para aprender como primer lenguaje.

# Preparémonos para trabajar
Como mencionamos anteriormente, JavaScript se puede usar en varios entornos, aunque la mayoría de las veces será un navegador web o un servidor con un entorno node.js. Cada entorno impone una manera un poco diferente de usar este lenguaje, y aparecen algunos mecanismos o funciones propias del mismo. Sin embargo, la parte esencial del lenguaje, su núcleo, sigue siendo el mismo. En esta parte del curso, aprenderemos a programar utilizando esta parte central e invariable de JavaScript: cómo declarar variables, escribir funciones, instrucciones condicionales o bucles; todo esto será igualmente utilizable en cualquier entorno en el que decidamos utilizar este lenguaje.

Programar en cualquier lenguaje no es algo fácil de aprender, y es posible que te sientas abrumado por tanta información nueva. Si eres persistente y te concentras, estarás escribiendo scripts simples en poco tiempo, y no hay otra forma de aprender a programar que escribir muchísimo código.

Lo más importante es que no te rindas incluso cuando estés atascado: tómate un descanso, sal a caminar, vuelve a hacerlo con una mente fresca e inténtalo de nuevo. Al final, el ser constante te hace ganar la carrera.

¡Ahora, vamos a empezar!
