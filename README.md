# ⚽ Análisis de la Premier League 1993-2023

## 📋 Descripción
Análisis de más de 30 temporadas de la Premier League con el objetivo 
de identificar qué factores determinan si un equipo termina en los 
primeros puestos o pelea el descenso.

## 🔍 Preguntas del análisis
1. ¿Quién gana más, el local o el visitante?
2. ¿Cómo evolucionaron los goles a lo largo de los años?
3. ¿Qué equipos dominaron históricamente?
4. ¿Qué factores separan a los equipos del Top 4 de los que descienden?

## 🛠️ Herramientas utilizadas
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks
- Power BI
- Tableau Public

## 📁 Estructura del proyecto
premier-league-analysis/
│
├── notebooks/
│   ├── 01_limpieza_datos.ipynb
│   ├── 02_analisis_exploratorio.ipynb
│   ├── 03_visualizaciones.ipynb
│   └── 04_conclusiones.ipynb
│
├── data/
│   ├── matches_limpio.csv
│   └── tabla_posiciones_2023.csv
│
└── dashboard/
     ├── DashBoard_Premier_League_Matches_1993-2023.pbix

## 📊 Dashboard interactivo
👉 [Ver dashboard en Tableau Public](https://public.tableau.com/views/PremierLeagueAnalysis1993-2023/Dashboard1)

## 📌 Hallazgos principales
- El local gana el **46%** de los partidos, casi el doble que el visitante
- El promedio de goles alcanzó su **máximo histórico en 2023** (2.85 por partido)
- Sin público por el **COVID en 2021**, la ventaja del local casi desapareció
- **Manchester United** lidera históricamente en victorias y goles de local
- Los equipos del Top 4 superan los **70 puntos**, mientras los que descienden 
no llegan a **35 puntos**

## 📥 Dataset
Los datos originales se pueden descargar desde 
[Kaggle - Premier League Matches](https://www.kaggle.com/datasets/evangower/premier-league-matches)
