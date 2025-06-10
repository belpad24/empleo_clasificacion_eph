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

empleo_clasificacion_eph/
│
├── data/
│   ├── raw/                  # Datos originales de los 4 trimestres de 2023
│   ├── processed/            # Datos procesados y filtrados (listas para modelado)
│
├── notebooks/
│   ├── eda_preprocesamiento.ipynb        # Limpieza y análisis exploratorio con T1
│   ├── eda_preprocesamiento - copia.ipynb # Limpieza con T4
│   ├── modelado_resultados.ipynb         # Modelado con datos T1
│   ├── modelado_resultados - copia.ipynb # Modelado con datos T4
│
├── reports/
│   ├── entregas_parciales/   # PDFs con entregas del trabajo práctico
│
├── requirements.txt
└── README.md

![image](https://github.com/user-attachments/assets/638a850c-7415-4141-8213-1ee65a48b675)


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
