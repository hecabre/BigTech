# Longest Repeating Character Replacement

[← Anterior: Range Sum Query 2D - Immutable](../Semana%2019/04-Jueves-range-sum-query-2d-immutable.md) · [Siguiente: Spiral Matrix →](../Semana%2020/01-Lunes-spiral-matrix.md)

> [!quote] Para darle con todo
> «Trabaja duro, diviértete, haz historia.»
> — *Jeff Bezos, lema de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-repeating-character-replacement/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Sliding window
- **Semana:** 19 — Prefix sums + sliding window (problema 5 de 5)
- **Día:** [Semana 19 — Viernes](../../Semanas/Semana%2019/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Longest Substring Without Repeating Characters](../Semana%2017/04-Jueves-longest-substring-without-repeating-characters.md):** Es la ventana variable con otra condición de validez.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Una ventana es válida si `tamaño - frecuenciaMax <= k`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Lleva un conteo de 26 letras y `maxFreq`.

> [!question]- Pista 3 — el algoritmo
> Si deja de ser válida, avanza `l` y resta su conteo.

> [!warning]- Trampa común
> Recalcular `maxFreq` en cada paso: no hace falta que baje.

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
