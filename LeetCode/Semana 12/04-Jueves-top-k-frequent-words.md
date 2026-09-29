# Top K Frequent Words

[← Anterior: K Closest Points to Origin](../Semana%2012/03-Miercoles-k-closest-points-to-origin.md) · [Siguiente: Task Scheduler →](../Semana%2012/05-Viernes-task-scheduler.md)

> [!quote] Para darle con todo
> «Siempre es el Día 1.»
> — *Jeff Bezos, fundador de Amazon, carta a accionistas*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/top-k-frequent-words/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Heap + Hash map
- **Semana:** 12 — Heaps (problema 4 de 5)
- **Día:** [Semana 12 — Jueves](../../Semanas/Semana%2012/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/):** Es Top K Frequent Elements con desempate alfabético.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cuenta las frecuencias con un `Map`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Ordena por frecuencia descendente y, si hay empate, por palabra ascendente.

> [!question]- Pista 3 — el algoritmo
> Toma las primeras k. Después, reescríbelo con un heap.

> [!warning]- Trampa común
> Olvidar el desempate: `a.localeCompare(b)`.

> [!success]- Complejidad meta
> Tiempo O(n log n) ordenando, O(n log k) con heap

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
