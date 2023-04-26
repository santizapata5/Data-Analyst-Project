## Proyecto Individual #2 - Data Analytics


Para el presente proyecto se realizó un análisis completo del comportamiento del acceso a internet en Argentina, gracias a los datos abiertos de ***ENACOM***. 

Se emplearon un total de 11 conjuntos de datos proporcionados por ***ENACOM***. Agrupados en dos categorías: general y provincias, según correspondieran a la información general del país o al desglose de las provincias.

Los datasets de la categoría general son:

1. Velocidad media de bajada.
2. Distribución de las tecnologías entre Banda Ancha y Dial Up.
3. Ingresos en miles de pesos argentinos.
4. Acceso por cada 100 hogares y cada 100 habitantes.
5. La velocidad media de bajada, desglosada por 7 rangos.
6. Las tecnologías que hacen parte de Banda Ancha y Dial Up como ADSL, Cablemodem, fibra óptica, Wireless, entre otros.

Los restantes datasets son de la categoría 'provincias':

1. Velocidad media de bajada por provincia.
2. Banda ancha y Dial up por provincia.
3. Acceso por cada 100 hogares y habitantes por provincia.
4. Rangos de velocidad de bajada media por provincia.
5. Tecnologías (ADSL, Cablemodem, fibra, etc)

Estos conjuntos de datos fueron unidos de acuerdo a columnas comunes como "Año", "Trimestre", "Periodo", etc, con la finalidad de optimizar el proceso de limpieza de los datos, análisis y carga a la herramienta de visualización en linea empleada (Looker Studio).

En las libretas de Jupyter llamadas ***'ETL & EDA General'*** y ***'ETL & EDA Provincias'*** se encuentra el trabajo realizado mediante numpy, pandas y matplotlib para efectos de transformación, limpieza, análisis, exploración, visualización, entre otros. 

Posteriormente se realizó el reporte del análisis, con su respectivo dashboard y KPI's utilizando la herramienta gratuita de Google ***Looker Studio***. En el mismo reporte podrán encontrar mayor información acerca del contexto de la entidad, los KPI's sugeridos y algunas conclusiones.

Enlace al dashboard en línea: [***Dashboard***](https://lookerstudio.google.com/reporting/c01cc39d-e52d-4020-8b2e-668304889813)
