# proyecto-final-andino-duarte
Proyecto Final Diplomado Ciencia de Datos - UCOM


# Objetivos
Desarrollar un modelo predictivo utilizando regresión logística que permita clasificar el diagnóstico de tumores de mama como benignos o malignos. Este análisis se basará en las características cuantitativas presentes en el conjunto de datos Breast Cancer Wisconsin (Diagnostic)
El modelo busca proporcionar una herramienta efectiva para la detección temprana del cáncer de mama, contribuyendo al apoyo de decisiones clínicas y a mejorar los resultados del tratamiento. La validación del modelo incluirá la evaluación de métricas como accuracy, precision, recall, F1-score y AUC-ROC, para garantizar su desempeño y confiabilidad en escenarios reales.



# Especificaciones - Cronograma de Actividades:
Día 1: Configuración del Entorno
Objetivo: Preparar el entorno de trabajo.
Tareas:
Instalar las bibliotecas necesarias
Descargar el dataset y confirmar que se carga correctamente en Python.

Día 2: Exploración de Datos
Objetivo: Entender la estructura del dataset.
Tareas:
Inspeccionar columnas, tipos de datos y valores nulos.
Generar estadísticas descriptivas para todas las variables.
Visualizar la distribución de la variable objetivo (diagnosis) con gráficos de barras.

Día 3: Limpieza de Datos, Escalado y Divisiòn
Objetivo: Eliminar columnas innecesarias y preparar los datos.
Tareas:
Eliminar columnas no predictivas (id, Unnamed: 32).
Codificar la variable objetivo (diagnosis) como binaria.
Escalar las características usando StandardScaler.
Dividir los datos en conjuntos de entrenamiento y prueba. (analizar porcentaje)

Día 4: Identificación de Relaciones
Objetivo: Identificar patrones y correlaciones.
Tareas:
Generar un heatmap para analizar correlaciones entre las variables.
Identificar las variables con mayor correlación con la variable objetivo.


Día 5: Entrenamiento del Modelo
Objetivo: Entrenar el modelo de regresión logística.
Tareas:
Configurar y entrenar el modelo inicial usando el conjunto de entrenamiento.
Obtener predicciones para el conjunto de prueba.
Calcular métricas como accuracy, precision, recall y F1-score.
Generar una matriz de confusión.

Día 6: Análisis de Desempeño
Objetivo: Visualizar los resultados.
Tareas:
Calcular y graficar la curva ROC-AUC.
Identificar posibles áreas de mejora (hiperparámetros, features).

Día 7: Ajuste de Hiperparámetros
Objetivo: Mejorar el desempeño del modelo.
Tareas:
Implementar GridSearchCV para encontrar los mejores hiperparámetros.
Evaluar el modelo optimizado en el conjunto de prueba.

Día 7-8: Presentación Final
Objetivo: Comunicar hallazgos.
Tareas:
Preparar un informe con:
Descripción del dataset.
Resultados del modelo.
Insights clave.


Documentar el código y los gráficos generados.
Generar conclusiones sobre el desempeño del modelo y las características más importantes.
