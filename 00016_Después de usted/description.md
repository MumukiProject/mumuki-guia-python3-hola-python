No todos los operadores que vimos tienen la misma prioridad a la hora de ser evaluados. De hecho en esta tabla te mostramos la precedencia de algunas operaciones que vimos (y otras que no), desde las que primero se evalúan a las últimas:


<table class="table table-striped table-bordered table-condensed text-center">
  <tr>
    <th class ="text-center" style="width: 75px">Operaciones</th>
    <th class ="text-center" style="width: 75px">Descripción</th>
  </tr>
  <tr>
    <td>**</td>
    <td>Exponenciación</td>
  </tr>
  <tr>
    <td>*,  /,  %</td>
    <td>Multiplicación, división, resto</td>
  </tr>
  <tr>
    <td>+,  -</td>
    <td>Suma, resta</td>
  </tr>
  <tr>
    <td>in,  <,  <=,  >,  >=,  ==,  !=</td>
    <td>Pertenencia, comparaciones</td>
  </tr>
  <tr>
    <td>and</td>
    <td>Conjunción lógica</td>
  </tr>
  <tr>
    <td>or</td>
    <td>Disyunción lógica</td>
  </tr>
</table>

Sin embargo, podemos cambiar la precedencia utilizando paréntesis, ¡como en matemática!

> Mirá en la consola las diferencias entre: 
>
>`2 + 3 * 5`
>
> y 
>
> `(2 + 3) * 5`.
