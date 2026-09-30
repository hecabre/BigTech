# LRU Cache

[← Anterior: Design Circular Queue](../Semana%2026/02-Martes-design-circular-queue.md) · [Siguiente: Insert Delete GetRandom O(1) →](../Semana%2026/04-Jueves-insert-delete-getrandom-o1.md)

> [!quote] Para darle con todo
> «Cuando algo es lo suficientemente importante, lo haces aunque las probabilidades no estén a tu favor.»
> — *Elon Musk, fundador de SpaceX*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/lru-cache/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Hash map + lista doble
- **Semana:** 26 — Diseño de estructuras (POO) (problema 3 de 5)
- **Día:** [Semana 26 — Miércoles](../../Semanas/Semana%2026/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

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
