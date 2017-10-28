# Freelancer 
***

## Html
***

###### Head: Enlace las tipografías de Montserrat y Lato, con sus debidos valores.
###### También enlace el Css de FontAwesome para que aceptara mis iconos en el código de Css, y además a la vez mi Css del trabajo fue enlazado.

###### En el body dividí mi contenido en 3 grandes secciones: nav, main y footer.En general que cada sección estuviera en un div:contenedor,para que la herencia, fuera mejor aceptada, y más ordenado trabajarlo.

###### Dentro de nav: Esta el nombre de la web y una botonera de navegación 
###### con estado de hover(o sobre), que cambia de color al pasar el mouse sobre este.

###### En el main, lo conforme por 4 secciones : Entrada, Portafolio, About y Contact.

###### Contenido de Entrada: Se encuentra un título, el icono de bajada de la estrella y 2 rayitas, que las forme con 2 rectangulos, les di posición y alineamiento. 
###### Luego le di el texto de bajada del ejercicio.


###### Contenido Portafolio: Puse el título de la sección y repeti el codigo de la estrella con los colores del ejemplo, luego en un div agrupe las imagenes para que me fuera más fácil llamarlas desde el Css.

###### Contenido About: Puse el título, repeti el codigo de la estrella, luego en una tabla, les di posición a los parrafos y los distribuí.
###### Después bajo la propiedad buttom, genere el boton Dowload con el icono de descarga, y le di posición.

###### Contenido Contacto: Le di un tiulo, repeti el codigo de la estrella,
###### y bajo la propiedad form, genere mi formulario, luego les di los input que salian en el ejemplo , les di posición y caracteristicas.
###### Hice mi boton de Send con button, y le di propiedades de color y posición.

###### Footer: En una tabla, genere mi footer, donde les di caracteristicas de color, tamaño y posición.En un div puse los iconos, les di un circulo con border radius para que tuvieran esa forma, luego fuera de mi tabla, coloque mi copyright, y le di posición.



## Css
***

###### Nav : Coloque mi tipografía que iba ser utilizada >Montserrat>, le di un background y les di una posición fixed, un <z-index:100> para darle prioridad al menú, al momento que quisiera darle posiciones al contendio. Use un width al 100% para hacerlo al ancho de  toda pantalla.
###### Use la propiedad (a) para generar mi menú de navegación, aplique la propiedad (text-decoration: none; ), para quitarle el subrayado que da (a)

###### Le di una clase, llamada (.header) y luego fui llamando por herencia a los elementos para darle colores, posiciones , declarar la tipografía a ser usada, que fue Montserrat.Con esta clase genere la botonera de mi menu de navegación, y bajo la misma clase, bajo herencia, le di el estado hover a mi botonera.

###### Entrada: Le di un contenedor y lo llame atraves de una clase <contenido1> , le di posición absoluta, un color, use <text-align:center> para que tanto los textos y los contenidos quedaran centrados a mi contenedor.
###### Luego coloque la imagen del contenido de entrada, y luego por herencia de la posición de los elementos, fui llamando a la imagen, le di margen para colocarla en posición, luego por la herencia llame a mi titulo y le di sus propiedades de color, tipografía: tamaño, y peso.Coloque el icono de la estrella y las 2 rayitas, que hice con 2 rectangulos, les di las mismas posiciones y les di un (float left) para alinearlas.
###### Luego a traves de la clase <sub-text> llame mi texto de bajada y le di la tipografia pedida <Lato>, tamaño , peso y padding respecto del contenido anterior.

###### Portafolio: Le di un background, con posicion absoluta, luego por herencia, coloque el titulo, la tipografia de titulos (Montserrat), repeti mi codigo de la estrella y las rayitas.
###### Mediante un div, coloque las imagenes, les di una clase (image) y por herencia, las llame,trabaje con los paddding ,y las alinie con (float: left),por herencia las llame, les di un tamaño (ancho y alto), y un margen, para que no estuvieran tan pegadas entre sí. 	


###### About: Le di un contenedor, posicion absoluta, color, posiciones, luego por herencia le di un titulo, use la tipografía <Montserrat>para los titulos, repeti mi codigo de la estrella, luego le di las propiedades para los parrafos, los introduje en una tabla, donde le di margenes y posiciones, y les di la tipografía <Lato>.

###### Contacto: Mediante un background color y contenedor, introduje mi codigo para seguir una herencia.Les di posiciones, un titulo, posiciones y propiedades , luego repeti mi codigo de la estrella, mediante la propiedad form , genere mi código, y mediante la clase (contact form), les di la tipografia (Lato), margenes, luego por herencia les di valores al (input) , luego mediante la propiedad buttom, genere mi boton (boton-form) y lo modifique, y por heerencia tambien le di un estado hover.

###### Footer: Le di un contenedor, luego mediante una tabla, genere mi contenido, con un h3 se los di a mis titulos, fui generando la herencia y posiciones, donde por herencia a los h3 les di la tipografia (Montserrat) y luego a los otros textos les di (Lato), en un div introduje mis iconos, los llame desde (table i), les di margenes superior, y el tamaño tipografico, luego con el div contenedor los alinie con (display:inline block) y les di un (border-radius) para que quedaran adentro de un círculo. Luego para generar ese cambio de color que llama a un enlace le di un (a), y los llame por herencia de la tabla, y por último escribí el texto del copyright, mediante un (p).	




***

###### Ejercicio realizado por Valentina Herrera para Laboratoria, llamado Freelancer, entregado ```30.10.2017``` , en Santiago de Chile.