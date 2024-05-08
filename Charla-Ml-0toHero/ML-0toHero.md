# Machine Learning from 0 to Hero en AWS 🚀

## Descripción

Este documento es un recurso adicional a la charla "Machine Learning from 0 to Hero en AWS" impartida en el User Group de Buenos Aires. Aquí, exploraremos los fundamentos necesarios para comenzar a trabajar como Data Scientist utilizando tecnologías de AWS. El contenido está diseñado para complementar la charla, proporcionando ejemplos prácticos, enlaces útiles y consejos para aprovechar al máximo las herramientas de AWS en el campo del Machine Learning. 🧠

## Contenidos 📋

- Por qué la charla?
- PPT de la charla
- Recursos ML en general
- Capa Gratuita AWS
- Otras charlas interesantes

## ¿Por qué la charla? 🤔

En los años que llevo en la industria de la tecnología, he tenido la oportunidad de trabajar en diferentes roles, proyectos y negocios. Siempre lo más complicado fue definir exactamente cuáles son las capacidades que debe tener un equipo de Data Science para poder llevar adelante un proyecto de Machine Learning. Además de ser una consulta muy recurrente en la comunidad, es un tema que me apasiona y que me gustaría compartir con todos ustedes.

## PPT de la charla 📊

El ppt de la charla se encuentra en la carpeta `ppt` correspondiente a esta charla.

## Recursos ML en general 📚

Tengan en cuenta que existen muchos recursos en la web para aprender Machine Learning. Aquí les dejo algunos de los que considero más útiles:

- [Datacamp](https://www.datacamp.com/) - Datacamp es una plataforma de aprendizaje en línea que ofrece cursos de ciencia de datos y análisis de datos. Es una excelente opción para aquellos que desean aprender Machine Learning desde cero. (Nota: Datacamp ofrece una prueba gratuita de 7 días).
- [kaggle.com](https://www.kaggle.com/) - Kaggle es una plataforma en línea que permite a los científicos de datos y a los entusiastas de la ciencia de datos colaborar en proyectos de Machine Learning. Es una excelente manera de aprender y practicar Machine Learning en un entorno de la vida real.
- [Udemy - Curso practico de Sage Maker](https://www.udemy.com/course/practical-aws-sagemaker-6-real-world-case-studies/?couponCode=ST20MT50724)- El curso está en inglés y de pago, pero es una excelente opción para aquellos que desean aprender Machine Learning en AWS. (Nota: Udemy ofrece una garantía de devolución del dinero de 30 días).(Nota 2: No tengo relación con el autor del curso, solo lo recomiendo porque lo hice y me pareció muy bueno).
- [AWS Skill Builder](https://explore.skillbuilder.aws/learn/signin) - Existen varios cursos de introducción al ML con sage maker y otros servicios de AWS que son 100% gratuitos.

## Capa Gratuita AWS 🆓

AWS ofrece una prueba gratuita de muchos de sus servicios dentro de su programa de free tier. Aquí les dejo algunos de los servicios que pueden utilizar para aprender Machine Learning en AWS:


# [Amazon SageMaker](https://aws.amazon.com/sagemaker/) 🤖

Amazon SageMaker es un servicio de Machine Learning completamente administrado que permite a los desarrolladores y científicos de datos crear, entrenar y implementar modelos de Machine Learning de forma rápida y sencilla.

- **250 horas** al mes de ml.t3.medium en los blocs de notas de Studio o **250 horas** al mes de ml.t2.medium o ml.t3.medium en las instancias de bloc de notas bajo demanda 📚
- **25 horas** al mes en ml.m5.4xlarge en SageMaker Data Wrangler 🔧
- **10 millones de unidades** de escritura, **10 millones de unidades** de lectura, **25 GB** de almacenamiento al mes en el almacén de características de SageMaker 🏬
- **50 horas** al mes de instancias m4.xlarge o m5.xlarge en entrenamiento 🏋️‍♂️
- **125 horas** de instancia m4.xlarge o m5.xlarge al mes en inferencias 🔍

# [Amazon S3](https://aws.amazon.com/s3/) 🗄️

Amazon S3 es un servicio de almacenamiento de objetos que ofrece escalabilidad, disponibilidad y durabilidad de los datos. Es una excelente opción para almacenar grandes cantidades de datos para su uso en proyectos de Machine Learning.

- **5 GB** de almacenamiento estándar 📦
- **20.000** solicitudes GET y **2.000** solicitudes PUT 🔄
- **15 GB** de transferencia de datos salientes 📤
- **1 GB** de transferencia de datos entrantes 📥

# [Amazon Rekognition](https://aws.amazon.com/rekognition/) 🧠

Amazon Rekognition es un servicio de visión por computadora que permite a los desarrolladores analizar y reconocer objetos, texto y rostros en imágenes y videos. Es una excelente opción cuando tenemos que comparar caras, identificar objetos o analizar secuencias de video.

- **5.000** unidades de análisis de imágenes al mes 🖼️
- **1.000** unidades de análisis de video al mes 🎥

# [Amazon Personalize](https://aws.amazon.com/personalize/) 💡

Amazon Personalize es un servicio de recomendación que permite a los desarrolladores crear sistemas de recomendación personalizados para sus aplicaciones. Es una excelente opción para aquellos que desean implementar sistemas de recomendación de productos o servicios dentro de sus sistemas (trabaja en tiempo real o batch lo que lo hace excelente para newsletters).

- **2** meses de prueba gratuita 🆓
- **20** GB de almacenamiento de datos 📈
- **100** horas de uso de modelos (Recomendable usar 50 horas de entrenamiento y 50 horas de inferencia) ⏳

# [Amazon Comprehend](https://aws.amazon.com/comprehend/) 📖

Amazon Comprehend es un servicio de procesamiento de lenguaje natural (NLP) que permite a los desarrolladores analizar y extraer información de texto en varios idiomas. Particularmente útil para analizar sentimientos, entidades y temas en grandes volúmenes de texto, como por ejemplo transcripciones de charlas telefónicas o comentarios de clientes en redes sociales.

- **5.000** unidades de análisis de texto al mes 📝

# [Amazon Transcribe](https://aws.amazon.com/transcribe/) 🎙️

Amazon Transcribe es un servicio de transcripción automática de voz a texto que permite a los desarrolladores convertir archivos de audio en texto. Es una excelente opción para aquellos que desean transcribir entrevistas, reuniones o conferencias. Excelente para trabajar en conjunto con comprehend. (Se utiliza mucho en casos de uso de call centers)

- **60 minutos** de transcripción al mes ⏲️

# [Amazon Textract](https://aws.amazon.com/textract/) 🔍

Amazon Textract es un servicio de OCR (reconocimiento óptico de caracteres) que permite a los desarrolladores extraer texto y datos de documentos en papel y archivos PDF. Muy útil para digitalizar documentos en papel y extraer información de ellos.

- **1.000** páginas de texto extraído al mes 📄

# [Amazon Translate](https://aws.amazon.com/translate/) 🌍

Amazon Translate es un servicio de traducción automática que permite a los desarrolladores traducir texto entre idiomas.

- **2 millones** de caracteres de texto traducidos al mes 📑

# [Amazon EC2](https://aws.amazon.com/ec2/) 💻

Amazon EC2 es un servicio de informática en la nube que proporciona capacidad informática escalable en la nube. Es una excelente opción para ejecutar instancias de máquinas virtuales para entrenar y ejecutar modelos de Machine Learning. Útil cuando correr un modelo pequeño o probar un modelo que tengamos desarrollado en otro lado.

- **750 horas** al mes de distintas instancias de EC2 (t2.micro, t3.micro, t3a.micro, t4g.micro) ⏳




# Importante sobre el Free Tier

Mucho cuidado con dejar cosas prendidas. Siempre que terminen de usar un servicio, apaguenlo o eliminenlo. Si no lo hacen, les van a cobrar y no hay manera al día de hoy de poner un corte en la facturación (aunque AWS está trabajando en ello).


## Autores

-[Alvaro Garcia](https://linktr.ee/alvarongg)

## Licencia

Licencia abierta a la comunidad para que puedan utilizar, compartir y modificar el contenido de acuerdo a sus necesidades.

## Agradecimientos

Agradecimientos a los user gruoups que me permitieron participar de las charlas y a Matias Cirillo que me ayudó en la revisión del contenido.