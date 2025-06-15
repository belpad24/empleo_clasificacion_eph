# 📊 Clasificación del Estado Laboral con Machine Learning – EPH 2023

Este proyecto forma parte de la evaluación final del curso de Aprendizaje Automático. Tiene como objetivo aplicar técnicas de clasificación para predecir la condición laboral (ocupado/desocupado) de personas en Argentina, utilizando datos reales de la Encuesta Permanente de Hogares (EPH) publicada por el INDEC.

---

## 📌 Objetivo

El proyecto busca predecir si una persona está ocupada o desocupada a partir de variables sociodemográficas como:

- Sexo
- Edad
- Nivel educativo alcanzado
- Categoría ocupacional
- Aglomerado

---

## 🗂️ Origen de los datos

- Fuente: Encuesta Permanente de Hogares (EPH) – INDEC
- Trimestre utilizado: T4 2023
- Archivos originales: disponibles en la carpeta `../data/raw/`
- Dataset procesado: disponible en `../data/processed/datos_limpios.csv`

Se trabajó exclusivamente con personas en estado “ocupado” o “desocupado”, excluyendo inactivos y no clasificados.

---

## 🧪 Metodología

Se realizó:

- Limpieza y filtrado del dataset
- Análisis exploratorio de datos (EDA) con gráficos y estadísticas
- Entrenamiento y evaluación de tres modelos:
  - Regresión Logística
  - Árbol de Decisión
  - Random Forest

Los modelos se evaluaron con métricas de clasificación: accuracy, precision, recall, F1-score, y matriz de confusión.

---

## 📈 Resultados

- Se observó un desbalance entre clases (mayoría de ocupados).
- Las variables edad y nivel educativo mostraron alto peso predictivo.
- Random Forest fue el modelo con mejor desempeño general.
- **Modelo final:** Random Forest
- **Accuracy:** 97.12%
- **F1-Score (desempleado):** 0.67
- **Evaluación regional en Tierra del Fuego:** Accuracy 97.31%

---

## 📁 Estructura del repositorio

![image](https://github.com/user-attachments/assets/44d1f4ad-f1f7-42f9-9cfc-c8cd58c35181)


---
## 📊 Datos

- **Fuente:** INDEC - Encuesta Permanente de Hogares (EPH)
- **Trimestre:** T423 - Cuarto trimestre de 2023
- **Aglomerado específico:** Ushuaia–Río Grande (AGLOMERADO 91)

---
## 🛠️ Herramientas utilizadas

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
---

## 🎥 Presentación

Link a Video desde Drive: (https://drive.google.com/file/d/10zVQE0JEaydl8wAKlEjuGdfmInMRBkLi/view?usp=sharing)

---

## 🧑‍💻 Autor

- Belen Padron
- Año: 2025
- Materia Aprendizaje Automatico
- Profesor: Mirabetes Martin
