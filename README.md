# Predicción de Calidad de Vino

## Descripción

Este proyecto utiliza un conjunto de datos que contiene información sobre diversas características físico-químicas de muestras de vino tinto y su calidad asociada. Las características incluyen:

- Acidez fija
- Acidez volátil
- Ácido cítrico
- Azúcar residual
- Cloruros
- Dióxido de azufre libre
- Dióxido de azufre total
- Densidad
- pH
- Sulfatos
- Alcohol

La calidad del vino está clasificada en una escala de 0 a 10, donde 0 representa la peor calidad y 10 la mejor.

## Proceso

1. **Análisis Exploratorio de Datos (EDA):** Se realizó un análisis exploratorio para entender mejor la distribución de los datos y las relaciones entre las características.
   
2. **Preprocesamiento:** Los datos fueron agrupados y escalados según su relevancia para mejorar la precisión de los modelos de clasificación.
   
3. **Modelos Probados:** Se entrenaron y compararon tres modelos de clasificación para predecir la calidad del vino:
   - Árboles de Decisión
   - K-Nearest Neighbors (KNN)
   - Regresión Logística

## Resultados

Después de probar varios modelos, se optó por la **Regresión Logística**. Aunque no es el modelo con los mejores resultados en términos absolutos, fue el que ofreció un rendimiento aceptable en comparación con los demás. Entre los tres modelos, la Regresión Logística presentó la mejor combinación de:

- **Exactitud (Accuracy)**
- **Precisión (Precision)**
- **Recall**
