# Proyecto de programación

!!! warning "Pendientes"
    - Ecuaciones matemáticas
    - Ejemplos de gráficas bien rotuladas
    - "Siguiente" y "anterior" en pie de página
    - Ofrecer estructura de presentación de resultados

Esta es la documentación del proyecto de programación de IE0405 - Modelos Probabilísticos de Señales y Sistemas.

Los objetivos están en esta página mientras que una introducción a los temas de recopilación, procesamiento y modelado de datos están en las páginas siguientes. Finalmente están las instrucciones específicas del proyecto.

## Objetivos

!!! note "Objetivo general"
    Implementar una canalización de datos (*pipeline*) en tiempo real para procesamiento y análisis a partir de una fuente de datos externa, utilizando las herramientas computacionales de Python.

### Objetivos específicos de ***programación***

1. Configurar tareas periódicas
2. Recopilar datos de un API web
3. Procesar datos en formato JSON
4. Utilizar bases de datos SQL
5. Documentar el desarrollo 

### Objetivos específicos de ***aplicación***

1. Explorar fuentes de datos en tiempo real para su recopilación y análisis.
2. Utilizar interfaces de programación de aplicaciones (API) de forma programática para obtener datos de fuentes externas.
3. Utilizar administradores de tareas (Celery Worker) y planificadores de tareas (Celery Beat) para ejecutar tareas periódicas.
4. Utilizar un gestor de bases de datos (SQLite3, PostgreSQL) y un mapeador de objetos relacional (SQLAlchemy) para interactuar con bases de datos.
5.  Procesar los datos obtenidos para tratamiento y análisis.
6.  Utilizar herramientas estadísticas de Python para hacer análisis estadístico descriptivo y modelado probabilístico de los datos recopilados.
7. Graficar los datos recopilados y sus análisis para visualización y análisis preliminar.
8. Crear documentación del proyecto en forma de página web para presentación al público en general.

### Objetivos específicos de ***estadística y probabilidad***

1. Realizar análisis exploratorios de datos con estadística descriptiva
2. Determinar modelos de probabilidad y sus parámetros
3. Graficar datos y sus modelos de probabilidad
4. Analizar transformaciones de variables aleatorias
5. Analizar procesos aleatorios

## Sobre la documentación

Esta documentación está creada con [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), una plataforma amplísima con múltiples opciones de formato.

En el archivo `mkdocs.yml` está la configuración básica de esta documentación, la cual debe ser modificada (especialmente la navegación) para incluir las secciones de la documentación del proyecto y sus resultados.

En la carpeta `img/` pueden colocar imágenes como gráficas y similares.

Pueden agregar la estructura de archivos y carpetas que sea necesaria.

!!! warning "Contenidos de la documentación del proyecto"
    Para la documentación de su proyecto, deben eliminar los textos del enunciado y solamente agregar la explicación propia de su trabajo. Eso incluye esta sección y las de recopilación, procesamiento y otras.
