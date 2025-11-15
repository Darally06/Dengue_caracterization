# **Metodología**

## **Fuentes de datos**
[comment]: <> (Añadir la descripción de las fuentes y el pq las tomamamos)

[comment]: <> (Añadir Tambien el pq eleigimos ese periodo)

## **Variables de estudio**
[comment]: <> (Tanto las de dengue como las variables de entorno)

##  **Indicadores**
[comment]: <> (Incidencia, REM)

Para el estudio se emplearon dos indicadores fundamentales: La *tasa de incidencia poblacional* y la *razón estandarizada de morbilidada (REM)*.

### *Tasa de Incidencia Poblacional*

Es una medida epidemiológica que describe la frecuencia con la que ocurren nuevos casos de una enfermedad en especifico (el dengue, en este caso) en una población especifica durante un período de tiempo determinado. Expresa el riesgo relativo de caer en enfermedad de  un territorio en terminos proporcionales y no absolutos. Asi como tambien describe la magnitud del problema en terminos poblacionales. 

### *Razón Estandarizada de Morbilidad (REM)*

Por su parte, el REM  es un indicador comparativo que relaciona el número de casos observados con los casos esperados. Este indicador nos permite identificar municipios con un riesgo mayor o menor al esperado, detectando patrones atípico que podría señalar brotes o condiciones de mayor vulnerabilidad. Esta medida permite e



| Municipio        | Casos Observados | Proporción | Población | Incidencia | Casos Esperados |   REM   |
|------------------|-------|------------|-----------|------------|-----------|---------|
| BARANOA          | 1021  | 0.070      | 405184    | 251.98     | 681.512   | 1.49814 |
| CAMPO DE LA CRUZ | 147   | 0.010      | 147981    | 99.34      | 248.785   | 0.59087 |
| CANDELARIA       | 52    | 0.004      | 104398    | 49.81      | 175.695   | 0.29597 |
| GALAPA           | 837   | 0.058      | 391774    | 213.64     | 657.891   | 1.27225 |
| JUAN DE ACOSTA   | 249   | 0.017      | 134313    | 185.39     | 225.477   | 1.10433 |
| LURUACO          | 271   | 0.019      | 181093    | 149.65     | 304.225   | 0.89079 |
| MALAMBO          | 1675  | 0.115      | 832032    | 201.31     | 1398.510  | 1.19770 |
| MANATÍ           | 253   | 0.017      | 128844    | 196.36     | 216.718   | 1.16742 |
| PALMAR DE VARELA | 100   | 0.007      | 188904    | 52.94      | 317.916   | 0.31455 |
| PIOJÓ            | 69    | 0.005      | 42781     | 161.29     | 71.924    | 0.95934 |
| POLONUEVO        | 394   | 0.027      | 116997    | 336.76     | 196.548   | 2.00460 |
| PONEDERA         | 186   | 0.013      | 152362    | 122.08     | 255.750   | 0.72727 |
| PUERTO COLOMBIA  | 766   | 0.053      | 333634    | 229.59     | 563.463   | 1.35945 |
| REPELÓN          | 95    | 0.007      | 167696    | 56.65      | 281.551   | 0.33742 |
| SABANAGRANDE     | 94    | 0.006      | 211268    | 44.49      | 355.591   | 0.26435 |
| SABANALARGA      | 1083  | 0.075      | 590598    | 183.37     | 990.362   | 1.09354 |
| SANTA LUCÍA      | 41    | 0.003      | 104634    | 39.18      | 176.092   | 0.23283 |
| SANTO TOMÁS      | 73    | 0.005      | 195560    | 37.33      | 329.282   | 0.22170 |
| SOLEDAD          | 6673  | 0.460      | 3935846   | 169.54     | 6619.400  | 1.00810 |
| SUAN             | 119   | 0.008      | 77623     | 153.31     | 130.573   | 0.91137 |
| TUBARÁ           | 74    | 0.005      | 112015    | 66.06      | 188.210   | 0.39318 |
| USIACURÍ         | 250   | 0.017      | 80996     | 308.66     | 136.519   | 1.83125 |


La tabla presenta, para cada municipio del departamento del Atlántico (exceptuando Barranquilla), la tasa de incidencia acumulada del dengue y el REM correspondientes al periodo **2018–2023**. Estos indicadores permiten comparar la carga de enfermedad entre municipios con diferentes tamaños poblacionales y evaluar si el número de casos registrados es coherente con lo que se esperaría según el comportamiento epidemiológico del territorio.

Municipios como **Soledad, Sabanalarga, Baranoa, Puerto Colombia, Galapa** y **Malambo** presentan tanto una alta incidencia acumulada como valores de REM superiores a 1, lo que indica un riesgo mayor al esperado y una transmisión más intensa o sostenida. Otros municipios más pequeños, como **Polonuevo** y **Usiacurí**, destacan por REM particularmente elevados pese a su baja población, sugiriendo brotes localizados o condiciones de vulnerabilidad específicas. En contraste, municipios como **Campo de la Cruz, Candelaria, Sabanagrande, Santo Tomás, Palmar de Varela** o **Repelón** muestran tanto incidencia como REM por debajo del promedio, reflejando una menor transmisión.

## **Diagrama ETL** 
[comment]: <> (Incluir enlace al github del ETL)

----------------

- **Caracterización de casos:**  Se quiere mostrar la distribución de casos en la unidad geográfica.  

- **Incidencia de casos:** Cálculo de la tasa de incidencia REM a partir de la proyección poblacional DANE. Buscamos detectar zonas de alto y bajo riesgo, aumentos o variaciones en la dinámica de casos.  


- **Covariables meteorológicas:** Uso de indicadores climáticos para verificar si estas tienen influencia en la cantidad de casos por semana.  La influencia debe calcularse con efecto a la semana siguiente. 
 

- **Análisis espacio-tiempo:** Buscamos detectar patrones el comportamiento cíclico de los casos en general y por evento, en diferentes periodos de tiempo: 

    - Semana epidemiológica 

    - Periodo epidemiológico (4 semanas) 

    - Patrones estacionales 

    - Revisar que lo encontrado corresponda a los boletines epidemiológicos  

