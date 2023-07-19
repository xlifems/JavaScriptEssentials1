# Sección 2
# Configuración del entorno de programación

Temas en esta sección:
  1. [Herramientas de desarrollo](#herramientas-de-desarrollo)
  1. [Entorno de desarrollo en línea](#entorno-de-desarrollo-en-línea)
  1. [Entorno de desarrollo local (editor de código, intérprete, depurador)](#entorno-de-desarrollo-local)

## Herramientas de desarrollo
Como cualquier otra tarea, la programación requiere las herramientas y el espacio de trabajo adecuados. El desarrollo de software, en la mayoría de los casos, requiere un editor de código y un compilador o intérprete de un lenguaje determinado. Este es el conjunto mínimo, que podemos ampliar según sea necesario con otras herramientas.

En esta etapa del curso, además del editor e intérprete de código JavaScript, también podemos utilizar el depurador, que es una herramienta que nos permite, entre otras cosas, pausar el programa en el lugar indicado y analizar su estado actual (por ejemplo, los valores de las variables indicadas).

Por supuesto, las herramientas en cuestión deberán ejecutarse en la computadora. En esta etapa, su rendimiento no es particularmente importante, y cualquier equipo que pueda manejar las tareas normales de oficina será suficiente, por lo que es muy recomendable trabajar desde una computadora de escritorio o portátil.

No se puede negar que el tamaño del monitor afectará la comodidad de tu trabajo. Cuanto más grande sea el monitor, más fácil será colocar el editor de código, el intérprete y otro contenido (por ejemplo, este curso) uno al lado del otro. En circunstancias normales de trabajo, los programadores suelen utilizar varios monitores.

No importa el sistema operativo, ya que se puede encontrar la herramienta adecuada para Windows, macOS y Linux.

En este momento, existen dos opciones. Puedes instalar todas las herramientas necesarias en tu máquina y trabajar en el entorno local. Este es el enfoque preferido, ya que así es como se ve en proyectos comerciales reales la mayor parte del tiempo. También puedes personalizar todo para satisfacer tus necesidades.

Todo el código que verás en este curso se probó en entornos locales y en línea, por lo que ambas opciones son válidas. Finalmente, podemos pasar a la elección de las herramientas.

## Entorno de desarrollo en línea
Los entornos en línea, son sitios que actúan como un editor sencillo y un entorno de ejecución. Todos ellos tienen conjuntos similares de características. Tienen diferentes interfaces de usuario, pero en principio se comportan de manera similar. Te permiten escribir código, ejecutarlo con fines de prueba y, en la mayoría de los casos, compartirlo con otros usuarios.

En el caso de JavaScript, donde la preparación de un entorno local que funcione se reduce a instalar un editor de código y ejecutar el navegador, no son tan importantes como los entornos de desarrollo regulares. Se utilizan principalmente como plataformas de prueba y capacitación, o lugares para publicar soluciones de muestra a problemas de programación.

Entre los programadores de JavaScript, los más populares son los siguientes:

1. JSFiddle
2. CodePen
3. JsBin
4. Plunker

Durante el curso, utilizaremos un entorno en línea integrado con la plataforma de capacitación. OpenEDG proporciona un entorno simple para escribir y ejecutar código en varios lenguajes de programación, incluido JavaScript. Gracias a eso, podrás practicar todo lo que hablamos de inmediato.

Sin embargo, no olvides que esta plataforma es una solución puramente didáctica y de prueba, y ciertamente no puede usarse como un entorno de desarrollo completo. Sin embargo, es ideal para nuestras necesidades, ya que en la mayoría de los casos podremos olvidarnos del entorno web de los programas escritos en JavaScript, incluidos los elementos HTML. Esto nos permitirá centrarnos únicamente en aprender el lenguaje JavaScript en sí.

Sin embargo, se recomienda encarecidamente que también configures tu propio entorno de desarrollo local. No es difícil, como descubrirás de inmediato, y te permitirá realizar algunos ejercicios de una forma mucho más parecida a cómo lo harías durante el desarrollo normal de software. Si, durante el curso, alguno de los ejercicios debe realizarse en un entorno de este tipo, lo indicaremos claramente.

## Entorno de desarrollo local
Como escribimos anteriormente, los requisitos de JavaScript para el entorno de desarrollo son muy modestos. En la mayoría de los casos, especialmente al comienzo del desarrollo, solo tres elementos son suficientes: un editor de código, un intérprete (es decir, un entorno de arranque) y un depurador.

Dependiendo del nivel de sofisticación, la complejidad del proyecto escrito o el entorno para el que escribimos nuestros programas (del lado del cliente, o del lado del servidor), es posible que también se necesiten otras herramientas.

Existirán, entre otras:

**Administradores de paquetes:** que permiten la gestión de librerías (que contienen soluciones listas para usar, que podemos emplear en nuestros programas) o componentes del entorno de desarrollo (por ejemplo: npm o yarn).

**Ejecutores de tareas y empaquetadores de módulos:** utilizados, en términos simples, para automatizar el proceso de desarrollo de software y unir el código resultante de muchos archivos y librerías (por ejemplo Grunt o Webpack).

**Frameworks de pruebas:** permiten realizar pruebas automáticas para la corrección de nuestro programa, al buscar posibles errores (por ejemplo Mocha, Jasmine, o Jest).

**Analizadores de seguridad:** como puede adivinar, se usan para controlar la seguridad de nuestra solución (por ejemplo, Snyk, RetireJS u OWASP Dependency Check).


La apertura de los entornos de desarrollo web es tanto una bendición como una maldición. Podemos elegir entre cientos de componentes, a partir de los cuales podemos crear el entorno más cómodo para nosotros.

Sin embargo, su cantidad, más los cambios dinámicos de herramientas particulares o incluso las tendencias entre los programadores hacen que sea difícil mantenerse al día con todo lo que sucede dentro de estos entornos.

Pero para nosotros, este es un problema para el futuro lejano.

Por ahora, necesitamos el trío mínimo: **un editor de código, intérprete y depurador**

## Editor de Código
El código de casi todos los lenguajes de programación se compone de alguna forma de texto. Entonces, para escribir el código, necesitamos un editor de texto. Pero debe ser una aplicación que escriba texto sin formato (no puede ser un editor de texto enriquecido, como MS Word). En otras palabras, solo un bloc de notas simple que pueda escribir archivos .txt es suficiente para escribir código, aunque es mucho más fácil si se usa un editor de código dedicado. El mercado está repleto de editores de código profesionales, tanto gratuitos como de paga. Algunos de ellos son universales, mientras que otros son exclusivos de lenguajes específicos. La principal ventaja de usar un editor de código dedicado es el resaltado de sintaxis, el autocompletado de texto y la verificación de errores. Esto mejora la eficiencia del trabajo y la comprensión del código, y reduce la cantidad de errores y errores tipográficos. Hay muchos buenos editores de código, pero puede ser realmente difícil seleccionar uno que funcione bien para ti.

Aquí se mencionan algunos populares:

**Visual Studio Code**
[Windows, macOS, Linux]

logo visual studio

Potente editor de código gratuito para uso personal y comercial. Se ha convertido rápidamente en uno de los favoritos cuando se trata de desarrollo web. Tiene funciones integradas como un depurador de JavaScript y herramientas para optimizar los proyectos web. También es altamente personalizable a través del sistema de extensiones (existen muchas adiciones especialmente para el lenguaje JavaScript).

**WebStorm**
[Windows, macOS, Linux]

logo webstorm

Un entorno de desarrollo comercial popular, en el que el editor de código es solo uno de los elementos más pequeños en un gran conjunto de herramientas que mejoran el desarrollo de código (por ejemplo, soporta realizar pruebas al código). Destinado para proyectos grandes, puede resultar demasiado pesado y complejo para programas pequeños. Aunque está destinado a un uso comercial, es posible obtener una licencia educativa gratuita.

**Sublime Text**
[Windows, macOS, Linux]

logo Sublime Text

Editor de código rápido y fácil de usar con muchas funciones avanzadas, como edición de varias líneas, búsqueda rápida y otras. Hay una versión de prueba disponible, pero para uso a largo plazo, se debe comprar una licencia ya sea para un uso privado y/o comercial.

**Notepad++**
[Windows]

logo Notepad++

Editor de código y texto gratuito y ligero. El programa es pequeño y rápido, admite docenas de lenguajes de programación y se puede ampliar con complementos (plugins). Puede ser viejo y feo, pero sigue siendo muy útil.

Existen muchos otros editores de código, tanto gratuitos como de paga, y puedes usar el que prefieras. Muchos desarrolladores usan, entre otras cosas, editores de consola, incluido el legendario vim. Los editores de consola no se ejecutan en un entorno gráfico, sino en una consola de texto. Sin embargo, solo puedes buscar tales soluciones si las tareas que vas a hacer resultan ser demasiado simples y quieres hacer tu vida un poco más difícil.

## Intérprete
Ya hemos hablado un poco sobre el intérprete y su función. Funciona como un entorno de ejecución para nuestro programa. Comprueba si hemos cometido algún error formal, por ejemplo, cometer un error tipográfico en el nombre de una función u olvidar cerrar un paréntesis, y luego ejecuta el programa instrucción por instrucción.

La elección del intérprete de JavaScript dependerá de la plataforma para la que escribamos nuestro software. Por ejemplo, si queremos escribir una aplicación sencilla del lado del servidor, es casi seguro que elegiremos el entorno node.js, que tendremos que instalar directamente en nuestro sistema operativo. En el caso del software del lado del cliente, nuestro intérprete será simplemente el navegador web que ya tienes instalado (porque, ¿de qué otra forma estarías leyendo este curso?).

Nuestro curso trata sobre los fundamentos de JavaScript, es decir, aquellos elementos del lenguaje que serán igualmente útiles en soluciones móviles, del lado del cliente y del lado del servidor. Así podemos practicarlos en cualquier entorno, utilizando cualquier intérprete. La forma más fácil de hacer esto es limitarse a un navegador web.

Como hemos dicho anteriormente, prácticamente todos los navegadores tienen motores (o intérpretes) JavaScript integrados, pero recomendamos encarecidamente usar Chrome de Google, o FireFox de Mozilla . Ambos son conocidos por su eficiencia y herramientas avanzadas integradas para desarrolladores web (ese eres tú). Están disponibles para Windows, macOS y Linux.

## Depurador
Los programas de computadora son bestias complicadas, miles o incluso millones de líneas de código (pero tranquilo, comenzaremos con solo unas pocas). Con tal complejidad y tamaño, es imposible producir código sin errores. Algunos tipos de errores, especialmente los lógicos (formalmente, el programa está escrito correctamente, pero probablemente inventamos la solución incorrecta al problema), solo se pueden encontrar mientras el programa se está ejecutando y, a menudo, solo en circunstancias especiales. Es realmente difícil averiguar qué sucede exactamente dentro de un programa que se ejecuta a la velocidad del rayo, y para esos problemas existen los depuradores.

Un depurador es una herramienta que te permite alentar o incluso detener la ejecución de un programa, ejecutar instrucciones paso a paso, ver y analizar el estado del programa en un momento dado.

Afortunadamente, en el momento en que decidimos usar el navegador web como nuestro entorno de arranque e intérprete de JavaScript, también obtuvimos un depurador. Todos los navegadores modernos están equipados con las herramientas de desarrollo. Durante el funcionamiento normal, son invisibles y tenemos que habilitarlos en las opciones del navegador (más sobre esto en el próximo capítulo).

Dependiendo del navegador, allí encontraremos varias herramientas, pero seguramente habrá:

El inspector, que nos permitirá, por ejemplo, analizar los elementos HTML individuales de un sitio web abierto.

La consola de JavaScript, que en primer lugar muestra toda la información sobre los errores y, en segundo lugar, nos permite ejecutar comandos de JavaScript únicos en el contexto de la página actual.

El depurador, que entre otras cosas, muestra los valores actuales de las variables y te permite pausar la ejecución del código en el lugar indicado y ejecutarlo paso a paso (es decir, ejecutar instrucciones del programa).


¿Cómo habilitas las herramientas para desarrolladores? Desafortunadamente, no hay una respuesta única; depende del navegador que estés utilizando (a veces también de su versión) y del sistema operativo. Las interfaces del navegador cambian con bastante frecuencia, por lo que es mejor aprender los atajos correctos en lugar de buscar la opción correcta en el menú. Prueba las siguientes combinaciones de teclas:

Sistemas operativos Windows y Linux, todos los navegadores comunes excepto Internet Explorer y Edge:
ctrl + shift + I

Sistema operativo Windows, Internet Explorer y Edge:
F12

Sistema operativo macOS, todos los navegadores comunes:
Command + Option + I
En el próximo capítulo, volveremos a este tema y aprenderemos algunas cosas más sobre estas útiles herramientas.

En el próximo capítulo escribiremos nuestra primera pieza de código JavaScript. Lo probaremos en primer lugar en el entorno de ejecución integrado con nuestra plataforma de formación. También lo utilizaremos para comprobar cómo funciona nuestro entorno de desarrollo local. Por lo tanto, hay que asegúrarse de que las herramientas seleccionadas estén instaladas y de que puedas iniciarlas. Si aún no sabes qué elegir, te sugerimos usar el entorno local con Visual Studio Code y el Chrome (navegador web con intérprete de JavaScript y depurador).
