# 🛒 Proyecto 4: Análisis Exploratorio del Comportamiento de Compra en Instacart

## 📑 Descripción del Proyecto

Este proyecto forma parte de un sprint de análisis de datos para comprender el comportamiento de compra en la plataforma **Instacart**. El conjunto de datos proporcionado fue reducido y modificado para optimizar el procesamiento y simular condiciones reales de negocio, incluyendo valores faltantes y registros duplicados.

El objetivo fue:
- Realizar un preprocesamiento de calidad de datos.
- Explorar la información para identificar patrones clave de compra.
- Analizar la fidelidad de los clientes y la recurrencia en la selección de productos.

## 🛠️ Herramientas Utilizadas

- **Python 3**
- **Jupyter Notebook**
- **Librerías:** `pandas`, `numpy`, `matplotlib`

## 🔍 Resumen de Actividades y Hallazgos

- Se cargaron e inspeccionaron cinco tablas principales: pedidos (`instacart_orders`), productos (`products`), detalles de productos por pedido (`order_products`), pasillos (`aisles`) y departamentos (`departments`).
- Se manejaron valores nulos y duplicados para garantizar la confiabilidad de los datos.
- Se combinaron tablas usando `merge` para crear un dataset maestro que permitió análisis cruzados.
- Se calculó la proporción de productos reordenados por cliente, encontrando perfiles con **100% de recurrencia**, lo que muestra hábitos de compra estables.
- Se identificaron los **productos más comunes agregados primero al carrito**, como frutas y productos orgánicos, destacando preferencias de consumo saludable.
- Se evaluaron departamentos y pasillos con mayor frecuencia de pedidos, dando información para optimizar la disposición de categorías y promociones.

## ✅ Conclusiones

El análisis permitió:
- Identificar niveles altos de fidelidad en segmentos clave de clientes.
- Detectar productos preferidos como primera elección, útil para estrategias de marketing dirigidas.
- Sentar bases para modelos de predicción de reordenamiento y recomendaciones personalizadas.

## 📂 Archivos

- `Sprint4_Proyecto.ipynb`: Notebook completo con análisis, visualizaciones y conclusiones.
- `README.md`: Documento actual con la descripción del proyecto.

## ✍️ Autor

Equipo de Análisis de Datos — Sprint 4.
