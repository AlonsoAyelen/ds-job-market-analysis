# 📊 Data Science Job Market Analysis

## 🧠 Descripción del proyecto

Este proyecto analiza el mercado laboral en Data Science utilizando un dataset de salarios.
El objetivo es identificar patrones salariales y entender cómo influyen variables como:

- nivel de experiencia
- tipo de empleo
- modalidad de trabajo (remoto, híbrido o presencial)
- rol desempeñado

El proyecto forma parte de mi portfolio como **Data Analyst**, con foco en análisis exploratorio,
visualización de datos y storytelling.

---

## 🎯 Objetivos del análisis

- Explorar la distribución de salarios en el mercado de Data Science
- Analizar cómo varía el salario según el nivel de experiencia
- Comparar salarios según tipo de contrato
- Evaluar el impacto del trabajo remoto
- Identificar los roles mejor pagos

---

## 📂 Dataset

- **Fuente:** Dataset público de salarios en Data Science
- **Formato:** CSV
- **Registros:** Posiciones laborales en el área de Data Science
- **Variables principales:**
  - `job_title`
  - `experience_level`
  - `employment_type`
  - `salary_in_usd`
  - `remote_ratio`
  - `work_year`

---

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

## 📊 Análisis realizado

El análisis incluye:

### 🔹 Exploración inicial
- Revisión de estructura del dataset
- Identificación de valores faltantes
- Análisis de roles más frecuentes

### 🔹 Análisis de salarios
- Distribución general de salarios
- Salarios según nivel de experiencia (boxplot)
- Salarios según tipo de empleo
- Salarios según modalidad de trabajo
- Top 10 roles mejor pagos

Cada visualización incluye interpretación e insights en el notebook.

---

## 📈 Principales insights

- El salario aumenta significativamente con el nivel de experiencia.
- Los roles senior y ejecutivos presentan mayor dispersión salarial.
- Las posiciones Full-Time muestran salarios promedio más altos.
- El trabajo remoto ofrece salarios competitivos frente al trabajo presencial.
- Los roles más especializados concentran los salarios más altos.

---

## 📁 Estructura del proyecto

```text
ds-job-market-analysis/
│
├── data/
│   ├── raw/
│   │   └── ds_salaries.csv
│   └── processed/
│
├── notebooks/
│   └── ds_job_market_analysis.ipynb
│
├── README.md
└── .gitignore
