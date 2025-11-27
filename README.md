# proyectoiiprograii
Proyecto II Programación II


Descripcion breve del proyecto: 
El presente proyecto tiene como objetivo realizar un análisis descriptivo de las
principales variables que tienen que ver con la prevalencia de enfermedades 
infecciosas tomando como ejemplos de analisis al HIV, TUBERCULOSIS y Dengue en diferentes países alrededor 
del mundo junto con las características económicas de estos países, para evidenciar el comportamiento de estas variables
a traves de los ultimos años. 

Informacion de las bases de datos:

FECHA DE DESCARGA: 12-11-25
BASE DENGUE 1
dengue-global-data-2025-11-12.xlsx
https://worldhealthorg.shinyapps.io/dengue_global/
LICENCIA: Creative Commons Attribution 4.0 International (CC BY 4.0)

BASE DENGUE 
Content licensed under CC BY 4.0.
National_extract_V1_3.csv
https://opendengue.org/

BASE TUBERCULOSIS 
Our charts, articles, and data are licensed under CC BY, unless stated otherwise
number-of-tuberculosis-cases.csv
https://ourworldindata.org/grapher/number-of-tuberculosis-cases

BASE HIV 
Licence: CC BY-NC-SA 3.0 IGO. 
HIV_estimates_from_1990-to-present.xlsx
https://www.unaids.org/en/resources/documents/2025/HIV_estimates_with_uncertainty_bounds_1990-present

BASE GASTO DEL PIB EN SALUD POR PAIS
Licencia Creative Commons Reconocimiento 4.0 Internacional (CC BY 4.0)
Gasto_corriente_en_salud_PIB(1).json
https://datos.bancomundial.org/indicador/SH.XPD.CHEX.GD.ZS
*Esta base originalmete se encuentra en XLS, pero para efectos del proyecto se traslada a JSON con autorizacion del docente

BASE INDICE DE PROBREZA
Licencia Creative Commons Reconocimiento 4.0 Internacional (CC BY 4.0)
indice de pobreza global.csv
https://pip.worldbank.org/



INSTRUCCIONES DE EJECUCIÓN:

1. ESTE PROYECTO ESTA DISEÑADO PARA SER EJECUTADO EN GOOGLE COLAB CON NOMBRE PROYECTO II(7) UBICADO EN SRC
2. CARGAR EL CUADERNO DISPONIBLE EN SRC https://github.com/Gusjh09/proyectoiiprograii/tree/main/src
3. USAR LAS BASES DISPONIBLES https://github.com/Gusjh09/proyectoiiprograii/tree/main/data_raw OJO, DEBE SER EN ESTE ORDEN DECENDENTE:
   
dengue-global-data-2025-11-12.xlsx
HIV_estimates_from_1990-to-present.xlsx
indice de pobreza global.csv
number-of-tuberculosis-cases.csv
Gasto_corriente_en_salud_PIB(1).json
National_extract_V1_3.csv

5. EJECUTAR EN ORDEN VERTICAL CADA CHUNK.
6. CUANDO SE INDIQUE INGRESE SU TOKEN DESDE NGROK
7. EJECUTE EL CHUNK DE SHINY, SEGUIDAMENTE VISITE LA URL PROPORCIONADA. SI EL SERVIDOR LEVANTÓ LA APLICACION DEBE MOSTRARLE UN SLIDE Y UN GRAFICO.
8. CONTINUE CON LA EJECUCION DE LAS SECCIONES OPCIONALES 

