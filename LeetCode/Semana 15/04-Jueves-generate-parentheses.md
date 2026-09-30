# Generate Parentheses

[← Anterior: Combinations](../Semana%2015/03-Miercoles-combinations.md) · [Siguiente: Word Search →](../Semana%2015/05-Viernes-word-search.md)

> [!quote] Para darle con todo
> «Me tomó 17 años y 114 días convertirme en un éxito de la noche a la mañana.»
> — *Lionel Messi, ocho veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/generate-parentheses/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Backtracking
- **Semana:** 15 — Backtracking (problema 4 de 5)
- **Día:** [Semana 15 — Jueves](../../Semanas/Semana%2015/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/):** Es Valid Parentheses, pero construyendo en lugar de validar.
- **Repaso del patrón:** [Backtracking](../../Estudio/Articulos/11-Backtracking.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Lleva cuántos `(` y cuántos `)` has usado.

> [!question]- Pista 2 — ¿qué estructura usar?
> Puedes abrir si `abiertos < n`.

> [!question]- Pista 3 — el algoritmo
> Puedes cerrar si `cerrados < abiertos`.

> [!warning]- Trampa común
> Generar todos los strings y validar al final: es mucho más lento.

> [!success]- Complejidad meta
> Tiempo O(4ⁿ/√n), espacio O(n)

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
