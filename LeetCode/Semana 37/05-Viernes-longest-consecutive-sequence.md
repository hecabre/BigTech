# Longest Consecutive Sequence

[← Anterior: Decode Ways](../Semana%2037/04-Jueves-decode-ways.md) · [Siguiente: Valid Parentheses →](../Semana%2038/01-Lunes-valid-parentheses.md)

> [!quote] Para darle con todo
> «No puedes conectar los puntos mirando hacia adelante; solo puedes conectarlos mirando hacia atrás.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-consecutive-sequence/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Set
- **Semana:** 37 — Eliminar errores repetidos — trampas típicas (problema 5 de 5)
- **Día:** [Semana 37 — Viernes](../../Semanas/Semana%2037/05-Viernes.md)
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
