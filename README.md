# Matemáticas con Python

Aprendizaje de matemáticas usando Python, NumPy, Matplotlib y SymPy.

## Estructura

```
udemy-python-maths/
├── 01_fundamentos/          # Tipos de datos, funciones, numpy básico
│   └── notebooks/
├── 02_algebra/              # Funciones, ecuaciones, polinomios
│   └── notebooks/
│       └── 1_Programando_funciones.ipynb
├── 03_calculo/              # Límites, derivadas, integrales (SymPy)
│   └── notebooks/
│       └── SymPy_LaTeX_Ejemplo.ipynb
├── 04_algebra_lineal/       # Vectores, matrices, transformaciones
│   └── notebooks/
├── 05_estadistica/          # Probabilidad, distribuciones, regresión
│   └── notebooks/
├── 06_matematica_discreta/  # Combinatoria, grafos, lógica
│   └── notebooks/
└── recursos/
    └── latex/               # Plantillas y referencias de LaTeX
        └── Plantilla_LaTeX.md
```

## Configuración del entorno

Requiere [UV](https://docs.astral.sh/uv/).

```bash
# Instalar dependencias y crear entorno virtual
uv sync

# Abrir JupyterLab
uv run jupyter lab
```

## Dependencias principales

| Librería    | Uso                              |
|-------------|----------------------------------|
| numpy       | Cálculo numérico y arrays        |
| matplotlib  | Gráficas y visualizaciones       |
| sympy       | Matemática simbólica             |
| pandas      | Análisis de datos                |
| jupyterlab  | Entorno de notebooks interactivo |
