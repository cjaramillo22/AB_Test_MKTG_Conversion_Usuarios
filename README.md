# Análisis A/B Test de Campañas de Marketing

## 📌 Descripción del proyecto
Este proyecto analiza los resultados de una prueba A/B realizada para evaluar la efectividad de eventos y campañas de marketing sobre el comportamiento de los usuarios.

El objetivo es determinar si la implementación de eventos promocionales tuvo un impacto estadísticamente significativo en la conversión de nuevos usuarios y apoyar la toma de decisiones basada en datos.

---

## 🎯 Objetivos
- Evaluar el impacto de eventos de marketing mediante pruebas A/B.
- Analizar el comportamiento de los usuarios en grupos de control y tratamiento.
- Comparar tasas de conversión entre grupos.
- Determinar si las diferencias observadas son estadísticamente significativas.

---

## 🗂️ Descripción de los datos
El análisis se basa en múltiples datasets relacionados con usuarios, eventos de marketing y participación en experimentos A/B.

**Archivos utilizados:**
- `ab_project_marketing_events_us.csv`: información sobre eventos de marketing.
- `final_ab_new_users_upd_us.csv`: datos de nuevos usuarios.
- `final_ab_participants_upd_us.csv`: usuarios participantes en el experimento.
- `final_ab_events_upd_us.csv`: eventos asociados a los usuarios durante la prueba.

---

## 🧪 Metodología

### 1. Preparación y limpieza de datos
- Revisión de duplicados y valores ausentes.
- Unificación de datasets mediante claves comunes.
- Filtrado de usuarios válidos para el experimento.

### 2. Análisis exploratorio
- Evaluación del tamaño de los grupos A y B.
- Análisis de eventos por usuario.
- Comparación preliminar de métricas clave.

### 3. Prueba A/B
- Cálculo de tasas de conversión para cada grupo.
- Formulación de hipótesis nula y alternativa.
- Aplicación de pruebas estadísticas para evaluar significancia.
- Interpretación de resultados.

---

## 🛠️ Herramientas utilizadas
- Python  
- Pandas  
- Matplotlib / Seaborn  
- SciPy  
- Statsmodels  
- Jupyter Notebook  

---

## 📊 Resultados y conclusiones
El análisis permite evaluar si las campañas de marketing generaron un efecto significativo en la conversión de usuarios.  
Los resultados apoyan la toma de decisiones sobre la efectividad de los eventos y proporcionan una base analítica para futuras estrategias de marketing.

---

## 📁 Estructura del repositorio

├── notebooks/

│ └── Analisis AB Test Marketing.ipynb

├── datasets/

│ ├── ab_project_marketing_events_us.csv

│ ├── final_ab_new_users_upd_us.csv

│ ├── final_ab_participants_upd_us.csv

│ └── final_ab_events_upd_us.csv

└── README.md

---

## 👤 Autor
**Carlos Jaramillo**  
Analista de Datos