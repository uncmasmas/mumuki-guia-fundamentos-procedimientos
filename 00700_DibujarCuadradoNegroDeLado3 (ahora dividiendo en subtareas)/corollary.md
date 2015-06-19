¿Viste cómo ayudó que `DibujarLineaNegra3` dejara el cabezal en la celda inicial? Esa es un poco la magia de **dividir en subtareas**, nos ocupamos de un problema a la vez y luego sólo tenemos que combinar las pequeñas tareas para resolver nuestro objetivo.

Además, el código queda mucho más claro (cuesta menos trabajo entender qué hace) y corto (es más fácil de leer). Compará tu versión con la que habíamos hecho al principio y vas a ver que no te estamos mintiendo:

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
```