# 🧪 Proyecto 10: Análisis de Resultados de Pruebas A/B para la Optimización de Ingresos

## 📑 Descripción del Proyecto

Este proyecto corresponde a un análisis exhaustivo de una **prueba A/B** ejecutada por una empresa de comercio electrónico. El objetivo fue **comparar dos versiones del sitio web** para evaluar cuál genera mayores ingresos y mejores métricas de conversión.

Se trabajó con tres fuentes de datos:
- **Hipótesis planteadas para mejoras.**
- **Registro de pedidos (por usuario, fecha, ingreso y grupo de prueba).**
- **Registro de visitantes diarios por grupo de prueba.**

## 🛠️ Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python 3  
- **Entorno:** Jupyter Notebook  
- **Librerías:**  
  - `pandas` para manipulación de datos.
  - `numpy` para cálculos numéricos.
  - `matplotlib` y `seaborn` para visualizaciones.
  - `scipy.stats` para pruebas de hipótesis.

## 🔍 Principales Hallazgos y Procesos Realizados

- Se evaluaron hipótesis usando **métodos ICE y RICE** para priorizar iniciativas de alto impacto.
- Se inspeccionaron y limpiaron registros de pedidos y visitantes, verificando valores atípicos y anomalías.
- Se calcularon métricas acumulativas de ingresos, conversión y tamaño medio de pedidos.
- Se aplicaron pruebas de hipótesis para comparar los grupos de prueba y control:
  - Verificación de normalidad y valores atípicos.
  - Comparación de ingresos y tasas de conversión usando métodos estadísticos robustos.
- Se generaron gráficos para visualizar la evolución de métricas clave y determinar cuándo los resultados son significativos.

## ✅ Conclusiones

El análisis permitió:
- Identificar **la versión del sitio con mejores métricas de ingresos y conversión**.
- Proporcionar recomendaciones basadas en datos para la implementación definitiva.
- Optimizar el enfoque de priorización de hipótesis para futuras pruebas A/B.

## 📂 Archivos

- `Proyecto10_JavierAguilera.ipynb` — Notebook completo con flujo de trabajo, visualizaciones y resultados.
- `README.md` — Este archivo de documentación.

## ✍️ Autor

Equipo de Análisis de Datos — Proyecto A/B Testing.
