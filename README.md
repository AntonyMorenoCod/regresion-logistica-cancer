# 🧬 Regresión Logística – Diagnóstico de Cáncer de Mama

## 📋 Descripción

Este repositorio contiene el desarrollo completo de un ejercicio aplicado de **Regresión Logística** para clasificación binaria.

El modelo predice si un tumor mamario es **maligno (1)** o **benigno (0)** a partir de características morfológicas extraídas de imágenes digitalizadas de biopsias.

---

## 🎯 Objetivo

Demostrar la comprensión del proceso completo de un problema de clasificación utilizando Regresión Logística:
- Selección y carga del dataset
- Exploración y preparación de los datos
- Entrenamiento del modelo
- Evaluación e interpretación de resultados

---

## 📁 Contenido del repositorio

| Archivo | Descripción |
|--------|-------------|
| `InformeRegresionLogisticaAMoreno.ipynb` | Notebook completo con el ejercicio en Python |
| `README.md` | Documentación del proyecto |

---

## 📊 Dataset

Se utilizó el dataset **Breast Cancer Wisconsin**, incluido en la librería Scikit-learn.

| Atributo | Detalle |
|----------|---------|
| Total de registros | 569 pacientes |
| Variables predictoras | 10 columnas (grupo *mean*) |
| Variable objetivo | diagnóstico: 1 = Maligno / 0 = Benigno |
| Distribución | 357 Malignos – 212 Benignos |
| Valores nulos | 0 |

---

## ⚙️ Tecnologías utilizadas

- 🐍 Python 3
- 📓 Google Colab
- 🐼 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 🤖 Scikit-learn

---

## 📈 Resultados del modelo

| Métrica | Valor |
|---------|-------|
| Accuracy (Exactitud) | **93.86%** |
| Precision (Precisión) | **94.44%** |
| Recall (Sensibilidad) | **95.77%** |
| F1-Score | **95.10%** |

✅ El modelo identificó correctamente el **96% de los tumores malignos**, con solo 3 falsos negativos en 114 casos de prueba.

---

## 🚀 Cómo ejecutar el notebook

1. Abrir [Google Colab](https://colab.research.google.com)
2. Ir a **Archivo → Abrir cuaderno → GitHub**
3. Pegar la URL de este repositorio
4. Ejecutar las celdas en orden con **Shift + Enter**

---

## 👤 Autor

**Ferley Antonio Moreno Cruz**  

Octubre 2026
