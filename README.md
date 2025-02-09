# 📊 Netflix Analysis & Prediction

Este repositorio contiene un análisis exploratorio y predictivo sobre películas y series de Netflix, utilizando Python y modelos de machine learning.

📌 Descripción del Proyecto

El objetivo de este proyecto es analizar las características de las películas y series en Netflix, identificar patrones en los datos y construir un modelo de predicción basado en Random Forest para estimar variables clave, como la popularidad de una película.

📂 Estructura del Repositorio

📁 Netflix_Analysis
│── 📁 data               # Datos (no incluidos en el repositorio, disponible en Kaggle)
│── 📁 Graficos           # Visualizaciones generadas
│── 📁 Linkedin Post      # Recursos para compartir en redes
│── 📄 Netflix_Analysis.ipynb  # Notebook con el análisis completo
│── 📄 README.md          # Este archivo

🔗 Dataset

Los datos utilizados en este proyecto provienen de Kaggle. Puedes encontrarlos aquí:
👉 Netflix Movies and TV Shows Dataset

🛠 Herramientas y Tecnologías Utilizadas

✅ Python - Lenguaje de programación principal
✅ Pandas - Manipulación y limpieza de datos
✅ Matplotlib & Seaborn - Visualización de datos
✅ Scikit-Learn - Modelado y optimización de hiperparámetros con Random Forest
✅ Git & GitHub - Control de versiones y almacenamiento del proyecto

🔍 Metodología

Exploración de Datos

Carga y limpieza de datos

Análisis de valores faltantes

Transformación de variables categóricas

Visualización de Datos

Distribución de características principales

Correlaciones entre variables

Importancia de características en Random Forest

Modelado Predictivo

Implementación de un modelo de Random Forest Regressor

Ajuste de hiperparámetros con GridSearchCV y RandomizedSearchCV

Evaluación del modelo con métricas MAE, MSE y R²

Exportación de Resultados

Generación de gráficos

Exportación de datos procesados para Power BI

📈 Principales Hallazgos

El número de votos (vote_count) y el presupuesto (budget) son las variables más influyentes en la predicción de la popularidad de una película.

Las películas con mayor presupuesto tienden a recibir más votos y popularidad.

El género y el país de origen también tienen un impacto en la popularidad.

El modelo de Random Forest optimizado logró un R² de aproximadamente 0.52, lo que indica una moderada capacidad predictiva.

🚀 Cómo Ejecutarlo

Clona este repositorio:

git clone https://github.com/juanfeijoo98/Netflix-Analysis-Predictio.git

Instala las dependencias necesarias:

pip install -r requirements.txt  # (si tienes un archivo de requerimientos)

Abre y ejecuta el notebook Netflix_Analysis.ipynb

🏆 Contribuciones

Si tienes sugerencias o mejoras, siéntete libre de abrir un Issue o hacer un Pull Request. ¡Tu aporte es bienvenido! 😊

📩 Contacto: LinkedIn

