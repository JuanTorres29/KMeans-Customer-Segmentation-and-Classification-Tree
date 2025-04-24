# KMeans_Customer_Segmentation_and_Classification-Tree

## Descripción del Proyecto

Este proyecto aplica técnicas de aprendizaje no supervisado y supervisado para realizar una **segmentación de clientes** y una **clasificación predictiva**. Primero se emplea el algoritmo **K-Means** para identificar patrones de comportamiento y formar clústeres significativos entre los clientes. Posteriormente, se entrena un **árbol de decisión** con estos clústeres como etiquetas para poder clasificar a nuevos clientes y anticipar su grupo de pertenencia, contribuyendo a mejorar las estrategias de marketing y fidelización de la empresa.

---

## Objetivos

- Detectar patrones de comportamiento entre los clientes a través de K-Means.
- Generar subgrupos internos dentro de cada clúster principal para un análisis más granular.
- Entrenar un modelo supervisado (árbol de decisión) que permita clasificar nuevos clientes según los segmentos definidos.
- Facilitar la toma de decisiones estratégicas para marketing, diseño de productos, atención al cliente y programas de lealtad.

---

## Técnicas Utilizadas

- **Análisis Exploratorio de Datos (EDA)**
- **Preprocesamiento** de datos numéricos y categóricos (escalado y one-hot encoding)
- **Reducción de dimensionalidad** con PCA (para comparativa)
- **K-Means Clustering**
- **Validación de número óptimo de clústeres** con métodos como el codo, silueta y Calinski-Harabasz
- **Segmentación jerárquica (subclústeres)**
- **Modelado supervisado con árboles de decisión**
- **Optimización de hiperparámetros** con Grid Search
- **Manejo de clases desbalanceadas** usando SMOTE

---

## Dataset

El conjunto de datos incluye más de 1.8 millones de observaciones y 13 variables que capturan:

- Datos demográficos: edad, ingresos
- Comportamiento de compra: frecuencia, valor promedio, días desde última compra
- Variables categóricas: dispositivo, método de pago, fuente de tráfico, tipo de producto
- Engagement: satisfacción y participación en programas de lealtad

---

## Resultados

- Se identificaron **2 clústeres principales**:
  - **Cluster 0**: Compradores jóvenes, digitales y frecuentes
  - **Cluster 1**: Compradores reflexivos, de alto valor y menos frecuentes
- Se crearon subgrupos internos en cada clúster para una segmentación más detallada.
- El árbol de decisión entrenado mostró **altos niveles de precisión** (>99%) en ambos escenarios: con y sin SMOTE.

---

## 📂 Estructura del Proyecto

```
├── data/                      # Datos originales y procesados
├── notebooks/                # Jupyter Notebooks del análisis y modelado
├── README.md                 # Este archivo
```

---

## 👥 Autores

- Juan Torres  
- Juliana Rubio  
- Neyl Peñuela  

---

¿Quieres que te lo prepare como archivo `README.md` listo para subir?
