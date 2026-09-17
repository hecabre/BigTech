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
```
function isValid(s: string): boolean {

const values = new Map<string, string>([

["(", ")"],

["{", "}"],

["[", "]"]

])

let stack = []

for(let i = 0; i <= s.length; i++){

let lastItem = stack[stack.length - 1]

if(values.has(s[i])){

stack.push(s[i])

} else {

if(values.get(lastItem) === s[i]) {

stack.pop()

} else {

return false

}

}

}

return stack.length !== 0 ? false : true

};
```
## Group Anagrams
En groups anagram, se crea un map, en ese map ordenamos el valor, eso genera una firma para el anagrama. SIno existe lo metemos y poner un contador, si existe el agarramos la firma y aumentamos el valor en 1.
Despues necesitamos