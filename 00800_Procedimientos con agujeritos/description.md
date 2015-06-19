Probablemente te estés preguntando: ¿y qué pasa si quiero hacer un cuadrado rojo o verde? ¿tengo que escribir todo esto de vuelta? Y seguramente también adivinaste que la respuesta es **no**, después de todo ¡la programación se trata de automatizar tareas repetitivas!

Pero empecemos con un ejemplo más fácil: supongamos que queremos **generalizar** el procedimiento `Poner3Verdes`, para que funcione con cualquier color que querramos (pero uno solo por vez). Necesitaríamos hacer 3 cosas:

- **cambiarle el nombre**, porque ahora serviría para cualquier color. Un buen nombre podría ser `Poner3`
- avisarle a la computadora que el procedimiento está incompleto, tiene un _agujero_, y que quien lo use **debe** llenar ese _agujero_ con algún **valor**
- poder usar el valor del _agujero_ dentro del procedimiento

Una vez más, te vamos a contar la respuesta nosotros (pero sólo por un ratito).

> Copiá y pega el siguiente código en el editor y vas a ver que funciona como esperarías:

```puppet
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