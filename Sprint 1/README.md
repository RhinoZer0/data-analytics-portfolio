# 📊 Proyecto: Limpieza y Evaluación Inicial de Datos de Usuarios

## 📑 Descripción del Ejercicio

Este proyecto corresponde a la primera etapa de un análisis de datos para un cliente. El objetivo principal es **evaluar la calidad de una muestra de datos de usuarios** y **prepararla para análisis posteriores**. Durante este proceso se realizó una exploración preliminar y se aplicaron técnicas básicas de limpieza y transformación de datos.

Los datos provistos incluyen información de usuarios como:
- **ID de usuario**
- **Nombre**
- **Edad**
- **Categorías favoritas de compra**
- **Gastos totales por categoría**

## 🛠️ Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python 3  
- **Entorno de trabajo:** Jupyter Notebook  
- **Librerías:** No se emplearon librerías externas; se utilizaron funciones básicas de Python para:
  - Limpieza de cadenas (`strip`, `replace`, `split`)
  - Conversión de tipos de datos (`int`)
  - Ordenación de listas (`sort`)
  - Operaciones aritméticas y de agregación (`sum`)

## 🔍 Principales Hallazgos y Procesos Realizados

- Se detectaron inconsistencias en los nombres de usuario:  
  - Presencia de espacios innecesarios.
  - Uso de guiones bajos en lugar de espacios.
  - Falta de separación clara entre nombre y apellido.

- Se implementó una limpieza sistemática:  
  - Eliminación de espacios extra.
  - Reemplazo de guiones bajos por espacios.
  - División del nombre completo en nombre y apellido para mayor granularidad.

- Se validaron y ajustaron tipos de datos:  
  - Conversión de edades de **float** a **entero** para coherencia.

- Se realizaron cálculos básicos:  
  - Suma de gastos totales por usuario usando funciones integradas.

- Se ordenó la lista de usuarios por ID para facilitar búsquedas y futuras operaciones.

- Se consolidó un subconjunto de usuarios con datos limpios para ejemplificar la estructura final deseada.

## ✅ Estado del Proyecto

Este notebook constituye el **primer sprint** de un proyecto mayor. La muestra de datos está ahora preparada para:
- Integrarse a un análisis exploratorio más avanzado.
- Ser visualizada mediante gráficos.
- Responder preguntas específicas del cliente en la siguiente fase.

## 📂 Estructura de Archivos

- `Project1.ipynb` — Notebook principal con todo el proceso paso a paso.
- `README.md` — Este archivo de documentación.

## ✍️ Autor

Equipo de Análisis de Datos — Proyecto de Práctica.
