# Top K Frequent Words

[← Anterior: Reorganize String](../Semana%2035/01-Lunes-reorganize-string.md) · [Siguiente: Search Suggestions System →](../Semana%2035/03-Miercoles-search-suggestions-system.md)

> [!quote] Para darle con todo
> «Corres el peligro de vivir una vida tan cómoda y blanda que te mueras sin descubrir tu verdadero potencial.»
> — *David Goggins, Can't Hurt Me*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/top-k-frequent-words/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Heap + Hash map
- **Semana:** 35 — Simulación Amazon — repaso OA (problema 2 de 5)
- **Día:** [Semana 35 — Martes](../../Semanas/Semana%2035/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Top K Frequent Elements](../Semana%2020/05-Viernes-top-k-frequent-elements.md):** Es Top K Frequent Elements con desempate alfabético.
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
