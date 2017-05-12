Entendamos qué acabamos hacer :hushed:.

Primero, declaramos un procedimiento, pero con una pequeña diferencia: toma un _parámetro_, llamado `color`.

```gobstones
procedure Poner3(color) {
  Poner(color)
  Poner(color)
  Poner(color)
}
```

Los parámetros (esos nombres que van entre paréntesis) son especiales, porque son reemplazados por valores concretos cuando los invocamos. Por ejemplo, si lo invocamos así..

```gobstones
program {
  Poner3(Negro)
}
```

...lo que se ejecuta es:

```gobstones
Poner(Negro)
Poner(Negro)
Poner(Negro)
```

Y si lo invocamos así...

```gobstones
program {
  Poner3(Rojo)
}
```

lo que se ejecuta es:

```gobstones
Poner(Rojo)
Poner(Rojo)
Poner(Rojo)
```

Notá como cada vez que aparece `color`, este es reemplazado por el valor que pasamos en la invocación. 

> Veamos si se va entendiendo: escribí un programa que ponga tres boltas verdes usando `Poner3`

