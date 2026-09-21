# Reverse String

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/reverse-string/)
- **Patrón:** Two pointers
- **Día:** [Semana 02 — Jueves](../../Semanas/Semana%2002/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Antes de programar

- **Entrada y salida con mis palabras:** Basicamente usamos dos punteros que hasta que se crucen se repite, guardamos los valores antes de sustituirlos y los invertimos, este fue sencillo
- **Restricciones importantes:**
- **Casos límite:**
- **Fuerza bruta y su costo:**
- **Patrón que intentaré:**

## Mi solución

```ts
/**

Do not return anything, modify s in-place instead.

*/

function reverseString(s: string[]): void {

let left = 0

let right = s.length - 1

while(left < right){

let aux = s[right]

let aux2 = s[left]

s[right] = aux2

s[left] = aux

left++

right--

}

};
```

## Complejidad

- **Tiempo:** TIempo n
- **Por qué:** Porque recorremos el arrelo 1 vez
- **Espacio adicional:** Estamos usando O1
- **Por qué:** Porque solo creamos dos variables en este caso

## Error o aprendizaje

- **Dónde me atasqué:** Nada
- **Pista consultada:** NAda
- **Invariante o idea clave:** Dos punteros
- **Qué haré distinto:** No usas variables auxiliares

## Repetición espaciada

- [ ] Reintento en 24 horas
- [ ] Reintento en 7 días
- [ ] Reintento en 30 días
