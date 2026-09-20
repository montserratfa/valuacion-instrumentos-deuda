# Valuación de Instrumentos de Deuda

Proyecto desarrollado en Python para la valuación de instrumentos de deuda y el análisis de tasas de interés.

## Descripción

Este proyecto implementa herramientas para la valuación de distintos instrumentos de deuda utilizados en el mercado financiero mexicano.

Incluye cálculos para:

- CETE
- M-BONO
- UDIBONO
- Curvas cupón cero
- Tasas forward

También incorpora funciones de validación de datos, manejo de fechas y días hábiles, interpolación y un menú interactivo para ejecutar las diferentes calculadoras.


## Instrumentos incluidos

### CETE

Cálculo del precio y rendimiento de instrumentos cupón cero.

### M-BONO

Valuación de bonos con cupones considerando sus características y fechas correspondientes.

### UDIBONO

Valuación de UDIBONOS considerando el valor de la UDI, precio limpio, precio sucio, intereses devengados y duración.

## Construcción de curvas

El proyecto incluye la construcción de una curva cupón cero mediante el método de **bootstrapping**.

A partir de la curva obtenida también se calculan **tasas forward**.

Para algunos cálculos numéricos se utiliza el método `fsolve` de `scipy.optimize`.

## Funcionalidades adicionales

El proyecto incluye funciones para:

- Validación de fechas.
- Validación de valores numéricos.
- Identificación de días hábiles.
- Ajuste de fechas.
- Cálculo de fracciones de año.
- Generación de fechas de cupones.
- Interpolación lineal.
- Manejo de errores y entradas inválidas.
- Menú interactivo para acceder a las diferentes calculadoras.

## Herramientas utilizadas

- Python
- NumPy
- SciPy
- Jupyter Notebook

## Estructura del proyecto

```text
valuacion-instrumentos-deuda/
│
├── README.md
└── proyecto_instrumentos_deuda.ipynb
