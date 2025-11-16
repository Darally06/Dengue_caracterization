# ***Análisis Geo-Espacial del Dengue en Colombia [Caso Atlántico]***

## **Contextualización**

El dengue es una enfermedad febril aguda de etiología viral, transmitida por vectores del género *Aedes* (*A. aegypti* y *A. albopictus*). Según la [Organización Mundial de la Salud (OMS, 2023)](https://www.who.int/es/news-room/fact-sheets/detail/dengue-and-severe-dengue), esta patología representa una de las mayores cargas sanitarias en regiones tropicales y subtropicales, con un estimado de **390 millones de infecciones anuales** a nivel global. Su espectro clínico abarca desde cuadros leves hasta formas graves potencialmente mortales que requieren atención médica urgente.  

A nivel mundial, el dengue constituye una de las enfermedades virales transmitidas por mosquitos de mayor expansión geográfica, con presencia en más de 120 países. En América Latina, la circulación endémica del virus se ha consolidado en las últimas décadas, con picos epidémicos recurrentes impulsados por factores climáticos, urbanización descontrolada y deficiencias en el control vectorial. En Colombia, el dengue representa un problema prioritario de salud pública debido a su patrón endemo-epidémico y a la amplia distribución del vector en el territorio nacional, que alcanza el **73.3%** de los municipios, según el [Instituto Nacional de Salud (INS, 2024)](https://www.ins.gov.co).  

El dengue tiene consecuencias significativas en la salud pública y en la sociedad. En el ámbito sanitario, genera alta demanda de atención médica, saturación hospitalaria durante los brotes y riesgos de mortalidad en poblaciones vulnerables. Desde el punto de vista social y económico, los periodos epidémicos provocan pérdida de productividad laboral, ausentismo escolar y costos elevados para los sistemas de salud locales. Además, la percepción de riesgo y las medidas preventivas implementadas en comunidades afectadas impactan el bienestar general y la dinámica cotidiana de la población.  

La vulnerabilidad frente al dengue en Colombia está determinada por factores ambientales, socioeconómicos y normativos. La urbanización no planificada, la deficiente gestión del agua y la acumulación de residuos favorecen la proliferación del vector. Desde el plano institucional, el país cuenta con un marco regulatorio que respalda la vigilancia y el control del dengue, sustentado en la **Ley 9 de 1979** (Código Sanitario Nacional), la **Ley 715 de 2001** (competencias en salud pública) y los lineamientos del **Sistema Nacional de Vigilancia en Salud Pública (SIVIGILA)**, que establece la notificación obligatoria de los casos sospechosos y confirmados. Adicionalmente, el **Plan Decenal de Salud Pública 2022–2031** incorpora estrategias de prevención, control vectorial y educación comunitaria orientadas a reducir la carga de la enfermedad.  


## **Problema**

El dengue constituye uno de los principales problemas de salud pública en Colombia y en gran parte de América Latina, debido a su alta incidencia, la carga epidemiológica que genera y la estrecha relación que mantiene con factores ambientales y climáticos. La presencia del mosquito Aedes aegypti en gran parte del territorio nacional, junto con diversos factores climáticos, ha facilitado que esta enfermedad permanezca de forma endémica y represente un riesgo para la población. 

En este contexto, resulta fundamental comprender la distribución espacial del virus, que no todos los territorios presentan el mismo nivel de riesgo. Zonas urbanas densamente pobladas, con problemas para acceder a la salud pública o con condiciones climáticas particulares, tienden a mostrar una mayor incidencia, lo que plantea retos diversos para la vigilancia epidemiológica y la implementación de medidas de control.  

Aunque existen reportes y análisis a nivel nacional, en los que se identifican departamentos con alta carga de casos, no siempre se cuenta con un estudio detallado que permita comprender las particularidades de cada región. En el caso del Atlántico, y de manera más específica, de la ciudad de Barranquilla, el aumento poblacional y las condiciones ambientales favorecen la transmisión del dengue, pero la información disponible a menudo se limita a cifras globales que no permiten identificar claramente las áreas más afectadas dentro del territorio ni los factores espaciales asociados a la propagación del virus.  Esta falta de análisis detallado limita la capacidad al momento de priorizar recursos, focalizar campañas de prevención y responder de forma adecuada y oportuna a los brotes de la enfermedad.  

Por lo tanto, se hace necesario un análisis geo-espacial que permita identificar patrones de distribución del dengue en Colombia, con énfasis en el Atlántico y en Barranquilla. Este tipo de estudio no solo contribuirá a reconocer zonas de mayor riesgo dentro del territorio, sino que también proporcionará una base sólida para diseñar estrategias de intervención más focalizadas y eficaces.

## **[Antecedentes](https://uninorte-my.sharepoint.com/:w:/g/personal/daniellaguerra_uninorte_edu_co/EaFc_6JVUttLkH3sMu8MYo4BOD-LLKBUlwujXVze6RIcEQ?e=aMb08c)**

1. **Fuentes-Vallejo (2017)**  
   **Tema:** Distribución espacio-temporal del dengue en un contexto urbano hiperendémico en Girardot (Cundinamarca).  
   **Métodos:** Análisis de conglomerados espaciales (Getis-Ord) y espacio-temporales (Kulldorff).  
   **Objetivo:** Identificar patrones de transmisión y su relación con la dinámica territorial.  
   **Resultados:** Se observó una concentración de casos en el suroeste de la ciudad, con mayor incidencia durante las temporadas secas.  
   **Región:** Girardot, Cundinamarca, Colombia.  

2. **Hernández et al. (2017)**  
   **Tema:** Epidemiología y georreferenciación del dengue en un hospital de segundo nivel.  
   **Métodos:** Estudio retrospectivo de casos entre 2010 y 2014, utilizando datos del sistema SIVIGILA y herramientas EpiInfo y EpiMap.  
   **Objetivo:** Describir la incidencia, mortalidad y distribución geográfica de los casos en El Espinal.  
   **Resultados:** Se identificó alta incidencia en población joven (1–24 años), un comportamiento bimodal y una distribución asociada a la densidad poblacional.  
   **Región:** Municipio de El Espinal, Tolima.  

3. **Muñoz, Poveda, Arbeláez & Vélez (2021)**  
   **Tema:** Dinámicas espacio-temporales del dengue en relación con el clima local y el fenómeno ENSO (2007–2017).  
   **Métodos:** Correlaciones cruzadas, análisis de ondículas y causalidad no lineal (PCMCI).  
   **Objetivo:** Evaluar la relación entre ENSO, variables climáticas y casos de dengue en Colombia.  
   **Resultados:** Se encontró que las fases de El Niño y La Niña influyen en aumentos y disminuciones de los casos, con mayor impacto en las regiones Pacífica y Andina.  
   **Región:** Nacional, con énfasis en Pacífico y Andes.  

4. **Marceló-Díaz & Lesmes (2022)**  
   **Tema:** Análisis espacio-temporal de conglomerados de dengue en el suroccidente de Colombia (2014–2019).  
   **Métodos:** Modelos de Poisson, análisis Getis-Ord, índice de pupas y análisis de vecino más cercano.  
   **Objetivo:** Identificar áreas de alta transmisión de dengue a diferentes escalas (departamental, municipal y local).  
   **Resultados:** El municipio de Patía (Cauca) fue identificado como zona crítica, con alta incidencia y concentración de pupas.  
   **Región:** Departamento del Cauca, suroccidente colombiano.  

5. **Ortega-Lenis et al. (2024)**  
   **Tema:** Efectos de la variabilidad climática en la distribución del dengue en el Valle del Cauca (2001–2019).  
   **Métodos:** Modelos jerárquicos bayesianos espacio-temporales.  
   **Objetivo:** Analizar patrones espacio-temporales y cuantificar factores de riesgo asociados al dengue.  
   **Resultados:** La temperatura y la precipitación mostraron efectos retardados sobre el riesgo de transmisión, lo que evidencia su potencial para sistemas de alerta temprana.  
   **Región:** Valle del Cauca, Colombia.  

### *Anotaciones de los Antecedentes*

De los artículos revisados, se han tomado referencias de la metodología de trabajo, modelos estadísticos y análisis aplicados (Modelos de Poisson, correlaciones cruzadas, análisis de conglomerados, modelos espacio-temporales), así como el tratamiento de datos relacionados con variables climáticas, demográficas y de eventos de salud pública.

Se ha tomado como artículo guía la publicación de Marceló Díaz \& Lesmes (2022), con la intención de realizar un análisis espacio-temporal del dengue en el departamento del Atlántico y, en particular, en la Ciudad de Barranquilla. Asi mismo, se integrará la descripción de las dinámicas espacio-temporales asociadas al clima en el Atlántico, siguiendo el enfoque de Muñoz, et al. (2021) y Ortega et al. (2024), mediante el uso de variables meteorológicas proporcionadas por el IDEAM. 

Por otro lado, se pretende caracterizar los casos en Colombia con base en la incidencia relacionada a la densidad poblacional, siguiendo la idea de Hernández et al. (2017). A diferencia de las investigaciones previas, este estudio busca aportar un análisis focalizado en el Atlántico, con énfasis en Barranquilla, lo cual permitirá generar evidencia localizada en el contexto urbano de alta vulnerabilidad. 

