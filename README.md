# 📉 Predicción de Cancelación de Clientes en Telecom X

Proyecto realizado como parte de un análisis de churn en Telecom X. En este trabajo se estudian los factores asociados a la cancelación de clientes y se comparan distintos modelos de machine learning para predecir qué usuarios tienen mayor probabilidad de abandonar el servicio.

## 📌 Descripción

### 1. Analizar los datos de clientes
Evaluación de distintas variables relacionadas con la cancelación, incluyendo:
- Tiempo de permanencia del cliente
- Tipo de contrato
- Cargos mensuales y cargos totales
- Método de pago
- Servicios contratados
- Correlación entre variables y churn

### 2. Preparar y modelar los datos
Se aplican distintas técnicas de preprocesamiento y modelado:
- Limpieza y transformación de datos
- Codificación de variables categóricas con One-Hot Encoding
- Balanceo de clases con SMOTE
- Estandarización de variables para modelos sensibles a la escala
- Entrenamiento y evaluación de modelos de clasificación

### 3. Comparar resultados y obtener conclusiones
Se comparan varios modelos para identificar cuál ofrece mejor rendimiento en la predicción de churn:
- Logistic Regression
- k-Nearest Neighbors (kNN)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

## ✅ Requisitos

### Bibliotecas utilizadas

pandas  
matplotlib.pyplot  
seaborn  
scikit-learn  
imblearn  
xgboost

## 📁 Estructura del proyecto

```tap
├── Challenge-BD-Alura-Latam--Telecom-x-2.ipynb       # Notebook principal del análisis
├── datos_telecomX.csv     # Dataset procesado en formato CSV
├── TelecomX_Data.json     # Dataset original en formato JSON
└── README.md              # Descripción del proyecto
```

## 📂 Acceso al proyecto

- [Notebook principal](./Challenge-BD-Alura-Latam--Telecom-x-2.ipynb)
- [Dataset CSV](./datos_telecomX.csv)
- [Dataset JSON](./TelecomX_Data.json)

## 📊 Conclusión

El análisis muestra que variables como la permanencia del cliente, el tipo de contrato y los cargos tienen una relación importante con la cancelación. Después de comparar distintos modelos, los resultados obtenidos fueron similares entre sí, lo que sugiere que modelos más simples como la regresión logística pueden capturar adecuadamente el problema sin necesidad de aumentar demasiado la complejidad.
