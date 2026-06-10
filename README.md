#Sebastián Celis León
#Proyecto académico – Análisis de datos y Machine Learning


# SaberPro-ScorePrediction

## Descripción del proyecto

Este proyecto realiza un análisis exploratorio y predictivo de los resultados del examen Saber Pro (Colombia), utilizando técnicas de regresión en Machine Learning.

Se evalúan diferentes modelos estadísticos para determinar cuál explica mejor la relación entre variables y se realizan predicciones sobre el comportamiento futuro de los puntajes.

---

## Objetivos

- Unificar bases de datos de varios años del examen Saber Pro.
- Analizar la relación entre el puntaje global y el módulo de razonamiento cuantitativo.
- Comparar modelos de regresión:
  - Lineal
  - Polinómica
  - Logarítmica
- Determinar el modelo con mejor desempeño (R²).
- Realizar predicciones de puntajes globales futuros.
- Analizar la evolución del puntaje para el programa de Ingeniería de Sistemas, Telemática y Afines.

---

## Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Estructura del proyecto

```bash
saber-pro-analysis/
│
├── data/
│   ├── Examen_Saber_Pro_Genericas_2021.txt
│   ├── Examen_Saber_Pro_Genericas_2022.txt
│   ├── Examen_Saber_Pro_Genericas_2023.txt
│   └── Examen_Saber_Pro_Genericas_2024.txt
│
├── src/
│   └── main.py
│
├── requirements.txt
├── README.md
└── .gitignore
