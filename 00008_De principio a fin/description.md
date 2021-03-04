Si bien `in` nos puede decir si un string está incluído en otro cuenta con dos casos particulares: cuando un string comienza, o termina, con otro. 

La sintaxis de estas operaciones es _apenitas_ :ok_hand: diferente de lo que venimos haciendo: hay que prefijarlas con `str.`. Por ejemplo, la operación que devuelve si un `string` comienza con otro es `str.startswith`, mientras que la que nos dice si termina con otro es `str.endswith`. :eyes:

> Probalas en la consola escribiendo:
>
> * `str.startswith("Fundación", "Fundación e imperio")`
> * `str.endswith("y sí", "Bueno, y sí")`
> * `str.endswith("Hola", "Hola, ¿qué tal?")`
