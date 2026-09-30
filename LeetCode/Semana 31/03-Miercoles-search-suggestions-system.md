# Search Suggestions System

[← Anterior: Reorder Data in Log Files](../Semana%2031/02-Martes-reorder-data-in-log-files.md) · [Siguiente: Partition Labels →](../Semana%2031/04-Jueves-partition-labels.md)

> [!quote] Para darle con todo
> «El talento sin trabajo duro no es nada.»
> — *Cristiano Ronaldo, cinco veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/search-suggestions-system/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Sorting + binary search / Trie
- **Semana:** 31 — Etiquetados frecuentes de Amazon (problema 3 de 5)
- **Día:** [Semana 31 — Miércoles](../../Semanas/Semana%2031/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

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
