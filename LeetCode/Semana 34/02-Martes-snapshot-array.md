# Snapshot Array

[← Anterior: Robot Bounded In Circle](../Semana%2034/01-Lunes-robot-bounded-in-circle.md) · [Siguiente: Minimum Window Substring →](../Semana%2034/03-Miercoles-minimum-window-substring.md)

> [!quote] Para darle con todo
> «El primer principio es no autoengañarte, y la persona más fácil de engañar eres tú.»
> — *Richard Feynman, Nobel de Física*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/snapshot-array/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Diseño + binary search
- **Semana:** 34 — Últimos patrones nuevos (problema 2 de 5)
- **Día:** [Semana 34 — Martes](../../Semanas/Semana%2034/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Time Based Key-Value Store](../Semana%2026/05-Viernes-time-based-key-value-store.md):** Es Time Based Key-Value Store con otro nombre.
- **Repaso del patrón:** [POO y diseño](../../Estudio/Articulos/16-POO-y-SOLID.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Copiar el arreglo en cada `snap` es demasiado caro.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cada índice guarda una lista de `[snapId, valor]`.

> [!question]- Pista 3 — el algoritmo
> `get` hace búsqueda binaria del mayor `snapId <= id`.

> [!warning]- Trampa común
> Copiar el arreglo completo en cada `snap`.

> [!success]- Complejidad meta
> Tiempo O(log s) en `get`, espacio O(n + sets)

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
