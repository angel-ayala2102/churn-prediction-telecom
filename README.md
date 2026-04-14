# Predicción de Cancelación de Clientes (Churn)

---

## 🤖 Descripción del proyecto
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
git clone https://github.com/angel-ayala2102/churn-prediction-telecom.git

2. Instalar dependencias:
pip install -r requirements.txt

3. Abrir el notebook:
jupyter notebook churn_prediction.ipynb

4. Ejecutar todas las celdas para reproducir el análisis y los modelos

---

## 🧑‍💻 Autor

**Ángel Luis Ayala Guzmán** – Data Analyst | Aspiring Data Scientist

🌐 [Portafolio](https://tu-portfolio.com) · [LinkedIn](https://www.linkedin.com/in/angel-luis-ayala) · ✉️ ayala.luis2102@gmail.com
