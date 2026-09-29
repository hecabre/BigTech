# Product of Array Except Self

[← Anterior: Number of Islands](../Semana%2038/04-Jueves-number-of-islands.md)

> [!quote] Para darle con todo
> «Lo que define a quien es campeón no son sus victorias, sino cómo se recupera cuando cae.»
> — *Serena Williams, 23 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/product-of-array-except-self/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Prefix/suffix
- **Semana:** 38 — Modo entrevista — repaso ligero (problema 5 de 5)
- **Día:** [Semana 38 — Viernes](../../Semanas/Semana%2038/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Find Pivot Index](../Semana%2019/01-Lunes-find-pivot-index.md):** Es Find Pivot Index con productos en lugar de sumas.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> No puedes dividir (piensa en los ceros).

> [!question]- Pista 2 — ¿qué estructura usar?
> Primera pasada: `res[i]` = producto de todo lo que está a la izquierda.

> [!question]- Pista 3 — el algoritmo
> Segunda pasada de derecha a izquierda: multiplica por un acumulado de lo que está a la derecha.

> [!warning]- Trampa común
> Usar división y fallar cuando hay ceros.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(1) extra

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
