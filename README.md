# DIU21
Prácticas Diseño Interfaces de Usuario 2020-21 (Tema: Planificación y Organización de Viajes) 

Grupo: DIU1_Salsoteca  Curso: 2020/21 
Updated: 8/11/2021

Proyecto: 
Navis, aplicación para realizar itinerarios y planificar viajes

Descripción: 
Nuestra idea es realizar una aplicación que permitar realizar itinerarios de viajes personalizados, permitiendo a los usuarios guardar documentos, imágenes y videos relacionadas con el mismo, así como estimar un saldo común para su viaje. Para nuestro proyecto sería también interesante asociarse con servicios tales como Airbnb o Uber para facilitar el alojamiento y el transporte durante el viaje.

Logotipo: 
Opcionalmente si diseña un logotipo para su producto en la práctica 3 pongalo aqui

Miembros
 * :bust_in_silhouette:  [Santiago Carbó García](https://github.com/santiagocarbo89/)     :octocat:     
 * :bust_in_silhouette:  [Ignacio Joaquín García Moreno](https://github.com/ignaciogmoreno/)     :octocat:

----- 




# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis


De entre diversas aplicaciones como [TripIt](https://www.tripit.com/web), [RoadTrippers](https://roadtrippers.com/) o [WonderLog](https://wanderlog.com/), nos hemos quedado con [Lambus](https://www.lambus.com/) ya que es una aplicación muy completa pero pensabamos que escoger la mejor, en este caso wonderlog, no habría mucho con lo que comparar.
> [Información completa](https://github.com/santiagocarbo89/DIU21/blob/master/P1/README.md#competitive-analysis)


![Método UX](img/Persona.png) 1.b Persona



![MathewPetersonPersona](https://user-images.githubusercontent.com/75760642/111619018-58158d00-87e5-11eb-8f71-bbae15ccfc0f.png)
![DianeDouglasPersona](https://user-images.githubusercontent.com/75760642/111619061-65327c00-87e5-11eb-8941-7917ccb4b08f.png)


 Hemos seleccionado estas dos personas con unos buenos intereses en viajar pero con vidas realistas.
>  [Información completa](https://github.com/santiagocarbo89/DIU21/blob/master/P1/README.md#persona)

![Método UX](img/JourneyMap.png) 1.c User Journey Map

![Mathew Petterson](https://user-images.githubusercontent.com/62752334/114553939-78aaf880-9c66-11eb-8bf2-43830797aad5.png)
![Diane Douglas](https://user-images.githubusercontent.com/62752334/114603361-eb809780-9c97-11eb-9524-dff00e1e074c.png)



 En estos journey map, hemos puesto casos reales que les podrían pasar a los usuarios

![Método UX](img/usabilityReview.png) 1.d Usability Review
----
Revisión de usabilidad: (toma los siguientes documentos de referencia y verifica puntos de verificación de  usabilidad)
 - Enlace al [documento](https://github.com/santiagocarbo89/DIU21/blob/master/P1/UsabilityLambus.xls) 
 - Valoración final (numérica) de la aplicación [Lambus](https://www.lambus.com/): 76
 - Comentario sobre la valoración:
La aplicación es de las mejores que se oferta en el mercado, pero a veces puede fallar en algunos aspectos respecto a otras aplicaciones. Es una de las aplicaciones líderes aunque tenga defectos como pagos en algunos sistemas o modos de uso complicados. 
> [Información completa](https://github.com/santiagocarbo89/DIU21/blob/master/P1/README.md#usability-review)



## Paso 2. UX Design  


### IDEACIÓN 

* A continuación, aparece representada la **Malla Receptora de Información** (*Feedback Capture Grid*). Nos hemos puesto en la piel de nuestros dos personajes ficticios (Matthew y Diane) para desarrollarla, después de analizar los pros y contras, así como los preguntas, de la aplicación. También hemos añadido una serie de ideas innovadoras.

![feedback2](https://user-images.githubusercontent.com/75760642/115245717-87415600-a125-11eb-9033-eb2332d98eeb.PNG)


* En este caso, también en la piel de Matthew y Diane, hemos desarrollado el **Mapa de Empatía** (*Empathy Map*). Éste, a su vez, podría decirse que se divide en dos partes: los cuatro cuadrantes principales (*Think and feel*, *Hear*, *Say and do* y *See*) y una segunda parte formada por los pros y contras de la idea.

![empathy_map2](https://user-images.githubusercontent.com/75760642/115261024-929b7e00-a133-11eb-84e2-864e955646f1.PNG)


* Para finalizar el apartado de ideación, presentamos un apartado que se denomina **POV** (*Point of View*). Aquí analizamos una situación, en este caso desde la piel de Diane Douglas, e intentamos comprender qué es realmente lo que quiere el usuario.

![pov1](https://user-images.githubusercontent.com/75760642/115119303-f729d200-9fa7-11eb-9eb7-647225149615.jpg)

### PROPUESTA DE VALOR

* A modo de **propuesta de valor**, definimos nuestro proyecto como una aplicación que ayuda a realizar un **itinerario**, así como una **planificación**, de un determinado viaje. Una vez realizado el itinerario y adjuntado todos los documentos e imágenes relacionados con éste, se podrá hacer uso de aplicaciones tales como Airbnb o Uber para que el viaje sea más cómodo. También hemos pensado en otras ideas para implementar en la aplicación, como son desarrollar una **funcionalidad offline** para poder acceder a los archivos sin necesidad de esta conectado a la red. Otra funcionalidad sería poder **administrar los itinerarios en función de una categoría**, para que el usuario pueda personalizarlo. Y, como última funcionalidad, hemos pensado en que el usuario pueda realizar **itinerarios para múltiples destinos**.

* A continuación presentamos el **ScopeCanvas**, donde definimos nuestros propósitos y objetivos a la hora de desarrollar nuestro proyecto. También identificamos las necesidades y acciones de nuestros usuarios, así como las métricas para definir nuestro éxito.

![ScopeCanvas](https://user-images.githubusercontent.com/75760642/115152910-851ebf00-a073-11eb-80a6-32b22511ba6c.PNG)


### TASK ANALYSIS

A continuación, presentamos la **User Task Matrix**:
Resaltado en Gris encontramos el público hacia el que más dirigida está la aplicación así como las tareas más importantes.
En la matriz de usuarios/taresas, podemos distinguir entre 6 conjuntos de perfiles:
- ##### Jóvenes: Se encuentran las personas más jóvenes, dirigido a personas como estudiantes o personas que no son mayores de edad.
- ##### Adultos: Se encuentran personas de mediana edad que viajan solas.
- ##### Familias: Conjunto de personas de la misma unidad familiar, dirigido a un matrimonio con hijos.
- ##### Parejas: Dirigido a personas que mantienen una relación sentimental.
- ##### Jubilados: Se encuentran las personas mayores que ya no trabajan.
- ##### Amigos: Grupo de unas cuantas personas que mantienen una relación de amistad.

Una User/Task Matrix, es una matriz en la que colocamos a los usuarios con las tareas que realiza la aplicación y vemos la importancia o el uso que los usuarios podrían darle a estas tareas.

![User/Task Matrix](https://user-images.githubusercontent.com/62752334/115283141-48be9200-a14b-11eb-8747-1bca4f0527fb.png)







### ARQUITECTURA DE INFORMACIÓN

* En primer lugar desarrollar el **Sitemap**: 

![sitemap](https://user-images.githubusercontent.com/62752334/115236261-6ffd6b00-a11b-11eb-8c38-3ff98c945cac.png)


* Y en segundo lugar desarrollamos el **Labelling**: 

![labelling](https://user-images.githubusercontent.com/62752334/115236864-2cefc780-a11c-11eb-9042-5c7f8d8558a8.png)



### PROTOTIPO LO-FI WIREFRAME

* Finalmente, presentamos una serie de "bocetos" que representan las interfaces más importantes de la aplicación. Hemos representado las partes más importantes: **crear cuenta**, donde se crea una nueva en nuestra aplicación, **planificar viaje (sin itinerario)**, donde se va directo a elegir el destino, sin guardar itinerario, y **planificar viaje con itinerario**, donde desarrollamos todos los pasos para que el usuario desarrolle su itinerario.


![bocetos_lofi2](https://user-images.githubusercontent.com/75760642/115285137-cedbd800-a14d-11eb-9816-56760a409a88.png)


### CONCLUSIONES DE ESTA PARTE

Durante esta parte del proyecto hemos aprendido muchas herramientas para sintetizar información acerca de nuestro proyecto. Particularmente, el prototipo Lo-Fi ha servido para que le "pongamos cara" a la aplicación que queremos desarrollar y hacer una primera aproximación de nuestra interfaz. También nos ha llamado particularmente la atención el "*Empathy Map*", puediendo, valga la redundancia, empatizar con los usuarios que van a utilizar la app. En definitiva, ha servido para sintetizar mucha información necesaria para el proyecto.



## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----

![image](https://user-images.githubusercontent.com/62752334/119808023-ff98f500-bee3-11eb-8995-c48877cfbb76.png)

![Método UX](img/landing-page.png)  3.b Landing Page

![image](https://user-images.githubusercontent.com/62752334/119808065-0b84b700-bee4-11eb-9ff2-7d40d28416e7.png)


![Método UX](img/guidelines.png) 3.c Guidelines
----

* Breadcrumbs:


![image](https://user-images.githubusercontent.com/62752334/119808122-1dfef080-bee4-11eb-9cec-e05a6a66d46b.png)

* Account registration:


![image](https://user-images.githubusercontent.com/62752334/119808188-2c4d0c80-bee4-11eb-9d3e-b83fd4ac6aa1.png)

* Scroll:


![image](https://user-images.githubusercontent.com/62752334/119808251-3b33bf00-bee4-11eb-9aa0-73629a4e605b.png)

* FAQ:
![image](https://user-images.githubusercontent.com/62752334/119808296-4555bd80-bee4-11eb-8b62-99bc21ece31a.png)




![Método UX](img/mockup.png)  3.d Mockup
![image](https://user-images.githubusercontent.com/62752334/119808336-50a8e900-bee4-11eb-969e-a8914b7e25b2.png)
![image](https://user-images.githubusercontent.com/62752334/119808358-56063380-bee4-11eb-9ab7-4c0e7c70b7d4.png)
![image](https://user-images.githubusercontent.com/62752334/119808385-5bfc1480-bee4-11eb-946b-ea6b128866a1.png)

![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----
Enlace al [vídeo](https://youtu.be/L9DWngRv_P8)

## Paso 4. Evaluación 


## Caso 1 - Navis, [DIU1.Salsoteca](https://github.com/santiagocarbo89/DIU21)

Navis es una aplicación diseñada para planear un viaje, es decir, los vuelos, los hoteles u hostales, y el transporte en el destino, así como la opción de realizar un itinerario y agregar imágenes, vídeos, audios, en definitiva, experiencias.    

![landing_page](https://user-images.githubusercontent.com/75760642/120108140-28c7b880-c164-11eb-9849-60fb3a112ef2.png)

## Caso 2 - VisitaGranada, [DIU2.Marmotas](https://github.com/Mapachana/DIU21)

VisitaGranada es una aplicación cuyo objetivo es planificar viajes a Granada, además de ofrecer información acerca de diversas actividades y eventos dentro de la ciudad.

<img src="https://user-images.githubusercontent.com/75760642/120108875-53ffd700-c167-11eb-8ead-a7b955d8688d.png" width="400">
  

## User Testing

Para elaborar el test de usabilidad, han participado los siguientes usuarios:

* **Usuario 1**: Profesora de universidad de la facultad de Odontología, 48 años. Utiliza Internet bastante a menudo, de forma que tiene algo de experiencia.
* **Usuario 2**: Chica estudiante de audiología, 19 años. Utiliza Internet a diario, tiene bastante experiencia.
* **Usuario 3**: Mujer jubilada, 82 años. Usa Internet desde hace solo unos pocos años, y no se desentiende muy bien. No tiene mucha experiencia.
* **Usuario 4**: Hombre de 60 años, ingeniero aeronáutico. Utiliza Internet muy a menudo en el trabajo, tiene experiencia pero hay aspectos que le son difíciles.
* **Usuario 5 (Ficticio)**: Chico estudiante de derecho, 19 años. Utiliza Internet todos los días tanto para trabajo como para ocio, tiene bastante experiencia.
* **Usuario 6**: Chica estudiante de psicología, 21 años. Usa el Internet para trabajo y de manera personal, pero no tiene mucha experiencia.
* **Usuario 7 (Ficticio)**: Hombre jubilado, 84 años. Lleva usando Internet unos cuantos años y sabe prácticamente de todo, tiene mucha experiencia.
* **Usuario 8 (Ficticio)**: Hombre farmacéutico, 32 años. Utiliza Internet principalmente en el trabajo, aunque no se desenvuelve bien, no tiene mucha experiencia.

<img src="https://user-images.githubusercontent.com/62752334/120110600-692c3400-c16e-11eb-99e5-d2d3e816b338.png" width="750">

*Experiencia 1 (Navis) : Para hacer una prueba de la aplicación, se ha intentado crear un viaje, para ello se ha accedido a la [página de la aplicación](https://github.com/santiagocarbo89/DIU21) y se han visto los diferentes pasos que llevar a cabo.* 

*Experiencia 2 (VisitaGranada) : Para hacer una prueba de la aplicación, se ha intentado crear un viaje, para ello se ha accedido a la [página de la aplicación](https://github.com/Mapachana/DIU21) y se han visto los diferentes pasos que llevar a cabo.*
	
[**SUS Score Navis**](https://github.com/santiagocarbo89/DIU21/files/6569721/Navis.ods)

<img src="https://user-images.githubusercontent.com/62752334/120181726-bf9c7f80-c20d-11eb-8ced-68391d7a950a.png" width="750">


[**SUS Score VisitaGranada**](https://github.com/santiagocarbo89/DIU21/files/6569724/VisitaGranada.ods)


<img src="https://user-images.githubusercontent.com/62752334/120111575-b8746380-c172-11eb-88a7-74a8081ba577.png" width="750">


## Conclusiones


[Informe de Usabilidad de Navis: ](https://github.com/santiagocarbo89/DIU21/files/6569783/DIU_report-template-usability-testOK-Navis.pdf)


A modo de conclusión, nos damos cuenta de que tenemos cuatro usuarios cuyas valoraciones se encuentran por encima de 80.3 (Puntuación A). Por otro lado, tenemos tres usuarios por encima de 68 (Puntuación B, ya que se encuentran bastante por encima). Finalmente, tenemos un usuario que tiene una puntuación por debajo de 51 (Puntuación F). Pese a la amplia variedad de notas, el promedio sería 75,62, es decir, una puntuación B (Notable).

Aunque a la amplia mayoría de los usuarios les ha gustado la aplicación, este resultado denota que al público general le gusta, sin embargo, existe un bajo porcentaje a quien no le gusta nada. O te encanta o no te gusta nada. También es importante puntuar que la puntuación negativa la ha valorado una persona mayor que no se desenvuelve mucho con Internet, de forma que, en cierto modo, es normal.


[Informe de Usabilidad de VisitaGranada: ](https://github.com/santiagocarbo89/DIU21/files/6571344/DIU_report-template-usability-testOK-VisitaGranada.pdf)


A modo de conclusión, nos damos cuenta de que tenemos tres usuarios cuyas valoraciones se encuentran por encima de 80.3 (Puntuación A). Por otro lado, tenemos cuatro usuarios por encima de 68 (Puntuación B, ya que se encuentran bastante por encima). Finalmente, tenemos un usuario que tiene una puntuación por debajo de 51 (Puntuación F). Pese a la amplia variedad de notas, el promedio sería 72.81 , es decir, una puntuación B (Notable).

Los resultados resaltan que la aplicación en general gusta bastante a la mayoría de los usuarios a los que se ha preguntado. Cabe destacar que el usuario que ha obtenido una puntuación baja la ha obtenido porque es una persona mayor que no tiene ninguna experiencia relativa al mundo de la informática. Como conclusión final podemos decir que la amplia mayoría de los usuarios querrán utilizar esta página y que les será, en general, bastante fácil de usar.

### *A/B TESTING*
El promedio de Navis (75.62) es ligeramente superior al promedio de VisitaGranada (72.81). Además, ambos han tenido, más o menos, el mismo desenlace: casi todos los usuarios le han dado valoraciones muy buenas, salvo un usuario que ha dado puntuación negativa. Con estos datos presentes podemos finalizar diciendo que Navis ha cumplido las expectativas de su público. A modo de mejora, Navis podría perfeccionar su introducción a usuarios con una muy baja utilización de Internet.




## Conclusión final / Valoración de las prácticas

Para concluir, nos gustaría valorar los resultados que hemos obtenido tras la realización del proyecto Navis. Creemos que se han seguido los pasos correctamente, de forma que todo el proceso se ha desarrollado "construyendo la casa de arriba a abajo". Los resultados del proyecto han resultado ser bastante positivos, aunque siempre creemos que podemos pulir y añadir funcionalidades a nuestro proyecto. 

Finalmente comentar que la puntuación obtenida mediante el 'A/B Testing' ha resultado ser 'B', de forma que podemos concluir que ha resultado satisfactoria.













