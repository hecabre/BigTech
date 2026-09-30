# Remove All Adjacent Duplicates In String

[← Anterior: Baseball Game](../Semana%2005/01-Lunes-baseball-game.md) · [Siguiente: Backspace String Compare →](../Semana%2005/03-Miercoles-backspace-string-compare.md)

> [!quote] Para darle con todo
> «Todo lo negativo —la presión, los retos— es una oportunidad para elevarme.»
> — *Kobe Bryant, cinco veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 05 — Pilas (problema 2 de 5)
- **Día:** [Semana 05 — Martes](../../Semanas/Semana%2005/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Baseball Game](../Semana%2005/01-Lunes-baseball-game.md):** Sigue siendo una pila, pero ahora de caracteres.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cuando borras un par, los vecinos pueden formar otro par nuevo.

> [!question]- Pista 2 — ¿qué estructura usar?
> Una pila recuerda el último carácter que «sobrevivió».

> [!question]- Pista 3 — el algoritmo
> Si el carácter actual es igual al tope, haz `pop`; si no, `push`. Al final, `join`.

> [!warning]- Trampa común
> Borrar pares con `replace` en un ciclo: funciona, pero es O(n²).

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
