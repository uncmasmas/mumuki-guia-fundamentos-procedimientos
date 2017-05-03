Probablemente te estés preguntando: ¿y qué pasa si quiero hacer un cuadrado rojo o verde? ¿tengo que escribir todo esto de vuelta? Adiviná: ¡**no**! Después de todo ¡la programación se trata de automatizar tareas repetitivas!

Empecemos con algo fácil: supongamos que queremos **generalizar** el procedimiento `Poner3Verdes`, para que funcione con cualquier color que querramos (pero uno solo por vez). Lo que necesitamos es agregarle al procedimiento una especie de _agujero_, que luego pueda ser completado cada vez que se use.

Una vez más, te vamos a contar la respuesta nosotros (pero sólo por un ratito).

> Copiá y pega el siguiente código en el editor y vas a ver que funciona como esperarías:

```gobstones
procedure Poner3(color) {
  Poner(color)
  Poner(color)
  Poner(color)
}

program {
  Poner3(Negro)
  Poner3(Rojo)
}
```
