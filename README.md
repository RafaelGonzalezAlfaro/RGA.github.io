# Ingeniero Mecatrónico | Analista de datos

## Acerca de mi
Ingeniero Mecatrónico titulado con 7 años de experiencia en diseño y manufactura. Además, ¡soy Analista de Datos Jr. certificado! 

Mi enfoque profesional combina el desarrollo de soluciones técnicas con el análisis de datos, permitiéndome optimizar procesos y 
mejorar la toma de decisiones en entornos industriales y de manufactura.

Me caracterizo por mi orientación a resultados, capacidad de adaptación y compromiso con la eficiencia y calidad en cada proyecto.

## Habilidades Tecnológicas

- Análisis y gestión de datos utilizando **Python / SQL / Excel / Pandas / Matplotlib**
- Visualización de datos usando **Tableau**
- Manejo de programas **VS code / Jupiter**

## Competencias

Análisis de datos / Análisis y Resolución de problemas / Comunicación efectiva / Responsabilidad / Trabajo en equipo / Orientación a resultados / Organización / Proactividad / Atención al detalle / Optimización de Procesos / Liderazgo / Compromiso

## Mas sobre mi:
[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafaelgonzalezalfaro/)

# Proyectos Destacados
## Identificar operadores ineficaces
El objetivo de nuestro análisis es desarrollar un sistema para identificar operadores ineficaces con el cual, se busca mejorar la calidad del servicio, 
reducir la pérdida de clientes y optimizar la asignación de recursos.

Este enfoque va dirigido a supervisores y gerencia, los cuales utilizarán esta información para la gestión del rendimiento, la formación de operadores 
y la planificación de la capacidad. Los cuales se beneficiarán de una mayor eficiencia operativa y satisfacción del cliente.

Se tomaron decisiones sobre la capacitación adicional de los operadores, la reasignación de tareas, la optimización de los flujos de trabajo e incluso 
posibles medidas disciplinarias o de incentivos. El análisis también puede ayudar a identificar problemas sistémicos que contribuyen a la ineficiencia.

### Metodología

- **Preprocesamiento de datos:** Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- **Exploratory Data Analysis (EDA):** Se analizaron distintos datos, se crearon histogramas y graficas para visualizacion de datos mas claramente
- **Pruebas de Hipotesis:** Se realizaron pruebas de hipotesis para observar si la tasa de llamadas perdidas no está correlacionada con el tiempo de espera y 
si hay alguna diferencia en el tiempo de espera entre operadores eficientes e ineficientes.

Herramientas utilizadas en este proyecto:

![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Modelos de predicción](https://img.shields.io/badge/Modelos_de_predicción-295F98?style=for-the-badge)

## Preguntas clave del análisis:

1. ¿La tasa de llamadas perdidas está relacionada directamente con el tiempo de espera en llamada?
2. ¿Hay diferencia en el tiempo de espera entre operadores eficientes e ineficientes?
3. ¿Que estrategias podemos utilizar basado en nuestros resultados para optimizar el servicio?

## Visualizaciones destacadas

1. **relación de tiempo de espera promedio por eficiencia**
Deacuerdo a la gráfica contamos con evidencia visual de que los operadores clasificados como "ineficientes" tienden a
tener tiempos de espera considerablemente más largos que los operadores "eficientes".

![Time Related Graf](/assets/img/TIME_RELATED_GRAF.png)

2. **relación de tiempo de espera y tasa de llamadas perdidas**
la relación a medida que aumenta el tiempo de espera, la tasa de llamadas perdidas disminuye.
Esto sugiere que los usuarios entre más duración tienen en la llamada, tienen a seguir en ella,
quizá porque no quieren perder el tiempo que llevan esperando.

![Llamadas perdidas](/assets/img/LLAMADAS_PERDIDAS.png)

**Más detalles de este proyecto aqui -> [Repositorio completo](https://github.com/RafaelGonzalezAlfaro/Telecom_operadores_ineficaces).**

## Conclusiones generales y recomendaciones:
### En base al análisis:
de acuerdo al tiempo de espera en las llamadas, tasa de llamadas perdidas y la eficiencia de los operadores
eficientes e ineficientes en base al tiempo de espera de las llamadas, podemos concluir que:

- No hay una gran diferencia en la tendencia central de la tasa de llamadas perdidas entre los diferentes cuartiles de tiempo de espera.
- Existe una correlación negativamente significativa entre el tiempo de espera y la tasa de llamadas perdidas.
  A medida que aumenta el tiempo de espera, la tasa de llamadas perdidas disminuye.
- Existe una diferencia estadísticamente significativa entre los operadores eficientes e ineficientes, es decir,
  los operadores clasificados como "ineficientes" tienden a tener tiempos de espera considerablemente más
  largos que los operadores "eficientes".
- Las llamadas sin identificación (desconocidas) representan una gran parte de los datos, creando posibles sesgos en los datos.

## Acciones recomendadas:
- **Optimizar procesos:**

➢ Analizar los flujos de trabajo y sistemas actuales para identificar posibles cuellos de botella.

➢ Implementar mejoras en los procesos para agilizar el manejo de llamadas y reducir el tiempo que los
clientes pasan esperando.

- **Mejorar la capacitación:**

➢ Proporcionar a los operadores capacitación adicional sobre el manejo eficiente de llamadas, incluyendo
técnicas de comunicación, manejo de objeciones y resolución de problemas.

- **Ajustar la asignación de personal:**

➢ Analizar la demanda de llamadas en diferentes horarios y días de la semana para optimizar la programación
del personal y asegurar una cobertura adecuada en los momentos de mayor demanda.

- **Implementar sistemas de enrutamiento inteligente:**

➢ Utilizar sistemas que distribuyan las llamadas de manera más eficiente entre los operadores disponibles,
teniendo en cuenta la experiencia y habilidades de cada uno, con una mejor clasificación del cliente que llama.

## Comportamiento de 2 Grupos en Tienda Internacional

El objetivo de este analisis es evaluar la efectividad de las pruebas A/B realizadas por el equipo anterior, 
para asi determinar si hubo diferencias significativas en el comportamiento de los usuarios entre los grupos A y B en las pruebas que se mencionan:

**recommender_system_test**
**interface_eu_test**

Tambien se analizó la influencia de campañas de marketing al probar cambios relacionados con la introducción de un sistema de recomendaciones 
mejorada y evaluar la distribución geográfica, dispositivo utilizado y actividad para detectar posibles sesgos en la asignación de grupos.

### Metodología

- **Preprocesamiento de datos:** Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- **Exploratory Data Analysis (EDA):** Se analizaron distintos datos, se crearon graficas para visualizacion de datos mas claramente
- **Pruebas A/B:** Se realizaron pruebas A/B para comprobar si el comportambiento entre ambos grupos es significativamente distinto.

Herramientas utilizadas en este proyecto:

![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas A/B](https://img.shields.io/badge/A/B_Testing-orange)


## Preguntas clave del análisis:

1. ¿El número de eventos por usuario está distribuido equitativamente entre las muestras?
2. ¿Que porcentaje del total de personas llegan desde la primera hasta a la ultima etapa?
3. ¿Cómo se distribuye el número de eventos entre los días?

## Conclusiones Generales:
### Deacuerdo al comportamiento de los grupos para cada evento:
- **login**: podemos observar que no hay diferencias significativas entre el grupo A y B en esta etapa, ya que, el 100% de los usuarios pasan por esta etapa.
- **product_page**: observamos una diferencia estadísticamente significativa entre los grupos A y B. El grupo A tuvo una tasa de conversión mayor que el grupo B.
- **product_cart**: No se observa una diferencia significativa entre los grupos A y B en este evento.
- **purchase**: podemos observar una diferencia estadísticamente significativa entre los grupos A y B para el evento purchase. El grupo A tuvo una tasa de conversión mayor que el grupo B.

## Recomendaciones:
-  Para **recommender_system_test**, deacuerdo al análisis, se descubrio que el Grupo B es significativamente mas pequeño que el grupo A,
el desequilibrio puede sesgar los resultados, por lo cual se recomienda reequilibrar los grupos o recolectar más datos para el grupo B antes de analizar los resultados.
- Se recomienda reestructurar las paginas de **Product_page** para se mas llamativas y amigables, ya que, deacuerdo al análisis, pudimos notar que solo el 34% de los usuarios pasan de la
etapa del registo a la pagina del producto, esto quiza porque tuvieron una mala experiencia con la pagina, por lo cual no pudieron navegar o simplemente perdieron interés.
Y esto afecta directamenta las siguientes 2 etapas del proceso. 

## Visualizaciones destacadas

1. **Comportamiento de personas en cada Etapa**
Deacuerdo al resultado mostrado, podemos analizar que:

- **Login**: 58,696 usuarios únicos completaron esta etapa. Al ser la primera etapa, la tasa de conversión es del 100%, osease,
  todos los usuarios pasan por aqui.
- **Product_page**: 38,929 usuarios unicos llegaron a esta etapa,esto nos indica que aproximadamente el 33.68% de los usuarios que se
  registraron no llegaron a ver una página de producto. 
- **Product_cart**: 19,284 usuarios únicos añadieron un producto al carrito.Esto nos dice que casi la mitad de los usuarios (50.46%) que vieron
  una página de producto no añadieron un producto al carrito.
  Nuevamente, esto nos dice que quiza tuvieron problemas tecnicos con la pagina o simplemente los productos se les hicieron caros.
- **Purchase**: 19,568 usuarios únicos realizaron una compra. La tasa de conversión es 1.47% lo cual nos dice que solo un pequeño porcentaje
  de los usuarios que añadieron un producto al carrito completaron la compra. Quiza algunos usuarios no añadieron el producto al carrito, si no que compraron directamente.

![Grafica embudo](/assets/img/conversion.png)

2. **Distribución de los eventos a lo largo del tiempo**
La siguiente gráfica nos muestra la distribución del número de eventos de usuario diarios para los grupos A y B a lo largo del tiempo.
Podemos observar que ambos grupos muestran un crecimiento en el número de eventos desde el inicio del periodo hasta alrededor del 21 de diciembre,
siendo este dia el pico mas grande de actividad, siendo mas alto en el Grupo A y despues caen considerablemente.
Esto nos dice que quiza por las fechas, las compras de ultimo momento son mayores este dia por las fechas festivas siguientes, y posterior a esta fecha ya no hay tantas compras.

![Distribucion usuarios](/assets/img/distribucion_usuarios.png)

**Más detalles de este proyecto aqui -> [Repositorio completo](https://github.com/RafaelGonzalezAlfaro/recommender_system_test).**
