# Datos, evidencia y decisiones — perfil de trabajo

**Analista de datos · Economista cuantitativa.** Convierto grandes volúmenes de datos administrativos y financieros en información que sustenta decisiones: Construyo pipelines, tableros y análisis de impacto.

Mi experiencia viene del **Banco de la República** y de un proyecto **BID / Universidad EAFIT**, trabajando con bases de cobertura nacional, en entornos donde la calidad del dato y la reproducibilidad no son opcionales.
---

## Qué hago

- **Construyo pipelines de datos:** Integro fuentes heterogéneas, con distintos identificadores, periodicidades y niveles de calidad, en bases analíticas confiables y auditables.
- **Construyo visualizaciones para tomar decisiones:** Traduzco datos complejos en visualizaciones que entienden audiencias no técnicas.
- **Mido impacto, no solo describo:** Aplico métodos de inferencia causal para responder *"¿esto funcionó?"* con rigor; el equivalente metodológico a un test A/B cuando no es posible experimentar.

---

## Datos financieros a escala nacional · Banco de la República
*Práctica profesional · ene.–dic. 2025*

**El contexto:** Investigaciones sobre el efecto de reformas regulatorias en el mercado de crédito colombiano, con bases de cobertura nacional.

**Qué hice.**
- **Integración y limpieza (ETL) de fuentes administrativas complejas** — bases empresariales y crediticias colombianas (**RUES**, **Supersociedades**, **Formato 345**) y microdatos de crédito, con identificadores y periodicidades distintas. *Impacto:* Una base analítica única, consistente y auditable a partir de fuentes que no conversaban entre sí.
- **Control de calidad y validación de datos** en cada etapa del proceso. *Impacto:* Resultados defendibles ante revisión técnica.
- **Automatización y control de versiones (Git)** de rutinas de procesamiento. *Impacto:* reproducibilidad total y soporte simultáneo a varios proyectos sin perder trazabilidad.
- **Medición de impacto con métodos cuasi-experimentales** para aislar el efecto real de un cambio regulatorio de las tendencias generales del mercado. *Impacto:* Conclusiones causales, no correlaciones.
- **Visualización de resultados (Python)** — gráficas y tablas para documentos técnicos.

## Tablero interinstitucional del mercado laboral

**El reto:** Cinco instituciones con intereses distintos: Banca central, academia, gremios y cajas de compensación, necesitaban una fuente común de indicadores del mercado laboral de Antioquia, con validez institucional, para tomar decisiones informadas.

**Los stakeholders:** Banco de la República · Universidad de Antioquia · Cámara de Comercio del Aburrá Sur · Comfama · Comfenalco Antioquia.

**Qué hice:** Apoyé el desarrollo de la **sección PILA** del tablero en **Power BI (DAX)**: transformé microdatos de seguridad social en indicadores de cotizantes y salarios formales con enfoque de género (brecha salarial, ratio mujeres/hombres), segmentables por subregión, edad y tipo de cotizante.

**El resultado:** Un producto de consulta pública que convierte datos administrativos crudos en insumos accionables para decisiones de política regional.

→ **[Ver el tablero en vivo](https://app.powerbi.com/view?r=eyJrIjoiZjlmN2IyZDEtYjg5NC00ZTY1LWI0MzEtZmEwZDM2NzA4ZWMzIiwidCI6IjJmZjI1NWUxLWFlMDAtNDRiYy05Nzg3LWZhOGY4MDYxYmY2OCIsImMiOjR9)**

---


## Análisis de brechas de género en crédito empresarial · BID / EAFIT
*Asistente de investigación cuantitativa · mar. 2026 – presente*

Proyecto con el **BID** y la **Banca de las Oportunidades**. Realizo la ingesta, depuración y estructuración de bases financieras con **Python** y **SQL**, y apoyo el análisis empírico que alimenta recomendaciones de política.

---

## Stack técnico

**Lenguajes y herramientas**
`Python (pandas, statsmodels)` · `SQL` · `Stata` · `R` · `Power BI (DAX)` · `Git` · `Excel avanzado` · `LaTeX`

**Competencias de datos**
ETL e integración de fuentes · calidad y validación de datos · construcción de bases panel · automatización de procesos · análisis exploratorio (EDA) · visualización y storytelling con datos · KPIs e indicadores · comunicación a audiencias no técnicas.

---

## Métodos analíticos

### Medición de impacto (inferencia causal)
Responder con rigor si una intervención, política o cambio produjo un efecto real:
- **Regresión discontinua (RDD)** — aprovecha umbrales de elegibilidad para comparar casos casi idénticos a ambos lados del corte.
- **Diferencias en diferencias (DiD)** — compara grupos tratados y de control, antes y después, aislando tendencias comunes.
- **Estudios de eventos** — traza cómo evoluciona el efecto en el tiempo alrededor de un cambio.
- **Diseños cuasi-experimentales** — usa cambios regulatorios como experimentos naturales cuando no se puede aleatorizar.
- **Validación** — tendencias paralelas, pruebas de placebo y análisis de sensibilidad.

### Análisis estadístico y econométrico
- **Datos de panel** — efectos fijos y aleatorios sobre estructuras longitudinales.
- **Microeconometría** — modelación con datos de individuos, firmas y hogares.
- **Series de tiempo** — dinámicas temporales y estacionalidad.
- **Análisis geoespacial y econometría espacial** — datos georreferenciados y dependencia espacial.
- **Inferencia robusta** — errores estándar agrupados (*clustered*) y robustos.

**Fuentes trabajadas:** microdatos de crédito · RUES · Supersociedades · Formato 345 · PILA · datos satelitales (IDEAM, NASA POWER).

---

## Mi código, en proyectos con datos públicos
Aquí no hay código porque los datos son reservados. Puedes verlo en:
- **[potencial-solar-colombia-eda]** — pipeline completo desde API pública (NASA POWER) y base SQLite hasta el análisis exploratorio, cruzando recurso solar con proyectos de la UPME.
- **[evaluacion-impacto-ifa-amazonia]** — evaluación de impacto (DiD) de un programa de pagos por servicios ambientales sobre la deforestación, con datos satelitales del IDEAM.

## Contacto
Diana García — Economista (Universidad Nacional de Colombia) · [LinkedIn](https://linkedin.com/in/diana-sirley-garcia-quintero-economia)
