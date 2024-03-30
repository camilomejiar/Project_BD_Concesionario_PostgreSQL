# Proyecto de Análisis de Datos: Estudio de Preferencias de compra de Automóviles en concesionario AutoElite SAS.
Proyecto Personal que permite simular cierta información para el analisis de datos en la tendencia de un concesionario ficticio, el cual va a permitir desarrollar habilidades, en creacion de tablas, extracción y consulta de la información suministrada de manera aleatoria.

## Descripción del Proyecto "AutoElite".

Actualmente trabajas para una compañía de consultoría de marketing la cual es especialista en análisis de datos y eres el Analista de Datos Junior de esta compañía. Te han citado para que participes en el proyecto de una de los clientes TOP de la compañía, “AutoElite”, esta compañía de concesionarios, lleva en el mercado más de 10 años, cuenta con varios concesionarios en las principales ciudades Colombia: Bogotá, Cali, Barranquilla, Medellín y Bucaramanga, actualmente cuenta con más de mil empleados a nivel nacional, dentro de portafolio de servicios se encuentra la venta de vehículos nuevos y usados que son dejados como forma de pago por los vehículos nuevos, el servicio post-venta y la garantía de los vehículos según el fabricante. Dentro de su sistema de marketing para los vehículos usados desarrollaron una app que les permite promocionar de manera más rápida los vehículos usados de los cuales ofrecen beneficios para estos vehículos que van desde el mantenimiento y kits preventivos hasta una garantía de 3 mil kilómetros después de la venta de los vehículos usados.
En la última junta directiva del concesionario “AutoElite SAS”, las directivas se encontraron muy interesados en comprender mejor los resultados que les ha traído esta estrategia comercial, de conocer las preferencias de compra de automóviles de sus clientes en el último año, al comenzar a validar la información se encontraron que está muy diversa con lo cual buscaron el apoyo de la consultoría de marketing para que les permita analizar y desarrollar nuevas estrategias de marketing, inventario y costos. 
Dentro de la información registrada la consultoría de marketing se encuentra con una base de datos con 22685 registros, cuenta con los siguientes atributos: marca, modelo, año de fabricación, color, kilometraje, precio del vehículo, sede en la que se encuentra el vehículo, género de compra o interés de compra y su estado en si está disponible o ya fue vendido.

## Objetivos planteados al proyecto:
1.	**Optimización de la experiencia del Cliente:** Identificar áreas de mejora en la experiencia del cliente a lo largo del ciclo de compra del vehículo, desde la primera interacción hasta la posventa.
2.	**Segmentación de Mercado:** Identificar segmentos de clientes potenciales en las diferentes regionales en la que se tiene sede (Bogotá. Cali, Medellín, Barranquilla y Bucaramanga) para generar estrategias de marketing y así capturar nuevos mercados a futuro.
3.	**Análisis de Rentabilidad:** Evaluar la rentabilidad de los diferentes modelos de vehículos y servicios ofrecidos por parte del concesionario “AutoElite” para optimizar la asignación de recursos y maximizar los ingresos.
4.	**Estrategias de Retención de Clientes:** Identificar patrones de comportamiento de los clientes para desarrollar estrategias efectivas de retención y lealtad.
5.	**Recomendaciones:** Proporcionar recomendaciones al concesionario “AutoElite” para adaptar su inventario, generar rentabilidad y estrategias de market

## Datos y Registros.
Se cuenta con una base de datos con más de 22 mil registros.

•	**Id.** Corresponde al ID de los datos.

•	**Brand.** Corresponde a la marca fabricante del automóvil.

•	**Model.** Corresponde a la referencia o versión del automóvil hecho por el fabricante. 

•	**Year.** Corresponde al año de fabricación del automóvil.

•	**Color.** Corresponde al color del vehículo.

•	**Mileage.** Corresponde a los Kilómetros recorridos del vehículo.

•	**Price.** Corresponde al precio vendido el vehículo.

•	**Headquarters.** Corresponde a las sedes que cuenta el concesionario en el país.

•	**Stock.** Describe si el vehículo se encuentra disponible o este ya fue vendido.

•	**Transaction.** Describe en que mes de año el vehículo fue adquirido para su venta o en qué mes fue vendido, según el dato del atributo Stock.

•	**Gender.** Corresponde al tipo de género (hombre o mujer) que haya realizado la compra del vehículo.

## Dentro de la reunión se pudieron establecer las siguientes preguntas clave para desarrollar la actividad.

**1.**	¿Cuáles son las principales tendencias de compra de vehículos en cada regional?.

**2.**	¿Cuáles son los modelos de vehículos más rentables y cuales requieren ajustes en términos de precios o promociones?.

**3.**	¿Cómo podemos mejorar la satisfacción del cliente en las diferentes etapas del proceso de compra y postventa?.

**4.**	¿Qué segmentos de clientes representan oportunidades de crecimiento significativo y cómo podemos llegar a ellos de manera más efectiva?.

**5.**	¿Cuáles son las principales fuentes de pérdidas de clientes y que acciones podemos tomar para reducir la tasa de deserción?.

**6.**	¿Cuáles son las regionales que muestran un potencial crecimiento que no haya sido explotado y cuáles son las estrategias recomendadas para penetrar en esos mercados?.

**7.**	¿Cuáles serían las estrategias que se plantearían para disminuir el costo de inventario de los automóviles sin vender y que aumente la compra?.

## Herramientas a Utilizar:

•	**PostgreSQL.** Se establece como herramienta de almacenamiento y gestión de bases de datos.

•	**Excel.** Esta herramienta muy poderosa va a permitir analizar, explorar y manipular los datos.

•	**Python.** Para realizar análisis avanzados, segmentos de clientes y modelado predictivo.

•	**Tableau y Power BI.** Para crear visualizaciones interactivas y paneles de control que faciliten la interpretación de los datos.

## Proceso Estructurado.

Después de realizar la reunión con el cliente concesionario “AutoElite” el equipo de trabajo se reúne para realizar el proceso estructurado que permita tener de manera eficiente y efectiva la obtención de los resultados esperados. 
A continuación, se comparte el proceso a seguir.

1.	**Reunión de Inicio del Proyecto.**
•	Se realiza la reunión inicial en donde se comprenden los objetivos del proyecto, las expectativas y los requisitos específicos.

2.	**Recopilación de los datos.**
•	Se obtienen los accesos a la base de datos del concesionario “AutoElite”, esta información será revisada y analizada para que este completa y disponible en su totalidad.

•	Se identificará cualquier deficiencia en los datos registrados y se tomaran las medidas para ser abordadas, como la limpieza de los datos y la eliminación de la duplicidad.

3.	**Exploración y Análisis de Datos Preliminar.**
•	Se utilizarán herramientas como PostgreSQL para explorar los datos y comprender su estructura y contenido.

•	Se realizará un análisis pre liminar para identificar tendencias, anomalías y posibles áreas de interés que permitan lograr el objetivo del proyecto.

4.	**Definición de métricas y KPI´s.**
•	Se trabajarán en las preguntas y objetivos planteados para definir métricas clave que sean relevantes para los objetivos del proyecto.

•	Se establecerán criterios claros para evaluar el éxito del proyecto en función de las métricas establecidas.

5.	**Preparación y Transformación de los datos.**
•	Se dará uso de herramientas como Excel y Python para limpiar, transformar y preparar los datos para su análisis.

•	Se convertirán los datos en un formato adecuado para su visualización y análisis posterior.

6.	**Análisis Avanzado.**
•	Se utilizarán herramientas como Power BI, Tableau y Python para realizar análisis avanzados, como segmentación de clientes, análisis de tendencias y modelado predictivo entre otros que permitan alcanzar los objetivos del proyecto.

•	Se identificarán patrones significativos y relaciones entre variables que puedan proporcionar información valiosa para la toma de decisiones.

7.	**Visualización de Datos.**
•	Se crearán visualizaciones claras y efectivas utilizando herramientas como Power Bi y Tableau para comunicar los hallazgos de manera comprensible y persuasiva.

•	Se desarrollarán paneles interactivos que permitan a los usuarios explorar los datos y obtener información relevante según los objetivos planteados o necesidades relevantes al proyecto.

8.	**Generación de Informes y Presentación de los Resultados.**
•	Se preparan los informes detallados que resuman los hallazgos encontrados, las recomendaciones y las acciones propuestas ante las preguntas planteadas en el proyecto.

•	Se realizará la presentación de los resultados ante la junta directiva del concesionario “AutoElite” y los interesados ante el proyecto.

9.	**Interacción y Retroalimentación.**
•	Se realizará retroalimentación a la junta directa e interesados al proyecto del concesionario “AutoElite” para ser implementadas las recomendaciones y estrategias derivadas del análisis de datos.

•	Se está abierto a realizar ajustes según sea necesario para garantizar que el proyecto cumpla con las expectativas y los objetivos establecidos.

10.	**Implementación y Seguimiento.**
•	Junto con las áreas asignadas por parte de la junta directiva del concesionario “AutoElite” se trabajará para implementar las recomendaciones y estrategias derivadas del análisis de datos.

•	Se establecerá un sistema de seguimiento para monitorear el progreso y evaluar el impacto de las acciones tomadas en función a los KPI¨S definidos.

## Desarrollo del Proyecto concesionario "AutoElite".

**1. Configuración de la Base de Datos.**
En el siguiente [enlace](https://github.com/camilomejiar/Curso-Introducci-n-a-la-Base-de-Datos-con-PostgreSQL..git) podra revisar como descargar y establecer **PostgreSQL** como el motor de la base de datos del proyecto.
