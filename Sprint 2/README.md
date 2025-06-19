# 📊 Proyecto 2: Análisis Avanzado y Filtrado de Datos de Clientes

## 📑 Descripción del Ejercicio

Este proyecto corresponde a la **segunda fase** del análisis de datos para Store 1. Tras limpiar y preparar la muestra de datos en la etapa anterior, ahora se aplicaron técnicas de **procesamiento avanzado** para:
- Homogeneizar nombres y categorías.
- Realizar consultas condicionales.
- Filtrar y segmentar usuarios según criterios específicos.

Se trabajó sobre una estructura de tabla almacenada como lista anidada, representando cada cliente con:
- **ID**
- **Nombre y apellido** como lista separada.
- **Edad**
- **Categorías de compra favoritas** normalizadas a minúsculas.
- **Gastos por categoría**

## 🛠️ Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python 3  
- **Entorno:** Jupyter Notebook  
- **Módulos adicionales:** `random` (para simulación de compras adicionales)
- **Funcionalidades empleadas:**
  - Creación y uso de **funciones personalizadas** para limpiar y transformar datos.
  - Uso de bucles `for` y condicionales `if` para filtrado.
  - Generación de números aleatorios (`randint`).
  - Funciones básicas de cadena y listas (`strip`, `replace`, `split`, `lower`, `sum`).

## 🔍 Principales Hallazgos y Procesos Realizados

- Se creó una **función robusta** para limpiar cada registro:
  - El nombre se convirtió a minúsculas, se eliminaron espacios y guiones bajos, y se dividió en nombre y apellido.
  - Las categorías favoritas se estandarizaron a minúsculas.

- Se implementaron **filtros dinámicos** para:
  - Identificar usuarios con edad menor a 30 años.
  - Filtrar aquellos con gastos totales superiores a un umbral específico.
  - Localizar clientes que compran en una categoría concreta (ej. 'home').

- Se aplicaron simulaciones de gasto adicional para alcanzar metas de ventas utilizando bucles `while` y números aleatorios.

- Se validaron los resultados mediante impresión estructurada de los datos filtrados.

## ✅ Estado del Proyecto

Con este sprint, se finaliza la **etapa de limpieza y segmentación de datos**, habilitando:
- Análisis estadísticos descriptivos o predictivos.
- Visualización de perfiles de clientes.
- Toma de decisiones basadas en datos para campañas de marketing dirigidas.

## 📂 Estructura de Archivos

- `Project2.ipynb` — Notebook con todo el flujo de trabajo.
- `README.md` — Este archivo de documentación.

## ✍️ Autor

Equipo de Análisis de Datos — Store 1.
