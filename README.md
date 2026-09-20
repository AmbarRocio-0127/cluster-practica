# 🤖 Clustering No Supervisado - Bootcamp de IA

Este repositorio contiene los ejercicios y prácticas desarrollados durante el bootcamp de Inteligencia Artificial, enfocados en el aprendizaje automático no supervisado y técnicas de segmentación de datos.

## 🛠️ Contenido y Tecnologías
* **Preprocesamiento:** Estandarización de variables numéricas utilizando `StandardScaler` para asegurar que todas las características tengan el mismo peso en el modelo.
* **Algoritmo Principal:** Implementación de **K-Means** (`n_clusters`, `random_state`, `n_init`) para agrupar los datos de forma automática.
* **Evaluación y Optimización:**
  * **Método del Codo (Elbow Method):** Para determinar el número óptimo de clústeres analizando la inercia.
  * **Coeficiente de Silueta (Silhouette Coefficient):** Métrica para evaluar la calidad, cohesión y separación de los grupos formados (con valores entre -1 y 1).
* **Visualización:** Gráficos personalizados utilizando `Matplotlib` (configuración de dimensiones con `figsize`).
