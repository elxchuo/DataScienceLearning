# Modelos en Scikit-learn

## Modelos Supervisados (Regresión y Clasificación)
Estos modelos necesitan un *target* (`y`) y características (`X`), como en tu caso con los precios de casas (`Price`).

### 1. Regresión (para predecir valores continuos, como precios)
- **LinearRegression**: Regresión lineal simple o múltiple.
  - *Ejemplo*: `Price = b₀ + b₁ * Rooms + b₂ * Landsize`.
- **Ridge**: Regresión lineal con regularización L2 (evita sobreajuste).
- **Lasso**: Regresión lineal con regularización L1 (selecciona características).
- **ElasticNet**: Combina Ridge y Lasso.
- **SGDRegressor**: Regresión con descenso de gradiente estocástico (bueno para datasets grandes).
- **DecisionTreeRegressor**: Árbol de decisión para regresión (el que usaste).
  - *Ejemplo*: 
    ```python
    melbourne_model = DecisionTreeRegressor()