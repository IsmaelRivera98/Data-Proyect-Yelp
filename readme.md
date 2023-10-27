# Contexto

En la era digital, la opinión de los usuarios se ha convertido en un recurso invaluable que influye significativamente en las decisiones de compra y en la estrategia de negocios. Plataformas de reseñas como Yelp y Google Maps han dado a los consumidores la capacidad de compartir sus experiencias sobre una amplia variedad de negocios, desde restaurantes hasta hoteles y otros servicios relacionados con el turismo y el ocio. En este contexto, las empresas han reconocido la importancia de comprender y aprovechar esta información para mejorar sus servicios, tomar decisiones estratégicas y anticipar las tendencias del mercado.

Nuestra consultora de datos ha sido contratada para llevar a cabo un análisis del mercado estadounidense en nombre de un conglomerado de empresas de restaurantes y negocios afines. El objetivo de nuestro proyecto es obtener información valiosa de las opiniones de los usuarios en dos plataformas clave: Yelp y Google Maps. Además, planeamos cruzar estos datos, utilizar técnicas de análisis de sentimientos y predecir los sectores de negocios que probablemente experimentará un crecimiento o declive. También, se busca identificar ubicaciones estratégicas para la apertura de nuevos locales y crear un sistema de recomendación de negocios, no necesariamente limitado a restaurantes, basado en las experiencias previas de los usuarios.

## Entregables

### Planteo de Objetivos
Documento que define los objetivos del proyecto, incluyendo la recopilación de datos, análisis de sentimientos, predicción de tendencias, recomendaciones de ubicación y sistemas de recomendación.

### Stack Tecnológico
Informe que detalla las tecnologías y herramientas que se utilizarán en cada etapa del ciclo de vida de los datos.

### KPIs (Indicadores Clave de Desempeño)
Documento que establece tres KPIs específicos, medibles y limitados en tiempo, relacionados con los objetivos del proyecto.

### Cronograma General
Planificación detallada que incluye tareas, tiempos de ejecución y dependencias entre tareas, representada en un diagrama tipo Gantt.

### EDA - Calidad
Resumen del análisis exploratorio de datos que aborda tipos de datos, valores faltantes, duplicados, outliers, distribución, y otros aspectos de calidad de los datos.

### ETL y Validación de Datos
Desarrollo de un proceso ETL unificado para la extracción, transformación y carga de datos de manera reproducible, con un mecanismo de validación de datos.

### Ciclo de Vida del Dato
Documento que describe el ciclo completo de vida de los datos, detallando las tecnologías utilizadas en cada etapa.

### Diseño del Modelo de Datos
Diseño consciente del modelo de datos que se fundamenta en las necesidades del proyecto y su implementación técnica.

### Infraestructura de Datos
Desarrollo de una infraestructura de datos, ya sea en la nube o en un entorno local, que incluye un pipeline end-to-end y considera la disponibilidad de datos para el desarrollo de ML y análisis.

### Automatización y Carga Incremental
Implementación de un orquestador de tareas para la automatización de procesos ETL, con validación para evitar redundancias.

### Diseño del Dashboard
Creación de un dashboard con colores, gráficos y elementos visuales efectivos, que sea interactivo y permita explorar los datos de manera intuitiva.

### Funcionalidad y Usabilidad
Asegurar que el dashboard sea funcional y que ofrezca una experiencia de usuario óptima, incluyendo filtros y selecciones eficientes.

### KPIs en el Dashboard
Integración de los KPIs definidos en el dashboard para su representación visual adecuada.

### EDA / Feature Selection
Realización de un EDA profundo y selección de características basada en el análisis, con fundamentación para la elección del modelo.

### Modelo de Machine Learning
Desarrollo de un modelo funcional con ajuste de parámetros que cumple con las métricas objetivo.

### Modelo ML en Producción
Implementación del modelo de machine learning en la nube con accesibilidad a través de una interfaz gráfica o llamados a un endpoint.

## Objetivo General

Este proyecto tiene como objetivo proporcionar a nuestro cliente una visión estratégica y orientada a datos de la dinámica del mercado, ayudándoles a tomar decisiones informadas sobre la expansión de sus negocios y a mejorar la satisfacción del cliente. La capacidad de anticipar tendencias y ofrecer recomendaciones basadas en datos es esencial en un entorno empresarial cada vez más competitivo y orientado hacia la satisfacción del consumidor.

## Objetivos Específicos del Proyecto

### Recopilación de Datos
- Extraer datos de Yelp y Google Maps, incluyendo reseñas, calificaciones, ubicaciones y otros detalles relevantes.
- Integrar datos de múltiples fuentes en un Data Warehouse unificado.

### Análisis de Sentimientos
- Aplicar análisis de sentimientos a las reseñas recopiladas para determinar la percepción de los usuarios con respecto a los negocios.
- Identificar aspectos positivos y negativos en las opiniones de los usuarios.

### Predicción de Tendencias
- Desarrollar modelos de machine learning para predecir sectores de negocios que experimentaron crecimiento o declive en el mercado estadounidense.
- Utilizar datos históricos y otros indicadores relevantes en las predicciones.

### Recomendaciones de Ubicación
- Utilizar técnicas de análisis espacial y machine learning para identificar ubicaciones estratégicas para la apertura de nuevos locales de restaurantes y negocios afines.
- Considerar la densidad de competidores, demanda de servicios y otras variables.

### Sistema de Recomendación
- Crear un sistema de recomendación personalizado para los usuarios de Yelp y Google Maps.
- Basar las recomendaciones en las experiencias previas de los usuarios y en sus preferencias.

### Validación y Garantía de Calidad de Datos
- Implementar mecanismos de validación de datos para asegurar la integridad y consistencia de la información en el Data Warehouse.
- Identificar y abordar valores faltantes, duplicados y outliers en los datos.

### Infraestructura de Datos
- Establecer una infraestructura de datos que permita la automatización de procesos ETL (Extracción, Transformación y Carga) y la disponibilidad de datos para su uso en análisis y machine learning.

### Diseño del Dashboard
- Desarrollar un dashboard interactivo que presenta visualmente los resultados del análisis de datos y las predicciones.
- Utilizar colores, gráficos y elementos visuales efectivos para mejorar la usabilidad y comprensión.

### Interacción con el Modelo de Machine Learning
- Desplegar el modelo de machine learning en la nube o en una plataforma accesible para el cliente.
- Permitir a los usuarios interactuar con el modelo a través de una interfaz gráfica o llamadas a un endpoint.

## Stack tecnológico del proyecto

### Recopilación de Datos

#### Extracción de Datos
- Pandas (Python): Utilizaremos Python para cargar los datos directamente desde los archivos proporcionados.

### Análisis de Sentimientos

#### Transformación y Procesamiento de Datos
- Pandas (Python): Realizaremos la limpieza y preparación de los datos utilizando Pandas.

#### Análisis de Sentimientos
- Bibliotecas de Procesamiento de Lenguaje Natural (NLP): Usaremos bibliotecas de NLP como NLTK o spaCy para realizar el análisis de sentimientos de las reseñas.

### Predicción de Tendencias

#### Machine Learning y Modelado de Datos
- Scikit-Learn (Python): Implementaremos modelos de clasificación y regresión para predecir tendencias de crecimiento o declive en diferentes sectores de negocios.

### Recomendaciones de Ubicación

#### Machine Learning y Modelado de Datos
- Scikit-Learn (Python): Utilizaremos algoritmos de machine learning para identificar ubicaciones estratégicas basadas en datos geoespaciales y otros indicadores.

### Sistema de Recomendación

#### Machine Learning y Modelado de Datos
- Scikit-Learn (Python): Diseñaremos un sistema de recomendación basado en algoritmos de filtrado.

### Validación y Garantía de Calidad de Datos

#### Transformación y Procesamiento de Datos
- Pandas (Python): Identificaremos y abordaremos valores faltantes, duplicados y outliers en los datos.

### Infraestructura de Datos

#### Almacenamiento de Datos
- Base de Datos SQL: Utilizaremos una base de datos SQL como PostgreSQL o MySQL para almacenar datos limpios y procesados.
- Data Warehouse en la Nube: Podemos utilizar servicios en la nube como Amazon Redshift o Google BigQuery para almacenar datos a gran escala.

#### ETL y Automatización
- Apache Spark (Python): Implementaremos ETL y procesamiento de datos a gran escala si es necesario.
- Orquestador de Tareas: Emplearemos herramientas de orquestación como Apache Airflow para automatizar el flujo de datos.

### Diseño del Dashboard

#### Visualización de Datos
- Bibliotecas de Visualización (Matplotlib, Seaborn): Crearemos gráficos y visualizaciones efectivas en Jupyter Notebooks.
- Herramientas de Business Intelligence (Power BI): Para diseñar el dashboard interactivo.

### Interacción con el Modelo de Machine Learning

#### Machine Learning y Modelado de Datos
- Scikit-Learn (Python): Implementaremos el modelo de machine learning.
- Despliegue en la Nube: Plataformas en la Nube (Azure): Desplegaremos el modelo en la nube.
- API: Proporcionaremos un endpoint para acceder al modelo a través de llamadas API.

## KPIs

### KPI de Participación de Usuarios
**Descripción:** Se refiere al número promedio de consejos o recomendaciones que cada usuario aporta a lo largo de un período de tiempo específico en la plataforma. Este indicador es crucial para evaluar el nivel de involucramiento de los usuarios en la plataforma y su contribución a la comunidad. Una disminución en este valor podría indicar una menor participación de los usuarios y una posible disminución en el atractivo de la plataforma.

**Participacion de usuarios** = Numero total de reviews / Numero total de usuarios

**Objetivo:** aumentar la Participación de Usuarios en un 10% cada año, lo que indicaría un crecimiento saludable de la comunidad.

**Función:** Este KPI sirve para medir la interacción y el compromiso de los usuarios en una plataforma de reseñas. Permite a las empresas y administradores de la plataforma evaluar la salud y la vitalidad de la comunidad de usuarios. Una alta participación de usuarios generalmente indica un alto nivel de satisfacción y compromiso con la plataforma, mientras que una disminución en este KPI puede señalar problemas que requieren atención.

### KPI de Proporción de Reseñas Negativas
**Descripción:** Se refiere a la proporción de reseñas negativas en comparación con el número total de reseñas de un negocio en una plataforma de reseñas, como Yelp o Google Maps. Las "reseñas negativas" se definen generalmente según una calificación específica, como 1 o 2 estrellas, o basadas en el análisis de sentimiento de las reseñas. Esta métrica es esencial para evaluar la percepción general de los clientes sobre un negocio y su nivel de satisfacción. Una proporción baja de reseñas negativas suele ser un indicador de una alta satisfacción del cliente.

**Proporción de reseñas negativas** = Número total de reseñas negativas / Número total de reseñas

**Objetivo:** reducir la Proporción de Reseñas Negativas en un 5% cada trimestre.

**Función:** Este KPI se utiliza para medir la satisfacción del cliente y la calidad del servicio ofrecido por un negocio. Proporciona información valiosa sobre la percepción de los clientes y ayuda a identificar problemas o áreas de mejora. Una proporción baja de reseñas negativas es indicativa de una experiencia positiva del cliente, mientras que una alta proporción de reseñas negativas puede señalar problemas que requieren atención.

### KPI de Proporción de Reseñas Positivas
**Descripción:** se refiere a la proporción de reseñas positivas en comparación con el número total de reseñas de un restaurante específico en una plataforma de reseñas. Las "reseñas positivas" pueden definirse según una calificación específica de estrellas o mediante un análisis de sentimiento de las reseñas escritas. Esta métrica permite evaluar la percepción general de los clientes sobre el restaurante y su nivel de satisfacción. Un aumento en la proporción de reseñas positivas o su estabilidad indica una buena satisfacción del cliente.

**Proporción de reseñas positivas** = Número total de reseñas positivas / Número total de reseñas

**Objetivo:** Se espera que la Proporción de Reseñas Positivas aumente o se mantenga estable cada año.

**Función:** Este KPI se utiliza para medir la satisfacción del cliente y la calidad del servicio ofrecido por un restaurante específico. Proporciona información valiosa sobre la percepción de los clientes y ayuda a identificar áreas en las que el restaurante puede estar haciendo un buen trabajo. Una proporción alta de reseñas positivas refleja una experiencia positiva del cliente.

### KPI de Tasa de Retención de Usuarios
**Descripción:** La Tasa de Retención de Usuarios es un indicador clave que mide la proporción de usuarios que continúan contribuyendo con consejos o recomendaciones en años posteriores en comparación con el año en que iniciaron su actividad en la plataforma. Esta métrica es esencial para evaluar la fidelización de los usuarios a lo largo del tiempo. Una disminución en la Tasa de Retención de Usuarios podría indicar una menor retención y participación de los usuarios en la plataforma.
**Fórmula:** Tasa de retención de usuarios = (Usuarios que contribuyeron en el año actual y en años posteriores) / (Número total de usuarios)
**Objetivo:** Aumentar en un 10% la Tasa de Retención de Usuarios cada año.
**Función:** La Tasa de Retención de Usuarios es crucial para evaluar la fidelización de los usuarios en una plataforma de recomendaciones. Proporciona información sobre cuántos usuarios continúan participando y contribuyendo con consejos a lo largo del tiempo. Esto es fundamental para entender la lealtad de los usuarios y su compromiso con la plataforma. Una Tasa de Retención de Usuarios saludable indica una fuerte retención y participación de la comunidad, mientras que una disminución en esta tasa puede ser una señal de que se deben tomar medidas para mejorar la retención de usuarios.

### KPI de Satisfacción de la Región
**Descripción:** El KPI de Satisfacción de la Región se basa en el análisis de sentimiento de las opiniones de los usuarios y clasifica estas opiniones por región. Para calcular este KPI, se asigna una puntuación de satisfacción a cada opinión en función de su sentimiento. Por ejemplo, se puede utilizar un sistema de puntuación de -1 (negativo) a +1 (positivo) para evaluar cada opinión. Luego, se calcula un promedio de estas puntuaciones para obtener la Puntuación de Satisfacción del Usuario para una región específica.
**Fórmula:** Crecimiento en Satisfacción = (Puntuación de Satisfacción del año actual - Puntuación de Satisfacción del año anterior) / (Número total de usuarios)
**Objetivo:** El objetivo es lograr un aumento del 5% en la satisfacción de los usuarios en la región en un período de 5 años.
**Función:** Este KPI tiene como objetivo evaluar la evolución de la satisfacción de los usuarios en una región específica a lo largo de un período de 5 años. Proporciona información clave sobre si la satisfacción del usuario está aumentando o disminuyendo con el tiempo. Una puntuación de satisfacción alta indica una satisfacción positiva de los usuarios, mientras que una puntuación baja sugiere una insatisfacción.

# Cronograma General
El cronograma general del proyecto se divide en tres semanas, con tareas distribuidas en un período de siete días para las 2 primeras semanas y para la tercera un período de 4 días teniendo en cuenta que la Demo se presenta el día viernes de esta misma. Cada semana se enfoca en etapas clave del proyecto, desde la definición de objetivos y selección de tecnologías en la primera semana, hasta la implementación de un modelo de machine learning y su despliegue en la tercera semana. Este cronograma proporciona una estructura detallada que guía el desarrollo del proyecto, asegurando que cada tarea se realice en el momento adecuado y se cumplan los plazos establecidos.
![image](https://drive.google.com/uc?id=1bZSUgyX-hXhI2bKLbiYVwGWReTPwhAFr)

# Tabla de Dependencias de Tareas
A continuación, se presenta una tabla de dependencias de tareas para el proyecto de análisis de datos que has planteado. Esta tabla muestra cómo algunas tareas dependen de la finalización de otras tareas dentro del proyecto.
![image](https://drive.google.com/file/d/1T3njZXswr5IQFsRc5V21aCUq6v6tiMny/view?usp=drive_link)

# Tareas Asignadas
Las tareas asignadas en un proyecto se distribuyen estratégicamente a medida que se avanza en el proyecto para garantizar una ejecución eficiente y eficaz. La distribución de tareas en la primera semana se realizó de la siguiente manera:
- En la primera semana del proyecto, se llevó a cabo la fase inicial de planificación y definición, lo que incluyó la elaboración del Planteo de Objetivos, la selección del Stack Tecnológico, la definición de KPIs (Indicadores Claves de Desempeño), la creación del Cronograma General (Diagrama de Gantt), el desarrollo del EDA preliminar y el avance del ETL.
- La asignación de tareas en esta etapa se realizó de la siguiente forma:
  - El planteamiento de objetivos, la selección del stack tecnológico y la definición de los KPIs se llevaron a cabo de manera colaborativa entre todos los miembros del equipo. Esto garantizó que se aprovecharan las perspectivas y conocimientos, permitiendo así tener una comprensión compartida y una visión clara del camino a seguir en el proyecto.
  - En la fase de Análisis Exploratorio de Datos (EDA), se adoptó un enfoque colaborativo donde los archivos se distribuyeron de manera equitativa entre los miembros del equipo. A medida que un miembro del equipo completaba su análisis de un conjunto de datos, se fomentaba la colaboración y el apoyo entre los miembros del equipo, de manera que aquellos que habían finalizado su tarea brindaban ayuda y orientación a los compañeros que estaban trabajando en otros conjuntos de datos. Esta dinámica de trabajo en equipo garantiza una distribución equitativa de la carga de trabajo y permitió un progreso eficiente en la realización del EDA.
  - Para el avance del proceso de Extracción, Transformación y Carga (ETL), cada miembro del equipo trabajó en los archivos que les fueron asignados durante el EDA. Donde se adoptó la misma metodología de colaboración y apoyo entre los miembros del equipo.
