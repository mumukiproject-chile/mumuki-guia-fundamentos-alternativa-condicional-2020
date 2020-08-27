En el día a día, se presentan muchas situaciones donde debemos elegir entre dos acciones diferentes, dependiendo de si se cumple una cierta condición o no.

* Si la polera está limpia, me la pongo, _si no_, la lavo.
* Si tengo aceite para freír las papas, lo uso, _si no_, las meto al horno.
* Si me puedo mover al este, lo hago, _si no_, me muevo al norte.

Para estos casos, en Gobstones tenemos una nueva palabra clave que nos ayuda a cumplir nuestra tarea: el **else**. En castellano significa _si no_, y hace justamente lo que necesitamos: ejecuta una serie de acciones _si no se cumple_ la condición que pusimos en el `if`.

Supongamos que queremos definir un procedimiento que se mueva al oeste y, en caso de que no pueda, lo haga hacia el norte. Haciendo uso del `else`, podemos definirlo de la siguiente manera:

```gobstones
procedure MoverComoSea() {
    if (puedeMover(Oeste)) {
        Mover(Oeste)
    } else {
        Mover(Norte)
    }
}
```

> Escribe ese código en el editor y fíjate en cómo resuelve el problema.