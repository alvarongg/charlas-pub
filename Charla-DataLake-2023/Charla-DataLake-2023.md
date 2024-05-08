 # Navegando en aguas tranquilas :
 ## Cómo evitar que tu Data Lake se convierta en un Data Swamp 🏞️



## Descripción

Este documento es un recurso adicional a la charla "Navegando en aguas tranquilas : Cómo evitar que tu Data Lake se convierta en un Data Swamp 🏞️" impartida en el Community Day de Chile 2023. Aquí, exploraremos los fundamentos de un data lake en aws, como mantenerlo util, seguro y que realmente genere un impacto en el negocio. El contenido está diseñado para complementar la charla, proporcionando ejemplos prácticos, enlaces útiles y consejos para aprovechar al máximo las herramientas de AWS en la creación y mantenimiento de un data lake.

## Contenidos 📋

- Por qué la charla?
- PPT de la charla
- Recursos de seguridad.
- Otras charlas interesantes

## ¿Por qué la charla? 🤔

Muchas veces veo que se habla mucho de la creación de data lakes serverless y muchas veces se dejan de lado temas tan importantes como el mantenimiento, la calidad de los datos, la gobernanza y por sobre todo la utilidad de los datos. En esta charla vamos a ver como podemos evitar que nuestro data lake se convierta en un data swamp y que servicios podemos utilizar para hacerlo de manera simple y costo eficiente.

## PPT de la charla 📊

El ppt de la charla se encuentra en la carpeta `ppt` correspondiente a esta charla.

## Recursos de seguridad en general 📚

Tengan en cuenta que existen muchos recursos en la web para aprender sobre seguridad en datalakes. Aquí les dejo algunos de los que considero más útiles:

- [Charla Online](https://www.linkedin.com/events/losanillosdeseguridad-salvaguar7082429703814287360/theater/) - Grabación de la charla que tuve la oportunidad de dar en el user group de Chile, posterior al evento presencial.
- [Udemy - Curso Certificación - AWS Data Engineer Asociate ](https://www.udemy.com/course/aws-data-engineer/)- El curso está en inglés y de pago, pero es una excelente opción para aprender sobre ingenieria de datos en aws, adicionalmente prepararse para rendir una certificación (Nota: Udemy ofrece una garantía de devolución del dinero de 30 días).(Nota 2: No tengo relación con el autor del curso, solo lo recomiendo porque lo hice y me pareció muy bueno).
- [AWS Skill Builder](https://explore.skillbuilder.aws/learn/signin) - Existen varios cursos sobre seguridad y otros servicios de AWS asociados que son 100% gratuitos.

## Capa Gratuita AWS 🆓

AWS ofrece una prueba gratuita de muchos de sus servicios dentro de su programa de free tier. Aquí les dejo algunos de los servicios que pueden utilizar para aprender sobre seguridad para data lakes en AWS:

# [Amazon s3](https://aws.amazon.com/s3/) 🗄️

Amazon S3 es un servicio de almacenamiento de objetos que ofrece escalabilidad, disponibilidad y durabilidad de los datos. Es una principal opcion de almacenamiento para un data lake en AWS.

- **5 GB** de almacenamiento estándar 📦
- **20.000** solicitudes GET y **2.000** solicitudes PUT 🔄
- **15 GB** de transferencia de datos salientes 📤
- **1 GB** de transferencia de datos entrantes 📥

# [Amazon Glue Data Catalog ](https://aws.amazon.com/glue/) 🧩

Amazon Glue es un servicio de ETL (Extract, Transform, Load) completamente administrado que facilita la preparación y carga de datos para el análisis. Amazon Glue descubre automáticamente y cataloga los metadatos de los datos en su data lake, lo que facilita la búsqueda y la consulta de estos datos.

- **1 millón** de objetos almacenados en el catálogo de datos de AWS Glue  al mes 🧩
- **1 millón** de solicitudes realizadas por mes al catálogo de datos de AWS Glue 🧩


# [Amazon Athena](https://aws.amazon.com/athena/) 🏛️

Amazon Athena es un servicio interactivo de consultas que facilita el análisis de datos en Amazon S3 mediante SQL estándar. Amazon Athena es ideal para analizar grandes conjuntos de datos de forma rápida y sencilla sin tener que preocuparse por la administración de la infraestructura.

- **5 TB** de escaneo de datos por mes 🏛️
- **30 GB** de almacenamiento de resultados por mes 🏛️

# [AWS Data Zone](https://aws.amazon.com/es/datazone/pricing/#:~:text=indican%20a%20continuaci%C3%B3n.-,Prueba%20gratuita,en%20una%20cuenta%20de%20AWS.)🏛️

AWS Data Zone es un servicio de almacenamiento de datos en la nube que permite a los clientes almacenar, proteger y gestionar sus datos de forma segura y eficiente. AWS Data Zone ofrece una amplia gama de capacidades de almacenamiento de datos, incluyendo almacenamiento de objetos, almacenamiento de archivos, almacenamiento de bloques y almacenamiento de copias de seguridad.

- **3 meses de prueba** para 50 usuarios 


# [Amazon Macie](https://aws.amazon.com/macie/) 🕵️‍♂️

Amazon Macie es un servicio de seguridad y privacidad de datos que utiliza el aprendizaje automático y la inteligencia artificial para descubrir, clasificar y proteger los datos confidenciales almacenados en AWS. Macie ayuda a proteger sus datos confidenciales, como la información personal identificable (PII) y la información financiera, al proporcionar visibilidad y control sobre sus datos en AWS.

- **30 días** de prueba gratuita 📚


# Importante sobre el Free Tier

Mucho cuidado con dejar cosas prendidas. Siempre que terminen de usar un servicio, apaguenlo o eliminenlo. Si no lo hacen, les van a cobrar y no hay manera al día de hoy de poner un corte en la facturación (aunque AWS está trabajando en ello).


## Otras charlas interesantes 📚

- [Machine Learning from 0 to Hero en aws](../Charla-Ml-0toHero/ML-0toHero.md)

- [Los Anillos de Seguridad en AWS](../Anillos-de-Seguridad/Anillos-de-Seguridad.md)


## Autores

-[Alvaro Garcia](https://linktr.ee/alvarongg)

## Licencia

Licencia abierta a la comunidad para que puedan utilizar, compartir y modificar el contenido de acuerdo a sus necesidades.

## Agradecimientos

Agradecimientos a los user gruoups que me permitieron participar de las charlas y a Ysa Troconis que me ayudó en la revisión del contenido.