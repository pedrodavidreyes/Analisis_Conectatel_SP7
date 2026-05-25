# 📱 Análisis Conéctatel SP7

## 📌 Descripción
Análisis de los datasets de telecomunicaciones de Conectatel con operaciones en México y Colombia, durante el 2024

## 🎯 Objetivo
Identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario. En un reporte final, para entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes).

## 💾 Datasets utilizados
Se exploran, limpian y analizan estas bases de datos para construir una visión clara, confiable y accionable sobre el comportamiento de uso de los clientes y cómo varía entre diferentes grupos de usuarios.
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## 🛠️ Herramientas y tecnologías
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook / Google Colab
- Limpieza y transformación de datos
- Visualización exploratoria

## 🔎 Etapas del análisis realizadas

-  **Paso 1: Cargar y explorar**  
Cargar libreriras y explorar plans, users_latam, usage.	Visión clara de la estructura y tipos de columna de cada dataset.  
-  **Paso 2: Identificación de problemas de calidad de datos**  
Contar nulos, detectar sentinels, revisar fechas fuera de rango.	Lista priorizada de problemas que pueden sesgar decisiones.  
-  **Paso 3: Limpieza básica de datos**  
Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.	Datos consistentes y listos para análisis estadístico.  
-  **Paso 4: Summary statistics de uso por usuario**   Revisar las medidas clave en variables categóricas y numéricas.	Medidas clave (media, mediana, percentiles) que muestran el comportamiento típico y extremo  
-  **Paso 5: Visualización de distribuciones (uso y clientes) y outliers**  
Creación de histogramas y boxplots.	Visualización de sesgos, patrones de usuarios o datos atípicos.  
-  **Paso 6: Segmentación de Clientes**  
Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.	Segmentos accionables que permiten diseñar ofertas, campañas y migraciones de plan.  
-  **Paso 7: Insight Ejecutivo para Stakeholders**  
Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.	Responder a las preguntas del negocio y proponer acciones concretas.**

## 🚀 Cómo ejecutar el notebook
1. Abre el archivo `Analisis_Conectatel_SP7.ipynb` en Google Colab o Jupyter Notebook.
2. Carga los archivos `plans.csv`, `users_latam.csv` y `usage.csv`.
3. Verifica que las rutas de los archivos coincidan con las usadas en el notebook.
4. Ejecuta las celdas en orden, desde la importación de librerías hasta las conclusiones.
5. Revisa las tablas, visualizaciones y hallazgos generados.

## 🔁 Guía de reproducción
Para reproducir el análisis, descarga el repositorio, abre el notebook principal y ejecuta todas las celdas en orden.  
Los datasets deben estar disponibles en la misma carpeta del notebook o en la ruta indicada dentro del código.
