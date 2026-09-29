# Middle of the Linked List

[← Anterior: Min Stack](../Semana%2006/05-Viernes-min-stack.md) · [Siguiente: Linked List Cycle →](../Semana%2007/02-Martes-linked-list-cycle.md)

> [!quote] Para darle con todo
> «Somos lo que hacemos repetidamente. La excelencia, entonces, no es un acto, sino un hábito.»
> — *Will Durant, historiador, resumiendo a Aristóteles*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/middle-of-the-linked-list/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Fast & slow pointers
- **Semana:** 07 — Listas enlazadas (problema 1 de 5)
- **Día:** [Semana 07 — Lunes](../../Semanas/Semana%2007/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/):** Después de Reverse Linked List, este es el segundo truco base: rápido y lento.
- **Repaso del patrón:** [Listas enlazadas](../../Estudio/Articulos/06-Listas-enlazadas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un puntero avanza 1 paso y otro avanza 2.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cuando el rápido llega al final, el lento va a la mitad.

> [!question]- Pista 3 — el algoritmo
> Condición del ciclo: `while (fast && fast.next)`.

> [!warning]- Trampa común
> Con un número par de nodos, el problema pide el segundo de los dos del medio.

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
