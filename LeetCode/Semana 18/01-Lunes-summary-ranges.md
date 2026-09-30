# Summary Ranges

[← Anterior: Group Anagrams](../Semana%2017/05-Viernes-group-anagrams.md) · [Siguiente: Non-overlapping Intervals →](../Semana%2018/02-Martes-non-overlapping-intervals.md)

> [!quote] Para darle con todo
> «The Marathon Continues. El maratón continúa.»
> — *Nipsey Hussle, rapero y empresario*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/summary-ranges/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Intervalos
- **Semana:** 18 — Intervalos y greedy (problema 1 de 5)
- **Día:** [Semana 18 — Lunes](../../Semanas/Semana%2018/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Merge Intervals](https://leetcode.com/problems/merge-intervals/):** Es tu primer problema de construir intervalos.
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un rango continúa mientras `nums[i + 1] === nums[i] + 1`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Guarda el inicio de cada rango.

> [!question]- Pista 3 — el algoritmo
> Al cortarse el rango, agrega `"a->b"`, o `"a"` si `a === b`.

> [!warning]- Trampa común
> Olvidar cerrar el último rango al salir del ciclo.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(1) sin contar la salida

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
