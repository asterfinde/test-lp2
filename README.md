# Descripción del caso
En este estudio, se recopilaron datos transversales de las Encuestas demográficas y de salud de Nigeria (NDHS) de 2018 para responder a preguntas de investigación sobre el efecto de la edad de las madres y otros factores socioeconómicos en el nivel de anemia de los niños de 0 a 59 meses en Nigeria. Las DHS son encuestas transversales de hogares representativas a nivel nacional que generalmente se realizan cada 5 años.
Los datos de esta encuesta consideraron los 36 estados de Nigeria, así como el Territorio de la Capital Federal (FCT). La población objetivo de este estudio son los niños de 0 a 59 meses y las madres de 15 a 49 años.
En esta encuesta, el ingreso del hogar se midió utilizando el índice de riqueza, la edad actual en grupos de 5 años se produce agrupando la edad actual en años completados, tipo de lugar de residencia donde el encuestado fue entrevistado como urbano o rural, la categorización se creó en función de si el número de punto de muestra o conglomerado se define como urbano o rural, el nivel más alto de educación alcanzado es una variable estandarizada que proporciona el nivel de educación en las siguientes categorías: Sin educación, Educación primaria, secundaria y superior, el número total de nacimientos en los últimos cinco años se define como todos los nacimientos en los meses 0 a 59 anteriores al mes de la entrevista, donde el mes 0 es el mes de la entrevista, la edad del encuestado en el primer nacimiento se calcula utilizando el CMC de la fecha de nacimiento del encuestado.

Después de la depuración de los datos, se utilizó el método Chi cuadrado para probar las hipótesis sobre la posible relación que existe entre ciertos factores socioeconómicos y los niveles de anemia en niños de 0 a 59 meses. El nivel de anemia fue la variable predictora y las variables explicativas son la edad de la madre, el nivel de educación, el índice de riqueza, el nacimiento en los últimos cinco años, el uso de mosquiteros, etc.

# Diccionario de datos
Type of place of residence
```Python
0: Rural
1: Urban


Highest educational level
0: Higher
1: No education
2: Primary
3: Secondary


Wealth index combined
0: Middle
1: Poorer
2: Poorest
3: Richer
4: Richest


Anemia level
0: Mild
1: Moderate
2: Not anemic
3: Severe


Have mosquito bed net for sleeping (from household questionnaire)
0: No
1: Yes


Smokes cigarettes
0: No
1: Yes


Current marital status
0: Divorced
1: Living with partner
2: Married
3: Never in union
4: No longer living together/separated
5: Widowed


Currently residing with husband/partner
0: Living with her
1: Staying elsewhere


When child put to breast
0: 102.0
1: 103.0
2: 104.0
... (continuando con valores similares)
38: Days: 1
39: Hours: 1
40: Immediately


Had fever in last two weeks
0: Don't know
1: No
2: Yes


Taking iron pills, sprinkles or syrup
0: Don't know
1: No
2: Yes
```