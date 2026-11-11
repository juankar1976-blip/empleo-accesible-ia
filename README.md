# Empleo Accesible IA

Building AI course project

## Summary

Empleo Accesible IA es una propuesta de asistente que ayuda a personas con discapacidad a encontrar ofertas acordes con su formación, capacidades y preferencias. Explica los requisitos con lenguaje claro y permite revisar las recomendaciones.

## Background

Buscar empleo exige leer muchas ofertas, interpretar requisitos y comprobar si las condiciones se ajustan a las necesidades de cada persona. Los anuncios no siempre explican la accesibilidad del puesto o las posibilidades de adaptación, lo que dificulta tomar decisiones informadas.

Mi motivación nace de mi formación en inserción laboral de personas con discapacidad y de mi interés por aplicar la inteligencia artificial a problemas cotidianos. El objetivo es facilitar la búsqueda y apoyar la autonomía de las personas, ofreciendo también una herramienta útil para profesionales de orientación laboral.

El proyecto se centra en tres problemas:

- El tiempo necesario para localizar ofertas relevantes.
- La dificultad para entender algunos requisitos y funciones.
- La falta de información clara sobre accesibilidad y adaptaciones.

## How is it used?

La persona introduce voluntariamente su formación, experiencia, competencias y preferencias: ubicación, horario, modalidad de trabajo y necesidades de accesibilidad. No es necesario indicar un diagnóstico médico.

El asistente muestra ofertas ordenadas por su relación con esas preferencias. Cada recomendación incluye los requisitos, las coincidencias, la información que falta y un enlace al anuncio original con su fecha de comprobación.

Por ejemplo, una persona que busca tareas administrativas desde casa podría recibir ofertas de atención al cliente o gestión de datos, acompañadas de una explicación de los requisitos que cumple y de los que debe comprobar.

La persona puede corregir su perfil, descartar resultados y decidir si presenta una candidatura. Los orientadores pueden utilizar la herramienta como apoyo, con autorización de la persona atendida. Las empresas se beneficiarían de anuncios más claros, pero el sistema no decidiría qué candidatos contratar.

La interfaz debería permitir navegación con teclado, lectura con tecnologías de apoyo y explicaciones breves. Su utilidad y comprensión se comprobarían con personas usuarias con distintas necesidades.

## Data sources and AI methods

El proyecto está en fase de propuesta: todavía no se han recopilado datos ni entrenado un modelo.

Para un primer prototipo se utilizarían perfiles ficticios y ofertas de ejemplo redactadas para el proyecto. Una fase posterior podría incorporar anuncios mediante fuentes que permitan su reutilización, acuerdos con entidades de empleo o interfaces autorizadas. Habría que comprobar permisos, calidad, fechas y condiciones de acceso antes de utilizarlas.

El sistema combinaría:

1. **Filtros explícitos:** ubicación, horario y modalidad elegidos por la persona. Los requisitos obligatorios se comprobarían antes de recomendar una oferta.
2. **Procesamiento del lenguaje natural:** extracción de funciones, competencias y requisitos de los anuncios.
3. **TF-IDF y similitud del coseno:** una primera aproximación para comparar las competencias del perfil con el contenido de las ofertas.
4. **Generación de explicaciones:** un modelo de lenguaje podría simplificar los requisitos utilizando únicamente la información del anuncio, indicando los datos ausentes en lugar de inventarlos.

La similitud textual no demostraría que una persona es apta para un puesto. Sería una ayuda para ordenar resultados, sujeta a revisión humana.

Se evaluaría el prototipo con un conjunto separado de ejemplos revisados por orientadores y personas usuarias. Se medirían la relevancia de las primeras recomendaciones, el incumplimiento de filtros obligatorios y los errores de las explicaciones. Los casos de evaluación no se utilizarían para ajustar el sistema. También se compararían los resultados con una búsqueda básica por palabras clave.

## Challenges

El asistente no garantiza empleo, accesibilidad del puesto ni adaptaciones por parte de la empresa. Tampoco determina la capacidad laboral, realiza diagnósticos o resuelve la compatibilidad de un trabajo con una prestación.

Una oferta puede estar caducada, incompleta o describir mal las funciones. El sistema debe mostrar la fuente, distinguir información comprobada de información desconocida y facilitar que se comuniquen errores.

Las recomendaciones podrían reproducir sesgos presentes en los anuncios. No se excluirían profesiones por un diagnóstico o porcentaje de discapacidad. Las preferencias y necesidades expresadas por cada persona tendrían prioridad, y se revisarían posibles diferencias injustificadas en los resultados.

Los perfiles reales requerirían consentimiento, minimización de datos, control de acceso y opciones para corregir o eliminar la información. No se publicarían currículos ni datos personales en el repositorio. El prototipo inicial emplearía únicamente datos ficticios.

## What next?

El primer paso sería crear un pequeño prototipo en Python con ofertas y perfiles ficticios, filtros básicos y comparación mediante TF-IDF. Después se realizarían pruebas con orientadores y personas con discapacidad para mejorar su utilidad y accesibilidad.

Para avanzar serían necesarias competencias de programación, tratamiento de texto, diseño accesible y evaluación de modelos, además de colaboración con entidades de inserción laboral. Solo después de validar el prototipo se plantearía una aplicación con ofertas reales y actualizaciones periódicas.

## Acknowledgments

La idea se inspira en los contenidos de Building AI sobre representación de texto, aprendizaje automático y evaluación, y en mi interés por la inserción laboral de personas con discapacidad.

La estructura de esta descripción sigue la plantilla del proyecto final de Building AI, creada por Reaktor Innovations y la Universidad de Helsinki.

Se ha utilizado ChatGPT como apoyo para estructurar y redactar esta propuesta. Este documento describe una idea; no presenta un sistema implementado ni resultados experimentales.

No se incluyen código, imágenes ni conjuntos de datos de terceros. Si se incorporan materiales externos en el futuro, se identificarán sus autores, fuentes y licencias.
