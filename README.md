# 📉 Predicción de Cancelación de Clientes (Churn)
🇲🇽 Español | 🇺🇸 English

---

## 🇪🇸 Español

Proyecto de machine learning enfocado en predecir la cancelación de clientes en una empresa de telecomunicaciones.  
El objetivo es identificar clientes con alta probabilidad de churn para apoyar estrategias de retención basadas en datos.

---

## 📋 Descripción del problema
La cancelación de clientes representa una pérdida directa de ingresos.  
Retener clientes existentes suele ser más rentable que adquirir nuevos.

El reto consiste en predecir qué clientes tienen mayor probabilidad de cancelar el servicio utilizando datos históricos.

---

## 🔄 Pipeline del modelo

Datos → Limpieza → EDA → Feature Engineering → Modelos → Evaluación → Selección → Insights

---

## 🔄 Pipeline de Machine Learning
Se desarrolló un pipeline de machine learning para procesar datos, entrenar modelos y seleccionar la mejor solución predictiva:

| Etapa | Descripción |
|------|------------|
| Limpieza de datos | Corrección de tipos, manejo de valores nulos |
| Análisis exploratorio (EDA) | Identificación de patrones y relaciones con churn |
| Ingeniería de características | Creación y selección de variables relevantes |
| Modelado | Entrenamiento de múltiples modelos de clasificación |
| Evaluación | Evaluación y comparación de modelos usando ROC-AUC |
| Selección final | Elección del mejor modelo (CatBoost) |

---

## 🤖 Modelos evaluados

Se evaluaron los siguientes modelos de clasificación:

- Regresión Logística  
- Árbol de decisión  
- Random Forest  
- Gradient Boosting (Scikit-learn)  
- K-Nearest Neighbors (KNN)  
- XGBoost  
- LightGBM  
- CatBoost

---

## 📈 Resultados

### 🏆 Modelo seleccionado
CatBoost

### 📊 Métrica principal

| Métrica | Valor |
|--------|------|
| ROC-AUC | 0.94 |

---

## 🔍 Insights clave

- Los clientes con contratos mensuales presentan mayor probabilidad de churn en comparación con contratos de largo plazo  
- Los clientes con menor antigüedad tienen mayor riesgo de cancelar el servicio  
- Un menor número de servicios contratados se asocia con mayor probabilidad de churn  
- Clientes con cargos mensuales más altos tienden a presentar mayor tasa de cancelación  

---

## 💡 Impacto

Este modelo permite:

- Identificar clientes con alto riesgo de cancelación  
- Priorizar estrategias de retención de manera proactiva  
- Diseñar ofertas personalizadas basadas en comportamiento  
- Apoyar la toma de decisiones basada en datos  

---

## 🛠️ Tecnologías utilizadas

- **Python** – lenguaje principal  
- **Pandas & NumPy** – procesamiento y manipulación de datos  
- **Scikit-learn** – modelos base y evaluación  
- **XGBoost** – modelo de boosting evaluado  
- **LightGBM** – modelo de boosting evaluado  
- **CatBoost** – modelo final seleccionado  
- **Matplotlib** – visualización de datos  
- **Seaborn** – visualización exploratoria  
- **Jupyter Notebook** – entorno de desarrollo

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/angel-ayala2102/churn-prediction-telecom.git
```

2. Instalar dependencias:
```bash
pip install -r requirements.txt
```

3. Abrir el notebook:
```bash
jupyter notebook churn_prediction.ipynb
```

4. Ejecutar todas las celdas para reproducir el análisis y los modelos  

---

## 🇺🇸 English

Machine learning project focused on predicting customer churn in a telecommunications company.  
The goal is to identify customers with a high probability of churn to support data-driven retention strategies.

---

## 📋 Problem Description
Customer churn represents a direct loss of revenue.  
Retaining existing customers is usually more cost-effective than acquiring new ones.

The challenge is to predict which customers are most likely to cancel the service using historical data.

---

## 🔄 Model Pipeline

Data → Cleaning → EDA → Feature Engineering → Modeling → Evaluation → Selection → Insights

---

## 🔄 Machine Learning Pipeline
A machine learning pipeline was developed to process data, train models, and select the best predictive solution:

| Stage | Description |
|------|------------|
| Data cleaning | Data type correction and missing value handling |
| Exploratory Data Analysis (EDA) | Identification of patterns and relationships with churn |
| Feature engineering | Creation and selection of relevant variables |
| Modeling | Training multiple classification models |
| Evaluation | Model comparison using ROC-AUC |
| Final selection | Best model selection (CatBoost) |

---

## 🤖 Evaluated Models

The following classification models were evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting (Scikit-learn)  
- K-Nearest Neighbors (KNN)  
- XGBoost  
- LightGBM  
- CatBoost  

---

## 📈 Results

### 🏆 Selected Model
CatBoost

### 📊 Main Metric

| Metric | Value |
|--------|------|
| ROC-AUC | 0.94 |

---

## 🔍 Key Insights

- Customers with monthly contracts have a higher churn probability compared to long-term contracts  
- Customers with lower tenure are more likely to churn  
- Fewer subscribed services are associated with higher churn probability  
- Customers with higher monthly charges tend to show higher churn rates  

---

## 💡 Impact

This model enables:

- Identification of high-risk customers  
- Proactive prioritization of retention strategies  
- Design of personalized offers based on behavior  
- Data-driven decision-making  

---

## 🛠️ Technologies Used

- **Python** – main programming language  
- **Pandas & NumPy** – data processing and manipulation  
- **Scikit-learn** – baseline models and evaluation  
- **XGBoost** – evaluated boosting model  
- **LightGBM** – evaluated boosting model  
- **CatBoost** – final selected model  
- **Matplotlib** – data visualization  
- **Seaborn** – exploratory visualization  
- **Jupyter Notebook** – development environment  

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/angel-ayala2102/churn-prediction-telecom.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook churn_prediction.ipynb
```

4. Run all cells to reproduce the analysis and models  

---

## 🧑‍💻 Author

**Ángel Luis Ayala Guzmán** – Data Analyst | Machine Learning & Customer Behavior  

🌐 [Portfolio](https://angel-ayala-portfolio.my.canva.site/) · [LinkedIn](https://www.linkedin.com/in/angel-luis-ayala) · ✉️ ayala.luis2102@gmail.com
