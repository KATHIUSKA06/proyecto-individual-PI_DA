<p align="center"><img src="src\henry_logo.png" height=100></p>
<h1 align=center>PROYECTO INDIVIDUAL Nº2 </h1>


<h1 align=center>DATA ANALYTICS</h1>

<p align="center">
<img src="src\47618cf8f33a2bfbac2fa643111d5ef8.jpg"  height=400>
</p>
<hr>
<h1 align=center>Introducción</h1>
En un mundo cada vez más conectado, las telecomunicaciones se han convertido en el tejido que une a las personas, organizaciones y dispositivos a lo largo y ancho del planeta. Desde la transmisión de señales de radio hasta la revolución digital del internet, estas tecnologías han revolucionado la forma en que interactuamos, trabajamos, aprendemos y nos entretenemos.

En el contexto argentino, la industria de las telecomunicaciones desempeña un papel crucial, facilitando la información a nivel global y permitiendo una comunicación constante, incluso en tiempos de desafíos globales como la pandemia. La transferencia de datos y la comunicación fluyen a través de diversos medios, incluyendo el internet, líneas telefónicas fijas y móviles, abarcando prácticamente cada rincón del país.

Comparado con la media mundial, Argentina se encuentra en una posición destacada en el desarrollo de las telecomunicaciones, con un impresionante total de 62.12 millones de conexiones registradas para el año 2020. Este logro refleja un compromiso constante con la evolución y expansión de la conectividad en el país.

En este informe, se presentará el proceso utilizado para analizar la distribución de velocidades de Internet en diferentes regiones del país. El objetivo de este análisis es identificar patrones y tendencias en la calidad de la conexión a Internet en diversas localidades argentinas.

<h1 align=center>Descripción</h1>

La primera etapa de nuestro proceso involucra la importación de datos de la plataforma de ENACOM. En total, hemos importado 15 conjuntos de datos relacionados con la sección de Internet. Estos conjuntos de datos incluyen información valiosa sobre la velocidad de conexión, tecnologías utilizadas, ingresos generados y visualizaciones a nivel nacional y provincial.

La segunda etapa se constituye en el Análisis Exploratorio de Datos (EDA), en la cual se realizó una revisión exhaustiva de los datos. Para cada conjunto de datos, se llevó a cabo el tratamiento de datos nulos e imputación de valores faltantes, se revisaron los outliers y duplicados, se realizó una descripción estadística detallada y se generaron gráficos pertinentes.

Toda esta información detallada del proceso de EDA se encuentra en el documento [EDA](EDA.ipynb). Este análisis exhaustivo nos permitió comprender a fondo la calidad de los datos y extraer conocimientos clave que serán fundamentales en las etapas posteriores del análisis.

En la visualización de Datos, Se crearon visualizaciones de datos para representar gráficamente las velocidades promedio de Internet en diferentes localidades. Estas visualizaciones incluyeron gráficos de barras y mapas interactivos que destacaron las disparidades en la calidad de la conexión.

<h1 align=center>Desarrollo del Proyecto</h1>

## Observaciones Análisis exploratorio de los datos: (Exploratory Data Analysis-EDA)

Los archivos utilizados para este procesamiento, se encuentran en la carpeta  [Carpeta Datasets](datasetsxls).<br>
Algunas Observaciones son las siguientes:

### Gráfico Accesos Tecnología fija por año 

|  | |
| --------- | --------- |
| ![Texto alternativo 1](/src/tecnologias.png)| ![Texto alternativo 2](/src/tecnologia_prov.png) |

En el conjunto de datos "Acceso a Internet fijo por tecnología y provincia", se detalla el desglose anual de las tecnologías de Internet utilizadas en Argentina. Un aspecto destacado es el rápido crecimiento de la fibra óptica, seguida de cerca por el cable módem. Estas tecnologías están en ascenso gracias a su capacidad para ofrecer conexiones más rápidas y estables, mientras que el ADSL muestra una tendencia a la baja.

Es evidente que la provincia de Buenos Aires se destaca como líder en adopción tecnológica en el país. El cable módem y el ADSL son opciones de conectividad ampliamente utilizadas en esta región, lo que refleja un alto nivel de adopción tecnológica y una sólida infraestructura de telecomunicaciones. Esto permite a residentes y empresas disfrutar de conexiones de Internet de alta velocidad y confiabilidad, lo que facilita la navegación en línea, la comunicación efectiva y el acceso a una amplia gama de recursos digitales.
### Gráfico Accesos cada 100 hogares por provincia

|  | |
| --------- | --------- |
| ![Texto alternativo 1](/src/accesos_hogar.png) | ![Texto alternativo 2](/src/penetracion.png) |



En el conjunto de datos "internet_Penetracion," se destaca que la provincia de Capital Federal lidera en acceso a Internet por cada 100 hogares, mientras que Formosa muestra la menor disponibilidad. Esta disparidad pone de manifiesto las notables diferencias en la conectividad a Internet en diversas regiones de Argentina, influenciadas por factores como la infraestructura de telecomunicaciones, densidad poblacional, desarrollo económico e inversión tecnológica.

Paralelamente, a lo largo de los años, se ha registrado un crecimiento sostenido en el acceso a Internet en las distintas provincias del país. Este aumento no solo refleja la creciente importancia de la conectividad digital en la vida cotidiana de las personas, sino que también es un indicador esencial del progreso tecnológico y económico en Argentina.


### Gráfico Velocidad de bajada por provincias
|  | |
| --------- | --------- |
| ![Texto alternativo 1](/src/velocidad_prov.png) | ![Texto alternativo 2](/src/velocidad_media.png) |

En el análisis de datos a partir de los conjuntos de datos "Accesos de Internet de bajada por provincia" y "Velocidad media de bajada de Internet fijo por provincia", se destaca la Ciudad de Buenos Aires, conocida como Capital Federal, seguida de la provincia de Buenos Aires, por su destacada velocidad media de descarga de Internet. Este liderazgo en la calidad de la conectividad tiene un impacto significativo en la experiencia en línea de los residentes y en el desarrollo tecnológico de la región.

La observación revela un aumento notable en la media anual de las velocidades de Internet, atribuible a avances tecnológicos, creciente demanda de servicios en línea como streaming y juegos, y las inversiones de las empresas de telecomunicaciones en mejorar sus redes. Este incremento demuestra la importancia de una conectividad de alta calidad en la vida cotidiana y el progreso tecnológico.

<h1 align=center>KPIS</h1>

###  KPI 1: 
Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia.

Ejemplo de uso: 
<p align="center"><img src="src\kpi1.png" height=300></p>

Este KPI permite medir cuánto ha aumentado la disponibilidad de servicios de Internet en relación con el trimestre anterior. Si el KPI resultante es igual al 2%, esto significa que se ha logrado el objetivo de aumentar la disponibilidad. Si es mayor, se ha superado el objetivo, y si es menor, se ha quedado por debajo.

Es importante utilizar este KPI para evaluar el progreso en la expansión de la conectividad en diferentes provincias y tomar medidas para garantizar que más hogares tengan acceso a Internet, lo que es fundamental en la era digital.


### KPI 2:
Aumentar en un 30% la velocidad de bajada del internet por provincia para el próximo año.

Ejemlo de uso:
<p align="center"><img src="src\kpi2.png" height=400></p>

Este KPI tiene como objetivo medir el aumento en la velocidad de bajada de Internet en las diferentes provincias de un país durante el próximo año. La velocidad de bajada se refiere a la velocidad a la que los datos son transferidos desde Internet hacia el dispositivo del usuario, lo que afecta la rapidez con la que se pueden cargar páginas web, videos, descargas, entre otros.

Este KPI tiene como objetivo aumentar la velocidad de descarga de Internet en un 30% en todas las provincias para el próximo año en comparación con el año actual. Esta mejora en la velocidad es esencial para mejorar la calidad de la experiencia en línea, afectando áreas como la productividad, educación en línea, entretenimiento y telemedicina. El seguimiento de este KPI permite evaluar el progreso en la mejora de la conectividad y tomar medidas para alcanzar el objetivo de velocidad.


<h1 align=center>Conclusiones </h1>

Durante el análisis de los datos y las visualizaciones, se pudieron identificar patrones intrigantes relacionados con la calidad de la conexión a Internet en distintas localidades. Se observó que algunas regiones presentaban velocidades de Internet considerablemente superiores a otras, lo que sugiere disparidades en la infraestructura o el acceso a servicios de alta velocidad. Además, se resaltaron áreas que podrían beneficiarse de mejoras en la conectividad.

En resumen, este informe proporciona una descripción detallada del proceso de análisis de la calidad de la conexión a Internet en diversas localidades utilizando Power BI. Los resultados enfatizan la importancia de abordar las diferencias en el acceso a velocidades de Internet de alta calidad. Esta información ofrece una base sólida para la toma de decisiones informadas en cuanto a la expansión de servicios de Internet y la mejora de la conectividad en aquellas áreas que requieren atención.





<h1 align=center> Links de utilidad </h1>

➮ [EDA Jupyter Notebook](EDA.ipynb)<br>
➮ [Página ENACOM](https://datosabiertos.enacom.gob.ar/home)<br>
➮ [Carpeta Datasets](datasetsxls)<br>
➮ [Carpeta Imagenes](src)<br>




<h1>Autor:</h1>

Kathiuska del Carmen Mangones Ramos <br>
Email: [kathiuska06@hotmail.com](kathiuska06@hotmail.com)<br>
[GitHub](https://github.com/KATHIUSKA06/PI_ML_OPS/blob/master/README.md) <br>
[LinkedIn](https://www.linkedin.com/in/kathiuska-mangones-ramos-1b494913b/)


