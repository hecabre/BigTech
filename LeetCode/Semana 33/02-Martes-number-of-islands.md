# Number of Islands

[← Anterior: Two Sum](../Semana%2033/01-Lunes-two-sum.md) · [Siguiente: Word Break →](../Semana%2033/03-Miercoles-word-break.md)

> [!quote] Para darle con todo
> «La mentalidad Mamba no se trata de buscar un resultado; se trata del proceso de llegar a ese resultado.»
> — *Kobe Bryant, The Mamba Mentality*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/number-of-islands/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Grid DFS
- **Semana:** 33 — Semana de mocks — repaso de clásicos (problema 2 de 5)
- **Día:** [Semana 33 — Martes](../../Semanas/Semana%2033/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Flood Fill](https://leetcode.com/problems/flood-fill/):** Es Flood Fill repetido por cada isla nueva.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Recorre todas las celdas.

> [!question]- Pista 2 — ¿qué estructura usar?
> Al encontrar un `'1'` no visitado, suma 1 y hunde toda la isla con DFS.

> [!question]- Pista 3 — el algoritmo
> Hundir = cambiar a `'0'` antes de recursar en las 4 direcciones.

> [!warning]- Trampa común
> Comparar con el número `1` cuando el grid tiene strings `'1'`.

> [!success]- Complejidad meta
> Tiempo O(filas·cols), espacio O(filas·cols)

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
