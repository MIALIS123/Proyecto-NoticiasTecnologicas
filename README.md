# Proyecto-NoticiasTecnológicas

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
