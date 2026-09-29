# Valid Parentheses

[← Anterior: Two Sum](../Semana%2016/01-Lunes-two-sum.md) · [Siguiente: Reverse Linked List →](../Semana%2016/03-Miercoles-reverse-linked-list.md)

> [!quote] Para darle con todo
> «El mérito pertenece a quien está realmente en la arena, con la cara manchada de polvo, sudor y sangre.»
> — *Theodore Roosevelt, «El hombre en la arena», 1910*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/valid-parentheses/)
- **Dificultad:** Easy
- **Tipo:** Repaso
- **Patrón:** Stack
- **Semana:** 16 — Semana ligera — repaso de fundamentos (problema 2 de 5)
- **Día:** [Semana 16 — Martes](../../Semanas/Semana%2016/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es la base de todas las pilas del plan.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada cierre tiene que coincidir con la última apertura.

> [!question]- Pista 2 — ¿qué estructura usar?
> Guarda las aperturas en una pila; usa un `Map` de cierre → apertura.

> [!question]- Pista 3 — el algoritmo
> Al final, la pila debe quedar vacía.

> [!warning]- Trampa común
> Olvidar el caso `"("`: se recorre sin errores, pero la pila no queda vacía.

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
