Como introducimos brevemente con el ejemplo del cuadrado, podemos empezar a diferenciar dos tipos de comandos dentro de un programa:

- los que **vienen definidos por el lenguaje** y nos sirven para expresar operaciones básicas, como `Mover`, `Poner` y `Sacar`. A estos los llamaremos **comandos primitivos**, o simplemente **primitivas**
- y los que **definimos nosotros**, que nos sirven para expresar tareas más complejas. Como el nombre de esta guía sugiere, estos son los **procedimientos**

Entonces, cuando creamos un procedimiento estamos "enseñándole" a la computadora a realizar una tarea nueva, que originalmente no estaba incluida en el lenguaje (sería imposible escribir un lenguaje que traiga _TODO_ lo que se nos pueda ocurrir hacer, ¿no?). A esta acción de crear un procedimiento nuevo la conocemos como **definición** o **declaración**, y consta de 3 elementos:

- la palabra reservada `procedure`, que indica que vamos a definir un procedimiento nuevo
- un nombre que represente lo que nuestro procedimiento va a hacer, para poder usarlo luego. En Gobstones, como en muchos otros lenguajes, los nombres se escriben siguiendo el estilo [CamelCase](http://es.wikipedia.org/wiki/CamelCase), es decir: sin espacios ni signos de puntuación y usando una mayúscula para cada palabra (si conocés Twitter, probablemente te habrás dado cuenta que los hashtags usan esta misma convención). Algunos ejemplos: `DibujarCuadrado()`, `Sacar10Bolitas()`, `LlenarTableroDeBolitasRojas()`. Algo importante: **los paréntesis del final son necesarios**, más adelante veremos por qué.
- un **bloque de código**, que va a ser lo que se va ejecutar cada vez que **invoquemos** a nuestro procedimiento. Este bloque va encerrado entre llaves `{}`

Definamos un procedimiento que ponga tres bolitas verdes:

```puppet
procedure Poner3Verdes() {
  Poner(Verde)
  Poner(Verde)
  Poner(Verde)
}

program {
  Poner3Verdes()
}
```

Como ves, se pueden distinguir dos momentos:

- la **definición**, que es cuando ponemos `procedure Poner3Verdes()`
- el **uso** o **invocación**, que es cuando escribimos `Poner3Verdes()` en alguna parte de nuestro programa

Para seguir adelante, copiá el código en el editor, presioná Enviar y fijate si hace lo que esperabas.
