# Merge Intervals

[← Anterior: Valid Parentheses](../Semana%2038/01-Lunes-valid-parentheses.md) · [Siguiente: LRU Cache →](../Semana%2038/03-Miercoles-lru-cache.md)

> [!quote] Para darle con todo
> «No se trata de qué tan fuerte pegas. Se trata de qué tan fuerte te pueden pegar y seguir avanzando.»
> — *Rocky Balboa, personaje de Sylvester Stallone*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/merge-intervals/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Intervalos
- **Semana:** 38 — Modo entrevista — repaso ligero (problema 2 de 5)
- **Día:** [Semana 38 — Martes](../../Semanas/Semana%2038/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es la plantilla base de intervalos.
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Ordena por el inicio.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si el actual se solapa con el último guardado, extiende su final.

> [!question]- Pista 3 — el algoritmo
> Si no se solapa, agrégalo como un intervalo nuevo.

> [!warning]- Trampa común
> Usar `end = actual.end` en vez de `max(end, actual.end)`.

> [!success]- Complejidad meta
> Tiempo O(n log n), espacio O(n)

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
