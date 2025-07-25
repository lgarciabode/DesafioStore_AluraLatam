# 🛒 Análisis de Ventas – Alura Store (Desafío Data Science)

Este proyecto forma parte del **Challenge de Ciencia de Datos** de Alura Latam, donde se analiza el rendimiento de 4 tiendas de la cadena **Alura Store** para ayudar al Sr. Juan a tomar una decisión importante: **¿Qué tienda debería vender para iniciar un nuevo emprendimiento?**

---

## 📌 Objetivo

Identificar, mediante un análisis integral de datos, la **tienda menos eficiente** para recomendar al Sr. Juan cuál vender. La decisión se fundamenta en múltiples variables: ingresos, calificaciones de clientes, volumen de ventas, categorías más vendidas, costos de envío y distribución geográfica.

---

## 📊 Fuentes de Datos

Los datos provienen de archivos `.csv` disponibles públicamente en el repositorio oficial del desafío. Se cargaron 4 datasets, uno por cada tienda:

- tienda_1.csv  
- tienda_2.csv  
- tienda_3.csv  
- tienda_4.csv

---

## 🧠 Análisis Realizado

El análisis incluye:

- **Ingresos Totales por Tienda**  
- **Categorías de Productos más y menos vendidas**  
- **Productos más y menos vendidos**  
- **Calificación Promedio de los Clientes por Tienda**  
- **Costo de Envío Promedio por Tienda**  
- **Visualización Geográfica de Ventas**
  - Gráficos de dispersión (matplotlib)
  - Mapas de calor (Folium)

---

## 📍 Análisis Geográfico

Para visualizar la distribución de ventas, se realizaron:

- Mapas de dispersión de coordenadas (`lat` y `lon`)
- Heatmaps interactivos por tienda
- Agrupaciones por región geográfica (ingresos y calificaciones promedio)

Esto permitió identificar zonas con mayor concentración de ventas y detectar posibles patrones regionales.

---

## ✅ Recomendación Final

Tras analizar todos los factores, se concluyó que la **Tienda 4** es la **menos eficiente** en términos de:

- **Menor volumen de ventas**
- **Calificación promedio más baja**
- **Categorías con bajo rendimiento**
- **Ingresos menos significativos**

Por lo tanto, se recomienda al Sr. Juan **vender la Tienda 4** para iniciar su nuevo emprendimiento, ya que tiene un bajo impacto estratégico comparado con el resto.

---

## 🛠️ Tecnologías utilizadas

- Python (pandas, numpy, matplotlib, seaborn, folium)
- Google Colab
- Jupyter Notebooks
- Git & GitHub

---

## 📂 Estructura del proyecto

📦alura-store-analysis
┣ 📁visualizaciones
┃ ┗ 📊 gráficos y mapas generados
┣ 📁data
┃ ┣ tienda_1.csv
┃ ┣ tienda_2.csv
┃ ┣ tienda_3.csv
┃ ┗ tienda_4.csv
┣ 📄 análisis_final.ipynb
┗ 📄 README.md


---

## ✨ Créditos

Proyecto desarrollado por **Lucia Garcia Bode** como parte del programa **Formación Oracle Next Education - Data Science - Alura LATAM**.

---

## 💬 Contacto

📧 lugarciabode@email.com  
📸 [Instagram @lubode_](https://instagram.com/lubode_)  
🔗 [LinkedIn @lucia-garcia-bode](https://www.linkedin.com/in/lucia-garcia-bode/)



---



