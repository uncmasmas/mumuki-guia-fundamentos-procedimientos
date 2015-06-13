No te olvides de **definir** tu procedimiento, usando la palabra clave `procedure` y de **invocarlo** en tu `program`, escribiendo su nombre seguido de un par de paréntesis `()`.

Te dejamos el código del ejercicio anterior como referencia:

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