### Código del HTML

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Crimson+Text&display=swap" rel="stylesheet">
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <link rel="stylesheet" href="css/estilos.css">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Brenda Juárez 🤞✌💕</title>

    </head>
    <body>
        <header id="inicio">
            <nav>
                <div class="logo"> 
                    <img src="img/logo.jpg" alt="logo">
                    <p> 💕BRENDA N. JUÁREZ TORRES💕</p>
                </div>

                <ul>
                    <li><a href="#inicio">INICIO</a></li>
                    <li><a href="#acerca_de">ACERCA_DE</a></li>
                    <li><a href="">PORTAFOLIO</a></li>
                    <li><a href="">CONTACTO</a></li>
                </ul>
            </nav>

            <div class="caja">
                <div class="cajita">
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

        </main>

        <footer>
        </footer>
    </body>
    </html>
    
    
    
   ### Código del CSS
   
       *{
        margin: 0; 
        padding: 0;
        font-family: 'Crimson Text', serif;}

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



    a {
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
    }
    .cajita img{
        width: 100%;
    }
    span{
        color: #684ea6 ;
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
   
   
