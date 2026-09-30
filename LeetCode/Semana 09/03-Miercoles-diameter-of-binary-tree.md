# Diameter of Binary Tree

[← Anterior: Path Sum](../Semana%2009/02-Martes-path-sum.md) · [Siguiente: Balanced Binary Tree →](../Semana%2009/04-Jueves-balanced-binary-tree.md)

> [!quote] Para darle con todo
> «La frase más peligrosa del idioma es: «Siempre lo hemos hecho así».»
> — *Grace Hopper, pionera de la computación y almirante de la Marina de EE. UU.*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/diameter-of-binary-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 09 — Árboles — DFS (problema 3 de 5)
- **Día:** [Semana 09 — Miércoles](../../Semanas/Semana%2009/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/):** Es Maximum Depth, pero actualizando una respuesta global en cada nodo.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El camino más largo que pasa por un nodo es `altura(izq) + altura(der)`.

> [!question]- Pista 2 — ¿qué estructura usar?
> La función devuelve la altura, pero actualiza una variable `mejor`.

> [!question]- Pista 3 — el algoritmo
> `mejor = max(mejor, L + R)` y `return 1 + max(L, R)`.

> [!warning]- Trampa común
> Suponer que el diámetro siempre pasa por la raíz.

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
