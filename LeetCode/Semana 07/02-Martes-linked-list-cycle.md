# Linked List Cycle

[← Anterior: Middle of the Linked List](../Semana%2007/01-Lunes-middle-of-the-linked-list.md) · [Siguiente: Remove Linked List Elements →](../Semana%2007/03-Miercoles-remove-linked-list-elements.md)

> [!quote] Para darle con todo
> «Cuando crees que ya no puedes más, apenas vas al 40%.»
> — *David Goggins, la regla del 40%*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/linked-list-cycle/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Fast & slow pointers
- **Semana:** 07 — Listas enlazadas (problema 2 de 5)
- **Día:** [Semana 07 — Martes](../../Semanas/Semana%2007/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Middle of the Linked List](../Semana%2007/01-Lunes-middle-of-the-linked-list.md):** Son los mismos punteros rápido y lento de ayer.
- **Repaso del patrón:** [Listas enlazadas](../../Estudio/Articulos/06-Listas-enlazadas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Versión fácil: un `Set` de nodos visitados.

> [!question]- Pista 2 — ¿qué estructura usar?
> Versión O(1): si hay ciclo, el rápido termina alcanzando al lento.

> [!question]- Pista 3 — el algoritmo
> Si `fast === slow` hay ciclo; si `fast` llega a `null`, no lo hay.

> [!warning]- Trampa común
> Comparar valores (`slow.val === fast.val`) en lugar de comparar nodos.

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
