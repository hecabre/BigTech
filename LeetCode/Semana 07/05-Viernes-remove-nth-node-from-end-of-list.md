# Remove Nth Node From End of List

[← Anterior: Palindrome Linked List](../Semana%2007/04-Jueves-palindrome-linked-list.md) · [Siguiente: Search Insert Position →](../Semana%2008/01-Lunes-search-insert-position.md)

> [!quote] Para darle con todo
> «Disciplina es hacer lo que odias como si lo amaras.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Two pointers
- **Semana:** 07 — Listas enlazadas (problema 5 de 5)
- **Día:** [Semana 07 — Viernes](../../Semanas/Semana%2007/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Middle of the Linked List](../Semana%2007/01-Lunes-middle-of-the-linked-list.md):** Son dos punteros otra vez, pero ahora con una distancia fija entre ellos.
- **Repaso del patrón:** [Listas enlazadas](../../Estudio/Articulos/06-Listas-enlazadas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Usa un `dummy` antes de la cabeza (puede que haya que borrarla).

> [!question]- Pista 2 — ¿qué estructura usar?
> Adelanta `fast` n + 1 pasos desde `dummy`.

> [!question]- Pista 3 — el algoritmo
> Mueve ambos hasta que `fast` sea `null`: `slow.next` es el nodo que hay que borrar.

> [!warning]- Trampa común
> Adelantar n pasos en lugar de n + 1 y quedar parado sobre el nodo en vez de uno antes.

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
