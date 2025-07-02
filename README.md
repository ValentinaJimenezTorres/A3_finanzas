# A3_finanzas
# Tasa de Interés por Riesgo Crediticio

Este repositorio contiene el desarrollo de un modelo para estimar la tasa de interés asociada al riesgo crediticio de nuevos clientes que solicitan un crédito de libre inversión, como parte del curso de Analítica en Finanzas.

### Estructura del proyecto

- `modelo.ipynb`: Notebook principal con exploración, modelado y predicción.
- `grupo4.csv`: Archivo de salida con la tasa de interés de riesgo estimada (`int_rc`) por cliente.

### Enfoque

Se entrenaron varios modelos de regresión sobre datos históricos (`NoPaidPerc` como variable objetivo). Se seleccionó **XGBoost** por su buen desempeño y se ajustó la predicción final sumando el MAE del modelo como factor de seguridad.

### Resultado final

El archivo `grupo4.csv` entrega la tasa de interés por riesgo, lista para ser integrada al cálculo total de interés.

## Autores

Valentina Jimenez, David Diaz, Vaylen Vega, Nicolás Niño
