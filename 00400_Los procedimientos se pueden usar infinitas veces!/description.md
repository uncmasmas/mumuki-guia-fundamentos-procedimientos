Como ya te adelantamos, a la acción de crear un procedimiento nuevo la conocemos como **definición** o **declaración**, y consta de 3 elementos:

- la palabra reservada `procedure`, que indica que vamos a definir un procedimiento nuevo
- un nombre que represente lo que nuestro procedimiento va a hacer, para poder usarlo luego. En Gobstones, como en muchos otros lenguajes, los nombres se escriben siguiendo el estilo [CamelCase](http://es.wikipedia.org/wiki/CamelCase), es decir: sin espacios ni signos de puntuación y usando una mayúscula para cada palabra (si conocés Twitter, probablemente te habrás dado cuenta que los hashtags usan esta misma convención). Algunos ejemplos: `DibujarCuadrado()`, `Sacar10Bolitas()`, `LlenarTableroDeBolitasRojas()`. Algo importante: **los paréntesis del final son necesarios**, más adelante veremos por qué.
- un **bloque de código**, que va a ser lo que se va ejecutar cada vez que **invoquemos** a nuestro procedimiento. Este bloque va encerrado entre llaves `{}`

Algo _MUY_ importante es que un procedimiento se define **una sola vez** y luego se puede **usar** todas las veces que necesitemos. Por esto, su nombre debe ser **único** dentro de todo el programa (si se repitiera el nombre, la computadora no sabría cuál elegir).

> Escribí ahora un programa que ponga 9 bolitas verdes en la celda actual, usando el procedimiento `Poner3Verdes` que creaste antes.