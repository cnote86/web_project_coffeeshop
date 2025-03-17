# Triple Espresso
Nombre del Proyecto:Página de Triple Espresso

Descripción Breve del Proyecto: Pagina Web de la cafetería Triple Expresso, de la biblioteca TripleTen.

Tecnología y técnicas utilizadas:
-Lenguaje de programación: HTM y CSS (hojas de estilo)
-Metodología: BEM

Descripción detallada de la página:

-La página de Triple Esspreso consta de los siguientes bloques principales:

 °HEAD°

   * Configuración de Idioma: Español.
   * La página se adapta al ancho de la pantalla 
     del dispositivo por medio de la etiqueta 
     viewport.
   * Se agrega descripción detallada de la 
    página por medio de las etiquetas meta con tipo de contenido: description, keywords y author para ayudar a 
    los motores de busqueda a detrminar el contenido.
   * Pestaña de página personalizada con el nombre de la página e icono
   * La página cuenta con fuentes de terceros (google fonts), enlazadas por medio de la etiqueta link, además se agregaron fuentes de respaldo para cada fuente en caso de que la página no pudiera acceder a la fuente del tercero.

BODY:
La página fue diseñada como un infinite scroll, poniendo una sección debajo de otra  por medio del atributo display flex de ccs a cada parte de la página (encabezado, contenido principal y pie de página).

   ENCABEZADO:
   * El encabezado realiza la función de dar la 
    bienvenida al usuario, proporcionar la información 
    general de la cafetería como horarios de apertura y 
    dirección, como pieza principal del encabezado 
     tenemos una moderna ilustración que ejemplifica el 
      interior de la cafetería.

    * Ilustración posicionada con  el atributo position, el resto de los elementos fueron posicionados con el atributo display: flex

   * Logo de la cafeteria Triple Esspreso como primer elemento de la página, el logo fue insertado por medio de la etiqueta img y al igual que en el resto de imagenes de la página incluye una descripción de la imagen introducida por medio del atributo alt para mejorar la experiencia de navegación de personas que requieren el apoyo de lectores de voz de páginas web.

* El encabezado cuenta con un menú de navegación, con 3 links que llevan a cada una de las secciones de la página web (recetas, reserva una mesa y contactos) por medio del atributo id en html en cada una de las etiquetas link, fueron  agrupados en fila en la esquina superior derecha por medio del atributo en css display flex, cada link cuenta con efecto hover que cambia el color de la fuente cuando el el link es activado para mejorar la interactividad con el usuario.

SECCIÓN RECETAS:

* La sección recetas está dedicada a bridar a la comunidad material externo relacionado con la preparación del café, lo que alienta a los visitantes a profundizar en el tema.
* Todos los elementos de la sección fueron posicionados por medio de bloques div, agregando atributos a la hoja de estilos css, se agregaron 2 videos relacionados con preparación de café utilizando la etiqueta iframe, todos los atributos de estilo como ptamaño y posicionamiento fueron determinados en la hoja de estilo correspondiente respetando la metodología BEM.

SECCIÓN DE RESERVAS:

* Esta sección consta de un formulario para recolectar la información de solicitudes de reserva de los visitantes, el formulario fue insertado utilizando etiquetas input y label relacionadas entre ellas por un atributo for, todas las inputs a continuación fueron configuradas como obligatorias por medio del atributo required de la etiqueta input, se utilizaron inputs de tipo:

       -Text: para la entrada del nombre del comensal.
       -Number: para la entrada de número de comensales, se han configurado un mínimo de un conmensal y un maximo de 8 por medio de los atributos min y max.
       -Datetime-local: entrada para seleccionar fecha y hora de la reserva.
       -Email: entrada para introducir el email de contacto del comensal, esta entrada detecta automaticamente si la información introducida no cumple con el formato de un correo electrónico válido.
       -Checkbox: Esta entrada permite al comensal aceptar los términos de uso de la información introducida

* Contiene una etiqueta tipo botón que con un efecto hover que baja la opacidad del botón al ser activado.

FOOTER:

*Contiene nuevamente el logo de la cafetería junto con dos links que redirigen al usuario a las redes sociales de la cafetería, incertados mediante la etiqueta link  así como la información de copyright del autor, todos los elementos fueron posicionados por medio de bloques div y el atributo display flex, a excepción del detalle en la esquina superior izquierda, un circulo azul realizado con un elemento de bloque div con los bordes redondeados al 100% y color de fondo de color azul #2F80ED declarado desde el correspondiente archivo css. 

PLANES DE MEJORA DEL PROYECTO: 

-fijar el menú de navegación a la parte superior de la página, hará más comoda la navegación.

-Agregar un icono de home al menú nav de tal manera que peudas volver al encabezado de la página facilmente si estás al final de la misma.

-Bloquea fecha/hora anteriores a la fecha/hora actual para evitar errores en las reservas.

-Cambio estético: quitar el borde oscuro de las input en form.

-Al terminar el formulario la página debería devolverte al link del formulario y no al menú nav, es más cómodo para los usuarios.

-En la sección recetas dedicaría un párrafo a animar a los visitantes a dejarnos sus opiniones en redes sociales sobre el contenido de los videos o saber si les gustaría ver contenido de algún tema en especifico relacionado con el café, para hacer un poco más dinamica la interacción con los visitantes.

-El texto asociado a la casilla de aceptación de términos de uso debería ser un enlace ya que debería poderte llevar a un documento con los términos y condiciones.
