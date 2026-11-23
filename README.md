# DINAMICA-COBERTURA-FORESTAL-2020-2024

Este repositorio consolida la infraestructura computacional, metodologías y algoritmos aplicados por el Instituto Nacional de Bosques (INAB) para la generación del Mapa de Dinámica de la Cobertura Forestal de Guatemala (Período 2020–2024).

Con el propósito de garantizar la transparencia, reproducibilidad y rigor técnico del monitoreo forestal nacional, se integran tecnologías de procesamiento masivo en la nube (Google Earth Engine, SEPAL) con flujos analíticos avanzados en GEE, SEPAL, Python y automatización geoespacial en ArcPy.

Pilares Técnicos y Metodológicos:
- Detección de Pérdidas Forestales: Implementación de algoritmos de series temporales continuas (CCDC sobre constelaciones Landsat 8 y 9) para la captura precisa de eventos de deforestación y degradación.
- Identificación y Calibración de Ganancias: Fusión de índices espectrales de vegetación y humedad (NDFI, EVI) combinados con datos de radar de apertura sintética (Sentinel-1 C-SAR) y calibración estadística pareada no paramétrica (Prueba de Wilcoxon) para mitigar falsos positivos.
- Estandarización y Filtrado Espacial: Aplicación de reglas de vecindad espacial para homologar la Unidad Mínima de Mapeo (UMM de 0.5 hectáreas), garantizando coherencia con las definiciones forestales nacionales y de la FAO.
- Validación y Estimación de Áreas (Buenas Prácticas IPCC / FAO): Protocolo de inferencia y diseño muestral estratificado probabilístico implementado bajo el marco AREA2 (Olofsson et al.), permitiendo reportar estimaciones de superficie ajustadas por error temático con sus respectivos intervalos de confianza y matrices de confusión validadas.
