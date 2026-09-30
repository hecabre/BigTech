# Backspace String Compare

[← Anterior: Remove All Adjacent Duplicates In String](../Semana%2005/02-Martes-remove-all-adjacent-duplicates-in-string.md) · [Siguiente: Make The String Great →](../Semana%2005/04-Jueves-make-the-string-great.md)

> [!quote] Para darle con todo
> «Disciplina es libertad.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/backspace-string-compare/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 05 — Pilas (problema 3 de 5)
- **Día:** [Semana 05 — Miércoles](../../Semanas/Semana%2005/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Remove All Adjacent Duplicates In String](../Semana%2005/02-Martes-remove-all-adjacent-duplicates-in-string.md):** El `#` borra el tope, igual que el par en el problema anterior.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Construye el texto final de cada string y compáralos.

> [!question]- Pista 2 — ¿qué estructura usar?
> `#` es un `pop` (si la pila no está vacía); cualquier otro carácter es un `push`.

> [!question]- Pista 3 — el algoritmo
> Reto opcional: resuélvelo con espacio O(1) recorriendo ambos strings desde el final.

> [!warning]- Trampa común
> Hacer `pop` sobre una pila vacía, como en `"a##c"`.

> [!success]- Complejidad meta
> Tiempo O(n + m), espacio O(n + m)

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
