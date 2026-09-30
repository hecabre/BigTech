# Basic Calculator II

[← Anterior: Accounts Merge](../Semana%2036/03-Miercoles-accounts-merge.md) · [Siguiente: Copy List with Random Pointer →](../Semana%2036/05-Viernes-copy-list-with-random-pointer.md)

> [!quote] Para darle con todo
> «Siempre es el Día 1.»
> — *Jeff Bezos, fundador de Amazon, carta a accionistas*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/basic-calculator-ii/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 36 — Otras empresas — Medium variados (problema 4 de 5)
- **Día:** [Semana 36 — Jueves](../../Semanas/Semana%2036/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Evaluate Reverse Polish Notation](../Semana%2005/05-Viernes-evaluate-reverse-polish-notation.md):** Es una pila de números, como RPN, respetando la precedencia.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `*` y `/` se resuelven en el momento; `+` y `-` se guardan en la pila.

> [!question]- Pista 2 — ¿qué estructura usar?
> Guarda el último operador visto; al terminar de leer un número, aplícalo.

> [!question]- Pista 3 — el algoritmo
> `-` guarda `-num`; `*` hace `pop() * num`; `/` hace `Math.trunc(pop() / num)`. Al final, suma la pila.

> [!warning]- Trampa común
> No procesar el último número al terminar el string.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(n)

## Antes de programar

- **Entrada y salida con mis palabras:**
- **Restricciones importantes:**
- **Casos límite:**
- **Fuerza bruta y su costo:**
- **Patrón que intentaré:**

## Mi solución

```ts

```

## Complejidad

- **Tiempo:**
- **Por qué:**
- **Espacio adicional:**
- **Por qué:**

## Error o aprendizaje

- **Dónde me atasqué:**
- **Pista consultada:** ninguna / 1 / 2 / 3
- **Invariante o idea clave:**
- **Qué haré distinto:**

## Repetición espaciada

- [ ] Reintento en 24 horas
- [ ] Reintento en 7 días
- [ ] Reintento en 30 días
