#  🧪 A/B Testing Analysis for Landing Page Optimization 

Este proyecto presenta un análisis de un experimento A/B Testing realizado sobre dos versiones de una página de aterrizaje (Landing Page A y Landing Page B) de una plataforma de comercio electrónico.

El objetivo fue determinar si la nueva versión de la página (Variante B) mejora el desempeño del negocio en términos de tasa de conversión y gasto promedio por usuario, así como evaluar si el efecto de la nueva versión varía según la fuente de tráfico y el tipo de usuario.

Para validar las diferencias observadas se aplicaron pruebas de hipótesis estadísticas, permitiendo establecer conclusiones con evidencia cuantitativa y formular recomendaciones para la toma de decisiones.

El dataset `landing_experiment.csv` contiene información de usuarios que participaron en el experimento A/B.

## 📂 Contenido del repositorio

- `/Experimento_A_B.ipynb`
  → Notebook principal con limpieza, análisis de hipótesis y conclusiones.
- Dataset →Links a dataset trabajado

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar este notebook de las siguientes formas:

### Opción 1: Abrir en Google Colab
- Ve a Google Colab
- Haz clic en “File” > “Open notebook”
- Selecciona la pestaña “GitHub”
- Pega el enlace de este repositorio
- Abre el archivo .ipynb

### Opción 2: Ejecutar en local

- Clona este repositorio:
git clone [https://github.com/pablojbec/Analisis_Correlacional]
- Accede a la carpeta del proyecto:
- cd repositorio

- Abre Jupyter Notebook:
  - jupyter notebook
  - Selecciona el archivo .ipynb y ejecútalo

## 🔁 Guía de reproducción
Para reproducir los resultados:

- Instala las dependencias necesarias (recomendado usar entorno virtual o Anaconda):
pip install -r requirements.txt
- Asegúrate de tener los datos en la ruta correcta (ver carpeta /data si aplica)
- Ejecuta las celdas del notebook en orden, desde el inicio
- Verifica que no haya errores y que los outputs coincidan con los esperados

## 🧠 Objetivo del análisis

- Comparar la tasa de conversión entre la Página A y la Página B.
- Analizar las diferencias en el gasto promedio de los usuarios que realizaron una conversión.
- Determinar si la fuente de tráfico influye en la probabilidad de conversión.
- Evaluar si el comportamiento de conversión cambia según el tipo de usuario (nuevo o recurrente).
- Validar estadísticamente los resultados mediante pruebas de hipótesis.
- Generar recomendaciones para optimizar la estrategia digital y maximizar el retorno de la inversión.

## 🧩Etapas de análisis realizadas

- Exploración inicial del conjunto de datos.
- Limpieza y validación de registros.
- Verificación de la correcta asignación de usuarios a las variantes A y B.
- Análisis exploratorio de las variables de conversión, gasto y características de los usuarios.
- Cálculo de la tasa de conversión para cada variante.
- Cálculo del gasto promedio por usuario convertido.
- Aplicación de la prueba t de Student para comparar el gasto promedio entre las variantes.
- Aplicación de la prueba Z para dos proporciones para evaluar diferencias en la tasa de conversión.
- Segmentación de los usuarios según la fuente de tráfico.
- Aplicación de la prueba Chi-cuadrado de independencia para evaluar la relación entre la fuente de tráfico y la conversión.
- Segmentación de los usuarios según su tipo (Nuevo o Recurrente).
- Aplicación de la prueba Chi-cuadrado y del Test Exacto de Fisher para analizar la relación entre el tipo de usuario y la conversión.
- Elaboración de visualizaciones para respaldar e interpretar los resultados estadísticos.
- Interpretación de los resultados obtenidos en las pruebas de hipótesis.
- Elaboración de recomendaciones de negocio basadas en la evidencia estadística.
