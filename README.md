# Proyecto de Machine Learning 

Trabajo Práctico Final de la materia Aprendizaje de Máquina. 

Segundo puesto en la convocatoria Premio Estímulo al Trabajo Académico Banco Santander 2025.

Tareas realizadas:
- Identificación de problemática y objetivos del proyecto.
- Obtención, exploración y pre-procesamiento de fuentes datos.
- Selección, entrenamiento, evaluación y ajuste de algoritmos de Machine Learning adecuados al problema.
- Reflexión sobre decisiones tomadas en cada etapa.
- Determinación del modelo más apropiado para la solución.

El trabajo aborda la detección automática de crisis epilépticas a partir de segmentos de electroencefalogramas (EEG) mediante técnicas de Aprendizaje Supervisado. Se utilizó un dataset de 11.500 ejemplos con 178 características por registro, transformando el problema multiclase en una clasificación binaria (crisis vs. no crisis). Debido al desbalance de clases, se prioriza la métrica Recall para minimizar falsos negativos, dado que no detectar una crisis es el error más crítico. 

Se entrenaron y compararon modelos de Regresión Logística, K-Nearest Neighbors y Support Vector Machine (lineal y no lineal). El SVM con kernel RBF obtuvo el mejor desempeño, alcanzando aproximadamente 98% de accuracy y alto recall en la clase positiva. Finalmente, se concluye que este modelo es el más adecuado para una detección rápida y confiable en contextos clínicos.
