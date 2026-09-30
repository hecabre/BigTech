# Trapping Rain Water

[← Anterior: Search a 2D Matrix II](../Semana%2030/03-Miercoles-search-a-2d-matrix-ii.md) · [Siguiente: LRU Cache →](../Semana%2030/05-Viernes-lru-cache.md)

> [!quote] Para darle con todo
> «Las últimas tres o cuatro repeticiones son las que hacen crecer el músculo.»
> — *Arnold Schwarzenegger, Pumping Iron*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/trapping-rain-water/)
- **Dificultad:** Hard
- **Tipo:** Nuevo
- **Patrón:** Two pointers
- **Semana:** 30 — Strings y arrays clásicos de Amazon (problema 4 de 5)
- **Día:** [Semana 30 — Jueves](../../Semanas/Semana%2030/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!warning] Hard
> Límite de 45 minutos. Si no sale, estudia la solución y reintenta en 7 días. No cuenta como fracaso.

## Por qué este problema

- **Se conecta con [Container With Most Water](../Semana%2002/01-Lunes-container-with-most-water.md):** Usa los dos punteros de Container With Most Water.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El agua sobre i es `min(maxIzq, maxDer) - h[i]`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Versión 1: precalcula arreglos `maxIzq` y `maxDer`.

> [!question]- Pista 3 — el algoritmo
> Versión 2: dos punteros; mueve el lado con el máximo menor y acumula agua ahí.

> [!warning]- Trampa común
> Mover el puntero equivocado: siempre se mueve el lado cuyo máximo es menor.

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
