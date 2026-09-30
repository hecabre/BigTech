# Make The String Great

[← Anterior: Backspace String Compare](../Semana%2005/03-Miercoles-backspace-string-compare.md) · [Siguiente: Evaluate Reverse Polish Notation →](../Semana%2005/05-Viernes-evaluate-reverse-polish-notation.md)

> [!quote] Para darle con todo
> «Odié cada minuto del entrenamiento, pero me dije: «No renuncies. Sufre ahora y vive el resto de tu vida como un campeón».»
> — *Muhammad Ali, tricampeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/make-the-string-great/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 05 — Pilas (problema 4 de 5)
- **Día:** [Semana 05 — Jueves](../../Semanas/Semana%2005/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Remove All Adjacent Duplicates In String](../Semana%2005/02-Martes-remove-all-adjacent-duplicates-in-string.md):** Es el mismo esqueleto; solo cambia la condición para borrar.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> ¿Cuándo son «malos» dos caracteres? Cuando son la misma letra con distinto caso.

> [!question]- Pista 2 — ¿qué estructura usar?
> Compara `a !== b && a.toLowerCase() === b.toLowerCase()`.

> [!question]- Pista 3 — el algoritmo
> Si el tope y el actual son malos, `pop`; si no, `push`.

> [!warning]- Trampa común
> Comparar solo con `toLowerCase` y borrar también `"aa"`.

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
