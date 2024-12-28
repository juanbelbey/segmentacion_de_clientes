 **Segmentación de Clientes Usando Clustering K-Means**  

#### **Descripción General**  
Este proyecto aplica técnicas de clustering, específicamente K-Means, para segmentar clientes en función de sus patrones de uso de tarjetas de crédito. A través del análisis y visualización de los datos, se identifican grupos de clientes distintos, proporcionando información útil para estrategias de marketing dirigidas, mejoras operativas y planes de retención de clientes.  

---

#### **Características Principales**  
- **Análisis Exploratorio de Datos (EDA):**  
  - Gestión de valores faltantes y estandarización de datos para mejorar el rendimiento del clustering.
  - Estadísticas descriptivas y visualizaciones para comprender la distribución de los datos.  
  - Pair plots y mapas de calor para explorar correlaciones y relaciones entre características.  

- **Clustering con K-Means:**  
  - Uso del método del codo (Elbow Method) para determinar el número óptimo de clusters.  
  - Implementación del algoritmo K-Means para agrupar clientes en diferentes segmentos.  
  - Visualización de los clusters mediante gráficos de dispersión para interpretar patrones.  

- **Análisis de Clusters:**  
  - Evaluación de las características de cada cluster mediante estadísticas descriptivas.  
  - Comparación de clusters basada en comportamientos de los clientes (límites de crédito, visitas, llamadas).  

- **Métricas de Evaluación:**  
  - Puntuación de Silhouette para evaluar la calidad de los clusters.  
  - Análisis de Componentes Principales (PCA) para identificar la importancia de cada característica.  

---

#### **Datos del Dataset**  
El dataset incluye información anónima de los clientes, como:  
- **Avg_Credit_Limit:** Límite promedio de crédito por cliente.  
- **Total_Credit_Cards:** Número total de tarjetas de crédito que posee el cliente.  
- **Total_visits_bank:** Frecuencia de visitas al banco.  
- **Total_visits_online:** Frecuencia de interacciones en línea.  
- **Total_calls_made:** Frecuencia de llamadas realizadas al banco.  

---

#### **Tecnologías Utilizadas**  
- **Librerías de Python:**  
  - `pandas`, `numpy`: Manipulación y preprocesamiento de datos.  
  - `matplotlib`, `seaborn`: Visualización de datos.  
  - `scikit-learn`: Algoritmos de clustering y métricas de evaluación.  
- **Algoritmos de Clustering:**  
  - K-Means y DBSCAN para análisis comparativo.  
- **Análisis de Componentes Principales (PCA):**  
  - Explicación de la contribución de varianza por característica. 

---

#### **Resultados e Insights**  
- Se identificaron tres grupos principales de clientes:  
  1. **Clientes con bajo gasto y poca interacción.**  
  2. **Usuarios moderados con actividad equilibrada.**  
  3. **Clientes de alto gasto con necesidades especializadas.**  

- Estos resultados permiten:  
  - Diseñar campañas de marketing dirigidas.  
  - Optimizar la asignación de recursos para clientes de alto valor.  
  - Mejorar el servicio al cliente basado en los patrones de interacción.  


---

#### **Cómo Ejecutarlo**  
1. Clona este repositorio en tu entorno local.  
2. Instala las librerías necesarias con el siguiente comando:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Ejecuta el Notebook o script de Python:  
   ```bash
   jupyter notebook Customer_Segmentation.ipynb
   ```  
4. Visualiza los resultados y revisa los insights en el notebook.  

---

#### **Contribuciones**  
¡Cualquier comentario o contribución es bienvenida! Si tienes sugerencias o ideas adicionales, no dudes en crear un pull request o abrir un issue.  

---
