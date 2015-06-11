Si llegaste hasta acá, entonces ya sabés:
- cómo escribir un programa (`program`)
- cómo poner y sacar bolitas, usando `Poner` y `Sacar`
- cómo desplazar el cabezal por el tablero, usando `Mover`

Como te imaginarás, con estas 3 cosas ya podés resolver muchos problemas: [dibujar la bandera de Portugal](/exercises/289), escribir tu nombre, hacer un plano de tu casa, etc, etc, etc. 

Veamos juntos un ejemplo de un programa que dibuja "algo", y tratá de imaginarte el tablero final:

```puppet
program {
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
  Mover(Norte)
  Poner(Negro)
  Mover(Oeste)
  Poner(Negro)
  Mover(Oeste)
  Poner(Negro)
  Mover(Norte)
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
}
```

¿Costó un poco no? Bueno, eso es normal porque **los humanos no somos computadoras** y normalmente nos cuesta ejecutar un programa en nuestra cabeza... pero por suerte existen las computadoras, que se encargan de resolver eso por nosotros.

Mirá ahora esta otra versión del mismo programa. Aunque todavía hay elementos de la **sintaxis** que no conocés, estamos seguros de que vas a tardar mucho menos en entender qué hace:

```puppet
procedure DibujarCuadradoNegroDeLado3() {
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
  Mover(Norte)
  Poner(Negro)
  Mover(Oeste)
  Poner(Negro)
  Mover(Oeste)
  Poner(Negro)
  Mover(Norte)
  Poner(Negro)
  Mover(Este)
  Poner(Negro)
  Mover(Este)
  Poner(Negro)    
}

program {
  DibujarCuadradoNegroDeLado3()   
}
```

Como probablemente hayas descubierto, el programa dibuja un cuadrado negro de lado 3. ¿Mucho más fácil de entender, no?

Pero, ¿cómo supo la computadora lo que tenía que hacer `DibujarCuadradoNegroDeLado3`?, ¿qué es eso de `procedure`?. 
¡Acompañanos al primer ejercicio!