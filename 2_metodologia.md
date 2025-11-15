# **Metodología**

## **Fuentes de datos**
[comment]: <> (Añadir la descripción de las fuentes y el pq las tomamamos)

[comment]: <> (Añadir Tambien el pq eleigimos ese periodo)

## **Variables de estudio**
[comment]: <> (Tanto las de dengue como las variables de entorno)

##  **Definición de indicadores**
[comment]: <> (Incidencia, REM)

### *Razón Estandarizada de Morbilidad (REM)*



| MUNICIPIO        |   casos |   esperado |      REM |
|:-----------------|--------:|-----------:|---------:|
| BARANOA          |    1021 |   681.512  | 1.49814  |
| CAMPO DE LA CRUZ |     147 |   248.785  | 0.590871 |
| CANDELARIA       |      52 |   175.695  | 0.295967 |
| GALAPA           |     837 |   657.891  | 1.27225  |
| JUAN DE ACOSTA   |     249 |   225.477  | 1.10433  |
| LURUACO          |     271 |   304.225  | 0.890788 |
| MALAMBO          |    1675 |  1398.51   | 1.1977   |
| MANATÍ           |     253 |   216.718  | 1.16742  |
| PALMAR DE VARELA |     100 |   317.916  | 0.314548 |
| PIOJÓ            |      69 |    71.9244 | 0.95934  |
| POLONUEVO        |     394 |   196.548  | 2.0046   |
| PONEDERA         |     186 |   255.75   | 0.727272 |
| PUERTO COLOMBIA  |     766 |   563.463  | 1.35945  |
| REPELÓN          |      95 |   281.551  | 0.337416 |
| SABANAGRANDE     |      94 |   355.591  | 0.264349 |
| SABANALARGA      |    1083 |   990.362  | 1.09354  |
| SANTA LUCÍA      |      41 |   176.092  | 0.232833 |
| SANTO TOMÁS      |      73 |   329.282  | 0.221695 |
| SOLEDAD          |    6673 |  6619.4    | 1.0081   |
| SUAN             |     119 |   130.573  | 0.911368 |
| TUBARÁ           |      74 |   188.21   | 0.393177 |
| USIACURÍ         |     250 |   136.519  | 1.83125  |

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

