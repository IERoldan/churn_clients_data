# 📊 Análisis de Evasión de Clientes – Telecom X

Este proyecto forma parte del desafío de Alura Latam sobre Ciencia de Datos. El objetivo es analizar los datos de clientes de la empresa **Telecom X**, identificando patrones y factores asociados a la **evasión de clientes** (churn), y proponer estrategias para reducirla.

---

## 🧠 Objetivo

Telecom X enfrenta una alta tasa de cancelaciones de sus servicios. Este análisis busca comprender:

- ¿Qué tipos de clientes tienden a cancelar?
- ¿Qué características están asociadas al churn?
- ¿Cómo se distribuye el churn según diferentes servicios, contratos o gastos?

---

## 📁 Estructura del proyecto

El análisis se desarrolló en un notebook de Colab con las siguientes etapas:

### 1. 📌 Extracción
- Importación de datos desde un archivo JSON.
- Aplanamiento de estructuras anidadas para facilitar su análisis.

### 2. 🔧 Transformación
- Eliminación de duplicados.
- Tratamiento de valores nulos.
- Corrección de tipos de datos.
- Normalización de categorías.
- Creación de la variable `Cuentas_Diarias` a partir del cargo mensual.

### 3. 📊 Análisis Exploratorio (EDA)
- Visualización de la distribución de churn.
- Comparación de churn según tipo de contrato y género.
- Análisis de variables numéricas como `Charges.Monthly` y `tenure`.
- Generación de una matriz de correlación entre variables numéricas.

### 4. 📄 Informe final
- Conclusiones y hallazgos clave.
- Recomendaciones estratégicas para reducir la tasa de churn.
- Insights que pueden alimentar futuros modelos de Machine Learning.

---

## 🛠️ Herramientas utilizadas

- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab

---

## 📌 Principales hallazgos

- Los contratos mensuales tienen una tasa de churn significativamente mayor.
- Clientes con menor tiempo de permanencia tienden a cancelar más.
- Un alto gasto mensual también se asocia a mayores niveles de churn.
- La métrica `Cuentas_Diarias` es útil para visualizar mejor el comportamiento económico del cliente.

---

## 🚀 Recomendaciones

- Promover contratos de largo plazo con beneficios especiales.
- Aplicar estrategias de fidelización a clientes nuevos o con menor permanencia.
- Monitorear proactivamente a clientes con alto gasto mensual.

---

---

## ✅ Estado del proyecto

✔️ Finalizado – Cumple con todas las consignas del desafío de Alura, incluyendo la parte opcional (correlaciones).

---

## 🧑‍💻 Autor

Iván Roldán
---
