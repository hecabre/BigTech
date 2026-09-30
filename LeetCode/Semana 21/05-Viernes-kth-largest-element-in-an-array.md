# Kth Largest Element in an Array

[← Anterior: Invert Binary Tree](../Semana%2021/04-Jueves-invert-binary-tree.md) · [Siguiente: Fruit Into Baskets →](../Semana%2022/01-Lunes-fruit-into-baskets.md)

> [!quote] Para darle con todo
> «No puedes conectar los puntos mirando hacia adelante; solo puedes conectarlos mirando hacia atrás.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Heap / quickselect
- **Semana:** 21 — Semana de examen SAA — solo repaso (problema 5 de 5)
- **Día:** [Semana 21 — Viernes](../../Semanas/Semana%2021/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Kth Largest Element in a Stream](../Semana%2012/01-Lunes-kth-largest-element-in-a-stream.md):** Es el min-heap de tamaño k de la semana 12.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un min-heap de tamaño k deja el k-ésimo mayor en el tope.

> [!question]- Pista 2 — ¿qué estructura usar?
> `push` y, si el tamaño pasa de k, `pop`.

> [!question]- Pista 3 — el algoritmo
> Reto: quickselect con un promedio de O(n).

> [!warning]- Trampa común
> Ordenar todo y no poder explicar la alternativa.

> [!success]- Complejidad meta
> Tiempo O(n log k), espacio O(k)

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
