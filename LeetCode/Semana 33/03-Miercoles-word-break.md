# Word Break

[← Anterior: Number of Islands](../Semana%2033/02-Martes-number-of-islands.md) · [Siguiente: Merge k Sorted Lists →](../Semana%2033/04-Jueves-merge-k-sorted-lists.md)

> [!quote] Para darle con todo
> «La frase más peligrosa del idioma es: «Siempre lo hemos hecho así».»
> — *Grace Hopper, pionera de la computación y almirante de la Marina de EE. UU.*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/word-break/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** DP 1D
- **Semana:** 33 — Semana de mocks — repaso de clásicos (problema 3 de 5)
- **Día:** [Semana 33 — Miércoles](../../Semanas/Semana%2033/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Decode Ways](../Semana%2023/04-Jueves-decode-ways.md):** Es la misma DP de prefijos, con palabras de tamaño variable.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i]` = ¿los primeros i caracteres se pueden segmentar?

> [!question]- Pista 2 — ¿qué estructura usar?
> `dp[0] = true`.

> [!question]- Pista 3 — el algoritmo
> `dp[i]` es true si existe j con `dp[j]` y `s.slice(j, i)` en el diccionario (usa un `Set`).

> [!warning]- Trampa común
> Hacer backtracking sin memo: es exponencial.

> [!success]- Complejidad meta
> Tiempo O(n²), espacio O(n)

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
