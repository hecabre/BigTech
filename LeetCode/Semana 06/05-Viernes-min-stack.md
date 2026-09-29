# Min Stack

[← Anterior: Simplify Path](../Semana%2006/04-Jueves-simplify-path.md) · [Siguiente: Middle of the Linked List →](../Semana%2007/01-Lunes-middle-of-the-linked-list.md)

> [!quote] Para darle con todo
> «Lo que define a quien es campeón no son sus victorias, sino cómo se recupera cuando cae.»
> — *Serena Williams, 23 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/min-stack/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Stack
- **Semana:** 06 — Pila monotónica (problema 5 de 5)
- **Día:** [Semana 06 — Viernes](../../Semanas/Semana%2006/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/):** Es la pila del calendario de la semana 5. Hoy la reconstruyes sin notas.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Necesitas `getMin` en O(1) incluso después de `pop`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Guarda, junto a cada valor, cuál era el mínimo en ese momento.

> [!question]- Pista 3 — el algoritmo
> Una segunda pila `mins` en la que `push(Math.min(val, minActual))`.

> [!warning]- Trampa común
> Guardar un solo `min` global: se pierde en cuanto haces `pop` del mínimo.

> [!success]- Complejidad meta
> Tiempo O(1) por operación, espacio O(n)

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
