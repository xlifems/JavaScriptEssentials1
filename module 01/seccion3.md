# Sección 3
# ¡Hola, Mundo!

Temas en esta sección:

 1. [Algunas palabras sobre HTML](#)
 1. [¿Cómo puedes ejecutar tu código JavaScript?]](#)
 1. [Ejecutando el código directamente en la consola](#)


# El Programa "¡Hola, Mundo!"
¿Por qué "¡Hola, Mundo!"? Durante casi 50 años, esta frase y sus derivados han marcado a alguien aprendiendo un nuevo lenguaje de programación, aunque es más una tradición que otra cosa. La frase se usó hace mucho tiempo en un libro muy importante sobre el lenguaje C, pero el texto en sí no es relevante ahora.

La idea es escribir algo en la pantalla utilizando un lenguaje específico. Primero, nos permite ver la sintaxis básica del lenguaje y compararlo con otros lenguajes de programación. En segundo lugar, es un programa muy simple y cualquiera puede escribirlo o copiarlo fácilmente de Internet y verificar si sus herramientas y su entorno están configurados correctamente. En tercer lugar, es un programa que genera algo, por lo que proporciona información sobre si se ejecutó correctamente o no.

En el caso de JavaScript del lado del cliente, mostrar algo en la pantalla se puede entender de dos maneras.

Primero, el JavaScript del lado del cliente siempre se ejecuta en el contexto de un sitio web y te permite manipular elementos de ese sitio web. Entonces podemos, por ejemplo, usar la función apropiada para insertar algún texto, cambiar un título, crear una tabla, etc. en la página. De esta manera, controlamos la parte visual del sitio web.

Segundo, podemos usar la consola como una pantalla para escribir alguna información. La consola, como mencionamos en el capítulo anterior, es parte de las herramientas del desarrollador. Por lo tanto, no está visible de forma predeterminada y debe estar habilitada correctamente (también escribimos sobre esto en el capítulo anterior). Para nuestras necesidades, será mucho más cómodo utilizar la consola, ya que evitaremos la necesidad de un análisis exhaustivo de la estructura del sitio web.

Pero, ¿qué es realmente una consola? En primer lugar, es un lugar donde se muestran varios mensajes, normalmente invisibles para el usuario del navegador. Estos mensajes pueden, por ejemplo, ser generados por el intérprete de JavaScript tras encontrar un error o si lo imprimimos, llamando a la función adecuada. En segundo lugar, podemos ejecutar comandos de JavaScript individuales en la consola, que se ejecutarán en el contexto de la página web actualmente cargada (se hablará un poco más sobre eso en un momento).



La función básica que nos permite escribir información en la consola es llamada console.log. Entonces, para referirnos al eterno "¡Hola, Mundo!", deberíamos mandarlo llamar de la siguiente manera:

```console.log("¡Hola, Mundo!");```

Podemos tratar a console.log como una función*. De hecho, la función es solo un registro y la consola es el objeto al que pertenece la función.

*Este tipo de función, perteneciente a un objeto, generalmente se denomina método. Pero una vez más, por el momento, para simplificar ciertas cosas, supongamos que se trata de una función ordinaria: no nos molestará en absoluto (aprenderemos sobre los objetos mucho más adelante).

Una **función** es un fragmento de código que te permite realizar una tarea específica (en nuestro caso, mostrar algo en la consola). Las funciones a menudo toman argumentos, en otras palabras, datos que usarán durante la operación. En JavaScript, ejecutamos una función llamándola, y la llamamos escribiendo su nombre seguido de un par de paréntesis, donde se proporcionan los argumentos (si la función no necesita argumentos, los paréntesis se dejan vacíos). En nuestro ejemplo, el argumento es el texto que queremos mostrar. Toma en cuenta que para indicar que "¡Hola, Mundo!" es el texto, lo ponemos entre comillas.

Para que el intérprete sepa dónde termina el comando, colocamos un punto y coma al final de la llamada a la función. En este caso, el intérprete se las arreglaría sin esa ayuda, pero es una buena costumbre terminar cada comando con un punto y coma, para que no lo olvides cuando realmente lo necesites.

Ya sabemos qué escribir, y la única pregunta ahora es, ¿dónde hacerlo?

# Entorno de desarrollo local
El JavaScript del lado del cliente es un lenguaje de la web y solo existe en el ecosistema web. En esta configuración, JavaScript no puede existir por sí mismo. El código JavaScript debe estar incrustado en un documento HTML. Cuando usamos el entorno en línea para ejecutar nuestro programa, se nos ocultaron ciertos aspectos. Esta vez tendremos que mirarlos más de cerca.

## Unas palabras sobre HTML
**HyperText Markup Language**, o **HTML**, es un conjunto de etiquetas utilizadas para describir la estructura de un sitio web. Nos permite dar a una página el formato de un documento que contiene secciones, encabezados, párrafos, listas y similares. HTML definitivamente está más allá del alcance del curso actual, por lo que presentaremos solo información básica al respecto, lo suficiente para que comprendas dónde y cómo podemos ejecutar el código JavaScript asociado con una página determinada.

Los tipos de etiquetas están predefinidos. Por ejemplo, la etiqueta que especifica un párrafo es ```<p>``` y la etiqueta para el encabezado de primer grado (el más grande) es ```<h1>```. El nombre de la etiqueta debe colocarse entre corchetes. Las etiquetas se suelen utilizar en pares, limitando un área determinada del documento (tenemos una etiqueta de apertura y otra de cierre). La etiqueta de cierre es diferente de la etiqueta de apertura porque aparece una barra antes del nombre. Por ejemplo, un párrafo puede verse así:

```<p>un párrafo ordinario</p>```

A menudo, las etiquetas pueden (y a veces deben) colocarse dentro del rango de otras etiquetas. Por ejemplo, nuestro párrafo debe colocarse dentro de la etiqueta <body>, que separa la parte principal de nuestro documento.
```htmnl
<body>
<p>un párrafo ordinario</p>
</body>
```


Documento HTML
Intentemos crear un HTML sencillo que defina una página vacía.

```htmnl
<!DOCTYPE html>
<html>
  <head>
    <title>Empty Page</title>
  </head>
  <body>
  </body>
</html>
```

Comencemos con la declaración ```<!DOCTYPE html>```. Esta no es una etiqueta típica, ya que se utiliza para informar al navegador que todo el documento se ha preparado de acuerdo con HTML5. La descripción del documento en si comienza con la etiqueta ```<html>```, la cual junto con la etiqueta ```</html>``` establece los límites del documento. Cualquier otra etiqueta debe estar dentro de estas. Si una etiqueta dada tiene otro contenido, habrá una etiqueta de cierre correspondiente, formando una especie de contenedor.

La siguiente etiqueta, ```<head>```, contiene información adicional sobre el documento, que también debe colocarse en etiquetas. La más básica es la etiqueta ```<title>```, que establece el título de la página mayormente visible en la barra de título del navegador. Después de <head> esta el elemento ```<body>```, y allí se debe colocar el contenido visible de la página web (por ejemplo, nuestro párrafo).

# La etiqueta ```<script>```
El código JavaScript que ejecutará el navegador en la página debe adjuntarse al HTML utilizando la etiqueta ```<script>```, y existen dos formas de hacerlo. El código se puede incrustar directamente dentro de las etiquetas ```<script>``` y ```</script>```, pero esto solo se recomienda cuando el código es corto. Otro enfoque es utilizar el atributo "src" para apuntar a un archivo separado que contiene el código JavaScript. Esto es especialmente cierto cuando se va a usar el mismo código en varias páginas, porque repetir exactamente el mismo código muchas veces es una mala práctica, ya que cualquier cambio debe aplicarse a todos los archivos; y además, aumenta artificialmente el tamaño de la página. La extensión del archivo JavaScript es .js.

HTML es leído por el navegador línea por línea, y las etiquetas se ejecutan justo en el momento en que el navegador analiza la etiqueta ```<script>``` (analizar en lenguajes de programación significa un análisis formal del código por parte de una máquina para comprender su estructura). Generalmente las etiquetas <script> se insertan en el encabezado de la página entre las etiquetas ```<head>``` y ```</head>```, y podemos insertar muchos de ellos en un archivo, por ejemplo, para incluir código JavaScript de diferentes archivos. Este comportamiento se puede cambiar para scripts externos señalados por el atributo ```"src"``` usando los atributos ```"defer"``` o ```"async"```.

**defer**: significa que el script debe ejecutarse después de cargar toda la página.

**async**: significa que el script se ejecutará inmediatamente, pero en paralelo al análisis del resto de la página.

# ... y un poco acerca de CSS
CSS, o Cascading Style Sheets, es un lenguaje utilizado junto con HTML para describir la apariencia de una página y sus elementos. En pocas palabras, HTML describe la estructura de un documento, mientras que CSS describe su presentación.

Por ejemplo, en HTML, podemos describir una página que tiene un encabezado, dos párrafos y una tabla de datos.

En CSS, podemos definir qué fuente se usará en toda la página, qué color tendrá el fondo o si el cursor del mouse, cuando se mueve sobre la tabla, debe cambiar de forma.

Entonces podemos tratar CSS como una especie de configuración de la capa visual de la página. Así, la mayoría de las veces el sitio web se construirá sobre la base de un archivo HTML (es decir, una descripción de la estructura), código JavaScript que nos permite agregar, por ejemplo, algunos mecanismos de interacción y un archivo CSS (que describe la presentación de la página). Sin embargo, lo importante es que no habrá página sin un archivo HTML, pero podemos crear fácilmente una página sin usar archivos CSS. La descripción de CSS en sí está fuera del alcance del curso actual y la mencionamos solo por orden.

# ¿Cómo podemos ejecutar nuestra código JavaScript?
Comencemos con un ejemplo simple, donde el navegador obtiene una página simple (quizás incluso vacía) de https://test.org. La dirección es ficticia para este ejemplo, así que no intentes ingresarla. Mira la figura de abajo.

![Captura de pantalla 2023-08-01 214747](https://github.com/xlifems/JavaScriptEssentials1/assets/19802299/4f5755b9-4377-4dce-89e4-b99fc98ca898)

Empecemos por el lado derecho de la figura. El usuario ejecuta un navegador web en su computadora (por ejemplo, Chrome). Usando el atajo de teclado apropiado, se activan las herramientas de desarrollo (ver el capítulo anterior) para poder usar la consola. Recuerda que estas herramientas no son necesarias para el uso normal del navegador y, por lo tanto, están ocultas por defecto. Luego, el usuario escribe https://test.org (la URL de nuestro sitio falso) en la barra de direcciones.

En el servidor remoto (lado izquierdo del dibujo), asociado a la dirección https://test.org, se esta ejecutando un servidor web que, tras recibir una solicitud de nuestro usuario, preparará una respuesta para ello. En el caso más simple, la respuesta solo contendrá un archivo html, que se puede almacenar en el mismo servidor. El archivo html (en este ejemplo, index.html) se devuelve al usuario y el navegador lo procesa. Si se define algún contenido (por ejemplo, un párrafo con texto), se mostrará en la ventana del navegador.

Sin embargo, nos interesa más el hecho de que el archivo index.html contiene las etiquetas ```<script>``` y ```</script>```, con una pieza de código JavaScript entre ellas. ¿Lo reconoces? Obviamente, esto es un intento de mostrar nuestro ```"¡Hola, mundo!"``` en la consola al cargar la página, se debe ejecutar el código colocado dentro de las etiquetas ```<script>``` y, si las herramientas para desarrolladores están habilitadas y el panel de la consola está visible, la consola mostrará ```"¡Hola, Mundo!"```.

