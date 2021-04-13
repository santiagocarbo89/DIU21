

## Competitive Analysis


![Multiple Competitor Feature Comparison](https://user-images.githubusercontent.com/75760642/111618823-1dabf000-87e5-11eb-81e6-80aaac9d9d39.jpg)


>>> Nosotros hemos elegido [Lambus](https://www.lambus.com/) frente a las demás aplicaciones ya que tiene ventajas que la mayoría de las otras aplicaciones no tienen. En primer lugar, podemos observar que hay aplicaciones que ni siquiera tienen una página web como es el caso de [TripIt](https://www.tripit.com/web) . También cabe destacar su servicio en Android, ya que Lambus no tiene pagos adicionales en este Sistema Operativo pero hay otras aplicaciones que si que tienen pagos, como es el caso de [TripIt](https://www.tripit.com/web), [RoadTrippers](https://roadtrippers.com/). Tenemos que añadir que cuando nos hemos puesto a realizar las comparativas entre los diferentes servicios, hemos visto otra aplicación que ofrece servicios similares pero tiene ventajas respecto a los pagos adicionales tanto en Android como en iOs. Por eso precisamente hemos elegido [Lambus](https://www.lambus.com/), porque es una buena aplicación que ofrece ventajas con respecto a casi todos los demás servicios pero se queda corto respecto a [WonderLog](https://wanderlog.com/), así será un análisis más realistas sin enfocarnos directamente en el servicio que a priori parece más completo. Hemos añadido un servicio que también ofrece algo similar a los anteriores, pero en este caso no dispone de aplicación en el móvil, por tanto no es equiparable al servicio que puede ofrecer [Lambus](https://www.lambus.com/), o directamente las demás aplicaciones. Como conclusión, hemos observado que [Lambus](https://www.lambus.com/) es una de las aplicaciones líderes pero se queda corta con respecto a [WonderLog](https://wanderlog.com/). 


## Persona



![MathewPetersonPersona](https://user-images.githubusercontent.com/75760642/111619018-58158d00-87e5-11eb-8f71-bbae15ccfc0f.png)
![DianeDouglasPersona](https://user-images.githubusercontent.com/75760642/111619061-65327c00-87e5-11eb-8941-7917ccb4b08f.png)


>>> El objetivo ha sido intentar buscar individuos con objetivos de viajes diferentes, así como biografías diferentes. De esta forma intentamos recoger distintos puntos de vista para ampliar nuestra visibilidad. También tienen metas diferentes, de forma que pueden aportar otros puntos de vista. También, otro objetivo ha sido que las dos personas tengan distintas personalidades, porque cada personalidad aporta algo distinto.
User Journey Map


## User Journey Map
/*******************************************/
/*             JOURNEY.JS                  */
/*     Datos para USER JOURNEY MAP         */   
/*          [DIU] UX Toolkit v1.0 2019     */                        
/*          ver 1.1 26/Feb/2020            */
/*******************************************/
    
/****  README:       */
/****  v.1.1 Incluye nombre de tu grupo de prácticas (Grupo.ID), curso académico y enlace a github ***/
/****  Modifica los datos para los Journey Map (uno para cada Persona)  */
/****  Usa los 6 pasos y sigue las instrucciones */   
/****  Las imagenes para  'Photo', 'feelX', 'imaX' están en carpeta ./photos **/
/****  Si se usan nuevas imágenes se deben añadir a esa carpeta **/
/****  Los valores de rating están entre 1..5 **/
/****  recursos de imágenes:  https://www.vectorstock.com/royalty-free-vectors/vectors-by_zdeneksasek ***/




angular.module("angular", [])
	.controller("controller", ["$scope", function($scope) { 
		$scope.Grupo_ID ="DIU1.ABCDEF";
        $scope.Curso ="2020/21";
        $scope.Github_ID ="https://github.com/mgea/UX-DIU-Toolkit";
        
		$scope.JourneyIndex = 0;
        
        $scope.Journeys = [
			{		
                
                /*************************************/
                /**** PRIMER USER JOURNEY MAP  *******/
                /*** Cambiar datos             *******/
                /*************************************/
                
				Id: 0,
				Name: "Pedro",
                Photo: "man.png",
    
                /*** PASO #1: INSPIRACION ***/ 
                goal1: "quiere preparar un viaje con sus amigos en Semana Santa",
                touch1: "agenda",
                feel1: "4",
                con1: "ver cuantos días puede tener libres para organizar lugar de viaje ",
                ima1: "cartoon-planning.png",
				
                /*** PASO #2: DECICION ***/ 
                goal2: "Busca en internet ofertas para esas fechas",
                touch2: "Movil",
                feel2: "2",
                con2: "hay demasiada información y pierde mucho tiempo, no hay precios 'baratos'",
                ima2: "cartoon-PCangry.png",
                
                /*** PASO #3: ACTUA ***/ 
                
                goal3: "Decide buscar un alojamiento rural  en plasencia, donde hay procesiones y parece que hará buen tiempo",
                touch3: "móvil (el tiempo)",
                feel3: "3",
                con3: "Está preocupado por el tiempo y el desplazamiento (coche y aparcamiento)",
                ima3: "cartoon-phone.png",
                
                /*** PASO #4: OBSERVA ***/ 
                
                goal4: "Los amigos le recomiendan una página para escoger alojamientos",
                touch4: "ordenador",
                feel4: "4",
                con4: "Buscar opciones en el lugar que había seleccionado, viendo precios y distancias, tiene que ver si hay aparcamiento fácil",
                ima4: "cartoon-PCtyping.png",
                
                 /*** PASO #5: ANALIZA ***/ 
                
                goal5: "Se encuentra 3 opciones que encajan en sus preferencias",
                touch5: "móvil (whatsapp)",
                feel5: "2",
                con5: "Llama a sus amigos (whatsapp no responen) para ver cual es su preferencia, tienen que reservar rápido por los precios",
                ima5: "cartoon-phoning.png",
                
                
                /*** PASO #6: CONCLUSION ***/ 
                
                goal6: "Consigue reservar, otro año se encarga otro!",
                touch6: "ordenador",
                feel6: "3",
                con6: "algunos amigos no confirmaron por lo que tuvo que seleccionar reserva con posibilidad de cancelación",
                ima6: "cartoon-resting.png",
                
			},
			{	
                /*************************************/
                /**** SEGUNDO USER JOURNEY MAP *******/
                /***      Cambiar datos        *******/
                /*************************************/
                
				Id: 1,
				Name: "Monica Suarez",
                Photo: "woman.png",
                
				 /*** PASO #1: INSPIRACION ***/ 
                goal1: "Quiere preparar un viaje con su familia para Verano, tiene sólo 15 dias libres",
                touch1: "agenda",
                feel1: "5",
                con1: "Quiere ir a un pais exotico pero que tenga atracciones para niños pequeños",
                ima1: "cartoon-going.png",
                
                /*** PASO #2: DECICION ***/ 
                goal2: "Ir a una agencia de viajes, y decirle sus preferencias y planes",
                touch2: "Servicio (agencia)",
                feel2: "4",
                con2: "Tiene que desplazarse a agencia, explica su intenciones, le llamaran porque no hay nada interesante",
                ima2: "cartoon-teamthinking.png",
                
                /*** PASO #3: ACTUA ***/ 
                
                goal3: "Le llaman a los pocos días con un viaje que no le convence",
                touch3: "Móvil (llamada)",
                feel3: "2",
                con3: "Piensa que ha perdido el tiempo",
                ima3: "cartoon-phoningangry.png",
                
                /*** PASO #4: OBSERVA ***/ 
                
                goal4: "Busca una oferta en hoteles cerca de playa y con parque atracciones",
                touch4: "Móvil (webapp)",
                feel4: "2",
                con4: "No hay mucha información del alojamiento ni de lo que hay alrededor, aunque el precio está bien, va por la calle por lo que está incómoda",
                ima4: "cartoon-phone-street.png",
                
                 /*** PASO #5: ANALIZA ***/ 
                
                goal5: "Reserva a traves de la aplicación ",
                touch5: "Móvil (webapp)",
                feel5: "3",
                con5: "Le pide muchos datos y le resulta incómodo completar formulario",
                ima5: "cartoon-phone-sitting.png",

                
                /*** PASO #6: CONCLUSION ***/ 
                
                goal6: "Consiguie reservar para vacaciones pero no era lo que tenía en mente",
                touch6: "Ordenador (reserva OK)",
                feel6: "2",
                con6: "Tendrá que buscar más información del lugar para ver que actividades ofrece y donde aparacar!",
                ima6: "cartoon-PChard.png",
                
                
                
			}
		];
        
		$scope.model = $scope.Journeys[0];

	}])
![JourneyMapMathewPeterson](https://user-images.githubusercontent.com/75760642/111619276-a591fa00-87e5-11eb-87ce-09ce564eab23.png)
![JourneyMapDianeDouglas](https://user-images.githubusercontent.com/75760642/111619305-af1b6200-87e5-11eb-81bb-1b9655b8d79d.png)



>>> Para realizar ambos Journey Map hemos tenido que ponernos en la piel de cada uno de nuestros personajes ficticios, y especular qué es lo que ellos pensarían a la hora de administrar un viaje mediante la empatía. Creemos que ha resultado interesante que pongamos una frase sobre qué piensan en cada una de las etapas, ya que representa muy bien lo que significa. También hemos intentado cambiar el punto de contacto poniéndonos en la piel del usuario, preguntándonos que resultaría más práctico para ellos.

## Usability Review															
![image](https://user-images.githubusercontent.com/62752334/114542240-fb788700-9c57-11eb-9d99-325ab12474d1.png)



----
>>>  Revisión de usabilidad: 
>>> - Enlace al [documento](https://github.com/santiagocarbo89/DIU21/blob/master/P1/UsabilityLambus.xls)
>>> - Valoración final (numérica): 76
>>> - Comentario sobre la valoración:
>>> A grandes rasgos, inicialmente podemos decir que la propia plataforma Lambus se preocupa por la usabilidad del mismo. Sin embargo, analizando su competencia, podría potenciar algunos puntos fuertes para poder diferenciarse, aunque existen algunos competidores fuertes en el mercado como son Wonderlog. Aparte, la plataforma ofrece una cierta calidad en materia de navegabilidad, solución de errores y feedback, contenido, ayuda… Su test de usabilidad tiene una puntuación razonablemente buena (76/100), de forma que se puede decir que ofrece un servicio de calidad.
También, a la hora de crear personajes ficticios, hemos tenido que actuar como ellos, y hemos podido ver de primera mano como es de usable la plataforma.

