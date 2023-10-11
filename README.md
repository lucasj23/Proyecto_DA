![image](https://github.com/lucasj23/Proyecto_DA/assets/131183621/381a326d-736b-4459-b516-773a6180ac9b)

# DATA SCIENCE - PROYECTO INDIVIDUAL Nº2: Data Analytics

# Contexto - Rol - Tarea a desarrollar

La aviación es una industria que ha transformado nuestra forma de viajar y ha desempeñado un papel fundamental en la conectividad global, desde hace muchisimos años. Se entiende por aviación al diseño, desarrollo, fabricación, producción, operación y utilización para fines privados o comerciales de aeronaves, especialmente las más pesadas que el aire . Sin embargo, así como la aviación existe desde hace muchisimo tiempo y nos ha traido muchisimas ventajas, también nacieron con ella los accidentes aéreos.
Nos referimos a accidentes aéreos cuando hablamos de eventos inesperados que involucran aeronaves y pueden tener graves consecuencias en términos de vidas humanas y pérdidas materiales. 

La causa de los accidentes aéreos puede ser diversa y variar. Las consecuencias de estos accidentes pueden ser significativas tanto en términos de pérdidas humanas como en pérdidas económicas. Es por esta razón que siempre existe la preocupación continua de mejorar la seguridad de la aviación y trabajar para mejorar día a día lo que es la seguridad aeronáutica. Para estos fines mencionados es que se desarrolló el presente proyecto. 

En este proyecto, nos situaremos en el papel de exploración y análisis de datos relacionados con accidentes aéreos que han ocurrido desde principios del siglo XX. El objetivo es realizar un análisis exhaustivo de los accidentes aéreos que han ocurrido desde principios del siglo XX y obtener un análisis de datos relacionado a estos incidentes. Para ello, además del análisis, se creará un dashboard interactivo en la herramienta Power BI, complementando así los análisis con visualizaciones informativas.

![image](https://github.com/lucasj23/Proyecto_DA/assets/131183621/45889498-aedd-4d2f-8ab5-3c2aed4ef6ac)


## Descripción

El análisis de accidentes aéreos es crucial para comprender la seguridad en la aviación y aprender de eventos pasados. Este proyecto se centra en la exploración y el análisis de datos detallados sobre accidentes de aviones, lo que incluye información sobre fechas (análisis de tiempo), ubicaciones, aerolíneas, tipos de aeronaves, número total de personas a bordo, fatalidades, supervivientes y mucho más.

## Objetivos

- Investigar en profundidad los accidentes aéreos ocurridos desde principios del siglo XX hasta la actualidad.
- Realizar un análisis exploratorio de datos para identificar patrones, tendencias y relaciones en los incidentes.
- Crear un dashboard interactivo en Power BI que complemente los análisis con visualizaciones informativas y útiles.
- Analizar las tendencias, evoluciones a lo largo del tiempo, diferentes variables y sus relaciones.
- Finalmente, analizar y entender dos KPI's (Key performance indicators) en particular, captando y comprendiendo el contenido de cada una de las métricas que intervienen en ellos, para luego relacionarlas con el objetivo pautado. 

## Contenido

- **EDA (Análisis exploratorio de datos) y ETL (Extract, Transform, Load)**: Este proyecto incluye un Jupyter Notebook que contiene el código Python utilizado para realizar el análisis exploratorio de datos y asimismo el proceso de ETL. Para tales fines se utilizan librerías como Pandas, Numpy, Matplotlib, Seaborn, Sklearn, entre otras para el análisis y visualización de datos. Aquí en particular se hicieron tareas de análisis, limpieza, agregaciones y conclusiones puntuales para cada variable y/o columna interviniente en el dataframe brindado. El objetivo ulterior es dejar la información lista para ser consumida para las visualizaciones.

- **Power BI Analysis**: Los resultados del EDA y ETL se importan y se realizan análisis más avanzados en Power BI. Se utiliza Power BI para crear visualizaciones interactivas y realizar un análisis más profundo de los datos, visualizando gráficos interactivos, con filtros y segmentaciones que afectan globalmente a todos los puntos de cada página, mostrando las diferencias y similitudes en cada visualización, siempre buscando la mejor asimilación de la información proporcionada, a través de las visuales. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://github.com/lucasj23/Proyecto_DA/assets/131183621/2509c11a-0628-448c-85df-c37b89f1d328)

## Dashboard e Insights


En el archivo ‘Dashboard – Accidentes Aereos’ (informe de Power BI) se encontrarán las visualizaciones interactivas y análisis avanzado. El dashboard consta de 1 portada y 5 páginas navegables. Se incluyen las siguientes páginas:

Página 1: Resumen General: Resumen de estadísticas clave y una visión general de los accidentes aéreos, siempre con el foco puesto en la segmentación por país. 

![image](https://github.com/lucasj23/Proyecto_DA/assets/131183621/374c0441-0b78-4ad0-bfb2-124c8c59cb95)

Conclusiones:
-  Se pueden observar los accidentes y fallecidos en total (incluyendo tanto pasajeros a bordo, como tripulación a bordo) por país, pudiendo filtrar a su vez por cada país que se quiera elegir. Cabe destacar que, lógicamente y como se explico, al seleccionar alguno o varios de estos filtros mencionados, el resto de la página se ve modificada acorde los datos en particular para ese filtro que se elija, es decir se vuelve interactivo. A su vez, la plantilla incluye otro filtro respecto al año en particular, la categoría del vuelo y lugar del accidente. 
-  Incluimos además un mapa también interactivo respecto al país que estemos segmentando, lo que nos sirve para ubicarnos respecto a la localizacion de los accidentes. Las burbujas mas grandes nos sirven para identificar mayores números o cantidades en las variables que filtramos, muy significativo si queres plasmarlo en un mapa geolocalizado. 
-  También se visualizan tarjetas que muestran la cantidad de accidentes historicamente, la cantidad de paises involucrados o que han tenido accidentes a lo largo de la historia y el total de personas que se han visto involucradas (es decir a bordo de aviones que han sufrido accidentes). Vemos que son numeros relativamente altos, tanto la cantidad de accidentes historicos, como las personas involucradas (estamos hablando de millones) y fallecimientos, como la cantidad de paises. 
-  Podemos observar a Estados Unidos como el país con mayor cantidad de accidentes a lo largo de la historia y Rusia como el segundo. También tienen el mismo puesto en el ranking de cantidad de personas fallecidas.  



Página 2: Análisis Temporal: Visualización de la distribución de accidentes aéreos a lo largo del tiempo. 

![image](https://github.com/lucasj23/Proyecto_DA/assets/131183621/e4e80c98-386a-4f4a-8619-7422f99c74e9)


Conclusiones:
- Aquí analizamos precisamente como ha evolucionado cada variable a lo largo del tiempo. Si bien lo dejamos configurado por defecto para que nos muestre la información relativa a los últimos 20 años, que es lo que nos interesaba averiguar en nuestro KPI principal, podemos visualizar la distribución desde el primer accidente registrado en el año 1908 hasta el último registrado en el año 2021.
- Visualizamos que en los ultimos 20 años se han registrado 690 accidentes, y ha habido más de 70.000 sobrevivientes respecto al total de personas que han ido a bordo. Dato no menor, considerando que la tasa de mortalidad de pasajeros asciende a casi el 70% (fórmula de fallecidos sobre el total de pasajeros a bordo).
- También vemos que hay una clara tendencia a la baja en la cantidad de accidentes a medida que nos acercamos a la actualidad. El pico de los últimos 20 años se puede observar en 2003 con 62 accidentes, y desde ahí hasta el año 2021 se puede observar como ha ido disminuyendo la cantidad de accidentes relativamente a medida que transcurren los años, llegando a registrarse solo 7 accidentes en el último año. Esto significaría, comparando los dos puntos (el más alto en 2003 y el más bajo en 2001) casi 9 veces menos accidentes, un dato muy importante.
- También vemos, que en promedio, la tasa de supervivencia de los accidentes de los últimos 20 años ha sido practicamente del 30%. Esto significa que -en promedio, aclaramos nuevamente-, de cada 100 personas que han viajado a bordo de una aeronave que se ha visto accidentada, 30 personas se han salvado, es decir han sobrevivido. Esto es incluyendo tanto pasajeros como tripulación a bordo.



Página 3: Análisis de Supervivencia: Información sobre la supervivencia de pasajeros y miembros de la tripulación en diferentes escenarios.

![image](https://github.com/lucasj23/Proyecto_DA/assets/131183621/8bb604f5-95e7-46be-9b4f-e34f553646c6)


Conclusiones: 
- Aquí visualizamos la información relacionada con las marcas de Aeronaves y Operadores/Aerolineas que mas participaciones han tenido en accidentes. Eso también se ve reflejada en la categoría del vuelo (militar/no militar) y en la aeronave en particular.
- Podemos visualizar claramente que la marca de Aeronaves 'McDonell Douglas' fue por mucha diferencia, la que más accidentes registró a lo largo de la historia. A su vez, la Aeronave en particular 'Douglas DC-3' fue la que más accidentes y fallecimientos registró.
- Podemos decir entonces, relacionando ambas variables (Marca - Aeronave) que los aviones Douglas resultaron, a lo largo de la historia, los aviones con más cantidad de siniestros. Esto se concluye porque, según se pudo averiguar, el fabricante de aviones Douglas Aircraft Company (conocido comúnmente como Douglas) dejó de existir como entidad independiente en 1967. En ese año, se fusionó con McDonnell Aircraft Corporation para formar McDonnell Douglas Corporation. 
A su vez, McDonnell Douglas fue adquirida por The Boeing Company en 1997.
- En conclusión, tanto McDonell, Douglas y Boeing, han estado relacionados a lo largo de los ultimos 60-70 años y podemos decir que han presentado un elevado número de siniestros comparados con el resto de las marcas.
- Asimismo, la aerolínea 'Aeroflot' y la Fuerza Aerea americana son los dos operadores que mas preponderan también a la hora de contabilizar accidentes.
- Claramente se ve también que, a lo largo de los años, la mayor cantidad de accidentes han sido de origen No Militar (casi un 85% del total de accidentes).


Contribuciones
Si deseas contribuir a este proyecto, siéntete libre de crear una bifurcación (fork) y enviar solicitudes de extracción (pull requests). Cualquier aportación, ya sea en forma de correcciones, mejoras o nuevas ideas, es bienvenida.

Licencia
Este proyecto se encuentra bajo la licencia MIT. Si deseas utilizar o modificar este código, por favor, consulta la licencia para obtener más detalles.

Contacto
Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto a través de [tu-email@example.com].

¡Esperamos que este análisis de accidentes aéreos y el informe de Power BI sean útiles y enriquecedores! Gracias por tu interés en este proyecto.
