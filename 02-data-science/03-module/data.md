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


Los científicos de datos tienen la tarea de **identificar y recopilar datos** de diversas fuentes dentro de una empresa. Estos datos pueden ser tanto **estructurados como no estructurados**, y suelen extraerse de:  

- Archivos estáticos, como hojas de cálculo.  
- Bases de datos.  
- Internet.  

**Exploración de Datos**  

Antes de proceder con el análisis, es fundamental examinar los datos recopilados. Si se detectan inconsistencias o información insuficiente, puede ser necesario **ajustar los requisitos de datos y recopilar más información**.  

La exploración inicial permite detectar **patrones y relaciones**, así como extraer información preliminar. Durante este proceso, los científicos de datos pueden hacerse preguntas clave como:  

- ¿Qué variables parecen relevantes para el análisis?  
- ¿Se han identificado nuevas características en los datos?  
- ¿Los hallazgos iniciales han cambiado la hipótesis original?  

**Preparación de Datos**  

Una vez explorados, los datos deben **prepararse para el modelado**, lo que implica:  

- **Limpieza y depuración** de datos.  
- **Combinación de información** proveniente de múltiples fuentes.  
- **Detección y corrección de problemas** como datos faltantes, valores incorrectos o atípicos.  

Dado que los datos del mundo real suelen contener errores o estar incompletos, los científicos de datos no pueden asumir que están listos para su uso inmediato. Para agilizar este proceso, emplean **herramientas y técnicas automatizadas**, lo que les permite **limpiar y transformar** los datos con mayor rapidez y precisión.

**Escenario del Proyecto: Exploración y Preparación de Datos**  

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

**Extracción y Organización de Datos**  

Scott emplea **SQL** para extraer los datos necesarios de la base de datos y guardarlos en un **archivo CSV**.  

- **SQL** es un lenguaje ampliamente utilizado para gestionar datos en bases de datos relacionales.  
- **CSV** es un formato tabular que facilita el almacenamiento y procesamiento de datos. 

**Limpieza y Refinamiento de Datos**  

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

*El Rol del Científico de Datos* 

Los científicos de datos actúan como investigadores que analizan los datos en busca de pistas relevantes. Para ello, utilizan diversas técnicas, herramientas y tipos de análisis que les permiten estructurar y transformar la información para extraer conclusiones significativas.  

*Uso de Estadísticas Descriptivas*  

Una técnica común para analizar los datos es la **estadística descriptiva**, la cual permite resumir numéricamente un conjunto de datos y responder preguntas como: *¿Qué está ocurriendo en los datos?*  

A través de tablas y análisis numéricos, los científicos de datos pueden extraer información clave y obtener una visión rápida de grandes volúmenes de información. Algunos de los principales indicadores utilizados son:  

- **Número total de observaciones (N):** Cantidad de registros en el conjunto de datos.  
- **Media:** Promedio de un conjunto de valores.  
- **Mediana:** Valor central en una lista ordenada de datos.  
- **Moda:** Valor que aparece con mayor frecuencia en los datos.  
- **Mínimo y máximo:** Valores extremos dentro del conjunto de datos.  
- **Desviación estándar:** Medida de la dispersión de los datos con respecto a la media.  

Por ejemplo, en la image4 se encuentra una tabla que indica el ingreso familiar promedio en dólares estadounidenses de los clientes de una empresa, según su nivel educativo. Los datos son ficticios y tienen fines ilustrativos.

*Exploración visual y transformación de datos*  

Las estadísticas por sí solas pueden resultar engañosas, por lo que los científicos de datos complementan su análisis con **visualizaciones exploratorias**. Estas representaciones gráficas, como gráficos de líneas o circulares, permiten identificar distribuciones, patrones y tendencias de manera más clara y comprensible.  

Además de analizar los datos, es fundamental evaluar su calidad. Un conjunto de datos de baja calidad puede afectar negativamente el rendimiento de los modelos predictivos en etapas posteriores del proceso de ciencia de datos.  

Tras la representación de los datos, se procede a su **transformación**. Los científicos de datos estructuran y organizan la información en un formato adecuado para el **aprendizaje automático**, una rama de la inteligencia artificial que emplea algoritmos para mejorar progresivamente su precisión. Dado que estos modelos solo interpretan números, es necesario convertir textos o imágenes en datos numéricos.  

Un ejemplo de transformación es la **tokenización**, que descompone textos en palabras, frases o símbolos significativos para luego convertirlos en información numérica. Para realizar estas transformaciones, los científicos de datos emplean herramientas y lenguajes de programación como **Python**, lo que les permite estandarizar y organizar los datos de manera óptima para el análisis.  

En esta etapa, también pueden refinar el enfoque analítico definido inicialmente en la fase de **comprensión del negocio**, ajustando su estrategia para obtener mejores resultados.

*Escenario del proyecto: Representación y transformación de datos*  

Scott Hill, el científico de datos del equipo, sigue avanzando en el proyecto para descubrir las razones detrás de la alta rotación de empleados en GAXR.  

Al profundizar en los datos, se da cuenta de que necesita una fuente adicional de información para comprender mejor las causas de la pérdida de personal. En particular, requiere datos que indiquen por qué cada empleado dejó la empresa.  

Para ello, Scott utiliza **SQL** y fusiona estos nuevos datos en su archivo **CSV**. Como parte de este proceso, agrega una columna clave llamada **"Attrition"**, que registra si un empleado ha renunciado. Este es un paso fundamental en su análisis

La columna **"Attrition** en la image6 contiene datos dicotómicos, lo que significa que cada celda solo puede tener dos valores posibles: **"Sí" o "No"**. Esta información permite a Scott responder de manera rápida y clara si un empleado dejó GAXR o no.  

Para garantizar la compatibilidad con el modelo que el equipo planea utilizar, Scott verifica que los datos estén en el formato adecuado.  

Además, emplea una herramienta de visualización para generar gráficos y tablas, obteniendo así información preliminar que le ayuda a identificar patrones en los datos.  

Es importante destacar que la columna **"Attrition"** servirá como datos de entrenamiento para construir un **modelo de aprendizaje supervisado**, permitiendo a la empresa analizar y anticipar futuras pérdidas de personal.

========================================================

**Paso 4: Visualización y presentación de datos**

La **visualización de datos** representa el resultado final del trabajo de un equipo de ciencia de datos, permitiendo interpretar y comunicar los conocimientos obtenidos durante la transformación de datos.  

Las visualizaciones ayudan a validar hipótesis y verificar suposiciones, permitiendo que los datos cuenten una historia y respondan al problema comercial planteado en el proyecto.  

El equipo de ciencia de datos emplea software especializado para generar visualizaciones que faciliten la interpretación de los datos. El objetivo es crear representaciones **claras, atractivas e impactantes**.  

Se dice que **"una imagen vale más que mil palabras"**, y esto cobra especial importancia en la visualización de datos. Un solo gráfico puede responder múltiples preguntas y ayudar a simplificar conceptos complejos.  

*Aspectos clave en la presentación de datos*
Para que la presentación final sea efectiva, debe ser **clara, persuasiva y fácil de interpretar** para el patrocinador empresarial. No se trata solo de mostrar resultados visuales, sino de estructurar la presentación considerando:  

- **Propósito**: ¿Qué problema se aborda y cómo la visualización contribuye a su solución?  
- **Audiencia**: ¿Quiénes verán la presentación y qué valor les aporta?  
- **Datos**: ¿La representación es adecuada y necesita actualizaciones futuras?  
- **Contexto**: ¿Dónde se utilizará la visualización (software, sitio web, informe comercial)?  

En definitiva, la visualización de datos debe responder al problema empresarial y presentar una solución clara y fundamentada.

*Escenario del proyecto: Visualización y presentación de datos*  

Scott Hill, el científico de datos del equipo, está listo para analizar la información y proponer una solución al problema de rotación en GAXR.  

Para ello, utiliza una herramienta de visualización de datos que le permite encontrar la mejor manera de representar la información. A través de un gráfico de dispersión con una curva en forma de **S**, Scott identifica un patrón claro: **los empleados que viven más lejos de la empresa tienden a renunciar con mayor frecuencia**.  

*Elementos clave de la visualización:* 
- Cada punto representa un empleado del conjunto de datos.  
- Se observa una relación entre la distancia al trabajo y la probabilidad de renuncia.  
- La "p" en la curva indica la probabilidad de que los empleados abandonen la empresa a medida que aumenta la distancia.  

Con base en estos hallazgos, Scott prepara una presentación para el equipo y Marilyn Shah, la directora de RR. HH. En ella, expone:  
1. El problema de la empresa.  
2. Las fuentes de datos utilizadas.  
3. Los procesos de preparación y transformación de datos.  
4. La visualización que muestra la información clave.  
5. Una posible solución al problema.  

Tras analizar la situación, el equipo propone como solución **permitir el teletrabajo dos días a la semana** para reducir el impacto de la distancia en la retención de empleados. Marilyn comparte esta idea con la dirección y, además, solicita al equipo que continúe con el proceso de ciencia de datos para **predecir futuros problemas de rotación** y anticipar soluciones a largo plazo.

Un proyecto de ciencia de datos puede finalizar en este punto con una solución única y específica.  

Sin embargo, también puede avanzar hacia el desarrollo de un modelo predictivo para anticipar problemas futuros. Con datos bien procesados y una comprensión clara de la información, los científicos de datos pueden construir un modelo que permita prever y abordar situaciones similares de manera proactiva.

========================================================

**Paso 5: Entrenar modelos de datos**

*¿Qué es un modelo?*  

Un modelo de datos define la estructura de la información, identificando los datos, sus atributos y las relaciones entre ellos. Proporciona una representación simplificada de la realidad empresarial, permitiendo comprender mejor el sistema analizado.  

*¿Por qué crear un modelo?*  

Desarrollar un modelo permite a los científicos de datos abordar problemas de manera más estructurada. Su principal propósito es mejorar la capacidad de predicción y profundizar en la comprensión del sistema que se estudia.  

*Entrenamiento del modelo y aprendizaje automático*  

Siguiendo el método científico, los científicos de datos experimentan con distintos modelos para realizar predicciones. Para entrenar un modelo, recurren al aprendizaje automático, que permite a las computadoras aprender de los datos sin necesidad de programar reglas explícitas. Mediante algoritmos, la máquina procesa la información y mejora su precisión con el tiempo.

En la image7 se muestra una tabla para una comparación rápida entre el aprendizaje supervisado y el aprendizaje no supervisado.

*Escenario del Proyecto: Entrenamiento de Modelos de Datos*  

Marilyn Shah, directora de RR.HH. y patrocinadora del proyecto, quiere ampliar el análisis para prevenir futuras renuncias en GAXR.  

Scott Hill, el científico de datos del equipo, se dispone a entrenar y validar un modelo. Para ello, utiliza la columna de "Deserción" en el archivo CSV, que contiene datos dicotómicos (“sí” o “no”). Estos datos servirán como base para entrenar un modelo de aprendizaje supervisado, específicamente un modelo de **regresión logística**.  

*¿Qué es un modelo de regresión?*  

Es un enfoque común en ciencia de datos para estimar la probabilidad de que ocurra un evento en función de ciertas variables independientes. Como el resultado es una probabilidad, la variable categórica suele adoptar valores como **sí/no, 1/0 o verdadero/falso**.  

Ejemplos de su aplicación incluyen la detección de correos electrónicos spam o la predicción de si un tumor es maligno o no.  

En un modelo de regresión logística, la relación entre variables se representa mediante una **curva en forma de S**. Por ejemplo, si se analiza la probabilidad de aprobar un examen en función de las horas de estudio, la curva S reflejará cómo el aumento en las horas de estudio incrementa la probabilidad de aprobar.

Scott emplea la última tecnología en GSRX, utilizando la función **AutoAI en IBM Watson Studio** para entrenar y validar el modelo. Luego, revisa los resultados que muestran la cantidad de predicciones acertadas y erróneas, permitiéndole evaluar su precisión.  

El modelo descarta que la deserción futura de empleados esté influenciada por el estado civil o el grupo empresarial al que pertenecen.  

En cambio, los resultados indican que la **distancia entre el hogar y el lugar de trabajo** sigue siendo un factor clave en la decisión de los empleados de dejar voluntariamente GSRX en el futuro.

=====================================================

**Paso 6: Implementar modelos de datos**

La implementación del modelo integra el aprendizaje automático en el entorno de producción de la empresa. Los científicos de datos utilizan herramientas específicas para guardarlo, ejecutarlo y mejorar las predicciones futuras. Una vez en marcha, el modelo opera según un cronograma y requiere mantenimiento continuo.

Scott Hill implementa el modelo en producción para GAXR con IBM AutoAI, generando un archivo de aprendizaje automático. Ahora, los datos futuros de los empleados podrán ayudar a reducir la deserción debido a la distancia al trabajo. Con el modelo operativo, Scott reflexiona sobre su mantenimiento, preguntándose cómo evaluar su desempeño, con qué frecuencia reentrenarlo, si los datos de producción diferirán de los de entrenamiento, si se procesarán en lotes o en flujo, y si el modelo deberá ejecutarse sin conexión.

=========================================================