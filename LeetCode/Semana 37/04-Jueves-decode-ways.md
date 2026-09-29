# Decode Ways

[← Anterior: Validate Binary Search Tree](../Semana%2037/03-Miercoles-validate-binary-search-tree.md) · [Siguiente: Longest Consecutive Sequence →](../Semana%2037/05-Viernes-longest-consecutive-sequence.md)

> [!quote] Para darle con todo
> «Odié cada minuto del entrenamiento, pero me dije: «No renuncies. Sufre ahora y vive el resto de tu vida como un campeón».»
> — *Muhammad Ali, tricampeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/decode-ways/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** DP 1D
- **Semana:** 37 — Eliminar errores repetidos — trampas típicas (problema 4 de 5)
- **Día:** [Semana 37 — Jueves](../../Semanas/Semana%2037/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/):** Es Climbing Stairs con condiciones: se da un paso de 1 o de 2 dígitos.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i]` = formas de decodificar los primeros i caracteres.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si `s[i-1] !== '0'`, suma `dp[i-1]`.

> [!question]- Pista 3 — el algoritmo
> Si `s[i-2..i-1]` está entre 10 y 26, suma `dp[i-2]`.

> [!warning]- Trampa común
> Aceptar `"06"` como un paso de dos dígitos.

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
