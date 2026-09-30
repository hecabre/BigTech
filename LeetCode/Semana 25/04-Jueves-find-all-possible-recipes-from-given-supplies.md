# Find All Possible Recipes from Given Supplies

[← Anterior: All Ancestors of a Node in a Directed Acyclic Graph](../Semana%2025/03-Miercoles-all-ancestors-of-a-node-in-a-directed-acyclic-graph.md) · [Siguiente: Redundant Connection →](../Semana%2025/05-Viernes-redundant-connection.md)

> [!quote] Para darle con todo
> «No puedes subir la escalera del éxito con las manos en los bolsillos.»
> — *Arnold Schwarzenegger, siete veces Mr. Olympia*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Topological sort
- **Semana:** 25 — Orden topológico y Union-Find (problema 4 de 5)
- **Día:** [Semana 25 — Jueves](../../Semanas/Semana%2025/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/):** Es Kahn con nodos que son strings.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Arista: ingrediente → receta.

> [!question]- Pista 2 — ¿qué estructura usar?
> El grado de entrada de una receta es su número de ingredientes.

> [!question]- Pista 3 — el algoritmo
> La cola empieza con los supplies; una receta que llega a grado 0 es posible y entra a la cola.

> [!warning]- Trampa común
> Olvidar que una receta puede ser ingrediente de otra.

> [!success]- Complejidad meta
> Tiempo O(V + E), espacio O(V + E)

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
