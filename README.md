# 🍻 Clustering y Segmentación de Mercado Retail (Machine Learning)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Contexto del Negocio
El objetivo central de este proyecto fue descifrar patrones ocultos de consumo en el sector de bebidas. El reto consistía en segmentar el comportamiento de compra para personalizar estrategias comerciales y optimizar una cartera que representa **$28.6M en ventas y un 56% de MarketShare** distribuidos en 11 marcas a través de 203 locales.

## 📊 Datos y Metodología
Se procesó un dataset robusto de más de **226,000 registros transaccionales**. 
* **Variables analizadas:** Marca, empaque, segmento, regional, unidades, hectolitros (hls) y valor comercial.
* **Modelo:** Se implementó el algoritmo de aprendizaje no supervisado **K-Means**, el cual agrupó los datos de manera óptima en 6 clústeres distintos tras una rigurosa limpieza y escalado de las variables continuas.

## 💡 Hallazgos y Estrategia Comercial (Insights)
El modelo logró agrupar a los clientes en perfiles de negocio altamente diferenciados, traduciendo datos matemáticos en estrategias accionables:

1. **Cluster 1 (Compradores intensivos no fidelizados):** Alto volumen (1577 hls, $452k ventas), bajo ratio de afinidad a la marca (0.38). Se propone implementar planes de fidelización agresiva.
2. **Cluster 2 (Clientes premium tradicionales):** Grupo de mayor rentabilidad (2259 hls, $654k ventas), preferencia por empaques grandes. Se propone un enfoque en mantenimiento de valor y defensa del segmento.
3. **Cluster 4 (Clientes pequeños leales):** Bajo volumen (86 hls, $25k ventas), alta tasa de afinidad de marca (0.48). Se propone el desarrollo de estrategias de incremento de ticket y up-selling.

## 📂 Estructura de este Repositorio
- `/data`: Muestra anonimizada del dataset y diccionario de variables.
- `/notebooks`: Scripts de limpieza de datos (ETL) y entrenamiento del modelo K-Means en Python.
- `/docs`: Presentación Ejecutiva (PDF) con gráficos de dispersión de los centroides y defensa de las estrategias comerciales.
