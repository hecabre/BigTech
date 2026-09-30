# Most Common Word

[← Anterior: LRU Cache](../Semana%2030/05-Viernes-lru-cache.md) · [Siguiente: Reorder Data in Log Files →](../Semana%2031/02-Martes-reorder-data-in-log-files.md)

> [!quote] Para darle con todo
> «Somos lo que hacemos repetidamente. La excelencia, entonces, no es un acto, sino un hábito.»
> — *Will Durant, historiador, resumiendo a Aristóteles*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/most-common-word/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Hash map
- **Semana:** 31 — Etiquetados frecuentes de Amazon (problema 1 de 5)
- **Día:** [Semana 31 — Lunes](../../Semanas/Semana%2031/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Top K Frequent Words](../Semana%2012/04-Jueves-top-k-frequent-words.md):** Son frecuencias más limpieza de texto.
- **Repaso del patrón:** [Arrays, hash maps y sets](../../Estudio/Articulos/03-Arrays-hash-maps-y-sets.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Pasa todo a minúsculas y reemplaza la puntuación por espacios.

> [!question]- Pista 2 — ¿qué estructura usar?
> Separa con `split(/\s+/)` y filtra las palabras vacías.

> [!question]- Pista 3 — el algoritmo
> Cuenta con un `Map`, ignorando las palabras del `Set` de prohibidas.

> [!warning]- Trampa común
> No limpiar la puntuación pegada a las palabras (`"ball,"`).

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
