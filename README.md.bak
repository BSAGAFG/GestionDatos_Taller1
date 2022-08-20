# GestionDatos_Taller1
Taller clase Fabian Peña, materia Gestion de Datos

Los dataset seleccionados son:

Secuestro
Homicidio
Extorcion
Terrorismo


Puntos a desarrollar:
1. [15%] Seleccione al menos 4 conjuntos de datos y realice un perfilamiento de
cada uno. Describa los hallazgos encontrados en cada conjunto de datos. No
olvide mencionar su estructura y aspectos relevantes de calidad como campos
nulos, departamentos mal escritos, formatos de fechas incorrectos, entre otros.
Si no evidencia ningún problema de calidad de datos, también mencionelo.

Respuesta:

-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------
Revisando el conjunto de datos del dataset Extorcion

El resumen general del dataframe es el siguiente:

Dataset statistics

Number of variables	6
Number of observations	69137
Missing cells	0
Missing cells (%)	0.0%
Duplicate rows	0
Duplicate rows (%)	0.0%
Total size in memory	3.2 MiB
Average record size in memory	48.0 B
Variable types

Categorical	4
Numeric	2

En el resumen notamos que no hay datos nulos ni datos en formatos que no sean consistentes.
Podemos observar datos como cantidad de observaciones por variable, tipo de dato, media, valores minimos, maximos
entre otros.

Los tipos de datos de las variables son:

FECHA HECHO     object
COD_DEPTO        int64
DEPARTAMENTO    object
COD_MUNI        object
MUNICIPIO       object
CANTIDAD         int64

Se tienen un total de 6 columnas con las variables: 

--------------------------
FECHA HECHO
Categorical

Distinct	8839
Distinct (%)	12.8%
Missing	0
Missing (%)	0.0%
Memory size	540.3 KiB

Muestra de los datos:
						Cantidad
02/15/2019 12:00:00 AM	 38
03/01/2022 12:00:00 AM	 37
10/20/2020 12:00:00 AM	 37
03/01/2019 12:00:00 AM	 36
07/25/2018 12:00:00 AM	 36
Other values (8834)		 68953 

--------------------------
COD_DEPTO
Real number (ℝ≥0)HIGH CORRELATION

Distinct	33
Distinct (%)	< 0.1%
Missing	0
Missing (%)	0.0%
Infinite	0
Infinite (%)	0.0%
Mean	38.86635231
Minimum	5
Maximum	99
Zeros	0
Zeros (%)	0.0%
Negative	0
Negative (%)	0.0%
Memory size	540.3 KiB

--------------------------
DEPARTAMENTO
Categorical

Distinct	33
Distinct (%)	< 0.1%
Missing	0
Missing (%)	0.0%
Memory size	540.3 KiB

Muestra de los datos:

					Cantidad
ANTIOQUIA			9580 
VALLE DEL CAUCA		6656 
BOGOTÁ D.C.			5142 
META				4487 
TOLIMA	 			3117
Other values (28)	40155 

--------------------------
COD_MUNI
Categorical

Distinct	1071
Distinct (%)	1.5%
Missing	0
Missing (%)	0.0%
Memory size	540.3 KiB
11,001	 5142
5,001	 3684
76,001	 2709
50,001	 2319
8,001	 1597
Other values (1066)	53686 
	
--------------------------
MUNICIPIO
Categorical

Distinct	989
Distinct (%)	1.4%
Missing	0
Missing (%)	0.0%
Memory size	540.3 KiB

Muestra de los datos:

					Cantidad
BOGOTA, D.C.	 	5141
MEDELLIN	 		3684
CALI	 			2709
VILLAVICENCIO	 	2319
BARRANQUILLA	 	1597
Other values (984)	53687 

--------------------------
CANTIDAD
Real number

Distinct	23
Distinct (%)	< 0.1%
Missing	0
Missing (%)	0.0%
Infinite	0
Infinite (%)	0.0%
Mean	1.257503218
Minimum	1
Maximum	89
Zeros	0
Zeros (%)	0.0%
Negative	0
Negative (%)	0.0%
Memory size	540.3 KiB

-------------------------------------------------------------
Revisando el conjunto de datos del dataset Terrorismo

El resumen general del dataframe es el siguiente:

Dataset statistics

Number of variables	6
Number of observations	3954
Missing cells	0
Missing cells (%)	0.0%
Duplicate rows	5
Duplicate rows (%)	0.1%
Total size in memory	185.5 KiB
Average record size in memory	48.0 B
Variable types

Categorical	4
Numeric	2

En el resumen notamos que no hay datos nulos, pero si se estiman 5 observaciones duplicadas.
Podemos observar datos como cantidad de observaciones por variable, tipo de dato, media, valores minimos, maximos
entre otros.

Los tipos de datos de las variables son:

Departamento    object
Municipio       object
CODIGO DANE      int64
ARMAS MEDIOS    object
FECHA HECHO     object
CANTIDAD         int64

Se tienen un total de 6 columnas con las variables: 

--------------------------
Departamento
Categorical

Distinct	29
Distinct (%)	0.7%
Missing	0
Missing (%)	0.0%
Memory size	31.0 KiB

Muestra de los datos:

					Cantidad
ANTIOQUIA			685 
NORTE DE SANTANDER	427 
ARAUCA				355 
NARIÑO				346 
CAUCA				326 
Other values (24)	1815 

--------------------------
Municipio
Categorical

Distinct	407
Distinct (%)	10.3%
Missing	0
Missing (%)	0.0%
Memory size	31.0 KiB

Muestra de los datos:

						 Cantidad
SAN ANDRES DE TUMACO	 161
TIBÚ	 				 118
ARAUQUITA	 			 93
ORITO	 				 92
NEIVA (CT)	 			 89
Other values (402)		 3401 

--------------------------
CODIGO DANE
Real number

Distinct	419
Distinct (%)	10.6%
Missing	0
Missing (%)	0.0%
Infinite	0
Infinite (%)	0.0%
Mean	45462302.48
Minimum	5001000
Maximum	99773000
Zeros	0
Zeros (%)	0.0%
Negative	0
Negative (%)	0.0%
Memory size	31.0 KiB

--------------------------
ARMAS MEDIOS
Categorical

Distinct	32
Distinct (%)	0.8%
Missing	0
Missing (%)	0.0%
Memory size	31.0 KiB

Muestra de los datos:

									Cantidad
ARTEFACTO EXPLOSIVO/CARGA DINAMITA	1638 
GRANADA DE MANO						778 
COMBUSTIBLE							330 
ARTEFACTO INCENDIARIO				263 
ARMA DE FUEGO						224 
Other values (27)					721 

--------------------------
FECHA HECHO
Categorical

UNIFORM
Distinct	2179
Distinct (%)	55.1%
Missing	0
Missing (%)	0.0%
Memory size	31.0 KiB

Muestra de los datos:

					Cantidad
10/08/2012	 		14
27/01/2022	 		11
31/03/2016	 		10
14/02/2020	 		10
23/02/2022	 		10
Other values (2174)	3899 

--------------------------
CANTIDAD
Real number

Distinct	6
Distinct (%)	0.2%
Missing	0
Missing (%)	0.0%
Infinite	0
Infinite (%)	0.0%
Mean	1.042235711
Minimum	1
Maximum	8
Zeros	0
Zeros (%)	0.0%
Negative	0
Negative (%)	0.0%
Memory size	31.0 KiB

-------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------


2. [20%] Responda la siguientes preguntas para cada uno de los conjuntos de
datos seleccionados:
2.1. [4%] ¿Cuáles han sido los departamentos (TOP 3) más afectados en
términos de cantidad de delitos cometidos en los últimos 5 años?
2.2. [4%] Para los casos en los que aplique, ¿cuál ha sido el arma o medio
más común para cometer el delito?
2.3. [4%] Para los casos en los que aplique, ¿cómo ha sido la proporción de
géneros y grupos etarios que han estado involucrados en este tipo de
delito? ¿Han variado con el paso de los años?
2.4. [4%] ¿Se evidencia alguna tendencia para cometer dicho delito en algún
mes particular del año?
2.5. [4%] Para los casos en los que se disponga del detalle del delito o de una
descripción, como por ejemplo en delitos sexuales y secuestro, ¿cuáles
son las descripciones o modalidades más comunes?

