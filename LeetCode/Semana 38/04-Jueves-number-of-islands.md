# Number of Islands

[← Anterior: LRU Cache](../Semana%2038/03-Miercoles-lru-cache.md) · [Siguiente: Product of Array Except Self →](../Semana%2038/05-Viernes-product-of-array-except-self.md)

> [!quote] Para darle con todo
> «Las últimas tres o cuatro repeticiones son las que hacen crecer el músculo.»
> — *Arnold Schwarzenegger, Pumping Iron*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/number-of-islands/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Grid DFS
- **Semana:** 38 — Modo entrevista — repaso ligero (problema 4 de 5)
- **Día:** [Semana 38 — Jueves](../../Semanas/Semana%2038/04-Jueves.md)
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
