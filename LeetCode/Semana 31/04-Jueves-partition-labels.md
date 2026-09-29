# Partition Labels

[← Anterior: Search Suggestions System](../Semana%2031/03-Miercoles-search-suggestions-system.md) · [Siguiente: Merge Intervals →](../Semana%2031/05-Viernes-merge-intervals.md)

> [!quote] Para darle con todo
> «Me tomó 17 años y 114 días convertirme en un éxito de la noche a la mañana.»
> — *Lionel Messi, ocho veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/partition-labels/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Greedy
- **Semana:** 31 — Etiquetados frecuentes de Amazon (problema 4 de 5)
- **Día:** [Semana 31 — Jueves](../../Semanas/Semana%2031/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Jump Game](https://leetcode.com/problems/jump-game/):** Es greedy de alcance máximo, como Jump Game.
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Guarda la última aparición de cada letra.

> [!question]- Pista 2 — ¿qué estructura usar?
> Recorre extendiendo `fin = max(fin, ultimo[c])`.

> [!question]- Pista 3 — el algoritmo
> Cuando `i === fin`, cierra la partición.

> [!warning]- Trampa común
> Cortar en cuanto una letra deja de repetirse.

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
