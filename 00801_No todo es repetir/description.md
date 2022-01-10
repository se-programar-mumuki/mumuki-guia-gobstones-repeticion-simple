Los ejemplos que hiciste en los ejercicios anteriores se solucionaban simplemente repitiendo cosas. Pero no todo es repetir, también podemos poner comandos tanto **antes** como **después** del `repeat`, al igual que veníamos haciendo hasta ahora.

Por ejemplo, este es un programa que se mueve al `Sur`, **luego** pone 4 bolitas de color `Rojo` y por último vuelve a moverse al `Norte`:

```gobstones
program {
  Mover(Sur)
  repeat(4) {
    Poner(Rojo)
  }
  Mover(Norte)
}
```

Fijate que `Mover(Sur)` lo pusimos **antes** del `repeat` y `Mover(Norte)` lo pusimos **después**. Por lo tanto cada movimiento se ejecuta solo una vez. Teniendo en cuenta esto:

> Definí el procedimiento `Poner3AlNoreste()`, que ponga 3 bolitas negras en la primera celda al Noreste del cabezal.

<table class= "table table-borderless" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 3 3
        head 1 1
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        cell 2 2 Negro 3
        head 2 2
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>