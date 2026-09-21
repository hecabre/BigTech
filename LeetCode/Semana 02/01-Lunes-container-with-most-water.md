# Container With Most Water

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/container-with-most-water/)
- **Patrón:** Two pointers
- **Día:** [Semana 02 — Lunes](../../Semanas/Semana%2002/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Antes de programar

- **Entrada y salida con mis palabras:** Primero pense en ordenar el arreglo y agarrar las ultimas dos posiciones, si eran iguales recorria para atras hasta que fueran diferentes y depues multiplicaba. Eso estaba mal debido a que no entendia el problema, si fuera asi solo tendria un area de xn xn- 1 y los valores que multiplicaba. No entendia el problema. Despues vi que el valor puede ser mejor si medimos las areas una vez que lo entendi. Despues busque un map para recordar valores, pero realmente no entendia bien. Despues de pensarlo vi que teniamos 4 valores: x1 que es el INDICE inciial, x2 el INDICE final y el y1 es el valor en el indice x1, el y2 es el valor en el indice y2. Pero recordaba valores que no tenian sentido. Eso si, llegue a guardar la mejor agua o "area". Si pense en two pointers desde el inicio porque teniamos que recorrer algo desde un extremo y mientras mas lejos podriamos tener mas area. En este caso busque la solucion y fue dificil, pero la pude comprender. Despues la implemente yo, debo de repasarlo
- **Restricciones importantes:** No hacer un n2
- **Casos límite:**
- **Fuerza bruta y su costo:** n2
- **Patrón que intentaré:** Two pointers

## Mi solución

```ts
function maxArea(height: number[]): number {

let water = 0

let left = 0

let right = height.length - 1

while(left < right) {

let waterAux = Math.min(height[left], height[right]) * (right - left)

water = Math.max(water, waterAux)

if(height[left] < height[right]) {

left++

} else {

right--

}

}

return water

};
```

## Complejidad

- **Tiempo:** O(n)
- **Por qué:** Porque recorremos en el peor de los casos 1 vez el arreglo debido a que 
- **Espacio adicional:** O(1)
- **Por qué:** Porque solamente tenemos 4 variables, da igual el tamano del arreglo, seran siempre 4 variables, no copiamos el arreglo o algo parecido.

## Error o aprendizaje

- **Dónde me atasqué:** Cuando use un set, me di cuenta de que repetia 2 valores que eran 0 y igual el height.length - 1. Ahi me di cuenta de algo mal
- **Pista consultada:** Two pointers, pero ya lo habia pensado
- **Invariante o idea clave:** Two pointers, solo guardar la agua maxima porque no nos han pedido las posiciones,
- **Qué haré distinto:** Practicar mas este ejercicio porque usa two pointers de manera distina, pareciera una busqueda binaria porque comparamos el valor izquierdo y dercho y en base a eso hacemos una resta  o suma.

## Repetición espaciada

- [ ] Reintento en 24 horas
- [ ] Reintento en 7 días
- [ ] Reintento en 30 días
