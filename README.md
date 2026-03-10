# Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes-Parte-2-
Este repositorio contiene la segunda fase del proyecto de inteligencia de datos para **TelecomX**. Tras la normalización inicial, este cuaderno se enfoca en la preparación avanzada de datos y el análisis de variables críticas con un enfoque puramente predictivo.

## 🎯 Propósito del Análisis

El objetivo principal de este estudio es **predecir el churn (cancelación)** de clientes mediante la identificación y evaluación de las variables más influyentes en su comportamiento. A través de un enfoque estadístico y de correlación, se busca entender qué factores determinan que un usuario permanezca en la compañía o decida abandonarla, permitiendo así tomar acciones preventivas basadas en datos.

## 🛠️ Tecnologías Usadas

Para el desarrollo de este análisis se utilizaron las siguientes herramientas y librerías de Python:

* **Pandas:** Para la carga del dataset `datos_tratados.csv`, manipulación de estructuras de datos y estandarización de etiquetas.
* **Seaborn & Matplotlib:** Para la creación de visualizaciones estadísticas, incluyendo mapas de calor (heatmaps) de correlación y gráficos de distribución.
* **Google Colab:** Como entorno de desarrollo interactivo basado en la nube.
* **Markdown:** Para la documentación técnica y presentación de hallazgos.

## 🚀 Etapas del Proyecto

1.  **Carga y Estandarización:** * Importación de los datos previamente procesados.
    * Homogeneización de categorías (ej. traducción de etiquetas y limpieza de inconsistencias).
2.  **Análisis de Proporción de Churn:** * Cálculo de la tasa de cancelación actual (detectada en un **26.6%**).
3.  **Matriz de Correlación:** * Identificación de las variables con mayor impacto (positivo o negativo) sobre la variable objetivo `Churn`.
4.  **Selección Predictiva:** * Evaluación de factores clave como el tipo de internet, método de pago y antigüedad del contrato.

## 📊 Hallazgos para el Modelo Predictivo

* **Factores de Riesgo (Alta probabilidad de Churn):**
    * **Internet de Fibra Óptica:** Muestra una correlación directa con la cancelación, señalando una posible insatisfacción con el precio o la estabilidad.
    * **Contratos Mensuales:** Los clientes sin compromiso anual son los más propensos a la fuga.
* **Factores de Retención (Baja probabilidad de Churn):**
    * **Contratos a Largo Plazo (1 y 2 años):** Es el predictor más fuerte de lealtad.
    * **Servicios Adicionales:** La contratación de soporte técnico y seguridad en línea reduce drásticamente la probabilidad de abandono.

## 💡 Recomendaciones Estratégicas

Basado en la capacidad predictiva de las variables analizadas:
1.  **Priorización de Fibra Óptica:** Implementar alertas proactivas para usuarios de fibra, ofreciendo optimizaciones de red antes de que surja la queja.
2.  **Conversión de Contratos:** Diseñar campañas de marketing para migrar a clientes de planes mensuales a anuales mediante beneficios exclusivos.
3.  **Automatización de Pagos:** Fomentar el uso de tarjetas de crédito/transferencias automáticas para reducir el Churn involuntario por falta de pago manual.
4.  **Optimización de Valor:** Revisar la relación costo-beneficio en planes de alto valor para mejorar la percepción de justicia en el precio.

---
*Este análisis es la base para el despliegue de modelos de Machine Learning destinados a la retención de clientes en TelecomX LATAM.*
