# Insert Delete GetRandom O(1)

[← Anterior: LRU Cache](../Semana%2026/03-Miercoles-lru-cache.md) · [Siguiente: Time Based Key-Value Store →](../Semana%2026/05-Viernes-time-based-key-value-store.md)

> [!quote] Para darle con todo
> «Pies, ¿para qué los quiero si tengo alas pa' volar?»
> — *Frida Kahlo, de su diario, 1953*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/insert-delete-getrandom-o1/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Hash map + array
- **Semana:** 26 — Diseño de estructuras (POO) (problema 4 de 5)
- **Día:** [Semana 26 — Jueves](../../Semanas/Semana%2026/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Design HashMap](../Semana%2026/01-Lunes-design-hashmap.md):** Es un `Map` de valor → índice más un arreglo.
- **Repaso del patrón:** [POO y diseño](../../Estudio/Articulos/16-POO-y-SOLID.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El arreglo te da `getRandom` en O(1).

> [!question]- Pista 2 — ¿qué estructura usar?
> El `Map` te da la posición de cada valor.

> [!question]- Pista 3 — el algoritmo
> Para borrar: intercambia con el último, actualiza su índice y haz `pop`.

> [!warning]- Trampa común
> Hacer `splice` en medio del arreglo: es O(n).

> [!success]- Complejidad meta
> Tiempo O(1) promedio, espacio O(n)

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
