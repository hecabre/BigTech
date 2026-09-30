# Path Sum

[← Anterior: Symmetric Tree](../Semana%2009/01-Lunes-symmetric-tree.md) · [Siguiente: Diameter of Binary Tree →](../Semana%2009/03-Miercoles-diameter-of-binary-tree.md)

> [!quote] Para darle con todo
> «La mentalidad Mamba no se trata de buscar un resultado; se trata del proceso de llegar a ese resultado.»
> — *Kobe Bryant, The Mamba Mentality*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/path-sum/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 09 — Árboles — DFS (problema 2 de 5)
- **Día:** [Semana 09 — Martes](../../Semanas/Semana%2009/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/):** Es la misma recursión de Maximum Depth, pero restando.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Resta el valor del nodo al objetivo mientras bajas.

> [!question]- Pista 2 — ¿qué estructura usar?
> La condición solo se revisa en una hoja (sin hijos).

> [!question]- Pista 3 — el algoritmo
> `return hasPath(left, t - val) || hasPath(right, t - val)`.

> [!warning]- Trampa común
> Revisar el objetivo en un nodo que no es hoja o en `null`.

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
