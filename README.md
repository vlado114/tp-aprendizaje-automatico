# Clasificación de expresiones genómicas — Proyecto de Machine Learning

Proyecto de aprendizaje supervisado orientado a predecir el pronóstico de pacientes a partir de la expresión de 200 genes.

## Objetivo
Entrenar y evaluar modelos de clasificación binaria y estimar su capacidad de generalización mediante validación cruzada estratificada y evaluación final sobre un conjunto held-out no visto.

## Metodología
- Separación estratificada de datos  
- Validación cruzada **5-fold**  
- Optimización de hiperparámetros con Randomized Search  
- Modelos evaluados: Árboles, KNN, SVM, Naive Bayes, LDA, Random Forest  

## Mejor modelo
**SVM con kernel RBF**  
Performance estimada: **AUC-ROC ≈ 0.8786** en datos held-out.****
