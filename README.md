# EquineLead: Motor de Recomendación 🐎📊

Este repositorio contiene el núcleo analítico y el **Motor de Recomendación** desarrollado para el proyecto **EquineLead**. Mi trabajo en este proyecto se centró en el ciclo de vida del dato: desde la limpieza y normalización hasta el entrenamiento de la lógica de recomendación y la visualización de métricas de fiabilidad.

## 🎯 Objetivo del Módulo
Desarrollar un sistema capaz de conectar perfiles de usuarios con caballos y servicios específicos mediante algoritmos de similitud, optimizando el funnel de ventas en el mercado ecuestre.

## 🛠️ Contribuciones Técnicas
* **Data Cleaning & Prep:** Normalización de variables y manejo de datos críticos para asegurar la integridad del modelo.
* **Feature Engineering:** Creación de variables de comportamiento de usuario.
* **Motor de Recomendación:** Implementación del algoritmo lógico de recomendación basado en [tu técnica, ej: similitud de perfiles].
* **Visualización de Resultados:** Generación de gráficos de fiabilidad, mapas de calor y distribución de distancias para validar la precisión del motor.

## 💻 Stack Tecnológico
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Scikit-Learn
* **Visualización:** Matplotlib, Seaborn
* **Entorno:** Jupyter Notebooks

## 📊 Análisis de Resultados y Validación

Para garantizar la precisión del motor de recomendación, se generaron visualizaciones que validan la lógica del modelo:

### 1. Distribución de Distancias
Este gráfico permite observar la cercanía semántica entre los perfiles analizados. Una concentración adecuada indica que el motor está agrupando correctamente las recomendaciones.
![Distribución de Distancias](distribucion_distancias.png)

### 2. Gráfico de Fiabilidad
Validación del rendimiento del modelo frente a los datos de prueba, asegurando que las recomendaciones tengan un sustento estadístico sólido.
![Gráfico de Fiabilidad](grafico_fiabilidad.png)

### 3. Mapa de Calor (Correlación)
Visualización de las variables que más influyen en el motor, permitiendo identificar los factores críticos de éxito para una recomendación efectiva.
![Mapa de Calor](mapa_calor.png)

---
*Nota: Este repositorio se enfoca estrictamente en el componente de Data Science y el desarrollo del Motor de Recomendación del proyecto EquineLead.*
