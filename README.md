# Análisis Vectorial — Geometría Diferencial con Python

Notebook de Jupyter con la resolución de cinco ejercicios de análisis vectorial y geometría diferencial, implementados con NumPy, Matplotlib y SymPy.

## Contenido

| Ejercicio | Descripción |
|-----------|-------------|
| 1 | Representación 3D de la curva paramétrica $\beta(t) = \bigl(\cos\frac{t}{\sqrt{2}},\, \sin\frac{t}{\sqrt{2}},\, \frac{t}{\sqrt{2}}\bigr)$, $t \in [0, 4\pi]$ |
| 2 | Triedro de Frenet (T, N, B), curvatura $\kappa$ y torsión $\tau$ de la curva anterior con SymPy |
| 3 | Representación 3D de la superficie $z = \sin(x+y)$ sobre $[-2\pi, 2\pi]^2$ |
| 4 | Primera y segunda forma fundamental, curvatura de Gauss $K$ y curvatura media $H$ de $\Phi(u,v) = (u^2\cos v,\, u^2 - v^2,\, uv)$ en el punto $(1,1,0)$ |
| 5 | Integral de línea del campo escalar $f(x,y) = x + y$ sobre $\alpha(t) = (2\cos t, 2\sin t, t)$, $t \in [0, \pi]$ |

## Requisitos

```
numpy
matplotlib
sympy
```

Instalación:

```bash
pip install numpy matplotlib sympy
```

## Uso

Abrir el notebook en JupyterLab, Jupyter Notebook o Google Colab y ejecutar las celdas en orden.

```bash
jupyter lab Tarea_Analisis_Vectorial_practica.ipynb
```

## Estructura del notebook

```
Tarea_Analisis_Vectorial_practica.ipynb
├── Ejercicio 1 — Visualización de curva paramétrica 3D
├── Ejercicio 2 — Triedro de Frenet, κ y τ (SymPy)
├── Ejercicio 3 — Visualización de superficie z = sin(x+y)
├── Ejercicio 4 — Formas fundamentales y curvaturas (SymPy)
└── Ejercicio 5 — Integral de línea escalar (SymPy)
```
