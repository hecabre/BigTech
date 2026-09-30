# Remove Linked List Elements

[← Anterior: Linked List Cycle](../Semana%2007/02-Martes-linked-list-cycle.md) · [Siguiente: Palindrome Linked List →](../Semana%2007/04-Jueves-palindrome-linked-list.md)

> [!quote] Para darle con todo
> «El talento sin trabajo duro no es nada.»
> — *Cristiano Ronaldo, cinco veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/remove-linked-list-elements/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Linked list
- **Semana:** 07 — Listas enlazadas (problema 3 de 5)
- **Día:** [Semana 07 — Miércoles](../../Semanas/Semana%2007/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/):** El nodo `dummy` de Merge Two Sorted Lists vuelve a salvarte.
- **Repaso del patrón:** [Listas enlazadas](../../Estudio/Articulos/06-Listas-enlazadas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> ¿Qué pasa si hay que borrar la cabeza?

> [!question]- Pista 2 — ¿qué estructura usar?
> Crea `dummy.next = head` para que la cabeza no sea un caso especial.

> [!question]- Pista 3 — el algoritmo
> Con `cur` en `dummy`: si `cur.next.val === val`, salta el nodo; si no, avanza.

> [!warning]- Trampa común
> Avanzar `cur` después de borrar y saltarte dos nodos seguidos que había que eliminar.

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
