# ETL_project
Master IA &amp; CD ETL project
En este trabajo vamos a trabajar con el dataset de kaggle llamado conjunto de datos de atención médica, disponible en [https://www.kaggle.com/datasets/prasad22/healthcare-dataset?resource=download]

## Acerca del conjunto de datos
Context:
Este conjunto de datos sintéticos de atención médica se ha creado para servir como un recurso valioso para los entusiastas de la ciencia de datos, el aprendizaje automático y el análisis de datos. Está diseñado para imitar los datos de atención médica del mundo real, lo que permite a los usuarios practicar, desarrollar y mostrar sus habilidades de manipulación y análisis de datos en el contexto de la industria de la atención médica.

## Inspiration:
La inspiración detrás de este conjunto de datos se basa en la necesidad de datos de atención médica prácticos y diversos con fines educativos y de investigación. Los datos sanitarios suelen ser sensibles y estar sujetos a normas de privacidad, lo que dificulta su acceso para el aprendizaje y la experimentación. Para abordar esta brecha, he aprovechado la biblioteca Faker de Python para generar un conjunto de datos que refleje la estructura y los atributos que se encuentran comúnmente en los registros de atención médica. Al proporcionar estos datos sintéticos, espero fomentar la innovación, el aprendizaje y el intercambio de conocimientos en el dominio de la analítica sanitaria.

## Dataset Information:
Cada columna proporciona información específica sobre el paciente, su admisión y los servicios de atención médica prestados, lo que hace que este conjunto de datos sea adecuado para diversas tareas de análisis y modelado de datos en el dominio de la atención médica. Aquí hay una breve explicación de cada columna en el conjunto de datos:

1.      Nombre: Esta columna representa el nombre del paciente asociado con la historia clínica.
2.      Edad: La edad del paciente en el momento del ingreso, expresada en años.
3.      Género: Indica el sexo del paciente, ya sea "Hombre" o "Mujer".
4.      Grupo sanguíneo: El tipo de sangre del paciente, que puede ser uno de los tipos de sangre comunes (por ejemplo, "A+", "O-", etc.).
5.      Dolencia: Esta columna especifica la afección médica primaria o el diagnóstico asociado con el paciente, como "Diabetes", "Hipertensión", "Asma" y más.
6.      Fecha de admisión: La fecha en que el paciente fue admitido en el centro de salud.
7.      Doctor: El nombre del médico responsable de la atención del paciente durante su ingreso.
8.      Hospital: Identifica el centro de salud u hospital donde el paciente fue ingresado.
9.      Proveedor de seguros: Esta columna indica el proveedor de seguros del paciente, que puede ser una de varias opciones, incluidas "Aetna", "Blue Cross", "Cigna", "UnitedHealthcare" y "Medicare".
10.     Monto de facturación: La cantidad de dinero facturada por los servicios de atención médica del paciente durante su ingreso. Esto se expresa como un número de punto flotante.
11.     Número de habitación: El número de habitación donde se alojó el paciente durante su ingreso.
12.     Tipo de admisión: Especifica el tipo de admisión, que puede ser "Emergencia", "Electiva" o "Urgente", reflejando las circunstancias de la admisión.
13.     Fecha de alta: La fecha en la que el paciente fue dado de alta del centro de atención médica, en función de la fecha de ingreso y un número aleatorio de días dentro de un rango realista.
14.     Medicación: Identifica un medicamento recetado o administrado al paciente durante su ingreso. Algunos ejemplos son "Aspirina", "Ibuprofeno", "Penicilina", "Paracetamol" y "Lipitor".
15.     Resultados de la prueba: Describe los resultados de una prueba médica realizada durante la admisión del paciente. Los valores posibles incluyen "Normal", "Anormal" o "No concluyente", lo que indica el resultado de la prueba.

## Usage Scenarios:

Este conjunto de datos se puede utilizar para una amplia gama de propósitos, entre ellos:

*   Desarrollo y prueba de modelos predictivos sanitarios.
*   Practicar técnicas de limpieza, transformación y análisis de datos.
*   Creación de visualizaciones de datos para obtener información sobre las tendencias de la atención médica.
*   Aprendizaje y enseñanza de conceptos de ciencia de datos y aprendizaje automático en un contexto sanitario.
*   Puede tratarlo como un problema de clasificación de varias clases y resolverlo para los resultados de la prueba, que contiene 3 categorías (normal, anormal y no concluyente).

##  Acknowledgments:
*   Reconozco la importancia de la privacidad y la seguridad de los datos sanitarios y enfatizo que este conjunto de datos es totalmente sintético. No contiene ninguna información real del paciente ni viola ninguna norma de privacidad.
*   Espero que este conjunto de datos contribuya al avance de la ciencia de datos y el análisis de la atención médica e inspire nuevas ideas. Siéntete libre de explorar, analizar y compartir tus hallazgos con la comunidad de Kaggle.