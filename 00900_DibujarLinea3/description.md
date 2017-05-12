Si prestaste atención en el ejercicio anterior, verás que tuvimos que cambiar algunas cosas para que `Poner3Verdes` sirva para cualquier color.

La más importante: **avisarle a la computadora que el procedimiento está incompleto**, tiene un _agujero_, y que quien lo use **debe** llenar ese _agujero_ con algún **valor**. Eso lo hicimos agregando la palabra `color` entre los paréntesis que hasta ahora siempre habíamos puesto vacíos.

> Tu turno: basándote en `DibujarLineaNegra3`...
> 
> ```gobstones
> procedure DibujarLineaNegra3() {
>     Poner(Negro)
>     Mover(Este)
>     Poner(Negro)
>     Mover(Este)
>     Poner(Negro)
>     VolverAtras()
> }
> ```
> 
> ...escribí un procedimiento `DibujarLinea3` que reciba un color y dibuje una línea de ese color. 
>
> Nosotros nos vamos a encargar de escribir los `program`s para usarlo con cada uno de los colores.