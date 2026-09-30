# Rotting Oranges

[← Anterior: Merge k Sorted Lists](../Semana%2033/04-Jueves-merge-k-sorted-lists.md) · [Siguiente: Robot Bounded In Circle →](../Semana%2034/01-Lunes-robot-bounded-in-circle.md)

> [!quote] Para darle con todo
> «Sin terquedad, abandonas los experimentos demasiado pronto. Sin flexibilidad, te das de topes contra la pared y no ves otra solución.»
> — *Jeff Bezos, fundador de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/rotting-oranges/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Multi-source BFS
- **Semana:** 33 — Semana de mocks — repaso de clásicos (problema 5 de 5)
- **Día:** [Semana 33 — Viernes](../../Semanas/Semana%2033/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [01 Matrix](../Semana%2014/02-Martes-01-matrix.md):** Es BFS multi-origen contando minutos.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Todas las naranjas podridas empiezan al mismo tiempo: mételas juntas a la cola.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cuenta las naranjas frescas.

> [!question]- Pista 3 — el algoritmo
> Procesa por niveles (cada nivel es un minuto). Si al final quedan frescas, la respuesta es -1.

> [!warning]- Trampa común
> Sumar un minuto de más al procesar el último nivel.

> [!success]- Complejidad meta
> Tiempo O(m·n), espacio O(m·n)

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
