# Subsets

[← Anterior: Maximum Depth of Binary Tree](../Semana%2016/04-Jueves-maximum-depth-of-binary-tree.md) · [Siguiente: Maximum Average Subarray I →](../Semana%2017/01-Lunes-maximum-average-subarray-i.md)

> [!quote] Para darle con todo
> «Tu tiempo es limitado, así que no lo desperdicies viviendo la vida de alguien más.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/subsets/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Backtracking
- **Semana:** 16 — Semana ligera — repaso de fundamentos (problema 5 de 5)
- **Día:** [Semana 16 — Viernes](../../Semanas/Semana%2016/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es el esqueleto de todo backtracking.
- **Repaso del patrón:** [Backtracking](../../Estudio/Articulos/11-Backtracking.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Para cada número decides: incluirlo o no incluirlo.

> [!question]- Pista 2 — ¿qué estructura usar?
> `bt(i, camino)`: al llegar a `i === n`, guarda una copia.

> [!question]- Pista 3 — el algoritmo
> Otra forma: guarda en cada llamada y recorre desde `inicio` con `push`/`pop`.

> [!warning]- Trampa común
> Guardar la referencia `camino` en lugar de una copia.

> [!success]- Complejidad meta
> Tiempo O(2ⁿ·n), espacio O(n)

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
