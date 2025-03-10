# Modelos de Machine Learning en Scikit-Learn

Este documento contiene una recopilación de los modelos más utilizados en `Scikit-Learn`, organizados por categorías.

---

## 1. Modelos de Regresión

### 🔹 Regresión Lineal (`LinearRegression`)
Modelo simple que asume una relación lineal entre las variables independientes y la variable objetivo.

### 🔹 Regresión Ridge (`Ridge`)
Extensión de la regresión lineal que agrega una penalización L2 para reducir el sobreajuste.

### 🔹 Regresión Lasso (`Lasso`)
Similar a Ridge, pero utiliza una penalización L1, lo que permite seleccionar automáticamente características importantes.

### 🔹 Regresión de Árboles de Decisión (`DecisionTreeRegressor`)
Modelo basado en la creación de árboles de decisión para realizar predicciones de variables continuas.  

📂 En el archivo [01_decision_trees.ipynb](notebooks\01_regresion_arboles_decision.ipynb) se pueden encontrar ejemplos con los cuales se pueden aplicar estos conceptos.

### 🔹 Random Forest Regressor (`RandomForestRegressor`)
Conjunto de múltiples árboles de decisión para mejorar la precisión y reducir el sobreajuste.

---

## 2. Modelos de Clasificación

### 🔹 Regresión Logística (`LogisticRegression`)
Aunque su nombre indica "regresión", es un modelo de clasificación basado en la función sigmoide.

### 🔹 K-Nearest Neighbors (`KNeighborsClassifier`)
Clasifica un punto en función de la clase mayoritaria de sus `k` vecinos más cercanos.

### 🔹 Máquinas de Soporte Vectorial (`SVC`)
Encuentra un hiperplano óptimo que separa las clases en un espacio de alta dimensión.

### 🔹 Árboles de Decisión (`DecisionTreeClassifier`)
Clasifica datos basándose en reglas de decisión en forma de árbol.

### 🔹 Random Forest Classifier (`RandomForestClassifier`)
Conjunto de múltiples árboles de decisión que mejora la robustez y la generalización.

### 🔹 Gradient Boosting (`GradientBoostingClassifier`)
Modelo basado en boosting que optimiza errores iterativamente, muy útil para datos tabulares.

---

## 3. Modelos de Clustering

### 🔹 K-Means (`KMeans`)
Agrupa datos en `k` clusters basándose en la similitud entre puntos.

### 🔹 DBSCAN (`DBSCAN`)
Modelo de clustering basado en densidad, ideal para detectar estructuras arbitrarias.

### 🔹 Mean Shift (`MeanShift`)
Agrupa datos sin necesidad de especificar `k` previamente.

---

## 4. Reducción de Dimensionalidad

### 🔹 Principal Component Analysis (PCA) (`PCA`)
Reducción de dimensionalidad basada en la varianza de los datos.

### 🔹 t-SNE (`TSNE`)
Técnica para visualización de datos en 2D/3D conservando relaciones de distancia.

---

📌 **Scikit-Learn** es una de las librerías más poderosas para Machine Learning en Python. Dominar estos modelos te permitirá abordar una gran variedad de problemas en ciencia de datos.

