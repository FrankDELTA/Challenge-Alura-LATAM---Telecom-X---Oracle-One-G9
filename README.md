# Challenge-Alura-LATAM---Telecom-X---Oracle-One-G9
Parte 1 del Challenge Telecom X
📊 Proyecto Telecom X: Análisis de Evasión de Clientes (Churn)
¡Hola! Soy Francisco, estudiante de Economía y Data Science en Alura/Oracle ONE. Este proyecto es mi análisis sobre la fuga de clientes en una empresa de telecomunicaciones, donde apliqué técnicas de ETL, Análisis Exploratorio (EDA) y Visualización de Datos con Python.

🎯 Objetivo del Proyecto
El problema principal es el Churn (evasión): muchos clientes están dejando el servicio y eso sale caro. Mi objetivo fue limpiar una base de datos compleja (que venía con datos anidados en JSON) y encontrar los motivos reales de por qué la gente se va, para proponer ideas que ayuden a retenerlos.

🛠️ Tecnologías y Herramientas
Para este laburo usé el ecosistema de Data Science en Python:

Pandas: Para toda la manipulación de datos y limpieza de JSON.

Seaborn & Matplotlib: Para crear los gráficos que cuentan la historia de los datos.

Google Colab: Como entorno de desarrollo.

JSON API: Fuente de los datos originales.

🏗️ Estructura del Repositorio
notebooks/: Contiene el archivo .ipynb con todo el proceso detallado.

data/: Información sobre la fuente de datos (API).

README.md: Este archivo que estás leyendo.

🧹 Proceso de Trabajo (ETL & EDA)
1. Extracción y Transformación
La data venía bastante "sucia" con diccionarios adentro de las celdas. Usé json_normalize para aplanar todo. También aproveché mis clases de manipulación de strings para pasar todo al español y que sea más fácil de entender para cualquiera que no hable inglés.

2. Análisis de Datos
Hice un análisis descriptivo para ver promedios de gasto y permanencia. Después, me metí de lleno en los gráficos para cruzar variables:

Evasión por contrato: Descubrí que los contratos mensuales son un peligro; ahí es donde se va casi todo el mundo.

Variables numéricas: Vi que los primeros 6 meses son críticos para la empresa.

📈 Hallazgos Principales (Insights)
La tasa de evasión es del 26.5%.

Los clientes que pagan con Electronic Check se van más rápido.

A mayor cargo mensual, mayor probabilidad de que el cliente busque otra opción.

🚀 Cómo ejecutar el proyecto
Tenés que tener una cuenta de Google.

Abrí el archivo .ipynb en Google Colab.

Dale a "Entorno de ejecución" > "Ejecutar todas".

¡Listo! Los gráficos se generan solos trayendo la data de la API.

🎓 Sobre mí
Soy Francisco, me apasiona cruzar la economía con los datos. Estoy en pleno aprendizaje de Python para Data Science y este es uno de mis primeros desafíos grandes.

LinkedIn: [Tu link de LinkedIn acá]

Twitter/X: [Tu link si tenés]
