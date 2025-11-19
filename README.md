# arbol_decision_para_clasificacion_automoviles
Árbol de decisión para la clasificación de automoviles

#  Proyecto de Clasificación de Automóviles – Árbol de Decisión  
### Machine Learning con Python y Scikit-Learn

Este repositorio contiene un análisis completo basado en el **Car Evaluation Data Set**, un dataset clásico de clasificación utilizado para evaluar modelos supervisados con variables categóricas.

---

##  Descripción del Proyecto

El objetivo del proyecto es **predecir la clase o nivel de aceptación de un automóvil** usando diferentes características relacionadas con costos, seguridad y capacidad.

El trabajo se divide en dos partes:

### 1️ Modelo completo  
Se entrena un **árbol de decisión** utilizando todas las características del dataset:

- buying  
- maint  
- doors  
- persons  
- lug_boot  
- safety  

Esto permite evaluar el rendimiento del modelo completo y analizar la importancia de cada variable para la clasificación.

### 2️ Modelo reducido (2 features)  
A partir de la importancia de variables, se identifica que:

- `persons`  
- `safety`

aportan la mayor proporción de información al modelo.

Se entrena un segundo árbol utilizando únicamente estas dos variables para evaluar si un modelo más simple puede lograr un desempeño comparable.

---

##  Resultados Principales

- El árbol completo logra un desempeño sólido y revela que **safety** y **persons** son las características más relevantes.
- El árbol reducido mantiene un accuracy similar, demostrando que **es posible simplificar el modelo sin perder demasiada precisión**.
- Se incluyen:
  - Matrices de confusión estilizadas  
  - Reportes de clasificación  
  - Gráfico de importancia de variables  
  - Comparación visual entre ambos modelos  

---

##  Tecnologías Utilizadas

- Python 3  
- Pandas  
- Scikit-Learn  
- Seaborn & Matplotlib  
- Category Encoders  

---

## 📁 Contenidos del Repositorio
│── car_evaluation.csv
│── decision_tree_analysis.ipynb
│── README.md



El notebook contiene:

- Exploración y limpieza del dataset  
- Codificación ordinal  
- Entrenamiento de dos modelos  
- Visualizaciones y comparación  
- Conclusiones finales  

---

## 📬 Autor

Proyecto desarrollado por Javier Martínez como parte de mi formación continua en Machine Learning y Ciencia de Datos.

---



