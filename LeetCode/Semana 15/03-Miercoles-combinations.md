# Combinations

[← Anterior: Letter Combinations of a Phone Number](../Semana%2015/02-Martes-letter-combinations-of-a-phone-number.md) · [Siguiente: Generate Parentheses →](../Semana%2015/04-Jueves-generate-parentheses.md)

> [!quote] Para darle con todo
> «El talento sin trabajo duro no es nada.»
> — *Cristiano Ronaldo, cinco veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/combinations/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Backtracking
- **Semana:** 15 — Backtracking (problema 3 de 5)
- **Día:** [Semana 15 — Miércoles](../../Semanas/Semana%2015/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Subsets](https://leetcode.com/problems/subsets/):** Es Subsets, pero solo guardas los de tamaño k.
- **Repaso del patrón:** [Backtracking](../../Estudio/Articulos/11-Backtracking.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Elige números en orden creciente para no repetir combinaciones.

> [!question]- Pista 2 — ¿qué estructura usar?
> `bt(inicio, camino)`: si `camino.length === k`, guarda una copia.

> [!question]- Pista 3 — el algoritmo
> Recorre `i` desde `inicio` hasta n: `push`, `bt(i + 1)`, `pop`.

> [!warning]- Trampa común
> Guardar `camino` en lugar de `[...camino]`.

> [!success]- Complejidad meta
> Tiempo O(C(n, k)·k), espacio O(k)

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
