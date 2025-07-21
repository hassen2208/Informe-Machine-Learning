# Informe de Machine Learning - Análisis de Depresión

Este repositorio contiene el desarrollo de dos notebooks correspondientes a un análisis aplicado de Machine Learning con el objetivo de predecir la presencia de depresión a partir de características personales, académicas y de salud mental.

## Participantes
- **Anderson Pantoja C.** - 1841610  
- **Miguel Ángel Muñoz Piñeros** - 2274590  
- **Hassen David Ortiz** - 2177273
- **David Urrego Martínez** - 2240407

---

## 📓 Notebook 1: Red Neuronal Multicapa (MLP)
En este primer cuaderno se realiza el entrenamiento de un modelo de red neuronal multicapa utilizando `MLPClassifier` de Scikit-learn.  
Incluye:
- Preprocesamiento de datos.
- Separación entrenamiento/prueba.
- Configuración de parámetros para la red neuronal.
- Análisis de desempeño del modelo.

## 🌳 Notebook 2: Árboles de Decisión
En este segundo cuaderno se implementa un clasificador basado en árboles de decisión.  
Incluye:
- Preprocesamiento mediante `ColumnTransformer`.
- Exploración comparativa de los criterios `gini` y `entropy`.
- Evaluación del efecto de hiperparámetros (`max_depth`, `min_samples_split`, `min_samples_leaf`).
- Visualización de árboles y análisis detallado de los resultados.

---

Este trabajo busca comparar el rendimiento de diferentes enfoques de clasificación aplicados a un conjunto de datos de salud mental, evaluando la influencia del preprocesamiento y la configuración de modelos sobre la precisión final obtenida.
