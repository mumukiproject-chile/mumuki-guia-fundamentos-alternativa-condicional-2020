Analicemos el procedimiento del ejercicio anterior:

```gobstones
procedure SacarAzulConMiedo() {
  if (hayBolitas(Azul)) {
    Sacar(Azul)
  } 
}
```

Como verás, introdujimos una nueva estructura de control: el **if**, que en castellano significa _si_; entendiendo el _si_ como **condicional** ("_si_ tuviera hambre me comería una empanada") y no como afirmación ("_sí_, yo rompí el teléfono").

Entonces, lo que le estamos diciendo al computador es _"si hay bolitas azules, saca una bolita azul"_, que dicho así suena un poco tonto, ¡y lo es! Ya te dijimos que el computador sólo sabe cumplir órdenes.

> ¡Ahora te toca a ti! Modifica el procedimiento que te dimos para que saque una bolita roja sólo _si_ hay alguna.