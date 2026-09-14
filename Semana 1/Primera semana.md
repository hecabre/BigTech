## Valid parentenses
En valid parentenses tenia una pila y si entendia eso, pero el problema era
como voy a tener el valor en la posicion del arreglo para borrarla? eso me hubiera tomado hacer un for dentro de otro, no era costeable
la primera vez pense en un map porque podria recordar valores, pero si solo recordaba el anterior valor que pasaba si tenia esto?
```
[[(]]
```
EL problema esta mal descrito.
El enfoque de obtener la posicion del arreglo esta mal, no necesitas la posicion del arreglo, necesitas EL VALOR, porque estas iterando valores, por eso el map aqui funciona, porque si iteras valores puedes recuperar su clave y SOLAMENTE guardas claves en la pila.
despues terminas de iterar y listo
