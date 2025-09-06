# **Análisis de datos exploratorio**

## 1. Introducción
El dengue es una enfermedad febril aguda de etiología viral, transmitida por vectores del género Aedes (A. aegypti y A. albopictus). Según la Organización mundial de la salud (OMS), esta patología representa una de las mayores cargas sanitarias en regiones tropicales y subtropicales, con un estimado de 390 millones de infecciones anuales a nivel global (OMS, 2023). Su espectro clínico varía desde formas asintomáticas hasta cuadros graves que requieren intervención médica urgente.

En Colombia, el dengue constituye un reto epidemiológico prioritario debido a su patrón endemo-epidémico y la amplia distribución del vector en el territorio nacional (73.3% según el INS, 2024). El Instituto Nacional de Salud (INS) reporta ciclos epidémicos cada 3 a 5 años, asociados a factores climáticos y sociodemográficos. Desde 2013, el país ha fortalecido sus estrategias de vigilancia reforzada a través del Sistema Nacional de Vigilancia en Salud pública (SIVIGILA), que exige la notificación obligatoria de casos sospechosos y confirmados.

% Anotar casos en el Atlántico y en Barranquilla, importancia del estudio focalizado. 

## 2. Descripción de los datos

### Origen y contexto

Los datos proceden del reporte de casos de Dengue y Dengue grave en el Sistema Nacional de Vigilancia en Salud Pública (SIVIGILA) de Colombia. 

Para cada escala en el estudio se tomaron registros que abarcan periodos de tiempo de acuerdo a la disponibilidad de datos por nivel:


* **Colombia:** 
    Periodo de análisis: 2013-2023
    Cantidad de casos: +900.000

* **Atlántico**
    Periodo de análisis: 2017-2024
    Cantidad de casos: +34.000

* **Barranquilla:**
    Periodo de análisis: 2024
    Cantidad de casos: +3.000

### Variables de estudio

Los conjuntos de datos utilizados comparten las mismas variables de estudio que describen cada caso registrado de forma anónima. 
Se toman en cuenta 16 variables de estudio, agrupadas en las siguientes categorías:

| Categoría | Variables | Tipo | 
|-----------|-----------|------|
|Demográficas| Edad, Sexo, Etnia, Tipo de aseguradora | Numérica/Categórica nominal|
|Espaciales| Departamento, Municipio, Area | Categóricas nominales|
|Evento| Evento, Tipo de caso, Semana, Año, Hospitalización, Muerte de paciente| Categóricas nominales, Numéricas|
|Temporales| Fecha de inicio de síntomas, Fecha de consulta, Fecha de notificación | Numérica, Categórica ordinal|

% Decir que para cada nivel de la escala de estudio, las variables espaciales varían, ampliando cada vez más la unidad espacial.
% Ampliar descripción por variable de acuerdo a la ficha técnica. 

### Limpieza y preparación

% Descripción y enlace a código. 

1. Problemas detectados
2. Ajustes aplicados

