# 📱 Proyecto 11: Análisis de Eventos en una Aplicación Móvil

## 📑 Descripción del Proyecto

Este proyecto aborda el análisis del **comportamiento de usuarios en una aplicación móvil** con el fin de evaluar la eficacia de la **nueva fuente de atracción de usuarios**. Se analiza un archivo de registro de eventos para entender la ruta que siguen los usuarios, calcular conversiones entre pantallas y comprobar si la nueva estrategia de adquisición es efectiva.

El análisis se centra en:
- Secuencia de eventos clave dentro de la app.
- Comparación de conversiones entre grupos de prueba (246, 247 y 248).
- Identificación de posibles fricciones o puntos de abandono.

## 🛠️ Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python 3  
- **Entorno:** Jupyter Notebook  
- **Librerías:**  
  - `pandas` para carga y limpieza de datos.
  - `numpy` para cálculos.
  - `matplotlib` y `seaborn` para gráficos.
  - `scipy.stats` para pruebas de hipótesis.

## 🔍 Principales Hallazgos y Procesos Realizados

- Se inspeccionaron más de **240,000 registros de eventos**, confirmando duplicados y ausencia de valores nulos.
- Se analizaron los eventos más frecuentes y la cronología de interacciones por usuario.
- Se construyó el **embudo de conversión**, desde la apertura de la app hasta la confirmación de pago.
- Se compararon métricas entre grupos de prueba y control, verificando estadísticamente las diferencias.
- Se realizaron visualizaciones para evidenciar la caída de usuarios en cada etapa.

## ✅ Conclusiones

El análisis permitió:
- Identificar puntos críticos de abandono para optimizar el flujo de usuario.
- Evaluar si la nueva fuente de usuarios contribuye efectivamente a mejorar las métricas clave.
- Recomendar ajustes para incrementar la tasa de conversión general de la aplicación.

## 📂 Archivos

- `Proyecto11_JavierAguilera.ipynb` — Notebook con el flujo completo de trabajo y resultados.
- `README.md` — Este archivo de documentación.

## ✍️ Autor

Equipo de Análisis de Datos — Proyecto Mobile App Events.
