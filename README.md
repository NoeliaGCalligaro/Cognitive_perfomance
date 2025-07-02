# 🧠 Cognitive Performance Analysis

### 📂 Proyecto: `human_cognitive_performance_clean.csv`

Este proyecto analiza un dataset de comportamiento y rendimiento cognitivo, con el objetivo de identificar qué hábitos y características personales están asociados al mayor desempeño mental.

---

## 📌 Objetivo

- Comparar perfiles entre los usuarios con **mejor rendimiento cognitivo (Top 10%)** y los **usuarios promedio (percentil 45–55)**.
- Determinar cuáles variables influyen más en la agilidad y capacidad cognitiva.
- Explicar el rol del **tiempo de reacción** como métrica clave del rendimiento mental.
- Generar visualizaciones y un informe detallado en formato `.docx`.

---

## 📊 Dataset Incluye:

- `Age`: Edad del usuario  
- `Sleep_Duration`: Horas de sueño diarias  
- `Stress_Level`: Escala de estrés (1–10)  
- `Caffeine_Intake`: Consumo de cafeína (mg/día)  
- `Daily_Screen_Time`: Horas frente a pantallas  
- `Reaction_Time`: Tiempo de reacción en milisegundos  
- `Memory_Test_Score`, `Cognitive_Score`, `AI_Predicted_Score`  
- Variables categóricas: `Gender`, `Diet_Type`, `Exercise_Frequency`

---

---

## 🔍 Análisis Realizado

- EDA Inicial y Final con visualizaciones en tonos verdes
- Comparación Top 10% vs Usuario Promedio
- Descripción e interpretación del tiempo de reacción
- Visualización comparativa de hábitos promedio
- Clustering exploratorio con PCA

---

## 📈 Resultados Clave

El rendimiento cognitivo ideal está asociado a:

- Mayor sueño (~7.5h)
- Menor estrés
- Menor uso de pantallas
- Menor consumo de cafeína
- Tiempo de reacción más bajo (~253ms)
- Ejercicio regular (frecuencia media)

---

## 📄 Archivos Clave

- `Informe_Perfil_Cognitivo_Ideal.docx`: Documento con análisis detallado
- `cognitive_performance.ipynb`: Notebook con visualizaciones
- `README.md`: Este archivo

---

## 📚 Requisitos

- Python 3.8+
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Python-docx

---

## ✅ Cómo Ejecutar

```bash
# Clonar repositorio y ejecutar notebook
git clone https://github.com/tu-usuario/tu-proyecto.git
cd tu-proyecto
jupyter notebook notebooks/cognitive_performance.ipynb
