# Copy List with Random Pointer

[← Anterior: Is Graph Bipartite?](../Semana%2027/04-Jueves-is-graph-bipartite.md) · [Siguiente: Reorganize String →](../Semana%2028/01-Lunes-reorganize-string.md)

> [!quote] Para darle con todo
> «Trabaja duro, diviértete, haz historia.»
> — *Jeff Bezos, lema de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/copy-list-with-random-pointer/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Hash map + linked list
- **Semana:** 27 — Mixto árboles y grafos (problema 5 de 5)
- **Día:** [Semana 27 — Viernes](../../Semanas/Semana%2027/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Clone Graph](https://leetcode.com/problems/clone-graph/):** Es Clone Graph en una lista: un `Map` de original → copia.
- **Repaso del patrón:** [Listas enlazadas](../../Estudio/Articulos/06-Listas-enlazadas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Primera pasada: crea todas las copias en un `Map`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Segunda pasada: `copia.next = map.get(orig.next)` y `copia.random = map.get(orig.random)`.

> [!question]- Pista 3 — el algoritmo
> Maneja `null`: `map.get(null)` debe dar `null`.

> [!warning]- Trampa común
> Apuntar a los nodos originales en lugar de a las copias.

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
