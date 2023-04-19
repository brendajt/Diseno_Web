
## ESTRUCTURA DEL HTML 
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Crimson+Text&display=swap" rel="stylesheet">
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <link rel="stylesheet" href="css/estilos.css">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
        <title>Brenda Juárez 🤞✌💕</title>

    </head>
    <body>
        <header id="inicio">
            <nav>
                <div class="logo"> 
                    <img src="img/logo.jpg" alt="logo">
                    <p> 💕BRENDA N. JUÁREZ TORRES💕</p>
                </div>
                <input type="checkbox" id="Menú"> <label for="Menú"><img class="hambur" src="img/menu.png" alt=""></label>
                <ul>
                    <li><a href="#inicio">INICIO</a></li>
                    <li><a href="#acerca_de">ACERCA_DE</a></li>
                    <li class="porta"><a href="">PORTAFOLIO</a> <ul class="menudes">
                        <li>Diseño</li>
                        <li>Base</li>
                        <li>Programación</li>
                    </ul> </li>
                    <li><a href="">CONTACTO</a></li>
                </ul>
            </nav>

            <div class="caja">
                <div class="cajitares">
                    <h1>BRENDA <span>JUÁREZ</span> TORRES</h1>
                    <p>Mi recorrido en la escuela de código de PILARES</p>
                    <a href="">ACERCA DE MI</a>
                </div>
                <div class="cajita">
                    <img src="img/perso-removebg-preview.png" alt="Foto">
                </div>
            </div>


        </header>

        <main>
            <section class="acerca" id="acerca_de">
                <h2>ACERCA DE</h2>

                <div class="acerca1">
                    <div class="acerca2">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui cupiditate earum, vel provident itaque maiores? Perspiciatis eveniet accusamus, ut consequuntur, ipsam dolores fugiat ullam iusto obcaecati maxime corporis asperiores, quidem vel voluptate deserunt? Maiores soluta adipisci id animi a veritatis vero quam ipsum? Voluptatibus ea quidem illum officia earum ex voluptatem provident voluptas sequi aliquid hic, fugiat ullam. Repellat quam amet rerum tenetur necessitatibus! Dolores quos vitae corporis illo reiciendis porro eos nostrum minus tempora placeat, at dolorum eius repellendus aliquid vero pariatur repudiandae adipisci inventore doloribus quo quaerat deserunt nisi. Voluptas fugit fugiat dicta aliquam, quos at totam itaque.</p>
                    </div>
                </div>



            </section>

            <div class="paralax">
                <p>“Sueña como si fueras a vivir para siempre, vive como si fueras a morir hoy.” </p>
            </div>

            <section class="portafolio">
                <h2>PORTAFOLIO</h2>
                <div class="portafolio1">
                    <div class="portafolio2">
                       <img src="img/CSS3_and_HTML5_logos_and_wordmarks.svg-removebg-preview (1).png" alt=""> 
                       <img src="img/Python-logo-notext.svg-removebg-preview.png" alt="">
                       <img src="img/Sql_data_base_with_logo-removebg-preview.png" alt="">
                    </div>
                </div>
            </section>

            <section class="contacto">
                <h2>Contacto</h2>
                <div class="contacto1">
                    <div class="contacto2">
                        <form action="" netlify>
                            Nombre:<input type="text" name="Nombre"class="input" placeholder="Nombre Apellido" required>
                            Telefono:<input type="tel" name="Telefono" class="input" minlength="10" maxlength="10">
                            Correo: <input type="email" name="Correo" class="input"> <br>
                            <p> Comentarios:</p><textarea name="Comentarios" id="" cols="70" rows="10" class="input"></textarea>
                            <input type="checkbox" value="Acepto" required> 

                            <p class="aviso"> Acepto aviso de Privacidad <span class="aviso1"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, nemo excepturi magni alias dolore velit accusamus expedita natus ratione eaque autem porro obcaecati eveniet magnam sequi commodi. Eius nemo, accusamus sunt asperiores omnis labore totam veniam ipsam. Excepturi quod consectetur nesciunt, dolor dolorum suscipit laborum magnam sunt facilis dolorem perferendis asperiores tempore nobis vel architecto eum eius commodi quasi, accusamus ipsam est tenetur libero maiores. Excepturi voluptate libero nam sapiente doloremque, et recusandae iure deleniti officiis ex ipsa accusantium, necessitatibus labore. Sunt illo, accusantium voluptatibus hic consectetur fugiat porro, nihil exercitationem, laborum aut repudiandae cumque. Voluptas suscipit quia quos facere!</span> </p>

                            <br>
                            <input type="submit" class="boton">
                        </form>
                    </div>
                </div>

            </section>                                                                                           

        </main>

        <footer>
            <img src="img/correo.png" alt="correo">
            <img src="img/llamada-telefonica.png" alt="telefono">
            <a href="https://www.instagram.com/"> <img src="img/instagram.png" alt="instagram"> </a>
            <a href="https://es-la.facebook.com/"> <img src="img/facebook.png" alt="facebook"> </a>
            <a href="https://twitter.com/?lang=es"> <img src="img/twitter.png" alt="twitter"></a>

        </footer>
        <div class="whats">
            <a href="https://wa.me/+525544634389"> <img src="img/whatsapp.png" alt="whatsapp"></a>
        </div>
    </body>
    </html>
    
    
    
    
   ## ESTRUCTURA DEL CSS
       @import url("https://fonts.googleapis.com"); /*enlace para las fuentes de google*/
    *{
        margin: 0; 
        padding: 0;
        font-family: 'Quicksand', sans-serif;
    }

    nav p{
        color:#684ea6; /*color de mi texto*/
       /* background-color: #E8EBF7; /* Color de la cajita de mi texto */
        font-size: 20px; /* tamaño de letra de mi texto*/
        text-align: left; /* orientación de mi texto*/
        letter-spacing: 5px; /*Espacio entre letras*/
        word-spacing: 10px; /* Espacio entre palabras*/
        text-shadow: -5px +5px 4px black; /*Metemos sombra a nuestro texto*/
        font-weight: bold; /* letras negritas e intensidad*/
    }



    header a {
        text-decoration: none; /*Para quitar subrayado*/
        color: white; 
        border: solid 1px black;
        background-color: #684ea6; 
        padding:10px;
        border-radius: 20px;
    }

    li{
        margin: 30px;
        list-style-type: none; /* Para quitar los puntitos que aparecen para representar las listas*/
    }
    .logo{
        display: flex;
        align-items: center;
    }
    nav {
        display: flex;
        justify-content: space-between; /*Alineación horizontal*/
        align-items: center; /*Alineación Vertical */
        height: 30%;
    }
    ul{
        display: flex;
    }
    nav img{
        width: 10%;
    }
    .caja{
        display: flex;
        height: 70%;
        display: flex;
        align-items: center;

    }
    .cajita{
    width: 50%;
    text-align: center;
    display: block;
    }
    .cajita img{
        width: 100%;
    }
    span{
        color: #684ea6 ;
        background: linear-gradient(360deg, #8E43AD, #A463BF, #ce2e9e, #F2C511, #DDE6E8, #ea678f, #da701a);
        -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    }

    h1 {
        font-size: 4em;

    }
    p{
        margin-bottom: 30px;
    }

            /* Termina barra de navegación */ 

            /*Establecer un tamaño al header*/

    header{
        width: 100%;
        height: 100vh;
        background: linear-gradient(  rgba(170, 62, 213, 0.936),white );

    }

    .acerca {
        height: 150vh;
        background: url(../img/fondo-ondulado-morado_1035-8665.avif);
        background-repeat: no-repeat;
        background-position: center;
        background-size:cover;

    }

    h2{
        text-align: center;
        font-size: 3em;
        background: linear-gradient(360deg, #8E43AD, #A463BF, #ce2e9e, #F2C511, #DDE6E8, #ea678f, #da701a);
        -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

    }
    .acerca1{
        height: 130vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .acerca2 {
        width: 50%;
        height: 50vh;
        background: linear-gradient(to right, rgba(170, 62, 213, 0.455), rgba(217, 164, 238, 0.449) ); /*Fondo de derecha a izquierda*/ 
        display: flex;
        justify-content: center;
        align-items: center;
        border-top-left-radius: 50px;
        border-bottom-right-radius:50px;
        padding: 20px;
        font-weight: bold;
    }

    /* Pseudoclases HOVER */ 
    /* Es cambiar el estilo predeterminado cuando pase algo*/

    a:hover{ /*Cuando pase el mouse por las "a" va a pasar algo*/
        color: rgb(106, 0, 255);
        font-size: 30px;
        background-color: rgb(188, 171, 210);
    }

    /* Division paralax */
    .paralax{
        width: 100%;
        height: 50vh;
        background: url(../img/pexels-felix-mittermeier-957040\ \(1\).jpg);
        display: flex;
        align-items: center;
        justify-content: center;
        background-attachment: fixed; /* Efecto de estar pegada*/
    }

    .paralax p {
        width: 60%;
        background-color: rgba(37, 69, 69, 0.532);
        padding: 30px;
        text-align: center;
        font-size: 3em;
        color: white;
        text-shadow: 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff, 0 0 42px #0fa, 0 0 82px #0fa, 0 0 92px #0fa, 0 0 102px #0fa, 0 0 151px #0fa; /* da un brillo, tipo neón a mi texto*/ 
    }

    /*Comienza PORTAFOLIO*/
    .portafolio{
        width: 100%;
        height: 100vh;
        background: url(../img/fondo-ondulado-morado_1035-8665\(1\).jpg);
        background-repeat: no-repeat;
        background-position: center;
        background-size:cover;
    }

    .portafolio1 {
        height: 80vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .portafolio2 {
        width: 60%;
        height: 70vh;
        border: solid 3px rgb(44, 95, 235);
        display: flex;

    }

    .portafolio2 img {
        width: 0;
        flex-grow: 1; /*agarra el espacio que le corresponde*/
        object-fit: cover; /*agarra el espacio sin rebazar*/
        opacity: .8 ; 
        transition: .5s ease; /*2 pasos, el primero a la img */

    }

    .portafolio2 img:hover {
        cursor: crosshair; /*Cursor se pone en cruz*/
        width: 40%;
        opacity: 1;
        filter: contrast(120%);
    }

    /* Empieza CONTACTO */

    .contacto {
        width: 100%;
        height: 80vh;
        background: linear-gradient( white , rgba(170, 62, 213, 0.936) );
    }

    .contacto1 {
        height: 70vh;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .contacto2 {
        width: 60%;
        height: 60vh;
        background-color:  rgba(37, 69, 69, 0.301) ;
        border-radius: 30px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .input {
        border: solid 3px #684ea6;
        border-radius: 10px;
    }

    .boton {
        color: white; 
        border: solid 1px black;
        background-color: #684ea6; 
        padding:10px;
        border-radius: 10px;
    }

    .whats {
        position: fixed;
        bottom: 10px;
        right: 10px;
    }

    footer{
        width: 100%;
        height: 20vh;
        background-color: rgba(170, 62, 213, 0.936);
        display: flex;
        align-items: center;
        justify-content: center;
    }

    footer img {
        border-radius: 50px;
        margin-right: 50px;
        transition: .5s, color .10s;
        -webkit-transition: .5s, color .10s;
        -moz-transition: .5s, color .10s;
    }
    footer img:hover{
        box-shadow: 0 8px 8px 0 #000000,0 8px 8px 0 #000000;
        transform: translate(0px,5px);
        -webkit-transform: translate(0px,5px);
        -moz-transform:translate(0px,5px);
    }

    .aviso{
        position: relative;
        display: inline-block; /*visible uno abajo del otro*/

    }

    /* vamos a trabajar con el span*/
    .aviso1{
        font-size: 0.8em;
        display: none; /*quita los elementos */
        width: 500px;
        border: solid 1px black;
        background: #0000003d;
        color: #fff;
        border-radius: 10px;
        position: absolute;
        top: 1px;
        left: 1px;
        z-index: 1; /* la posición de las cosas encimadas, posición 1 significa que se pasa adelante */

    }

    .aviso:hover .aviso1 { /*cuando pases el mouse sobre aviso, a aviso 1 le haras lo siguiente*/
        display: block;

    }
                  /*Diseños- Estilos de Paginas complementarías */

    .contenedor {
        height: 80vh;
        width: 100%;
        background: linear-gradient( white , rgba(170, 62, 213, 0.936) );

    }     

    .contenedor1{
        height: 70vh;
        display: flex;
        width: 90%;
        margin: auto;
        align-items: center;
        justify-content: space-around;

    }

    .card{
        width: 20%;
        background: white;
        border-radius: 30px;
        transition: .5s, color .10s;
            -webkit-transition: .5s, color .10s;
            -moz-transition: .5s, color .10s; 

    }

    .card a{
        color: #684ea6;
        text-decoration: none;
        justify-content: center;
        align-items: center;
        display: flex;
        margin-bottom: 20px;
    }


    .card a:hover{
        font-size: 1em;
        padding: 0;
        background: rgba(255, 255, 255, 0.281);
    }
    .card img{
        width: 100%;
        border-top-right-radius: 30px;
        border-top-left-radius: 30px;
    }

    .card:hover{transform: translatey(20px);
        -webkit-transform: translatey(20px);
        -moz-transform: translatey(20px);
    }

    .card p{
        margin-left: 10px;
        margin-right: 10px;
    }

            /* S E U D O E L E M E N T O S */

        /* Vamos a crear una barra de navegación */

    ::-webkit-scrollbar{
        background-color: #ce2e9e;
        width: 20px;

    }

    ::-webkit-scrollbar-track{
        border-radius: 30px;
        background-color: #684ea6;
        box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.722); /*inset le da una sombra*/
    }

    ::-webkit-scrollbar-thumb{ /*Creamos el carrito de la barra de navegación*/
        border-radius: 10px;
        background: linear-gradient(#cf89ba,#9a67b0);
    }

                                                     /* EJEMPLO  RESPONSIVO */
    .hambur{
        display: none; /*Lo oculta*/
    }
    #Menú{
        display: none;
    }

                        /* SubMenu Menú Desplegable  */

    .menudes{
        background-color: #684ea6;
        position: absolute;
        top: 140px;
        display: none;
    }

    .porta:hover .menudes{
        display: block;
    }



    @media(max-width:900px){    /*Todo lo que se ponga aquí aplica para max 900px*/
    .hambur{
        display: block; /*Lo muestra*/
        width: 60px;
        position: absolute;
        top: 20px;
        right: 10px;

    } 

       ul{
        display: none;
        width: 200px;
        border: solid;
        background: #9a67b0;
        background-color: #ce2e9e;
        position: absolute; 
        right: 70px;
        top: 40px;
    }
       input:checked ~ul{
       display: block;}
       #Menú{display: none;}

         /*  Estilos de HEADER */

    .cajita{
        display: none;

    }


    .cajitares{
        display: block;
        text-align: center;
        width: 100%;
        height: 60vh;
    }

    .logo p{
        font-size: .7em
    }

    .logo img{
        width: 20% ;
    }

    .acerca{
        width: 100%;
        height: 80vh;

    }

    .acerca1{
        height: 60vh;
        margin-top: 30px;
    }

    .acerca2{
        height: 60vh;
        width: 90%;
    }
    .acerca2 p{
        height:50vh;
        font-size: 0.8em;
    }
    .paralax p {
        width: 90%;
        font-size: 1em;
        padding: 10px;
        margin-bottom: 20px;
    }
    .portafolio{
        height: 40vh;

    }
    .portafolio1{
        height: 40vh;
        margin-bottom: 30px;

    }

    .portafolio2{
        width: 80% ;
        height: 30vh;
        margin-bottom: 40px;
    }

    .contacto{
        height: 90vh;

    }
    .contacto1{
        height: 80vh;

    }
    .contacto2{
        width: 90%;
        height: 70vh;
        font-size: .8em;
    }

    .contacto2 input{
        display: inline-block; /* Muestrate en linea*/
    }

    .input{
        margin-top: 20px;
        width: 300px;
    }

    .contenedor{
        width: 100%;
        height: 80vh;
        margin-left: 10px;
        margin-right: 10px;
    }

    .contenedor1{
        margin-top: 20px;
        width: 80%;
        height: 60vh;
        flex-direction: column;
    }

    .card{
        margin-bottom: 30px;
        width: 80%;
        height: 50vh;
        font-size: .8em;
    }
    }

   
   
   
   
   
