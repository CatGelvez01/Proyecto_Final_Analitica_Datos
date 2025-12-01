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
