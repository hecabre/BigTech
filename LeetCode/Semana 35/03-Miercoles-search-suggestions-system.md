# Search Suggestions System

[← Anterior: Top K Frequent Words](../Semana%2035/02-Martes-top-k-frequent-words.md) · [Siguiente: Trapping Rain Water →](../Semana%2035/04-Jueves-trapping-rain-water.md)

> [!quote] Para darle con todo
> «Stay hungry, stay foolish. Sigue con hambre, sigue con locura.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/search-suggestions-system/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Sorting + binary search / Trie
- **Semana:** 35 — Simulación Amazon — repaso OA (problema 3 de 5)
- **Día:** [Semana 35 — Miércoles](../../Semanas/Semana%2035/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Find First and Last Position of Element in Sorted Array](../Semana%2008/05-Viernes-find-first-and-last-position-of-element-in-sorted-array.md):** Es ordenar y luego usar búsqueda binaria para el primer elemento que cumple.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Ordena los productos.

> [!question]- Pista 2 — ¿qué estructura usar?
> Para cada prefijo, busca con búsqueda binaria el primer producto `>= prefijo`.

> [!question]- Pista 3 — el algoritmo
> Toma hasta 3 desde ahí que empiecen con el prefijo. Alternativa: un Trie.

> [!warning]- Trampa común
> Filtrar todos los productos en cada prefijo: O(n·L²).

> [!success]- Complejidad meta
> Tiempo O(n log n + L log n), espacio O(1) extra

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
