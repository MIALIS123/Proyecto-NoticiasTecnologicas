# Proyecto-NoticiasTecnológicas
   Todo lo que hice en Css.
    1-Para la clase contenedor(nav) le coloque esta medida para que toda la información y propiedades quepan y fui probando pixeles.

.contenedor {
 width: 1400px;
    
}


    2-Para est aparte del nav le quite el estilo predeterminado para que no aparezca y row por ser horizontal el diseño y luego gap para el espacio y de ultimo centrar

.navegacion-principal__menu {
    list-style: none;
    display: flex;
    flex-direction: row;
    gap: 20px;
    justify-content:center;
    align-content: center;
}

.navegacion-principal__menu-derecha {
    list-style: none;
    display: flex;
    flex-direction: row-reverse;
}

   3-Cambiar el color predeterminado a blanco
a{
    color: white;
}

   4- En el header coloque la imagen desde css y utilice grid lo deje en una sola fracción, centre el texto con text-align y para el botón lo posicioné con static y le di su relleno para el tamaño, luego le añadí hover para darle una transición al botón a un color azul.


/* CABECERA*/

.cabecera {
    background-image: url(/Assets/showcase.jpg);
    background-size: cover;
}

.cabecera {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    text-align: center;
}
.boton {
    position:static;
    background-color: rgb(21, 26, 30);
    color: #ffffff;
    margin: 50px auto;
    padding: 0.6em;
    border: 1px solid white ;
    
}
.boton:hover {
    background-color: rgb(4, 37, 52);
    transition: 0.5s;
    -webkit-transition: 0.5s;
    -moz-transition: 0.5s;
    -ms-transition: 0.5s;
    -o-transition: 0.5s;
}   

    5-Para esta parte coloque img en el index y luego probe medidas para las imágenes y utilice flex por ser en linea y ahi mismo centre el texto con text-align.

 /* TARJETA DE NOTICIAS */

 .tarjetas-noticias {
    display: flex;
    flex-direction: row;
    gap: 20px;
    text-align: center;
}



img {
   width: 337px;
   height: 270px ;
   position: relative;

}


/* Segunda Parte del proyecto */


/* <!-- TARJETAS DE NOTICIAS --> */

1.Utilice tarjetas_noticias2 y le agregue el 2 a la clase para no justar el mismo código de las primeras tarjetas de noticias.
2.Utilice flex y row por ir en fila el contenido.
3.Le agregue la clase img2 a las imágenes para que no tengan las mismas medidas de las imágenes anteriores.

/* <!-- Banner de Tarjetas 2--> */

1.Agregue la imagen en css y le agregue margin para el espacio de arriba y utilice grid y luego alinee con sus respectivas propiedades.

<!-- /* sección Social */ -->

1.Especifique la p en la clase social para que solo moviera con flex el texto.
2.Luego utilice la clase de los iconos y utilice flex , les di tamaño y centre los iconos.


/* <!-- Enlaces de Pie de Página --> */

1.Le puse margin para el espacio de arriba y background-color por su fondo.

2.En los enlaces utilice wrap para que los esparciera 2 en 2 y luego space-around para el espacio entre ellos.

/* <!-- Pie de Página --> */

1.Agregue su color respectivo.
2.Utilice grid y luego lo fraccione en 1.
3.Luego centre con sus respectivas propiedades.