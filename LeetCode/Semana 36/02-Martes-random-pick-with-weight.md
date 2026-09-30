# Random Pick with Weight

[← Anterior: Decode String](../Semana%2036/01-Lunes-decode-string.md) · [Siguiente: Accounts Merge →](../Semana%2036/03-Miercoles-accounts-merge.md)

> [!quote] Para darle con todo
> «Todo el mundo tiene un plan hasta que le dan un golpe en la boca.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/random-pick-with-weight/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Prefix sum + binary search
- **Semana:** 36 — Otras empresas — Medium variados (problema 2 de 5)
- **Día:** [Semana 36 — Martes](../../Semanas/Semana%2036/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Search Insert Position](../Semana%2008/01-Lunes-search-insert-position.md):** Es prefix sum más la búsqueda binaria de Search Insert Position.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Arma prefijos: `[1, 3]` para los pesos `[1, 2]`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Genera un aleatorio en `[1, total]`.

> [!question]- Pista 3 — el algoritmo
> Busca con búsqueda binaria el primer prefijo `>= aleatorio`.

> [!warning]- Trampa común
> Errores de ±1 en el rango del aleatorio.

> [!success]- Complejidad meta
> Tiempo O(log n) por pick, espacio O(n)

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
