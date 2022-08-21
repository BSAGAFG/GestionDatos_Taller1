# GestionDatos_Taller1
Taller clase Fabian Peña, materia Gestion de Datos
Presentado por: Norbey Marin
				Bryan Leonardo Figueredo



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

------------------------------------------------------------------------------
 Analisis del DataSet secuestro:
------------------------------------------------------------------------------
Tipo de los datos

FECHA HECHO     object
COD_DEPTO        int64
DEPARTAMENTO    object
COD_MUNI        object
MUNICIPIO       object
TIPO DELITO     object
CANTIDAD         int64
dtype: object
------------------------------------------------------------------------------
Number of variables	7
	-Categorical	5
	-Numeric	2
Number of observations	18642
Missing cells	0
Missing cells (%)	0.0%
Duplicate rows	0
Duplicate rows (%)	0.0%
------------------------------------------------------------------------------
***********Resumen de las Variables contenidas en el dataset******************

variable(Categorical): FECHA HECHO
	Distinct	6098
	Distinct (%)	32.7%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Real number): COD_DEPTO
	Distinct	33
	Distinct (%)	0.2%
	Missing	0
	Missing (%)	0.0%
	Infinite	0
	Infinite (%)	0.0%
	Mean	37.58260916
	Minimum	5
	Maximum	99
	Zeros	0
	Zeros (%)	0.0%
	Negative	0
	Negative (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical): DEPARTAMENTO
	Distinct	33
		ANTIOQUIA	3139 
		VALLE DEL CAUCA	1288 
		BOGOTÁ D.C.	1227 
		CESAR	1106 
		SANTANDER	 1034
		Other values (28)	1084
	Distinct (%)	0.2%
	Missing	0
	Missing (%)	0.0%
	8 
------------------------------------------------------------------------------
Variable(Categorical):COD_MUNI
	Distinct	971
		11,001	 1227
		5,001	 699
		76,001	 576
		50,001	 420
		47,001	 290
		Other values (966)	15430
	Distinct (%)	5.2%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------	
Variable(Categorical):MUNICIPIO
	Distinct	902
		BOGOTA, D.C.	 1227
		MEDELLIN	 699
		CALI	 576
		VILLAVICENCIO	 420
		SANTA MARTA	 290
		Other values (897)	15430 
	Distinct (%)	4.8%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------	
Variable(Categorical):TIPO DELITO
	Distinct	2
		SECUESTRO EXTORSIVO	11816 
		SECUESTRO SIMPLE	6826 
	Distinct (%)	< 0.1%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
variable(Real number):CANTIDAD
	Distinct	39
	Distinct (%)	0.2%
	Missing	0
	Missing (%)	0.0%
	Infinite	0
	Infinite (%)	0.0%
	Mean	1.45129278
	Minimum	1
	Maximum	156
	Zeros	0
	Zeros (%)	0.0%
	Negative	0
	Negative (%)	0.0%
	
------------------------------------------------------------------------------
 Analisis del DataSet Homicidios:
------------------------------------------------------------------------------
Tipo de los datos

DEPARTAMENTO            object
MUNICIPIO               object
CODIGO DANE              int64
ARMAS MEDIOS            object
FECHA HECHO             object
GENERO                  object
GRUPO ETARÍO            object
DESCRIPCIÓN CONDUCTA    object
CANTIDAD                 int64
dtype: object
------------------------------------------------------------------------------
***********Resumen de las Variables contenidas en el dataset Homicidios******************
------------------------------------------------------------------------------
Number of variables	9
	Categorical	7
	Numeric	2
Number of observations	59810
Missing cells	0
Missing cells (%)	0.0%
Duplicate rows	5
Duplicate rows (%)	< 0.1%
------------------------------------------------------------------------------
Variable(Categorical): DEPARTAMENTO
	Distinct	32
		CUNDINAMARCA	9026 
		ANTIOQUIA	7800 
		VALLE	7646 
		SANTANDER	3076 
		CESAR	 2457
		Other values (27)	29805
	Distinct (%)	0.1%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical):MUNICIPIO
	Distinct	969
		BOGOTÁ D.C. (CT)	4809 
		CALI (CT)	 	2853
		MEDELLÍN (CT)	 	2712
		BARRANQUILLA (CT)	904
		CARTAGENA (CT)	 	889
		Other values (964)	47643 
	Distinct (%)	1.6%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Real number):CODIGO DANE
	Distinct	1041
	Distinct (%)	1.7%
	Missing	0
	Missing (%)	0.0%
	Infinite	0
	Infinite (%)	0.0%
	Mean	38472459.81
	Minimum	5001000
	Maximum	99773000
	Zeros	0
	Zeros (%)	0.0%
	Negative	0
	Negative (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical):ARMAS MEDIOS
	Distinct	7
		VEHICULO	34319 
		MOTO	18230 
		NO REPORTADO	4536 
		SIN EMPLEO DE ARMAS	 2096
		BICICLETA	 552
		Other values (2)	 77
	Distinct (%)	< 0.1%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical):FECHA HECHO
	Distinct	4503
		1/01/2022	 51
		7/02/2021	 48
		1/01/2021	 46
		19/09/2021	 45
		9/01/2022	 45
		Other values (4498)	59575 
	Distinct (%)	7.5%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical):GENERO
	Distinct	4
		MASCULINO	47431 
		FEMENINO	12319 
		NO REPORTADO	 45
		NO REPORTA	 15
	Distinct (%)	< 0.1%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical):GRUPO ETARÍO
	Distinct	4
		ADULTOS	54671 
		ADOLESCENTES	 2924
		MENORES	 2170
		NO REPORTADO	 45
	Distinct (%)	< 0.1%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Categorical):DESCRIPCIÓN CONDUCTA
	Distinct	2
		ARTÍCULO 109. HOMICIDIO CULPOSO ( EN ACCIDENTE DE TRÁNSITO)	59800 
		ARTÍCULO 110. HOMICIDIO CULPOSO ( CIRCUNSTANCIAS DE AGRAVACIÓN)	 10
	Distinct (%)	< 0.1%
	Missing	0
	Missing (%)	0.0%
------------------------------------------------------------------------------
Variable(Real number):CANTIDAD

	Distinct	10
	Distinct (%)	< 0.1%
	Missing	0
	Missing (%)	0.0%
	Infinite	0
	Infinite (%)	0.0%
	Mean	1.098110684
	Minimum	1
	Maximum	10
	Zeros	0
	Zeros (%)	0.0%
	Negative	0
	Negative (%)	0.0%

-------------------------------------------------------------------------------------------------------------


2. [20%] Responda la siguientes preguntas para cada uno de los conjuntos de
datos seleccionados:
2.1. [4%] ¿Cuáles han sido los departamentos (TOP 3) más afectados en
términos de cantidad de delitos cometidos en los últimos 5 años?

Para esta secion, notamos que debemos realizar un casteo de la columna fecha, convirtiendola en formato fecha.
Para esto, generamos una funcion como se muestra en el codigo, posterior a esto, calculamos la fecha mayor y
realizmos una resta en años para tomar los ultimos 5, dando como resultado en los 4 dataset seleccionados
lo siguiente:

---------------------Secuestro-------------------------------
DEPARTAMENTO
VALLE DEL CAUCA    100
ANTIOQUIA           92
CAUCA               86
Name: CANTIDAD, dtype: int64
 
---------------------Homicidios-------------------------------
DEPARTAMENTO
CUNDINAMARCA    3945
ANTIOQUIA       3755
VALLE           3177
Name: CANTIDAD, dtype: int64
 
---------------------Extorcion-------------------------------
DEPARTAMENTO
ANTIOQUIA          6333
BOGOTÁ D.C.        5472
VALLE DEL CAUCA    4810
Name: CANTIDAD, dtype: int64
 
---------------------Terrorismo-------------------------------
Departamento
ANTIOQUIA             228
NORTE DE SANTANDER    170
ARAUCA                165
Name: CANTIDAD, dtype: int64
-------------------------------------

2.2. [4%] Para los casos en los que aplique, ¿cuál ha sido el arma o medio
más común para cometer el delito?

Para este punto, revisamos inicialmente en cuales dataset aplica la pregunta, con esto descartamos el dataset de secuestro y extorcion. 
Posterior a esto, realizamos una seleccion de las categorias involucradas en este item por dataset y contamos la cantidad de veces
en las que un arma o medio se vio involucrado, dando como resultado lo siguiente:

---------------------Categorias Homicidios-------------------------------
['MOTO' 'VEHICULO' 'NO REPORTADO' 'BICICLETA' 'SIN EMPLEO DE ARMAS' 'TREN'
 'CONTUNDENTES']
 
---------------------Cantidad por categoria------------------------------
VEHICULO               34319
MOTO                   18230
NO REPORTADO            4536
SIN EMPLEO DE ARMAS     2096
BICICLETA                552
TREN                      73
CONTUNDENTES               4
Name: ARMAS MEDIOS, dtype: int64
 
 
Para esta el medio mas utilizado es VEHICULOS con un total de 34319
 
---------------------Categorias Terrorismo-------------------------------
['ARTEFACTO EXPLOSIVO/CARGA DINAMITA' 'ARTEFACTO INCENDIARIO'
 'GRANADA DE MANO' 'CILINDRO BOMBA' 'MINA ANTIPERSONA' 'COMBUSTIBLE'
 'OLLA BOMBA' 'PAQUETE BOMBA' '-' 'PETARDO PLANFETARIO' 'CARRO BOMBA'
 'PERSONA BOMBA' 'ROCKET' 'BICICLETA BOMBA' 'CANTINA BOMBA'
 'CABALLO BOMBA' 'MOTO BOMBA' 'GRANADA DE FUSIL' 'GRANADA DE MORTERO'
 'ARMA DE FUEGO' 'LANCHA BOMBA' 'CASA BOMBA' 'BALON BOMBA'
 'PAPA EXPLOSIVA' 'BURRO BOMBA' 'NO REPORTADO' 'CARTA BOMBA'
 'SIN EMPLEO DE ARMAS' 'ARMA BLANCA / CORTOPUNZANTE' 'CONTUNDENTES'
 'DIRECTA' 'PERRO BOMBA']
 
---------------------Cantidad por  categoria-------------------------------
ARTEFACTO EXPLOSIVO/CARGA DINAMITA    1638
GRANADA DE MANO                        778
COMBUSTIBLE                            330
ARTEFACTO INCENDIARIO                  263
ARMA DE FUEGO                          224
NO REPORTADO                           160
MINA ANTIPERSONA                       151
PAQUETE BOMBA                           79
CILINDRO BOMBA                          65
SIN EMPLEO DE ARMAS                     65
CARRO BOMBA                             47
MOTO BOMBA                              30
-                                       24
GRANADA DE MORTERO                      23
OLLA BOMBA                              19
GRANADA DE FUSIL                        13
PETARDO PLANFETARIO                      8
BALON BOMBA                              6
CONTUNDENTES                             5
ROCKET                                   5
PAPA EXPLOSIVA                           3
CANTINA BOMBA                            3
LANCHA BOMBA                             2
CASA BOMBA                               2
CABALLO BOMBA                            2
ARMA BLANCA / CORTOPUNZANTE              2
DIRECTA                                  2
BICICLETA BOMBA                          1
BURRO BOMBA                              1
PERSONA BOMBA                            1
CARTA BOMBA                              1
PERRO BOMBA                              1
Name: ARMAS MEDIOS, dtype: int64


Para esta el medio mas utilizado es ARTEFACTO EXPLOSIVO/CARGA DINAMITA con un total de 1638

2.3. [4%] Para los casos en los que aplique, ¿cómo ha sido la proporción de
géneros y grupos etarios que han estado involucrados en este tipo de
delito? ¿Han variado con el paso de los años?

2.4. [4%] ¿Se evidencia alguna tendencia para cometer dicho delito en algún
mes particular del año?

2.5. [4%] Para los casos en los que se disponga del detalle del delito o de una
descripción, como por ejemplo en delitos sexuales y secuestro, ¿cuáles
son las descripciones o modalidades más comunes?

