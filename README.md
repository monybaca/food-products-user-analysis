# Food Products User Analysis

Este proyecto analiza el comportamiento de los usuarios en una empresa emergente que vende productos alimenticios mediante una aplicación. El objetivo es estudiar su actividad dentro de la plataforma, evaluar el embudo de conversión e investigar los resultados de un experimento **A/A/B**, para determinar si existen diferencias significativas entre los grupos de control y prueba.

---

## 📌 Objetivo
- Analizar cómo interactúan los usuarios con la aplicación.
- Limpiar y preparar datos de eventos con marcas temporales.
- Estudiar la actividad por fecha y detectar anomalías.
- Evaluar el embudo de conversión dentro de la app.
- Validar los resultados de un experimento A/A/B.
- Determinar si las variantes presentan diferencias significativas.

---

## 🧹 Preparación y Limpieza de Datos
Incluye:
- Conversión de timestamps y ajuste de zonas horarias.
- Detección y eliminación de inconsistencias.
- Filtrado de datos de acuerdo con volumen estable de eventos (a partir del 2019-08-01).
- Verificación de que el filtrado no sesga los grupos experimentales.
- Identificación de usuarios duplicados o con actividad atípica.

---

## 📊 Análisis Realizado
- Exploración del número de eventos diarios.
- Análisis del comportamiento antes y después del filtrado.
- Cálculo del tamaño y distribución por grupo experimental (246, 247, 248).
- Construcción de embudos para analizar las etapas del proceso dentro de la app.
- Comparación entre los grupos de control y el grupo de prueba.
- Pruebas estadísticas para comparar tasas de conversión.

---

## 📈 Resultados Principales
- El filtrado temporal mantiene una distribución uniforme entre los grupos, evitando sesgos.
- Se detectó un aumento de actividad a partir de agosto, justificando el recorte de datos.
- El embudo muestra caídas claras entre etapas críticas.
- Los grupos A/A no presentan diferencias significativas, validando la configuración del experimento.
- Las comparaciones entre los grupos A y B determinan si la variante tiene un impacto en la conversión.

---

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Statsmodels / Scipy**
- **Jupyter Notebook**

---

## 📁 Archivos del Proyecto
- `food-products-user-analysis.ipynb` — Notebook principal.
- Dataset de eventos (acciones de usuario con marca temporal).
- Información de grupos experimentales.

---

## 📬 Contacto
Proyecto desarrollado como parte del portafolio analítico de **Monica Baca**.
