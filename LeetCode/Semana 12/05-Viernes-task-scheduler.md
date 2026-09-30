# Task Scheduler

[← Anterior: Top K Frequent Words](../Semana%2012/04-Jueves-top-k-frequent-words.md) · [Siguiente: Find if Path Exists in Graph →](../Semana%2013/01-Lunes-find-if-path-exists-in-graph.md)

> [!quote] Para darle con todo
> «Stay hard. No aflojes.»
> — *David Goggins, ex Navy SEAL y ultramaratonista*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/task-scheduler/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Heap / greedy
- **Semana:** 12 — Heaps (problema 5 de 5)
- **Día:** [Semana 12 — Viernes](../../Semanas/Semana%2012/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/):** La frecuencia vuelve a decidir la respuesta.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> La tarea más frecuente determina la estructura.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si la máxima frecuencia es `f` y hay `c` tareas con ella: `(f - 1) * (n + 1) + c`.

> [!question]- Pista 3 — el algoritmo
> La respuesta es `max(tasks.length, fórmula)`.

> [!warning]- Trampa común
> No tomar el `max` con `tasks.length`.

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
