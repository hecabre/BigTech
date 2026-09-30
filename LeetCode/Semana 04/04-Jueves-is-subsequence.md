# Is Subsequence

[← Anterior: Intersection of Two Arrays II](../Semana%2004/03-Miercoles-intersection-of-two-arrays-ii.md) · [Siguiente: Longest Consecutive Sequence →](../Semana%2004/05-Viernes-longest-consecutive-sequence.md)

> [!quote] Para darle con todo
> «Siempre es el Día 1.»
> — *Jeff Bezos, fundador de Amazon, carta a accionistas*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/is-subsequence/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Two pointers
- **Semana:** 04 — Calentamiento arrays/strings (semana de examen CCP) (problema 4 de 5)
- **Día:** [Semana 04 — Jueves](../../Semanas/Semana%2004/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/):** Son dos punteros como en Valid Palindrome, pero cada uno avanza sobre un string distinto.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un puntero `i` en `s` y otro `j` en `t`.

> [!question]- Pista 2 — ¿qué estructura usar?
> `j` siempre avanza. ¿Cuándo avanza `i`?

> [!question]- Pista 3 — el algoritmo
> `i` avanza solo cuando `s[i] === t[j]`. Al final, ¿llegó `i` al final de `s`?

> [!warning]- Trampa común
> Buscar con `indexOf` desde el principio cada vez: se pierde el orden y el costo sube.

> [!success]- Complejidad meta
> Tiempo O(|t|), espacio O(1)

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
