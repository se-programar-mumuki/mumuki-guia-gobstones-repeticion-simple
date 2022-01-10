En el ejercicio anterior definimos el procedimiento `LineaNegra4Este`. Ahora vamos a utilizarlo para dibujar un cuadrado negro igualito a los de los tableros de ejemplo:

<table class= "table table-borderless" style="width:100%">
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 4 4
        cell 0 0 Negro 1
        cell 0 1 Negro 1
        cell 0 2 Negro 1
        cell 0 3 Negro 1
        cell 1 0 Negro 1
        cell 1 1 Negro 1
        cell 1 2 Negro 1
        cell 1 3 Negro 1
        cell 2 0 Negro 1
        cell 2 1 Negro 1
        cell 2 2 Negro 1
        cell 2 3 Negro 1
        cell 3 0 Negro 1
        cell 3 1 Negro 1
        cell 3 2 Negro 1
        cell 3 3 Negro 1
        head 3 3
      </gs-board>
    </td>
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 6 6
        cell 1 1 Negro 1
        cell 1 2 Negro 1
        cell 1 3 Negro 1
        cell 1 4 Negro 1
        cell 2 1 Negro 1
        cell 2 2 Negro 1
        cell 2 3 Negro 1
        cell 2 4 Negro 1
        cell 3 1 Negro 1
        cell 3 2 Negro 1
        cell 3 3 Negro 1
        cell 3 4 Negro 1
        cell 4 1 Negro 1
        cell 4 2 Negro 1
        cell 4 3 Negro 1
        cell 4 4 Negro 1
        head 4 4
      </gs-board>
    </td>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 5 5
        cell 1 1 Negro 1
        cell 1 2 Negro 1
        cell 1 3 Negro 1
        cell 1 4 Negro 1
        cell 2 1 Negro 1
        cell 2 2 Negro 1
        cell 2 3 Negro 1
        cell 2 4 Negro 1
        cell 3 1 Negro 1
        cell 3 2 Negro 1
        cell 3 3 Negro 1
        cell 3 4 Negro 1
        cell 4 1 Negro 1
        cell 4 2 Negro 1
        cell 4 3 Negro 1
        cell 4 4 Negro 1
        head 4 4
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>


> Definí el procedimiento `CuadradoNegro4` para dibujar un cuadrado de 4x4 con bolitas negras. Al empezar, el cabezal se encuentra en la esquina inferior izquierda del cuadrado (no necesariamente del tablero :exploding_head:) y cuando termine el programa el cabezal deberá quedar en el extremo superior derecho del cuadrado. No te olvides de invocar `LineaNegra4Este`. 

> Tené en cuenta lo que hablamos en el ejercicio anterior sobre el **caso borde**. :eyes:
