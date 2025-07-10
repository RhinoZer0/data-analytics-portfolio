# 📞 Proyecto 5: Análisis Comparativo de Tarifas de Prepago de Megaline

## 📑 Descripción del Proyecto

En este proyecto se realiza un **análisis exploratorio y estadístico** para la empresa de telecomunicaciones **Megaline**, con el objetivo de determinar cuál de sus dos tarifas de prepago —**Surf** y **Ultimate**— genera más ingresos.

Se utilizó una muestra representativa de **500 clientes**, con información de llamadas, mensajes de texto y uso de internet durante el año 2018.

El enfoque principal fue:
- Procesar, limpiar y preparar los datos de varias fuentes.
- Calcular ingresos individuales y medios por tarifa.
- Evaluar diferencias estadísticamente significativas mediante pruebas de hipótesis.

## 🛠️ Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python 3  
- **Entorno:** Jupyter Notebook  
- **Librerías:**  
  - `pandas` para manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `scipy.stats` para pruebas de hipótesis.
  - `matplotlib` para visualización.

## 🔍 Principales Hallazgos y Procesos Realizados

- Se integraron y exploraron cinco datasets: llamadas, mensajes, uso de internet, planes tarifarios y datos de usuarios.
- Se desarrollaron funciones para calcular ingresos mensuales considerando:
  - Minutos, mensajes y gigabytes incluidos en cada plan.
  - Cargos adicionales por excedentes.
- Se generaron estadísticas descriptivas para cada tarifa y se compararon ingresos promedio.
- Se aplicaron pruebas de hipótesis de dos muestras para determinar si la diferencia observada entre Surf y Ultimate es significativa.

## ✅ Conclusión

El análisis proporciona evidencia sólida para responder a la pregunta de negocio:  
> **¿Qué tarifa de prepago genera mayores ingresos?**

Los resultados sirven de base para ajustar estrategias de marketing y optimización de recursos publicitarios hacia la tarifa más rentable.

## 📂 Archivos

- `Proyecto5_JavierAguilera.ipynb` — Notebook con todo el análisis y las pruebas estadísticas.
- `README.md` — Este archivo de documentación.

## ✍️ Autor

Equipo de Análisis de Datos — Proyecto Megaline.
