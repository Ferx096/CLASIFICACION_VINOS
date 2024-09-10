# 📊 Predicción de Calidad de Vino 🍷

## Descripción

Este proyecto utiliza un conjunto de datos sobre vinos tintos para predecir su calidad. Las características analizadas incluyen:

- 🔬 **Acidez fija**
- 🌪️ **Acidez volátil**
- 🍋 **Ácido cítrico**
- 🍭 **Azúcar residual**
- 🧂 **Cloruros**
- 💨 **Dióxido de azufre libre**
- 💨 **Dióxido de azufre total**
- 🧪 **Densidad**
- 🌡️ **pH**
- 💧 **Sulfatos**
- 🥃 **Alcohol**

La calidad del vino está clasificada en una escala de 0 a 10, donde 0 representa la peor calidad y 10 la mejor.

## Proceso

1. **🔍 Análisis Exploratorio de Datos (EDA):** Se realizó un análisis para entender la distribución y las relaciones entre las características.
   
2. **🔧 Preprocesamiento:** Los datos fueron agrupados y escalados para mejorar la precisión de los modelos de clasificación.

3. **🧪 Modelos Probados:** Se entrenaron y compararon tres modelos de clasificación para predecir la calidad del vino:
   - 🌳 **Árboles de Decisión**
   - 🧩 **K-Nearest Neighbors (KNN)**
   - 📈 **Regresión Logística**

## Resultados

Después de probar varios modelos, la **Regresión Logística** se destacó como la mejor opción. Aunque no tuvo los mejores resultados absolutos, fue el modelo con mejor rendimiento relativo. La Regresión Logística presentó la mejor combinación de:

- ✅ **Exactitud (Accuracy)**
- 🎯 **Precisión (Precision)**
- 📊 **Recall**

Aunque no es perfecto, fue el modelo menos deficiente para esta tarea en particular.

