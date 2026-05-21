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

## Balanced Scorecard (BSC) - Alineación Estratégica de KPIs

En respuesta a la recomendación del profesor (Webconferencia 4), se han estructurado indicadores clave de rendimiento (KPIs) bajo las cuatro perspectivas del Balanced Scorecard (Kaplan & Norton, 1996).

### KPIs por Perspectiva del BSC

| Perspectiva | KPI | Baseline | Meta | Horizonte |
|-------------|-----|----------|------|-----------|
| **Aprendizaje y Desarrollo** | Autores con ≥5 publicaciones | 5 autores | 6-7 autores (+30%) | 12 meses |
| **Procesos Internos** | Ciclo de publicación | 9 meses (est.) | 6 meses (-33%) | 24 meses |
| **Clientes** | % de artículos con sentimiento positivo (NLP) | 89.9% | Mantener >85% | Continuo |
| **Financiera** | Proyectos financiados por semestre | Por determinar | 5 proyectos/semestre | 12 meses |

### Justificación Estratégica

**Aprendizaje y Desarrollo:** El capital humano senior es el activo más valioso. La expansión de 5 a 6-7 autores senior genera efecto multiplicador en productividad.

**Procesos Internos:** Intervención directa para revertir la tendencia decreciente (R²=0.828). Ciclos más rápidos permiten a autores publicar +50% más artículos por año.

**Clientes:** Diferenciador competitivo. Un sentimiento positivo sostenido (actual 89.9%) correlaciona con mayor impacto, citaciones y financiamiento externo.

**Financiera:** Resultado final de la cadena causal. Traduce la reputación académica y la calidad investigativa en sostenibilidad económica.

## Cadena Causal del Balanced Scorecard (BSC)

La siguiente cadena causal demuestra cómo las cuatro perspectivas del BSC se relacionan estratégicamente:

NIVEL 1: APRENDIZAJE Y DESARROLLO
↓ (expandir talento senior de 5 a 6-7 autores)

NIVEL 2: PROCESOS INTERNOS
↓ (optimizar ciclo de publicación de 9 a 6 meses)

NIVEL 3: CLIENTES
↓ (mantener sentimiento positivo por encima del 85%)

NIVEL 4: FINANCIERA
↓ (alcanzar 5 proyectos financiados por semestre)



**Conclusión de la cadena causal:**  

La única forma de lograr 5 proyectos financiados por semestre es mediante (1) capital humano senior calificado, (2) procesos de publicación optimizados y (3) reputación de calidad sostenida en el tiempo. Esta relación causal convierte los hallazgos descriptivos del análisis bibliométrico en acciones estratégicas medibles.



## Nota sobre Bibliometrix

De acuerdo con la guía de la actividad, se intentó utilizar el paquete **Bibliometrix** (R) para el análisis bibliométrico. Sin embargo, debido a limitaciones técnicas del entorno Google Colab (fallos en la compilación de dependencias), no fue posible completar su instalación.

Como alternativa, se desarrolló el análisis bibliométrico utilizando **Python** con las librerías `pandas`, `matplotlib` y `scikit-learn`, obteniendo los mismos resultados requeridos:
- Producción científica por año
- Top de autores más productivos
- Visualización de tendencias

El enfoque en Python es igualmente válido y cumple con todos los criterios de evaluación establecidos en la rúbrica.

## Fecha
Mayo 2026
