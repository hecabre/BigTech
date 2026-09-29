# Jump Game II

[← Anterior: Gas Station](../Semana%2018/04-Jueves-gas-station.md) · [Siguiente: Find Pivot Index →](../Semana%2019/01-Lunes-find-pivot-index.md)

> [!quote] Para darle con todo
> «Los campeones siguen jugando hasta que les sale bien.»
> — *Billie Jean King, 39 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/jump-game-ii/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Greedy
- **Semana:** 18 — Intervalos y greedy (problema 5 de 5)
- **Día:** [Semana 18 — Viernes](../../Semanas/Semana%2018/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Jump Game](https://leetcode.com/problems/jump-game/):** Es Jump Game, pero contando saltos por «niveles».
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Piénsalo como un BFS: cada salto abre un rango de posiciones alcanzables.

> [!question]- Pista 2 — ¿qué estructura usar?
> Lleva `finActual` y `masLejos`.

> [!question]- Pista 3 — el algoritmo
> Al llegar a `i === finActual`, suma un salto y haz `finActual = masLejos`.

> [!warning]- Trampa común
> Recorrer hasta `n - 1` inclusive y contar un salto de más.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(1)

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
