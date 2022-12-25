---
title: Data Base Creation Project
summary: This project consists on the developement of a RDBMS Data Base which purpose is the management of Hospitals
tags:
- SQL
- Data Base

date: "2022-12-22T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo extracted of Microsoft Access
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  link: https://github.com/MiguelAlvRed
url_code: "https://github.com/MiguelAlvRed/Northwind_SQL_EDA.git"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
**Especificaciones del Proyecto**


Para el diseño y la creación de la base de datos existen las siguientes restricciones:

* Cada hospital está compuesto por salas de especialidades.

* La plantilla del hospital compuesta por enfermeros / enfermeras y personal interno (no doctores) en turnos de mañana (M), tarde (T) y noche (N).

* Cada hospital tiene un número máximo de camas y en cada sala existe un número de camas asociado.

* Cada doctor depende de un hospital, no pudiéndose dar el caso de que un doctor pertenezca a varios
    hospitales.

* El atributo salario de la plantilla guarda información del salario anual bruto.

* Un enfermo tiene asignada una sala y una cama de dicha sala. 


**Objetivos**


Los objetivos mediante vamos a calificar si el proyecto ha resultado un éxito son los siguientes:

* Diseño de un diagrama Entidad - Relación que cumpla las necesidades expuestas en el enunciado.

* Implementar el modelo en MySQL.

* Estructurar la base de datos según una metodología sostenible:

    * Evitar la duplicidad de los datos.
    
    * Velar por la normalización de la base de datos.
    
* Desarrollar un modelo escalable, que a pesar de la adición de registros en cualquiera de sus tablas, se mantenga plenamente funcional


**Sentencias SQL**


* Encuentra todos los miembros del personal cuyo nombre comience por ‘H’.

* ¿Quiénes son las enfermeras y enfermeros que trabajan en turnos de tarde o mañana?

* Hacer un listado del personal de enfermería cuyo salario está comprendido entre 25.000 y 35.000 € al año.

* Mostrar, para todos los hospitales, el código de hospital, el nombre completo del hospital y su nombre abreviado de tres letras. Ordenar el resultado por esta abreviatura.

* Encontrar a todas las enfermeras y enfermeros con indicación del salario mensual de cada uno.

* Recuperar el número de empleado y nombre de las personas que perciban un salario > que la media de su hospital.

* Insertar en la tabla PLANTILLA a “Pedro Elguapo” con un salario anual de 30.000 €, número de empleado 1234. Trabaja en el hospital 22, sala 2.

* Actualizar al paciente número 74835 la dirección a la calle Alcalá, 411.

* Poner todas las direcciones de la tabla ENFERMO a NULL.

* Igualar la dirección y fecha de nacimiento del paciente 10995 a los valores de las columnas correspondientes almacenadas para el paciente 14024.

* En todos los hospitales del país se ha recibido un aumento del presupuesto, por lo que se incrementará el número de camas disponibles en un 10%.) ¿Cómo se haría en SQL? Analizar si es necesario cambiar la estructura de la tabla de HOSPITAL, y en ese caso crear una copia de seguridad de esta, además de hacer el correspondiente ajuste en el número de camas.

* Se va a realizar un programa de consulta de la información sobre enfermos. Los datos por mostrar serán sus apellidos, dirección, fecha de nacimiento y hospital en el que se encuentran. ¿Qué vista se definirá? ¿Es posible modificar datos a través de la vista anterior? 

* Obtener un listado que incluya el nombre de cada hospital, las salas, los empleados que trabajan en cada sala, agrupados por categorías profesionales y salarios.

* Obtener el grado de ocupación de cada hospital, es decir, el número de enfermos que hay en cada uno de los hospitales, analizar la ocupación actual por salas y obtener la diferencia entre la ocupación actual y la ocupación máxima por sala.

* Seleccionar todos los doctores por cada hospital, en el informe deberá aparecer el nombre del hospital y la correspondiente lista de doctores asociados.


**Conclusiones**


Durante el proyecto, he realizado tareas como el diseño de la estructura de la base de datos, la importación de datos y la creación de consultas. El resultado final es una base de datos funcional y escalable.

Además, el proyecto me ha permitido mejorar mis habilidades en SQL y aprender nuevas funciones y conceptos.

En general, ha sido una experiencia muy enriquecedora y estoy seguro de que la base de datos será muy útil para mis necesidades.

If you want to check the JupyterNotebook where I develop this project you will find it at the Code button at the top of the page.
