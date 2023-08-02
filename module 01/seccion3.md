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

Una *función* es un fragmento de código que te permite realizar una tarea específica (en nuestro caso, mostrar algo en la consola). Las funciones a menudo toman argumentos, en otras palabras, datos que usarán durante la operación. En JavaScript, ejecutamos una función llamándola, y la llamamos escribiendo su nombre seguido de un par de paréntesis, donde se proporcionan los argumentos (si la función no necesita argumentos, los paréntesis se dejan vacíos). En nuestro ejemplo, el argumento es el texto que queremos mostrar. Toma en cuenta que para indicar que "¡Hola, Mundo!" es el texto, lo ponemos entre comillas.

Para que el intérprete sepa dónde termina el comando, colocamos un punto y coma al final de la llamada a la función. En este caso, el intérprete se las arreglaría sin esa ayuda, pero es una buena costumbre terminar cada comando con un punto y coma, para que no lo olvides cuando realmente lo necesites.

Ya sabemos qué escribir, y la única pregunta ahora es, ¿dónde hacerlo?
