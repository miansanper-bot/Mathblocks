[README.md](https://github.com/user-attachments/files/26686906/README.md)
# MathBlocks — Composición y descomposición numérica

Módulo de matemáticas visual basado en la metodología de **Numberblocks** (BBC / NCETM), desarrollado para integrarse en **AULA-DUA**.

## Actividades

| Archivo | Descripción |
|---|---|
| `index.html` | Índice del módulo (punto de entrada para AULA-DUA) |
| `actividad1-composicion.html` | Explorador de formas — muestra todas las formas rectangulares de un número |
| `actividad2-descubre.html` | Reto de descubrimiento — el alumno construye cada forma y ve suma, multiplicación y lectura natural |

## Conceptos trabajados

- Arrays y representación rectangular de números
- Suma repetida → multiplicación (relación visual directa)
- Factores y divisibilidad
- Propiedad conmutativa (`3×4 = 4×3`)
- Lectura en lenguaje natural (`3 veces el 4 / el 4, 3 veces`)
- Números primos (solo 2 formas) y números cuadrados
- Rango: números del 1 al 100

## Enfoque pedagógico

Sigue el modelo **CPA** (Concreto → Pictórico → Abstracto) de Jerome Bruner:
1. El bloque visual es el concreto
2. El array animado es el pictórico
3. La ecuación aparece solo después

Alineado con:
- EYFS (Early Years Foundation Stage)
- KS1 (Key Stage 1, Years 1–2)
- Series 3–5 de Numberblocks
- Niveles 3–4 de la progresión MathBlocks

## Accesibilidad (DUA)

- Sin texto obligatorio para interactuar — todo es visual
- Compatible con modo oscuro del sistema operativo
- Tamaño de bloque adaptativo (no se desborda en ningún número)
- Pistas progresivas (no marca solo "incorrecto")
- Sin presión de tiempo

## Uso en AULA-DUA

Enlaza desde tu índice principal a `index.html` de esta carpeta. Cada actividad es un archivo HTML autocontenido, sin dependencias externas.

```html
<a href="mathblocks/index.html">MathBlocks — Composición numérica</a>
```

## Créditos

- Metodología: [Numberblocks](https://www.bbc.co.uk/cbeebies/shows/numberblocks) · BBC / Alphablocks Ltd
- Marco curricular: [NCETM](https://www.ncetm.org.uk/)
- Desarrollo: AULA-DUA
