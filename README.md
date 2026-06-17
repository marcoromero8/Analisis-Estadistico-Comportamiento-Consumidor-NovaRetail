# Analisis-Estadistico-Comportamiento-Consumidor-NovaRetail

##  Introducción
El objetivo de este reporte es presentar a la dirección de NovaRetail un análisis estadístico claro sobre el comportamiento de sus clientes en la plataforma de comercio electrónico.
Actualmente la empresa tiene guardada una gran cantidad de información sobre las visitas, el tiempo de navegación y las compras, pero el problema principal es que no hay claridad sobre cuáles factores influyen realmente para que un cliente decida hacer su compra.3
 Como en los últimos meses se han armado estrategias con resultados mixtos, este estudio servirá para dejar de tomar decisiones por intuición y empezar a basarse en evidencia real de datos.
 
##  Descripción del Conjunto de Datos
Para realizar este trabajo, nos encargamos de analizar una base de datos que contiene un total de 300 registros históricos de los clientes.
Dentro de este conjunto de datos se revisaron variables muy importantes como la edad de los usuarios, el segmento al que pertenecen (clientes frecuentes, nuevos y premium), el tiempo en minutos que pasan navegando en el sitio web y el gasto total que realizan medido en dólares (USD).
Todos estos datos se organizaron y limpiaron para asegurar que los resultados de las gráficas sean completamente confiables.

##  Metodología del Análisis
El análisis se dividió en tres partes para poder entender el problema desde diferentes puntos de vista.
*Análisis de edad:* Se creó una tabla de frecuencias agrupadas por intervalos y se calculó la marca de clase (MK), la frecuencia relativa y el porcentaje para armar un histograma con su polígono de frecuencias.
*Análisis por segmentos:* Se utilizó un gráfico dinámico para contar exactamente cuántos clientes tenemos en cada tipo de segmento (Frecuente, Nuevo y Premium).
*Análisis de correlación:* Se juntaron las columnas de tiempo en el sitio y el gasto en USD para hacer un gráfico de dispersión con una línea de tendencia y ver cómo se relacionan entre sí.

##  Resultados e Interpretación

### 1. Distribución de Edad (Histograma y Polígono)
Gracias al análisis que se realizó para conocer la frecuencia de edad de las personas que interactúan con NovaRetail, se determinó que el rango de edad que más predomina en primer lugar es de 29 a 37 años, en segundo lugar de 38 a 46 años y en tercer puesto de 20 a 28 años.

<img width="487" height="213" alt="imagen" src="https://github.com/user-attachments/assets/b7f55eed-973a-413b-96af-54ca2562edf0" />
<img width="411" height="127" alt="imagen" src="https://github.com/user-attachments/assets/12250329-2b1b-49da-8e0b-2007f3d40427" />
<img width="752" height="452" alt="imagen" src="https://github.com/user-attachments/assets/611e5402-375b-4e3d-8ff9-290ba9c8a4eb" />

### 2. Análisis por Segmentos (Gráfico de Barras)
Gracias a la tabla dinámica que se decidió usar para contar cuántas personas hay por segmento, podemos determinar que ha habido más nuevos clientes; sin embargo, los clientes frecuentes también se mantienen en una alta estadística

<img width="283" height="102" alt="imagen" src="https://github.com/user-attachments/assets/cf5df192-7c80-4cd3-b75c-5a5c14b3f906" />
<img width="923" height="444" alt="imagen" src="https://github.com/user-attachments/assets/3a4423a4-69fd-4c23-8524-030bfb801651" />

### 3. Análisis de Correlación (Gráfico de Dispersión)
Para el gráfico de dispersión se decidió poner una línea de tendencia que nos ayude a visualizar de mejor manera cómo se está comportando el gasto respecto al tiempo que se pasa en el sitio, y se determinó que entre más tiempo estén activos en el sitio más dinero se gasta

<img width="752" height="452" alt="imagen" src="https://github.com/user-attachments/assets/3542207a-c707-49ee-9f4a-2c6e031938f2" />

##  Conclusiones y Recomendaciones
Con base en los resultados que se obtuvieron en las gráficas, se pueden extraer las siguientes conclusiones para NovaRetail
*Optimizar la retención digital:* Como el gráfico de dispersión demostró que a mayor tiempo en el sitio web el gasto en dólares aumenta, se recomienda a la dirección enfocar esfuerzos en mejorar el diseño y el contenido de la plataforma para retener más tiempo a los usuarios.
*Estrategia para clientes nuevos:* El análisis por segmentos nos dejó ver que la mayor parte de nuestra base de datos son clientes nuevos. Se recomienda armar una campaña de correo o promociones exclusivas para este grupo, con el objetivo de fidelizarlos y lograr que pasen a ser clientes frecuentes.
*Enfoque demográfico:* Gracias al histograma sabemos que el mercado fuerte de la empresa está concentrado en personas de edades maduras. Las campañas de publicidad digital deberían segmentarse principalmente para este rango de edad para asegurar un mejor impacto en las ventas.
