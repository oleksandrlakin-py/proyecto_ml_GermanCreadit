# Proyecto Machine Learning - Predicción de Riesgo Crediticio

Este proyecto se centra en la **predicción de riesgo crediticio** utilizando el dataset **German Credit** (OpenML).  
El objetivo es clasificar a los solicitantes de crédito en **buenos** o **malos riesgos**, en base a características financieras y personales.

## Dataset
- Fuente: [OpenML - German Credit](https://www.openml.org/d/31)  
- 1.000 instancias y 20 variables predictoras  
- Variables numéricas y categóricas relacionadas con historial crediticio, edad, estado civil, empleo, etc.  

## Tecnologías utilizadas
- Python (pandas, numpy, scikit-learn)  
- Algoritmos de clasificación: Regresión Logística, Random Forest, Naive Bayes  
- Técnicas de preprocesamiento: codificación de variables, tratamiento de desbalanceo  
- Validación cruzada y búsqueda de hiperparámetros (Grid Search)  

## Resultados principales
- Modelo final: **Random Forest**  
- ROC-AUC en test: **0.781**  
- Reducción de costes de error: **-25%**  
- Mejora significativa en recall de la clase positiva (riesgo alto detectado).  

## Cómo ejecutar
1. Descargar el notebook `proyecto_ml_GermanCredit.ipynb`.  
2. Abrirlo en Jupyter Notebook o Google Colab.  
3. Ejecutar las celdas para reproducir el flujo de trabajo (EDA, entrenamiento, evaluación).  

---

Autor: Oleksandr Lakin
