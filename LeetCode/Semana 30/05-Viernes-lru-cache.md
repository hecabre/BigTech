# LRU Cache

[← Anterior: Trapping Rain Water](../Semana%2030/04-Jueves-trapping-rain-water.md) · [Siguiente: Most Common Word →](../Semana%2031/01-Lunes-most-common-word.md)

> [!quote] Para darle con todo
> «Lo que define a quien es campeón no son sus victorias, sino cómo se recupera cuando cae.»
> — *Serena Williams, 23 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/lru-cache/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Hash map + lista doble
- **Semana:** 30 — Strings y arrays clásicos de Amazon (problema 5 de 5)
- **Día:** [Semana 30 — Viernes](../../Semanas/Semana%2030/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Design HashMap](../Semana%2026/01-Lunes-design-hashmap.md):** Es un `Map` más una lista doblemente enlazada: tu problema de diseño más preguntado en Amazon.
- **Repaso del patrón:** [POO y diseño](../../Estudio/Articulos/16-POO-y-SOLID.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Necesitas `get` y `put` en O(1) y saber cuál es el menos usado.

> [!question]- Pista 2 — ¿qué estructura usar?
> `Map<key, nodo>` más una lista doble con `head` y `tail` dummy.

> [!question]- Pista 3 — el algoritmo
> Cada acceso mueve el nodo al frente; si se excede la capacidad, borra el anterior a `tail`.

> [!warning]- Trampa común
> Olvidar mover el nodo al frente en `get`.

> [!success]- Complejidad meta
> Tiempo O(1), espacio O(capacidad)

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
