# 📊 Clasificación del Estado Laboral con Machine Learning – EPH 2023

Este proyecto forma parte de la evaluación final del curso de Aprendizaje Automático. Tiene como objetivo aplicar técnicas de clasificación para predecir la condición laboral (ocupado/desocupado) de personas en Argentina, utilizando datos reales de la Encuesta Permanente de Hogares (EPH) publicada por el INDEC.

---

## 📌 Objetivo

El proyecto busca predecir si una persona está ocupada o desocupada a partir de variables sociodemográficas como:

- Edad
- Nivel educativo alcanzado
- Ingreso familiar
- Aglomerado

---

## 🗂️ Origen de los datos

- Fuente: Encuesta Permanente de Hogares (EPH) – INDEC
- Trimestre utilizado: T4 2023
- Archivos originales: disponibles en la carpeta `../data/raw/`
- Dataset procesado: disponible en `../data/processed/datos_limpios.csv`

Se trabajó exclusivamente con personas en estado “ocupado” o “desocupado”, excluyendo inactivos y no clasificados.

---

## ⚙️ Instalación

1. **Clonar el repositorio:**

git clone https://github.com/belpad24/empleo_clasificacion_eph.git
cd empleo_clasificacion_eph

2. **Crear entorno virtual**

python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows

3. **Instalar las dependencias**

pip install -r requirements.txt


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

- Fuerte desbalance entre clases (mayoría de ocupados).
- Random Forest fue el modelo con mejor desempeño general.
- **Modelo final:** Random Forest
- **Accuracy:** 97.12%
- **F1-Score (desempleado):** 0.67
- **Evaluación regional en Tierra del Fuego:** Accuracy 97.31%

---

## 📁 Estructura del repositorio

![image](https://github.com/user-attachments/assets/30bcb4ed-eae4-410c-903e-4869f530f002)

---
## 🛠️ Herramientas utilizadas

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

---

## 🎥 Presentación

Link a Video desde Drive: https://drive.google.com/file/d/14FstFBhPAVW80XPZNFUhvwel9jhAFb4x/view?usp=sharing

---

## 🧑‍💻 Autor

- Belen Padron
- Año: 2025
- Materia: Aprendizaje Automatico
- Profesor: Mirabetes Martin
