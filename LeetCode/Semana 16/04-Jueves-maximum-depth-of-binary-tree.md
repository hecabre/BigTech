# Maximum Depth of Binary Tree

[← Anterior: Reverse Linked List](../Semana%2016/03-Miercoles-reverse-linked-list.md) · [Siguiente: Subsets →](../Semana%2016/05-Viernes-subsets.md)

> [!quote] Para darle con todo
> «Cuando algo sale mal, solo di: «Good». Ahora tienes algo de qué aprender.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
- **Dificultad:** Easy
- **Tipo:** Repaso
- **Patrón:** Tree DFS
- **Semana:** 16 — Semana ligera — repaso de fundamentos (problema 4 de 5)
- **Día:** [Semana 16 — Jueves](../../Semanas/Semana%2016/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es la base de toda la recursión en árboles.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un árbol vacío tiene profundidad 0.

> [!question]- Pista 2 — ¿qué estructura usar?
> La profundidad de un nodo depende de la de sus hijos.

> [!question]- Pista 3 — el algoritmo
> `1 + max(depth(left), depth(right))`.

> [!warning]- Trampa común
> Contar aristas en lugar de nodos.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(h)

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
