# ENTREGA FINAL – CIENCIA DE DATOS APLICADA 

PROYECTO: ANALÍSIS DE FLUJO VEHICULAR EN PEAJES COLOMBIANOS 

INTEGRANTES: 

* Nicolas González Ochoa. 
* Francisco Santamaría. 
* Ana Catalina Gelvez.

# 📊 Link WEB APP 
https://p-gina-web-ciencia-de-datos.vercel.app/

▶️ Explicación WEB APP

El desarrollo del aplicativo combinó un conjunto de lenguajes, librerías y herramientas que permitieron llevar a cabo el análisis de datos, la construcción del modelo de machine learning y la implementación del dashboard interactivo para la visualización de resultados. A continuación, se presenta el detalle de las tecnologías empleadas, clasificadas según su propósito dentro del proyecto.
Los lenguajes de programación usados fueron Python, el cual fue el lenguaje principal para: limpieza y transformación de datos, análisis exploratorio (EDA), ingeniería de características, entrenamiento y validación de modelos. Además de cálculo de métricas y exportación de modelos entrenados. Para el desarrollo del dashboard web interactivo se usó JavaScript con el fin de Implementar la interfaz de usuario, visualización dinámica de modelos y resultados. Así mismo, la integración con servicios de despliegue. 
Como parte del front end se utilizó HTML y CSS para construir la estructura de la página web, aplicación de estilos, diseño y componentes visuales. También como soporte a la interfaz generada en React/Next.js

Finalmente, para el procesamiento y análisis de datos se utilizaron diversas librerías y frameworks de Python. Entre ellas, Pandas permitió el manejo de estructuras tabulares, así como la limpieza, filtrado y transformación del dataset. En este proyecto también se empleó NumPy para brindar soporte numérico en operaciones vectorizadas y cálculos eficientes, y la librería Datetime para la manipulación de fechas y secuencias temporales. Por otro lado, en la etapa de visualización se utilizaron Matplotlib para la generación de gráficos básicos y analíticos, y Seaborn para la creación de gráficos estadísticos y análisis visual más detallado.

El despliegue se efectuó a través de la plataforma Vercel, que ofrece los servicios de alojamiento y servidores requeridos para poner en funcionamiento esta primera versión del aplicativo. Sin embargo, a futuro, el aplicativo podrá migrar hacia una arquitectura en la nube que permite escalar de manera eficiente tanto el procesamiento de datos como la entrega de modelos y visualizaciones. Esta arquitectura podría basarse en servicios administrados que habiliten un flujo automatizado desde la ingestión y actualización del tráfico vehicular, hasta el entrenamiento, despliegue y monitoreo de los modelos de machine learning. Mediante servicios como almacenamiento en la nube para los datasets, contenedores o funciones serverless para la ejecución de los modelos, y un servicio gestionado de bases de datos para los resultados procesados, el sistema podrá operar con mayor estabilidad, seguridad y capacidad de respuesta. Adicionalmente, la integración con plataformas de despliegue web permitirá mantener el dashboard actualizado en tiempo real, ofreciendo una solución completamente escalable y preparada para el crecimiento del negocio y el incremento en los volúmenes de datos.

☁️ Futuro despliege serverless usando AWS 

A futuro, el aplicativo podrá evolucionar hacia una arquitectura en la nube basada en AWS, permitiendo escalar de forma segura y eficiente el procesamiento de datos y la entrega de modelos predictivos. En este esquema, Amazon S3 serviría como repositorio central para almacenar datasets históricos y resultados procesados, mientras que AWS Lambda o Amazon ECS podrían encargarse de ejecutar los modelos de machine learning de manera serverless o mediante contenedores escalables. Para la orquestación del entrenamiento y actualización de modelos, AWS Step Functions y Amazon SageMaker ofrecerían flujos automatizados y altamente gestionados. Los resultados del modelado podrían almacenarse en Amazon RDS o DynamoDB, permitiendo consultas rápidas desde el dashboard. Finalmente, Amazon CloudFront y AWS Amplify, o un despliegue directo a través de AWS Elastic Beanstalk facilitan la entrega del aplicativo web con alto rendimiento y disponibilidad global. Esta arquitectura proporciona escalabilidad, tolerancia a fallos, costos optimizados por demanda y una base sólida para integrar nuevas capacidades analíticas y productos de datos en el futuro.


# ▶️ Repositorio Aplicativo WEB
https://github.com/Pacho2020095/P-ginaWebCienciaDeDatos


# 💻 Presentación 
[PresentacionProyectoFinal.pdf](https://github.com/user-attachments/files/23845025/PresentacionProyectoFinal.pdf)

# ⏯️ Video presentación 

Link al video:
* https://drive.google.com/drive/folders/1CXXS1VpRkqFW4Hx2e3w2K0O7njkHmEx3?usp=sharing
* https://uniandes-my.sharepoint.com/:v:/g/personal/ac_gelvez1783_uniandes_edu_co/IQDIykJ-U4uUQ507W69205avAakdEwFHbVaTb4YxdOPBRoI

# 📑 PDF Documento 

[Entrega Final-Proyecto_AnalitcaDatos1 (1).pdf](https://github.com/user-attachments/files/23845258/Entrega.Final-Proyecto_AnalitcaDatos1.1.pdf)

# ⚠️ READ ME - Repositorio Modelos 

▶️ IMPORTANTE 

Dado que el dataset excede el límite de 25 MB permitido por GitHub, no fue posible alojarlo en el repositorio. En su lugar, se ha habilitado un enlace a una carpeta de OneDrive, accesible para usuarios con correo institucional de la Universidad de los Andes, desde donde podrán descargar los archivos para su ejecución local. 

Link al proyecto completo 
* https://uniandes-my.sharepoint.com/:f:/g/personal/ac_gelvez1783_uniandes_edu_co/IgC_NtThaH8ZToDHityGL7FUARKXvvbdXUn6ampmVEsA650?e=9Awf3A

# READ ME

🚧 Descripción del Proyecto

Este repositorio contiene el desarrollo completo del proyecto de análisis y modelado predictivo del tráfico vehicular para la Unión Temporal Peajes Nacionales (UTPN).
Incluye:

* Análisis exploratorio del comportamiento del tráfico.
* Procesamiento y limpieza del dataset.
* Entrenamiento de modelos de machine learning.
* Evaluación de métricas y desempeño.

Dashboard web para visualizar predicciones, errores y comportamiento del tráfico.

Documentación técnica, conclusiones de negocio y recomendaciones.

El objetivo principal del proyecto fue identificar oportunidades para optimizar los costos operativos de los peajes sin afectar su funcionamiento, utilizando modelos predictivos derivados de datos históricos.

🎯 Objetivos del Proyecto

* Comprender los alcances y calidad del dataset disponible.
* Realizar análisis exploratorio del tráfico por peaje y por sentido.
* Entrenar modelos predictivos que permitan anticipar el flujo vehicular.
* Determinar cuáles carriles pueden ser desactivados sin afectar la operación.
* Crear un dashboard para consulta, análisis y toma de decisiones.
* Proponer conclusiones de negocio y oportunidades de mejora.

🧠 Modelos de Machine Learning

Se entrenaron modelos independientes para cada peaje y cada sentido:

* Modelos utilizados
* DecisionTreeRegressor
* XGBoost Regressor (mejor desempeño general)
* Métricas implementadas
* RMSE
* MAE
* sMAPE
* MASE
* R²

Los modelos permitieron identificar escenarios donde es posible optimizar hasta un 50% de los costos operativos, manteniendo la operación sin afectaciones.

📊 Dashboard del Proyecto

El dashboard web muestra:

* Gráficas de tráfico promedio por tipo de día.
* RMSE y métricas de cada modelo entrenado.
+ Comparación entre tráfico real y predicho.
* Selección dinámica de peajes y sentidos.
* Resumen general del desempeño de todos los modelos.
* Tecnologías del dashboard
* Next.js
* React
* Recharts / Chart.js
* Vercel (despliegue)

🧹 Procesamiento y Limpieza de Datos

El dataset fue procesado aplicando:

* Eliminación de columnas irrelevantes o con más del 70% de nulos.
* Manejo de duplicados.
* Revisión y corrección de formatos de fecha y hora.
* Normalización y codificación de atributos categóricos.
* Selección de atributos clave:
* Fecha
* Tráfico por sentido
* Tipo de día

Se trabajó con un dataset consolidado:
* 38.833 registros, 44 peajes, periodo entre 2022–2025.

⚙️ Arquitectura Técnica (Actual y Futura)
Actual

Procesamiento y modelos: Python
* Visualización y uso: Dashboard en Next.js desplegado en Vercel

Distribución del dataset: OneDrive (por límite de 25MB en GitHub)
* Futura arquitectura en AWS
* S3 para almacenamiento de datasets.
* Lambda / ECS para ejecución de modelos.
* SageMaker para entrenamiento administrado.
* RDS o DynamoDB para almacenamiento de predicciones.
* CloudFront + Amplify para desplegar el dashboard.

📁 Estructura del Repositorio
/
├── notebooks/           # Análisis exploratorio y modelado (UTPN.ipynb)
├── models/              # Modelos entrenados (XGBoost / DecisionTree)
├── dashboard/           # Código del dashboard (Next.js)
├── diagrams/            # Diagramas del proyecto
├── data/                # Dataset (no incluido por límite de 25 MB)
├── utils/               # Funciones auxiliares
└── README.md

🔗 Acceso al Dataset

El dataset no se incluyó en el repositorio debido al límite de 25 MB impuesto por GitHub.
Ha sido habilitado en OneDrive para usuarios con correo institucional de la Universidad de los Andes.

🔗 Enlace al dataset:
(agregar aquí cuando tengas el link)

🤝 Contribuciones

Las contribuciones son bienvenidas a través de issues o pull requests.
Sugerencias de mejoras, optimizaciones o nuevos modelos son apreciadas.

📄 Licencia

Este proyecto se comparte bajo la licencia acordada con el cliente.
Modificar según corresponda (MIT, Apache, Proprietary, etc.).

🧩 Tecnologías y Librerías Utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Joblib / Pickle
* Datetime


📝 Conclusiones

El proyecto demuestra el potencial del uso de datos y modelos predictivos para optimizar la operación de peajes a nivel nacional. La implementación de soluciones basadas en datos permite reducir costos, mejorar procesos y fortalecer la toma de decisiones estratégicas.
Un desarrollo futuro puede incluir más características, datos en tiempo real y despliegue en una arquitectura cloud completamente escalable.

# ➕ Edición extendida documento 

ENTREGA FINAL – CIENCIA DE DATOS APLICADA 

PROYECTO: ANALÍSIS DE FLUJO VEHICULAR EN PEAJES COLOMBIANOS 

INTEGRANTES: 

Nicolas González Ochoa. 

Francisco Santamaría. 

Ana Catalina Gelvez. 

INTRODUCCIÓN 

...


PREPARACIÓN DE DATOS 

En el notebook se implementó un proceso estructurado de preparación de datos previo al entrenamiento de los modelos. Este proceso inició con la lectura y consolidación del dataset maestro, seguido de la normalización de tipos de datos y la estandarización del formato de fechas. Posteriormente, se eliminó información irrelevante (como la columna de archivo original) y se reorganizaron las columnas clave: peaje, sentido_1, sentido_2, total y fecha. 

Para el tratamiento del ruido, se aplicaron funciones especializadas que recortan ceros al inicio y final de cada serie, evitando que valores no representativos afectaran los patrones temporales. También se implementó la función to_int_no_decimals, que garantiza que todos los valores de tráfico sean numéricos y consistentes, independientemente del formato original del archivo. 

Como parte de la ingeniería de características, el notebook generó lags temporales, ventanas móviles (rolling means), indicadores de calendario y variables exógenas relevantes, con el fin de capturar la estacionalidad semanal y las tendencias del flujo vehicular. Asimismo, se aplicó la función slugify para normalizar los nombres de los peajes y evitar inconsistencias en el almacenamiento de modelos y resultados. 

Finalmente, se verificó la integridad del dataset, imputando ceros o eliminando valores faltantes cuando fue necesario (siempre preservando la coherencia temporal). El resultado fue un conjunto de datos limpio, consistente y enriquecido, listo para ser usado tanto en el entrenamiento de los modelos como en la construcción de dashboards analíticos. 

 <img width="520" height="896" alt="Frame 1" src="https://github.com/user-attachments/assets/43936a48-0350-4298-b5ee-49dfd863fb59" />

 

ESTRATEGIA DE VALIDACIÓN Y SELECCIÓN DE MODELO 

Estrategia de validación y selección de modelo 

Para la construcción del producto de datos se definió una estrategia de experimentación basada en series de tiempo, alineada con la naturaleza temporal del problema de predicción de flujo vehicular por peaje y sentido. 

Estrategia de experimentación 

El experimento se planteó a nivel de peaje y sentido, es decir, para cada estación y para cada columna objetivo (sentido_1 y sentido_2) se entrenó un modelo independiente. Sobre cada serie se aplicaron las mismas etapas: 

Preparación de datos: limpieza de registros inconsistentes, recorte de tramos con tráfico total igual a cero para evitar ruido, y generación de características temporales como lags de 1, 3, 7, 14, 21 y 28 días, medias móviles de 3, 7, 14 y 28 días, y variables calendarias. 

Modelos evaluados: se probaron tres algoritmos basados en árboles de decisión (XGBoost, LightGBM y CatBoost). Para XGBoost se realizó una búsqueda manual de hiperparámetros sobre una grilla de configuraciones, seleccionando la combinación con menor RMSE en validación. LightGBM y CatBoost se configuraron como modelos baseline avanzados y fueron comparados bajo las mismas métricas. 

Métricas utilizadas: se emplearon RMSE, MAE, SMAPE y MASE. La selección final del mejor modelo por peaje y sentido se basó principalmente en las métricas de prueba (RMSE_test y MAE_test), complementadas con SMAPE y MASE para medir la precisión relativa y la mejora frente a un modelo naïve estacional. 

En la mayoría de los casos, XGBoost resultó ser el modelo con mejor equilibrio entre precisión y estabilidad, por lo que fue seleccionado como algoritmo principal del producto de datos. 

Estrategia de partición: entrenamiento, validación y prueba 

Dado que se trabaja con series de tiempo, se utilizó una partición estrictamente cronológica para evitar fugas de información (data leakage). Para cada peaje y sentido, los datos se ordenaron por fecha y se aplicó una función especializada que divide los datos en: 

Conjunto de prueba: los últimos 30 días de la serie. 

Conjunto de validación: los 90 días anteriores al conjunto de prueba (o menos si la serie es corta). 

Conjunto de entrenamiento: todo el histórico anterior al conjunto de validación. 

En series muy cortas, la función ajusta dinámicamente los tamaños para garantizar un entrenamiento mínimo. Esta estrategia refleja adecuadamente el escenario real, donde el modelo aprende del pasado para predecir el futuro. 

Verificación de la distribución en los subconjuntos 

Para evaluar si los subconjuntos son representativos, se compararon estadísticas como media, desviación estándar, percentiles y rangos de tráfico por sentido. También se verificó la proporción de días entre semana y fines de semana. 

En la mayoría de los peajes, las distribuciones se mantuvieron coherentes entre los subconjuntos, preservando la estacionalidad y la variabilidad natural. Sin embargo, en estaciones con cambios abruptos en comportamiento (como La Parada o Pto. Triunfo), los conjuntos de validación y prueba mostraron mayor variabilidad, lo cual se reflejó en mayores errores. Esto indica que para esos casos podrían considerarse modelos más flexibles o incluir información adicional sobre cambios operativos. 

En general, la estrategia de validación implementada sigue las buenas prácticas en series de tiempo y permite una evaluación realista de la capacidad de generalización de los modelos. 

 

CONSTRUCCIÓN Y EVALUACIÓN DEL MODELO 

En el proceso de construcción y evaluación del modelo se tuvo en cuenta los siguientes criterios de Selección del Modelo Final.   

El modelo seleccionado para cada peaje/sentido fue aquel que cumplió con: 

Menor RMSE en el conjunto de prueba, el sMAPE estable y dentro de rangos aceptables (<20%). Además, el MASE < 1, indicando mejora sobre un modelo base y el comportamiento visual coherente en la comparación real vs. Predicho. Por otro lado, la estabilidad entre validación y prueba con estos criterios, el mejor desempeño identificado correspondió al peaje Bicentenario (Sentido 1) con un RMSE de prueba de 100.0. 

La estrategia integral de validación y selección garantiza que los modelos escogidos representen fielmente el comportamiento del tráfico, sean robustos frente a variaciones temporales, coherentes con las necesidades del cliente, igualmente, permitan tomar decisiones informadas sobre la operación de los peajes. Finalmente, en conjunto, este proceso asegura el uso de modelos confiables, interpretables y con desempeño comprobado en escenarios reales.} 

Nota: Si se desea información más detallada por favor visitar el repositorio en la sección del notebook UTPN.ipynb. 

RETROALIMENTACIÓN POR PARTE DE LA ORGANIZACIÓN 

 

A continuación, se listan las interacciones hechas con los stakeholders 

ITEM 

FECHA 

STAKEHOLDER 

CARGO 

ACTIVIDAD 

1 

27/08/25 

Gerónimo Canal 

Socio 1Solution (empresa socia de UTPN) 

hablar de la oportunidad que se presenta desde la materia en la cual se le muestra la oportunidad de crear un producto de datos que pueda aportar en la compañía, el stakeholder consigue la cita con el gerente de peajes nacionales 

2 

27/08/25 

Álvaro Avendaño 

Gerente UTPN 

Se realiza un primer acercamiento con el gerente con el fin de acceder a una cita para comentar la oportunidad que se presenta, se agenda cita para el 28/08/2025 

3 

28/08/25 

Alvaro Avendaño 

Gerente UTPN 

Se realiza reunion presencial en la oficina de UTPN, en esta se le cuenta al stakeholder la oportunidad que se tiene de generar un producto de datos, se evidencian diferentes dolores entre los cuales estan, operaciones con costos fijos contractuales, PQRS y mantenimiento recurrente en estaciones. Se decide en conjunto avanzar con los costos fijos de operación ya que se tienen datos. 

4 

8/09/25 

Alvaro Avendaño 

Gerente UTPN 

Se insiste al stakeholder en la entrega de información de datos. 

5 

9/09/25 

Alvaro Avendaño 

Gerente UTPN 

Se insiste al stakeholder en la entrega de información de datos, se indica que la persona encargada sera Carlos Guarin gerente financiero.  

6 

11/09/25 

Carlos Guarin  

Gerente financiero UTPN 

Se hace primer contacto con el stakeholder donde se le comenta la necesaidad de la información 

7 

12/09/25 

Carlos Guarin  

Gerente financiero UTPN 

Se realiza aclaración de dudas sonre la información requerida  

8 

17-30/09/2025 

Carlos Guarin  

Gerente financiero UTPN 

Se realiza seguimiento para entrega de la información 

9 

6/10/25 

Carlos Guarin  

Gerente financiero UTPN 

Se remite informacion por parte del stakeholder 

10 

7/10/25 

Carlos Guarin  

Gerente financiero UTPN 

Se confirma al stakeholder que ya se descargo la información y se solicitan aclaraciones, donde indica lo progresivo de la información 

11 

16/10/25 

Carlos Guarin  

Gerente financiero UTPN 

Se le cuenta cual es el plan de implementación al stakeholder  

12 

22/10/25 

Carlos Guarin  

Gerente financiero UTPN 

Se realiza un avance al stakeholder donde se muestra el analisis de información y basado en esto se realiza una selección de estaciones objetivos 

13 

4/11/25 

Carlos Guarin  

Gerente financiero UTPN 

Se realiza avance al stakeholder y se realizan preguntas sobre el tiempo de transitos en carriles, se remtie un nuevo stakeholder que es el gerente de operaciones 

14 

19/11/25 

Cristina Duran 

Gerente operaciones 

Se habla con el stakeholder para indagar por el tiempo promedio de un vehiculo en transitar  

15 

25/11/25 

Carlos Guarin  

Gerente financiero UTPN 

Remite información de costos promedio por carril en cada estación 

 

CONCLUSIONES 

¿Se cumplieron los objetivos del proyecto? 

El propósito central del proyecto consistió en encontrar alternativas que permitieran reducir los costos operativos de los peajes sin afectar su funcionamiento, empleando predicción mediante modelos de machine learning. Dado que la predicción de 30 días evidencio el ahorro en operación se cumple el objetivo de validar que es posible la reducción de costos de operacion.  

¿Cuáles fueron las mayores dificultades que se obtuvieron durante su Desarrollo? 

El propósito central del proyecto fue identificar alternativas para reducir los costos operativos de los peajes sin comprometer su funcionamiento, utilizando modelos de predicción basados en machine learning. Los resultados obtenidos en la proyección a 30 días demostraron que es posible anticipar el comportamiento del flujo vehicular con suficiente precisión para optimizar la asignación de recursos operativos. Esto permitió validar que la reducción de costos es alcanzable sin afectar la operación, cumpliendo así el objetivo planteado. 

¿Qué estimación se puede dar respecto a cómo se impactarían las métricas de negocio (KPIs) una vez el producto de datos sea utilizado por usuarios reales? 

La adopción del producto de datos por parte de los usuarios operativos tendría un impacto directo y medible sobre los principales KPIs del sistema de peajes. En primer lugar, al permitir anticipar con 30 días de antelación el flujo vehicular por estación y sentido, se optimiza la asignación de personal y la habilitación de carriles, lo que se traduce en una reducción significativa de los costos operativos asociados a turnos, horas extra y sobredimensionamiento de recursos. En segundo lugar, una operación más eficiente contribuye a mejorar indicadores como el nivel de servicio, ya que se mitigan congestiones, tiempos de espera prolongados y cierres innecesarios de carriles. 

Adicionalmente, el uso sistemático de predicciones precisas permite mejorar la planificación presupuestal, evitando sobrecostos por decisiones reactivas y favoreciendo la toma de decisiones basada en datos. También se espera un impacto positivo en la eficiencia operativa global, dado que los recursos son asignados donde realmente se necesitan según patrones históricos y proyectados. Finalmente, la correcta implementación del producto de datos puede favorecer KPIs estratégicos como la satisfacción del usuario, la disponibilidad operativa y la confiabilidad del servicio, consolidando un modelo de operación más sostenible y basado en analítica avanzada. 

¿Qué condiciones considera que deberían tener los datos para obtener mejores resultados? Más datos, nuevas características, menor sesgo, etc.  

Para incrementar la precisión y robustez de los modelos predictivos desarrollados, sería fundamental contar con datos que cumplan varias condiciones clave: 

Mayor volumen y continuidad temporal 
Los modelos de series de tiempo se benefician fuertemente de series largas, estables y sin interrupciones. Contar con varios años adicionales sin vacíos de información permitiría capturar mejor patrones estacionales, efectos recurrentes y variabilidad interanual. 

Datos más limpios y coherentes 
La presencia de ceros artificiales o valores atípicos generados por fallas de registro afecta la señal real del tráfico vehicular. Contar con datos sin ruido operativo y con un proceso riguroso de control de calidad mejoraría directamente el ajuste del modelo. 

Nuevas características (features) relevantes 
Incorporar variables externas con relación causal al tráfico puede mejorar sustancialmente el poder predictivo. Entre ellas: 

Festivos, puentes y calendarios locales más detallados 

Clima (lluvia, temperatura, visibilidad) 

Eventos especiales o cierres viales 

TRM, combustibles, comportamientos estacionales regionales 

Datos de sensores adicionales como densidad, velocidad o clasificación detallada del vehículo 

Menor sesgo por cambios operativos 
Algunas estaciones presentan quiebres abruptos en la serie debido a obras, cierres o momentos donde el contador dejó de funcionar. Series más homogéneas o con marcas claras de los eventos permitirían a los modelos aprender con consistencia y evitar rupturas que afectan la generalización. 

Mejor granularidad operacional 
Datos por carril, por categoría de vehículo o por intervalos de tiempo más pequeños (por ejemplo, cada hora) permitirían modelos más finos y 

explicativos, además de facilitar estimaciones más precisas para la toma de decisiones diarias. 

Mayor representatividad para casos extremos (picos y valles) 
Los modelos muestran un mayor error cuando deben predecir días altamente atípicos. Tener más ejemplos de esos escenarios ayudaría a capturar mejor su comportamiento y reducir errores futuros. 

¿El mejor modelo obtenido es suficiente para dar solución al problema u oportunidad de negocio abordado? 

El mejor modelo obtenido sí aporta una base sólida para abordar el problema de negocio, ya que demuestra que es posible predecir el flujo vehicular con una precisión suficiente para soportar decisiones operativas, especialmente las relacionadas con la programación de personal y habilitación de carriles, que son el principal costo operativo de los peajes. 

En términos prácticos, el modelo permite anticipar la demanda con 30 días de anterioridad, lo que habilita escenarios como: 

Optimizar turnos de operación, reduciendo horas hombre en días de baja demanda. 

Habilitar únicamente los carriles necesarios, disminuyendo costos sin afectar el nivel de servicio. 

Planificar mantenimientos o cierres parciales en días proyectados con menor flujo. Sin embargo, aunque el modelo es funcional y demuestra valor, no es aún la versión definitiva del producto de datos. Existen estaciones con comportamiento más complejo donde el error es mayor (por ejemplo, La Parada sentido 2), lo cual indica la necesidad de: Incluir variables externas más relevantes (clima, eventos, cierres viales). 

Mejorar la calidad y continuidad de las series históricas. 

Ajustar modelos personalizados por estación con arquitectura más flexible. 

En conclusión: 
El modelo actual es suficiente para demostrar viabilidad y generar ahorros operativos reales, pero requiere iteraciones adicionales para convertirse en un producto de datos robusto, escalable y apto para implementación en producción. 


