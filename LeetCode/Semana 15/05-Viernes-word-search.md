# Word Search

[← Anterior: Generate Parentheses](../Semana%2015/04-Jueves-generate-parentheses.md) · [Siguiente: Two Sum →](../Semana%2016/01-Lunes-two-sum.md)

> [!quote] Para darle con todo
> «Disciplina es hacer lo que odias como si lo amaras.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/word-search/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Backtracking en grid
- **Semana:** 15 — Backtracking (problema 5 de 5)
- **Día:** [Semana 15 — Viernes](../../Semanas/Semana%2015/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Number of Islands](../Semana%2014/05-Viernes-number-of-islands.md):** Es DFS en un grid como Islands, pero deshaciendo la marca al regresar.
- **Repaso del patrón:** [Backtracking](../../Estudio/Articulos/11-Backtracking.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Prueba iniciar desde cada celda.

> [!question]- Pista 2 — ¿qué estructura usar?
> `dfs(r, c, i)`: si `board[r][c] !== word[i]`, devuelve false.

> [!question]- Pista 3 — el algoritmo
> Marca la celda (`#`), explora las 4 direcciones y restaura la letra al volver.

> [!warning]- Trampa común
> No restaurar la celda: bloquea caminos que sí eran válidos.

> [!success]- Complejidad meta
> Tiempo O(filas·cols·4^L), espacio O(L)

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
