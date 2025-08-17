# Challenge-Telecom-X-Pt.2

## Descripción del Proyecto
Este repositorio contiene el desarrollo del **challenge de predicción de cancelación de clientes (churn)** para Telecom X. El objetivo principal fue crear modelos de machine learning capaces de predecir qué clientes tienen mayor probabilidad de cancelar sus servicios, permitiendo a la empresa implementar estrategias de retención efectivas.

## Historia del Desafío
¡Felicidades! 🎉 Tras un análisis exploratorio exitoso de la cancelación de clientes, fui invitado a formar parte del equipo de Machine Learning de Telecom X. Mi misión consistió en construir un pipeline robusto para anticipar la cancelación de clientes y entregar insights estratégicos a la empresa.

## Objetivos
- Preparar los datos para modelado (limpieza, codificación y normalización).
- Realizar análisis de correlación y selección de variables.
- Entrenar y evaluar modelos de clasificación.
- Interpretar resultados e identificar variables que influyen en la cancelación.
- Proponer conclusiones y estrategias de retención basadas en los hallazgos.

## Data & Archivos
- El archivo principal de análisis: `BARS_TelecomX_2.ipynb`
- Resultados de modelos: integrados en el notebook.

## Modelos Implementados
- **Regresión Logística:** modelo lineal interpretable que permite entender la influencia de cada variable.
- **Random Forest:** modelo basado en árboles que captura relaciones no lineales, mostrando mejor rendimiento en métricas de evaluación.

## Resultados Clave
- Random Forest superó a Regresión Logística en todas las métricas (Accuracy, Precision, Recall, F1-score, AUC-ROC).
- Factores más relevantes que influyen en la cancelación:
  - Tiempo de contrato
  - Tipo de contrato
  - Facturación acumulada
  - Servicios adicionales contratados
- Estrategias de retención recomendadas incluyen incentivos a contratos largos, programas de fidelización y promoción de servicios complementarios.

## Tecnologías y Herramientas
- Python 3
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook / Google Colab
