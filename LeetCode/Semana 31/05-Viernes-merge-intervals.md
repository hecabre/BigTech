# Merge Intervals

[← Anterior: Partition Labels](../Semana%2031/04-Jueves-partition-labels.md) · [Siguiente: All Nodes Distance K in Binary Tree →](../Semana%2032/01-Lunes-all-nodes-distance-k-in-binary-tree.md)

> [!quote] Para darle con todo
> «Disciplina es hacer lo que odias como si lo amaras.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/merge-intervals/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Intervalos
- **Semana:** 31 — Etiquetados frecuentes de Amazon (problema 5 de 5)
- **Día:** [Semana 31 — Viernes](../../Semanas/Semana%2031/05-Viernes.md)
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
