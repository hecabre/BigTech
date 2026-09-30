# Top K Frequent Elements

[← Anterior: Longest Substring Without Repeating Characters](../Semana%2020/04-Jueves-longest-substring-without-repeating-characters.md) · [Siguiente: Valid Anagram →](../Semana%2021/01-Lunes-valid-anagram.md)

> [!quote] Para darle con todo
> «Stay hard. No aflojes.»
> — *David Goggins, ex Navy SEAL y ultramaratonista*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/top-k-frequent-elements/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Heap / bucket sort
- **Semana:** 20 — Matrices + repaso bajo presión (semana SAA) (problema 5 de 5)
- **Día:** [Semana 20 — Viernes](../../Semanas/Semana%2020/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Group Anagrams](../Semana%2017/05-Viernes-group-anagrams.md):** Es un `Map` de frecuencias más un heap o cubetas.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cuenta las frecuencias.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cubetas: `buckets[freq] = [nums]`, con índices de 0 a n.

> [!question]- Pista 3 — el algoritmo
> Recorre las cubetas de mayor a menor hasta juntar k.

> [!warning]- Trampa común
> Ordenar todo cuando las cubetas lo resuelven en O(n).

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
