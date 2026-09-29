# Reverse Linked List

[← Anterior: Valid Parentheses](../Semana%2016/02-Martes-valid-parentheses.md) · [Siguiente: Maximum Depth of Binary Tree →](../Semana%2016/04-Jueves-maximum-depth-of-binary-tree.md)

> [!quote] Para darle con todo
> «Puedo aceptar el fracaso; todos fallan en algo. Lo que no puedo aceptar es no intentarlo.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/reverse-linked-list/)
- **Dificultad:** Easy
- **Tipo:** Repaso
- **Patrón:** Linked list
- **Semana:** 16 — Semana ligera — repaso de fundamentos (problema 3 de 5)
- **Día:** [Semana 16 — Miércoles](../../Semanas/Semana%2016/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es la base de todas las listas enlazadas.
- **Repaso del patrón:** [Listas enlazadas](../../Estudio/Articulos/06-Listas-enlazadas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Necesitas tres referencias: `prev`, `cur` y `next`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Guarda `next = cur.next` antes de cambiar el puntero.

> [!question]- Pista 3 — el algoritmo
> `cur.next = prev`, luego `prev = cur` y `cur = next`. Devuelve `prev`.

> [!warning]- Trampa común
> Perder el resto de la lista por no guardar `next`.

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
