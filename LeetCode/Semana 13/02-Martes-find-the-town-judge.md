# Find the Town Judge

[← Anterior: Find if Path Exists in Graph](../Semana%2013/01-Lunes-find-if-path-exists-in-graph.md) · [Siguiente: Island Perimeter →](../Semana%2013/03-Miercoles-island-perimeter.md)

> [!quote] Para darle con todo
> «Todo lo negativo —la presión, los retos— es una oportunidad para elevarme.»
> — *Kobe Bryant, cinco veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/find-the-town-judge/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Grados de grafo
- **Semana:** 13 — Grafos — introducción (problema 2 de 5)
- **Día:** [Semana 13 — Martes](../../Semanas/Semana%2013/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Conexión:** Introduce el concepto de grados de entrada y de salida.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El juez no confía en nadie (grado de salida 0).

> [!question]- Pista 2 — ¿qué estructura usar?
> Todos confían en el juez (grado de entrada n - 1).

> [!question]- Pista 3 — el algoritmo
> Usa un arreglo `score`: `score[a]--` y `score[b]++`. Busca `score[i] === n - 1`.

> [!warning]- Trampa común
> Olvidar que con `n = 1` y sin relaciones, la persona 1 es el juez.

> [!success]- Complejidad meta
> Tiempo O(n + t), espacio O(n)

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
