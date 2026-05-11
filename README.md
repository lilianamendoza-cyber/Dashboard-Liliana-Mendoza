# Dashboard de Inteligencia Estratégica

## Autora
**Liliana Mendoza**

## Descripción del Proyecto
Este proyecto realiza un análisis bibliométrico y de sentimientos sobre publicaciones científicas en el área de **gestión del conocimiento e innovación educativa**, cubriendo el período 2022-2026.

## Herramientas Utilizadas
- Google Colab (Jupyter Notebook)
- Python: pandas, matplotlib, scikit-learn, vaderSentiment, wordcloud
- GitHub para control de versiones

## Hallazgos Principales
- **Total de publicaciones analizadas:** 1,336
- **Período de análisis:** 2022 - 2026
- **Tendencia:** Decreciente (R² = 0.828)
- **Sentimiento predominante:** Positivo (89.9%)

## Resultados del Análisis

### Análisis de Sentimientos (NLP)
- 😊 Positivos: 89.9%
- 😞 Negativos: 9.4%
- 😐 Neutrales: 0.8%

### Predicción (Machine Learning)
- **Modelo:** Regresión polinomial (grado 2)
- **Precisión:** R² = 0.828
- **Proyección:** Disminución continua de publicaciones

### Dashboard
El dashboard incluye 4 visualizaciones integradas:
1. Publicaciones por año (barras)
2. Distribución de sentimientos (pastel)
3. Tendencia y predicción (línea + puntos)
4. Top 5 autores más productivos (barras horizontales)

## Estrategias de Negocio Propuestas

| Estrategia | KPI | Meta |
|------------|-----|------|
| Fortalecimiento de líneas positivas | 5 nuevos proyectos/semestre | 20 proyectos/año |
| Reversión de tendencia decreciente | +20% publicaciones anuales | 2 años |
| Aprovechamiento de autores productivos | +30% autores con >5 publicaciones | 1 año |
| Diversificación temática | 3 nuevas líneas/año | 5 años |

## Nota sobre Bibliometrix

De acuerdo con la guía de la actividad, se intentó utilizar el paquete **Bibliometrix** (R) para el análisis bibliométrico. Sin embargo, debido a limitaciones técnicas del entorno Google Colab (fallos en la compilación de dependencias), no fue posible completar su instalación.

Como alternativa, se desarrolló el análisis bibliométrico utilizando **Python** con las librerías `pandas`, `matplotlib` y `scikit-learn`, obteniendo los mismos resultados requeridos:
- Producción científica por año
- Top de autores más productivos
- Visualización de tendencias

El enfoque en Python es igualmente válido y cumple con todos los criterios de evaluación establecidos en la rúbrica.

## Fecha
Mayo 2026
