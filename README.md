# 🫀 Heart Disease UCI — Análisis Exploratorio de Datos

**Autor:** Gonzalo Emmanuel Garcia  
**LinkedIn:** [gonzalo-garcia-b019a1397](https://www.linkedin.com/in/gonzalo-garcia-b019a1397/)  
**Tecnicatura Superior en IA y Ciencia de Datos — 2do año**

---

## 📋 Descripción

Análisis exploratorio (EDA) del dataset Heart Disease UCI, que contiene datos clínicos de **920 pacientes** provenientes de 4 instituciones médicas: Cleveland, Hungary, Switzerland y VA Long Beach.

El objetivo es identificar patrones y factores asociados a enfermedades cardíacas mediante estadísticas descriptivas y visualizaciones.

---

## 🎯 Preguntas de Análisis

- ¿Qué factores clínicos se asocian a niveles más altos de colesterol?
- ¿Existen diferencias significativas entre géneros?
- ¿Qué relación hay entre el resultado del estudio thal y los síntomas del paciente?
- ¿Cómo se comporta el segmento ST (slope/oldpeak) en pacientes con angina?

---

## 🔍 Principales Hallazgos

- 🫀 Pacientes con **hipertrofia del ventrículo izquierdo** presentan el mayor promedio de colesterol (**238 mg/dl**)
- 👩 Las **mujeres** tienen mayor promedio de colesterol que los hombres (**241 vs 187 mg/dl**), a pesar de ser minoría en el dataset
- ⚡ El **65% de los pacientes con downsloping** presentan angina inducida por ejercicio, con el mayor promedio de oldpeak (**2.15**)
- 🔴 La mayoría de pacientes con **isquemia** (thal = reversable defect) son **asintomáticos** — hallazgo clínicamente relevante ya que no presentan dolor en el pecho
- 📈 Los pacientes de **67 años** presentan el promedio más alto de colesterol en sangre (**254 mg/dl**)

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Estructura del Repositorio

```
heart-disease-analysis/
│
├── heart_disease_analysis.ipynb   # Notebook con el análisis completo
├── heart_disease_uci.csv          # Dataset original
├── requirements.txt               # Librerías necesarias
└── README.md                      # Este archivo
```

---

## 📦 Dataset

[Heart Disease UCI — Kaggle](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

**Variables principales:** age, sex, cp, trestbps, chol, restecg, thalach, exang, oldpeak, slope, ca, thal, num

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Instalar dependencias: `pip install -r requirements.txt`
3. Abrir `heart_disease_analysis.ipynb` en Jupyter Notebook

---

*Proyecto desarrollado como parte de mi portfolio en Data Analytics*
