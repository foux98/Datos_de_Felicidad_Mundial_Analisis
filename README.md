# Proyecto de Análisis de Datos de Felicidad Mundial

Este proyecto se enfoca en el análisis de datos de felicidad mundial, utilizando diversos indicadores para comprender mejor los factores que influyen en la felicidad de diferentes países. Se han utilizado datos de múltiples fuentes, incluyendo índices de felicidad, PIB per cápita, soporte social, percepción de corrupción, esperanza de vida saludable, entre otros. También se ha incluido el índice de Gini para evaluar la desigualdad de ingresos.


# Datos y herramientas usadas

Ubicación geográfica del país: https://developers.google.com/public-data/docs/canonical/countries_csv (Google Web Developer), que contiene ubicaciones geográficas de 246 países.

Puntuaciones de felicidad: https://worldhappiness.report/ed/2019/#read (Informe mundial sobre la felicidad 2023, escrito por un grupo de expertos independientes que actúan a título personal. Las opiniones expresadas en este informe no reflejan necesariamente las opiniones de ninguna organización, agencia o programa de las Naciones Unidas), que mide la felicidad de 157 países a partir de diversas atribuciones, como la salud, el apoyo social, la percepción de la corrupción, la libertad, etc.

Coeficiente de Gini: https://datahub.io/world-bank/si.pov.gini#resource-data (datos del Banco Mundial), que registra 133 países en diferentes años.

**Herramientas**

Power BI para la visualización y análisis de datos.
Python para la preparación y limpieza de datos.


# Configuración de la aplicación 

**Etapa 1: Extracción y limpieza de datos**
Usando Python Pandas para el proceso de extracción y limpieza de datos.

**Etapa 2: Almacenamiento de datos en la base de datos SQLite**
El uso de SQLAlchemy crea y almacena datos limpios en una base de datos SQLite.

**Etapa 3: Crear aplicación**
El uso de Flask crea una aplicación que se conecta a la base de datos SQLite y regresa a la solicitud de API con datos en formato json.

**Etapa 4: Crear el panel de control de la base de datos**
Creación de un panel de página de inicio simple para la solicitud de API mediante HTML y CSS.


# Power Bi

Una vez preparados los datos, fuí a Power BI para analizarlos, utilizando diversas visualizaciones con el objetivo de analizar la felicidad a nivel global, para conocer el transfondo de algo tan intangible como este sentimiento tan importante para todos.

Se divide en:

1. Portada
Título: "Análisis de la Felicidad Mundial"
Descripción: Introducción y presentación del análisis.
2. Aclaraciones

Explicación de los datos y metodología utilizada.
Fuentes de los datos y criterios de inclusión/exclusión.
3. Felicidad por Continente 

Gráficos que muestran la felicidad promedio por continente.
Comparación de la felicidad a lo largo de los años por continente.
4. Felicidad por País

Gráficos de los países con mayor y menor felicidad.
Comparación detallada de la felicidad en diferentes países.
5. Percepción de Corrupción por Continente 
Análisis de la percepción de corrupción por continente.
Relación entre la percepción de corrupción y la felicidad.

6. Percepción de Corrupción por País
Gráficos de los países con mayor y menor percepción de corrupción.
Comparación de la corrupción y la felicidad a nivel nacional.
7. Libertad por Continente 

Análisis de la libertad social promedio por continente.
Relación entre libertad social y felicidad.
8. Libertad por País 

Gráficos de los países con mayor y menor libertad social.
Comparación de la libertad social y la felicidad a nivel nacional.
9. Esperanza de Vida Saludable por Continente 

Análisis de la esperanza de vida saludable promedio por continente.
Relación entre esperanza de vida saludable y felicidad.

10. Esperanza de Vida Saludable por País
Gráficos de los países con mayor y menor esperanza de vida saludable.
Comparación de la esperanza de vida saludable y la felicidad a nivel nacional.

11. Soporte Social por Continente
Análisis del soporte social promedio por continente.
Relación entre soporte social y felicidad.

12. Soporte Social por País 
Gráficos de los países con mayor y menor soporte social.
Comparación del soporte social y la felicidad a nivel nacional.

13. Generosidad por Continente
Análisis de la generosidad promedio por continente.
Relación entre generosidad y felicidad.

14. Generosidad por País
Gráficos de los países con mayor y menor generosidad.
Comparación de la generosidad y la felicidad a nivel nacional.

15. Análisis de España
Comparación de la felicidad y el PIB per cápita en España a lo largo del tiempo.
Análisis de las tendencias y factores que afectan la felicidad en España.

16. Mapa Interactivo
Mapa que muestra la distribución de la felicidad y otros indicadores a nivel mundial.
Herramientas interactivas para explorar los datos por continente y país.

17. Países que no aparecen en la lista
Países que no aparecen en la lista por diversos motivos


# Conclusiones

Este análisis proporciona una visión integral de los factores que influyen en la felicidad mundial. Los gráficos y visualizaciones permiten identificar patrones y tendencias, así como comparaciones entre diferentes regiones y países. El objetivo es ofrecer una herramienta útil para la toma de decisiones y la formulación de políticas que promuevan el bienestar y la felicidad global.

