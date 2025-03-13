**Introducción**

En este módulo aprenderemos sobre las tareas típicas en una metodología de ciencia de datos de seis pasos y seguiremos un escenario de proyecto para aprender de los ejemplos a medida que avanzamos en cada paso

**Objetivos**

- Explorar un escenario de proyecto de datos e identificar tareas clave a medida que avanza a través de una metodología.

======================================================

**Descripción general de la metodología**

En lecciones anteriores, se presentaron tres metodologías reconocidas en el ámbito de la ciencia de datos: el Proceso Estándar Intersectorial para Minería de Datos (CRISP-DM), el Descubrimiento de Conocimiento en Bases de Datos (KDD) y el enfoque de Muestreo, Exploración, Modificación, Modelado y Evaluación (SEMMA).  

En esta lección, profundizarás en una metodología específica de ciencia de datos.  

Los pasos que estudiarás en esta metodología incluyen:  

- Comprensión del negocio  
- Exploración y preparación de los datos  
- Representación y transformación de los datos  
- Visualización y presentación de los datos  
- Entrenamiento de modelos de datos  
- Implementación de modelos de datos

Los pasos de la metodología pueden variar, pero seguirlos permite comprender las tareas comunes que una empresa podría aplicar en sus proyectos de ciencia de datos. Esta metodología no depende de tecnologías o herramientas específicas y ofrece un marco de trabajo que los científicos de datos pueden emplear para obtener respuestas y resultados. Además, al basarse en un enfoque científico, su principal característica es la repetibilidad.

======================================================

**Paso 1: Compresión del negocio**

Todo proyecto, sin importar su tamaño, comienza con la comprensión del negocio. Antes de analizar los datos, el equipo debe identificar y comprender claramente el problema a resolver.  

En este proceso, el patrocinador empresarial juega un rol clave. Como líder del proyecto, es quien lo impulsa debido a la necesidad de solucionar un problema específico. Presenta este desafío al equipo de ciencia de datos y brinda apoyo durante todo el desarrollo del proyecto.   

El equipo de ciencia de datos analiza el problema empresarial y puede recurrir al **pensamiento de diseño** como metodología para resolverlo. Este enfoque pone al usuario en el centro, fomentando la empatía y la búsqueda de la mejor experiencia posible.  

A través de un taller de pensamiento de diseño, el equipo puede:  

- Definir claramente el problema.  
- Establecer los objetivos del proyecto.  
- Crear personajes ficticios que representen a los usuarios finales.  
- Documentar los requisitos de la solución desde una perspectiva empresarial.  

Definir el problema con precisión es clave para desarrollar una solución efectiva. Además, la participación del patrocinador empresarial es fundamental a lo largo del proceso, ya que aporta conocimientos clave, revisa los hallazgos y asegura que el proyecto avance en la dirección correcta.  

Una vez que el problema de negocio está bien definido, un científico de datos del equipo establece el enfoque analítico para resolverlo. Esto implica traducir el problema en términos de técnicas estadísticas y de aprendizaje automático. Por ejemplo, si el objetivo es predecir si un cliente responderá afirmativamente o no, se puede optar por desarrollar, probar e implementar un modelo de regresión logística. Los científicos de datos cuentan con diversas tecnologías y metodologías para abordar estos desafíos.

**Escenario del Proyecto: Comprensión del Negocio**  

La empresa ficticia **GAXR**, especializada en el desarrollo de software para empresas de diseño de videojuegos, enfrenta un problema en su área de **Recursos Humanos (RR. HH.)**. A pesar de contar con más de 1000 empleados, salarios competitivos y beneficios atractivos, como un gimnasio gratuito, la compañía ha experimentado una alta tasa de renuncias en los últimos seis meses.  

La directora de RR. HH., **Marilyn Shah**, quien actúa como patrocinadora empresarial, ha identificado que esta pérdida de personal es mayor a la esperada y se debe, en su totalidad, a renuncias voluntarias. Para abordar esta situación, convoca a un equipo y organiza un **taller de Design Thinking** de un día. El objetivo es comprender a fondo el problema y explorar posibles soluciones.  

**Inicio del Proyecto de Ciencia de Datos**  

Durante el taller, el equipo comienza a generar ideas y formular hipótesis sobre las razones detrás de la alta rotación de empleados. Como parte del equipo, el científico de datos **Scott Hill** trabaja en colaboración con sus compañeros para definir el enfoque analítico más adecuado. Además, evalúa qué herramientas de la empresa serán necesarias para desarrollar un análisis efectivo y obtener respuestas clave sobre el problema.

================================================================

**Paso 2: Exploracion y preparación de datos**

### Paso 2: Exploración y Preparación de Datos  

Los científicos de datos tienen la tarea de **identificar y recopilar datos** de diversas fuentes dentro de una empresa. Estos datos pueden ser tanto **estructurados como no estructurados**, y suelen extraerse de:  

- Archivos estáticos, como hojas de cálculo.  
- Bases de datos.  
- Internet.  

#### Exploración de Datos  

Antes de proceder con el análisis, es fundamental examinar los datos recopilados. Si se detectan inconsistencias o información insuficiente, puede ser necesario **ajustar los requisitos de datos y recopilar más información**.  

La exploración inicial permite detectar **patrones y relaciones**, así como extraer información preliminar. Durante este proceso, los científicos de datos pueden hacerse preguntas clave como:  

- ¿Qué variables parecen relevantes para el análisis?  
- ¿Se han identificado nuevas características en los datos?  
- ¿Los hallazgos iniciales han cambiado la hipótesis original?  

#### Preparación de Datos  

Una vez explorados, los datos deben **prepararse para el modelado**, lo que implica:  

- **Limpieza y depuración** de datos.  
- **Combinación de información** proveniente de múltiples fuentes.  
- **Detección y corrección de problemas** como datos faltantes, valores incorrectos o atípicos.  

Dado que los datos del mundo real suelen contener errores o estar incompletos, los científicos de datos no pueden asumir que están listos para su uso inmediato. Para agilizar este proceso, emplean **herramientas y técnicas automatizadas**, lo que les permite **limpiar y transformar** los datos con mayor rapidez y precisión.

### Escenario del Proyecto: Exploración y Preparación de Datos  

Scott Hill, el científico de datos del equipo, se reúne con Lena, la administradora de la base de datos de GAXR, para comprender qué tipo de información recopila el departamento de Recursos Humanos sobre los empleados. Tras su revisión, Scott selecciona los datos relevantes para el análisis, como:  

- Nombre  
- Apellido  
- Edad  
- Departamento  
- Distancia desde el hogar hasta el trabajo (en kilómetros)  
- Tarifa por hora  
- Tarifa diaria  
- Ingresos mensuales  
- Estado civil  

#### Extracción y Organización de Datos  

Scott emplea **SQL** para extraer los datos necesarios de la base de datos y guardarlos en un **archivo CSV**.  

- **SQL** es un lenguaje ampliamente utilizado para gestionar datos en bases de datos relacionales.  
- **CSV** es un formato tabular que facilita el almacenamiento y procesamiento de datos. 

#### Limpieza y Refinamiento de Datos  

Scott lleva a cabo una serie de tareas para depurar los datos y asegurarse de que sean adecuados para el análisis:  

1. **Eliminación de datos innecesarios**:  
   - Descarta el campo *Recuento de empleados*, ya que su valor es siempre 1.  
   - Suprime columnas irrelevantes para la predicción, como *Número de teléfono*.  
   - Borra datos personales como *Nombre* y *Apellido* para proteger la privacidad.  

2. **Formateo de datos monetarios**:  
   - Redondea los valores de *Tarifa por hora* y otros campos financieros al dólar más cercano para estandarizar la información.  

3. **Verificación de calidad de datos**:  
   - Se asegura de que no haya valores faltantes.  
   - Confirma que hay suficientes datos para un análisis significativo, con un total de **1470 registros** de empleados.  

Después de la limpieza y exploración de datos, Scott reafirma su hipótesis: **la principal razón por la que los empleados dejan GAXR es la necesidad de un salario más alto en la economía actual**.

=====================================================

**Paso 3: Representación y transformación de datos**

La fase de representación y transformación de datos dentro de la metodología de la ciencia de datos se enfoca en:  

- **Comprender los datos**  
- **Evaluar su calidad**  
- **Identificar patrones iniciales y conocimientos clave**  

#### **El Rol del Científico de Datos**  

Los científicos de datos actúan como investigadores que analizan los datos en busca de pistas relevantes. Para ello, utilizan diversas técnicas, herramientas y tipos de análisis que les permiten estructurar y transformar la información para extraer conclusiones significativas.  

#### **Uso de Estadísticas Descriptivas**  

Una técnica común para analizar los datos es la **estadística descriptiva**, la cual permite resumir numéricamente un conjunto de datos y responder preguntas como: *¿Qué está ocurriendo en los datos?*  

A través de tablas y análisis numéricos, los científicos de datos pueden extraer información clave y obtener una visión rápida de grandes volúmenes de información. Algunos de los principales indicadores utilizados son:  

- **Número total de observaciones (N):** Cantidad de registros en el conjunto de datos.  
- **Media:** Promedio de un conjunto de valores.  
- **Mediana:** Valor central en una lista ordenada de datos.  
- **Moda:** Valor que aparece con mayor frecuencia en los datos.  
- **Mínimo y máximo:** Valores extremos dentro del conjunto de datos.  
- **Desviación estándar:** Medida de la dispersión de los datos con respecto a la media.  

Por ejemplo, en la image4 se encuentra una tabla que indica el ingreso familiar promedio en dólares estadounidenses de los clientes de una empresa, según su nivel educativo. Los datos son ficticios y tienen fines ilustrativos.