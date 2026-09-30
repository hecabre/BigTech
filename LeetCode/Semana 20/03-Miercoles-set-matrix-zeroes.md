# Set Matrix Zeroes

[← Anterior: Rotate Image](../Semana%2020/02-Martes-rotate-image.md) · [Siguiente: Longest Substring Without Repeating Characters →](../Semana%2020/04-Jueves-longest-substring-without-repeating-characters.md)

> [!quote] Para darle con todo
> «He fallado más de 9,000 tiros en mi carrera. He perdido casi 300 partidos. 26 veces me confiaron el tiro ganador y lo fallé. He fallado una y otra y otra vez en mi vida. Y por eso tengo éxito.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/set-matrix-zeroes/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Matriz
- **Semana:** 20 — Matrices + repaso bajo presión (semana SAA) (problema 3 de 5)
- **Día:** [Semana 20 — Miércoles](../../Semanas/Semana%2020/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Conexión:** Es marcar primero y modificar después.
- **Repaso del patrón:** [Método para resolver problemas](../../Estudio/Articulos/02-Metodo-para-resolver-problemas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si pones ceros mientras recorres, contaminas las celdas que aún no revisas.

> [!question]- Pista 2 — ¿qué estructura usar?
> Primera pasada: guarda qué filas y qué columnas tienen un 0 (dos `Set`).

> [!question]- Pista 3 — el algoritmo
> Segunda pasada: pon en 0. Reto: usa la primera fila y la primera columna como marcadores.

> [!warning]- Trampa común
> Modificar la matriz durante la primera pasada.

> [!success]- Complejidad meta
> Tiempo O(m·n), espacio O(m + n) u O(1) en el reto

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
