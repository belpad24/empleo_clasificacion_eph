# 📊 Clasificación del Estado Laboral con Machine Learning – EPH 2023

Este proyecto forma parte de la evaluación final del curso de Aprendizaje Automático. Tiene como objetivo aplicar técnicas de clasificación para predecir la condición laboral (ocupado/desocupado) de personas en Argentina, utilizando datos reales de la Encuesta Permanente de Hogares (EPH) publicada por el INDEC.

---

## 📌 Objetivo

El proyecto busca predecir si una persona está ocupada o desocupada a partir de variables sociodemográficas como:

- Sexo
- Edad
- Nivel educativo alcanzado
- Categoría ocupacional

---

## 🗂️ Origen de los datos

- Fuente: Encuesta Permanente de Hogares (EPH) – INDEC
- Trimestre utilizado: T4 2023
- Archivos originales: disponibles en la carpeta `data/raw/`
- Dataset procesado: disponible en `data/processed/EPH_T423_filtrado_procesado.csv`

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
- Se utilizó `class_weight='balanced'` para compensar el modelo.
- Las variables edad y nivel educativo mostraron alto peso predictivo.
- Random Forest fue el modelo con mejor desempeño general.

---

## 📁 Estructura del repositorio

![image](https://github.com/user-attachments/assets/8c86780a-9b2b-4955-91d1-f22b6355f6a7)



---

## 🛠️ Herramientas utilizadas

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
---

## 🎥 Presentación

[📹 Link al video explicativo (Drive)](url_del_video)

---

## 🧑‍💻 Autor

- Belen Padron
- Año: 2025
- Materia Aprendizaje Automatico
- Profesor: Mirabetes Martin
