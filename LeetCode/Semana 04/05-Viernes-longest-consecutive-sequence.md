# Longest Consecutive Sequence

[← Anterior: Is Subsequence](../Semana%2004/04-Jueves-is-subsequence.md) · [Siguiente: Baseball Game →](../Semana%2005/01-Lunes-baseball-game.md)

> [!quote] Para darle con todo
> «Stay hard. No aflojes.»
> — *David Goggins, ex Navy SEAL y ultramaratonista*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-consecutive-sequence/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Set
- **Semana:** 04 — Calentamiento arrays/strings (semana de examen CCP) (problema 5 de 5)
- **Día:** [Semana 04 — Viernes](../../Semanas/Semana%2004/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/):** Es el mismo `Set` de Contains Duplicate, ahora para saber dónde empieza una secuencia.
- **Repaso del patrón:** [Arrays, hash maps y sets](../../Estudio/Articulos/03-Arrays-hash-maps-y-sets.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Mete todos los números en un `Set`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Un número solo inicia una secuencia si `n - 1` NO está en el set.

> [!question]- Pista 3 — el algoritmo
> Desde cada inicio, cuenta hacia arriba (`n + 1`, `n + 2`…) mientras existan en el set.

> [!warning]- Trampa común
> Contar desde todos los números y no solo desde los inicios: se vuelve O(n²).

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
