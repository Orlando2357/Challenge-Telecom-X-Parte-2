# 📊 Telecom X – Análisis y Predicción de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto

La evasión de clientes (Churn) es uno de los principales desafíos en empresas de telecomunicaciones, ya que la pérdida de clientes impacta directamente en los ingresos y en el crecimiento del negocio.

Este proyecto analiza los datos de clientes de **Telecom X** para identificar los factores que influyen en la cancelación del servicio y desarrollar modelos de **Machine Learning capaces de predecir el churn**.  

El objetivo es transformar los datos en **información estratégica** que permita a la empresa anticiparse a las cancelaciones y aplicar acciones de retención más efectivas.

---

## 🎯 Objetivos del Proyecto

- Analizar el comportamiento de los clientes de Telecom X.
- Identificar variables relacionadas con la cancelación del servicio.
- Aplicar técnicas de **preprocesamiento y balanceo de datos**.
- Entrenar y evaluar diferentes **modelos de Machine Learning**.
- Generar **insights y recomendaciones estratégicas** para reducir el churn.

---

## 🗂️ Dataset

El conjunto de datos contiene información sobre clientes de Telecom X, incluyendo:

- Datos demográficos
- Servicios contratados
- Información de facturación
- Tiempo de permanencia
- Método de pago
- Estado de cancelación (Churn)

La variable objetivo del análisis es:

**Churn / Evasion** → indica si el cliente canceló el servicio.

---

## ⚙️ Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando las siguientes herramientas:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 🔄 Metodología del Proyecto

El análisis se realizó siguiendo las principales etapas de un proyecto de ciencia de datos:

### 1. Extracción de Datos
- Importación de datos desde una API en formato JSON.

### 2. Limpieza y Preparación de Datos
- Manejo de valores nulos
- Conversión de tipos de datos
- Codificación de variables categóricas
- Normalización y escalado de variables

### 3. Análisis Exploratorio de Datos (EDA)
- Identificación de patrones relacionados con el churn
- Visualización de relaciones entre variables
- Análisis de correlación

### 4. Manejo de Desbalance de Clases
Se aplicaron diferentes técnicas para equilibrar el dataset:

- **SMOTE**
- **Random Oversampling**
- **Random Undersampling**

### 5. Entrenamiento de Modelos de Machine Learning

Se evaluaron diferentes algoritmos de clasificación:

- **Regresión Logística (Logistic Regression)**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**

### 6. Evaluación de Modelos

Los modelos fueron evaluados utilizando métricas como:

- Accuracy
- Recall
- Precision
- ROC-AUC
- Validación cruzada

---

## 📈 Resultados del Modelo

Los modelos evaluados mostraron un buen equilibrio entre detección de cancelaciones y reducción de errores.

El modelo de **Regresión Logística** destacó por su capacidad para identificar correctamente a los clientes que cancelan el servicio, logrando detectar aproximadamente **60% de las cancelaciones reales**.

Esto permite implementar estrategias de retención dirigidas a los clientes con mayor riesgo de abandono.

---

## 🔍 Principales Insights del Análisis

A partir del análisis exploratorio se identificaron varios factores asociados al churn:

- Los **clientes con contratos mensuales** presentan mayor probabilidad de cancelar el servicio.
- Los **clientes nuevos** tienden a abandonar la empresa con mayor frecuencia.
- Los **cargos mensuales más altos** aumentan la probabilidad de cancelación.
- Los **clientes con mayor antigüedad y contratos largos** presentan menor tasa de churn.

---

## 💡 Recomendaciones Estratégicas

Basado en los resultados del análisis, se sugieren las siguientes acciones para Telecom X:

- Incentivar contratos de **mayor duración** mediante descuentos o beneficios.
- Implementar **programas de fidelización para clientes nuevos**.
- Analizar los **planes con cargos mensuales elevados**.
- Identificar clientes con riesgo de churn para aplicar **estrategias de retención personalizadas**.
- Desarrollar sistemas de **alerta temprana basados en modelos predictivos**.

---

## 📂 Estructura del Proyecto

```
TelecomX-Churn-Analysis
│
├── TelecomX_LATAM_Parte_II.ipynb
├── datos_tratados.cvs
├── README.md
```

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
```

2. Abrir el notebook en **Jupyter Notebook o Google Colab**

3. Cargar el archvo **datos_tratados.cvs.**

4. Ejecutar las celdas paso a paso para reproducir el análisis.

---

## 👨‍💻 Autor

Proyecto desarrollado como parte del **Challenge de Data Science** enfocado en el análisis y predicción de evasión de clientes en empresas de telecomunicaciones.
