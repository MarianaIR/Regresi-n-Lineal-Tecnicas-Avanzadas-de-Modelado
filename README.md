# 📈 REGRESIÓN LINEAL: TÉCNICAS AVANZADAS DE MODELADO 

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

Este proyecto es la continuación y profundización del análisis de **Regresión Lineal**, enfocándose en **técnicas avanzadas de modelado** para mejorar el rendimiento predictivo. Se utiliza un *dataset* de ventas y marketing para construir un modelo predictivo que pueda extrapolar el gasto en publicidad.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Preparación de Datos
- **Carga de Datos:** Se utiliza un *dataset* de ventas que contiene información sobre gastos de marketing (`Marketing`), ventas (`Sales`) y otros datos de la empresa.
- **Análisis de Correlación:** Se evalúa la correlación entre la variable dependiente (`Sales`) y las variables explicativas (`Marketing`, etc.) para confirmar la idoneidad del modelo lineal.
- **División de Datos:** Se separa el conjunto de datos en *entrenamiento* y *prueba* (utilizando **80% para entrenamiento** y **20% para prueba**) para validar la generalización del modelo.

### 2️⃣ Modelado Avanzado y Optimización
- **Regresión Lineal Múltiple:** Se implementa un modelo de regresión lineal para predecir las ventas basándose en múltiples variables de marketing.
- **Estimación y Ajuste:** El objetivo es encontrar los **coeficientes** del modelo (`W's` o pesos) que mejor se ajustan a la relación lineal entre las variables.
- **Análisis de Residuos:** Se realiza un análisis de los errores o **residuos** para garantizar que cumplan con la **distribución normal**.

### 3️⃣ Evaluación y Previsión de Resultados
- **Métricas de Evaluación:** La performance del modelo se mide utilizando las métricas estándar de regresión:
    * **R² (Coeficiente de Determinación):** Indica la proporción de la varianza en la variable dependiente que es predecible a partir de la variable(s) independiente(s).
    * **Error Cuadrático Medio (ECM o MSE):** Mide el promedio de los errores al cuadrado.
- **Previsión de Datos No Vistos:** Se utiliza el modelo entrenado para realizar predicciones sobre el conjunto de datos de prueba (`Y_test`).
- **Conclusiones del Modelo:** Se analiza el **significado de los coeficientes** obtenidos para entender cómo cada unidad de cambio en el gasto de marketing afecta las ventas.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Pandas**     | Carga y manipulación del DataFrame|
| **NumPy**      | Operaciones numéricas|
| **Scikit-learn**| Implementación del modelo de Regresión Lineal y métricas de evaluación|
| **Seaborn / Matplotlib**| Visualización de datos, análisis de residuos y distribuciones|

---

## 🎯 Objetivo del Proyecto
Aplicar la **Regresión Lineal Múltiple** como una herramienta de Machine Learning para predecir un resultado continuo (Ventas). El proyecto se enfoca en las prácticas avanzadas: **división de datos, evaluación rigurosa (R² y ECM), y el análisis de la normalidad de los residuos**, esenciales para un modelo de regresión robusto.

---

## 📈 Resultados Clave
- Se demuestra cómo la **Regresión Lineal** puede ser una herramienta poderosa para **predecir resultados futuros** (previsión de ventas).
- Se destaca la necesidad de que los **residuos sigan una distribución normal** para validar la robustez del modelo.
- El modelo proporciona **coeficientes interpretables**, que permiten a los equipos de negocio entender el impacto directo de sus gastos de marketing en las ventas.

