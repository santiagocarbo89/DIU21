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

* A continuación, presentamos la **User Task Matrix**:
Resaltado en Gris encontramos el público hacia el que más dirigida está la aplicación así como las tareas más importantes.
En la matriz de usuarios/taresas, podemos distinguir entre 6 conjuntos de perfiles:
> ##### Jóvenes: Se encuentran las personas más jóvenes, dirigido a personas como estudiantes o personas que no son mayores de edad.
> ##### Adultos: Se encuentran personas de mediana edad que viajan solas.
> ##### Familias: Conjunto de personas de la misma unidad familiar, dirigido a un matrimonio con hijos.
> ##### Parejas: Dirigido a personas que mantienen una relación sentimental.
> ##### Jubilados: Se encuentran las personas mayores que ya no trabajan.
> ##### Amigos: Grupo de unas cuantas personas que mantienen una relación de amistad.

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


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Si diseña un logotipo, explique la herramienta utilizada y la resolución empleada. ¿Puede usar esta imagen como cabecera de Twitter, por ejemplo, o necesita otra?


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto en forma de video de 90 segundos aprox


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 


## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report 
----

>>> Indica qué pretendes evaluar (de accesibilidad) sobre qué APP y qué resultados has obtenido 

>>> 5.a) Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 
>>> 5.b) Uso de simuladores de accesibilidad 

>>> (uso de tabla de datos, indicar herramientas usadas) 

>>> 5.c Breve resumen del estudio de accesibilidad (de práctica 1) y puntos fuertes y de mejora de los criterios de accesibilidad de tu diseño propuesto en Práctica 4.



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













