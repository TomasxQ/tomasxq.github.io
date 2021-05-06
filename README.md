<!doctype html>
<html lang="en">
  <head>  
 
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

  
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
    <link rel="stylesheet" href="css pagina lol.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.1/font/bootstrap-icons.css"&gt;
    <title>La liga de las leyendas</title>
    <style>
      .backg{
        background-color: rgb(228, 228, 228);
      }
      .navbar{
        border-radius: 5px;
      }
      .cajicas{
        background-color: rgb(140, 140, 201);
        font-size: large;
        font-family: Arial, Helvetica, sans-serif;
        color:rgb(49, 46, 46);
        background-color: white;
      }
      #myVideo {
        position: fixed;
        right: 0;
        bottom: 50;
        min-width: 100%; 
        min-height: 100%;
      }
      .content {
        position: relative;
        background: rgba(185, 172, 172, 0.5);
        width: 100%;
        padding: 10px;
        bottom: auto;
      } 
    </style>


  </head>
  <body>
    <video autoplay muted loop id="myVideo">
      <source src="videolol.webm" type="video/mp4">
      Your browser does not support HTML5 video.
    </video>


      <div class="container-sm">
        
          <nav class="navbar navbar-expand-lg navbar-light bg-light">
              <div class="container-fluid">
                  <a href="web principal.html"><img src="campeones lol/League_of_Legends_icon_old2.png"  width="60" height="60"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                      <a class="nav-link active" aria-current="page" href="campeones.html">Personajes</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="profesionales.html">Profesionales</a>
                    </li>
                    <li class="nav-item dropdown">
                      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Modos de juegos
                      </a>
                      <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <li><a class="dropdown-item" href="modos/urf.html">URF</a></li>
                        <li><a class="dropdown-item" href="modos/5vs5.html">5vs5</a></li>
                        <li><a class="dropdown-item" href="modos/aram.html">ARAM</a></li>
                        <li><a class="dropdown-item" href="modos/3vs3.html">3vs3</a></li>
                      </ul>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="formulario.html">Formulario</a>
                    </li>
                  </ul>
                  <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                      <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                    </svg></button>
                  </form>
                </div>
              </div>
            </nav>

        <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="campeones lol/carousel_1.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="campeones lol/carousel_2.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="campeones lol/carousel_3.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="campeones lol/carousel_4.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
              <img src="campeones lol/carousel_5.jpg" class="d-block w-100" alt="...">
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>


        <div class="content">
          <div class="row">
            <div class="col-12" style="margin-top: 30px;">
        
              <h2>Que es el League of Legends</h1> 
              <div class="row"></div>
              <div class="badge text-wrap col-12 cajicas fw-light" style="width: 100%; ">
                League of Legends es un juego de estrategia por equipos en el que dos equipos de cinco campeones se enfrentan para ver quién destruye antes la base del otro. Elige de entre un elenco de 155 campeones para realizar jugadas épicas, asesinar rivales y derribar torretas para alzarte con la victoria. Originalmente fue lanzado en el 2009 en su fase beta pero conforme han pasado los años el juego ha ido evolucionado muchisimo, un ejemplo de ello es una renovación completa del mapa original en el 2014, el cual tenia una estetica muy de RPG de los 2000. El juego es un fenomeno mundial siendo el juego de PC mas jugado en la actualidad, en el 2011 la cantidad de personas que jugaban mensualmente era de 11.5 millones de jugadores, en cambio hoy en dia esa cifra ha subido hasta 120 millones. 
              </div>
            </div>
          </div>
        

      
          <div class="row">
            <div class="col-12" style="margin-top: 30px;">

              <h2>Conceptos básicos</h1> 
              <div class="row"></div>
              <div class="badge text-wrap col-12 cajicas fw-light" style="width: 100%; ">
                El mapa esta formado por 3 carriles principalmente uno en la parte superior del mapa, otro en el medio y el último en la parte de abajo. Entre los carriles hay un espacio conocido como la jungla. 
                Al ser un juego 5v5 cada persona tiene un rol y carril asignado, quien juega en el carril superior se le conoce como "Top", la persona que juego en el carril central se llama "Mid", en carril inferior juegan dos personas, el "ADC" y el "Apoyo" y el ultimo integrante del equipo es el "Jungla" que como se puede suponer juega en la jungla.
              </div>
            </div>
          </div>
          <div class="row" style="margin-top: 30px">
            <footer class="bg-dark text-center text-white">
              <div class="container p-4">
                <section class="mb-4">
                 
                  <a class="btn btn-outline-light btn-floating m-1" href="https://www.facebook.com/leagueoflegends" role="button"
                  ><i class="bi bi-facebook"></i>
                  </a>
  
               
                  <a class="btn btn-outline-light btn-floating m-1" href="https://twitter.com/lol_es?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor%22%3E" role="button"
                  ><i class="bi bi-twitter"></i>
                  </a>
  
                 
  
                 
                  <a class="btn btn-outline-light btn-floating m-1" href="https://www.instagram.com/leagueoflegends/%22%3E" role="button"
                  ><i class="bi bi-instagram"></i>
                  </a>
  
                 
                  <a class="btn btn-outline-light btn-floating m-1" href="https://www.youtube.com/user/RiotGamesInc%22%3E" role="button"
                  ><i class="bi bi-youtube"></i>
                  </a>
  
            
                </section>
                
  
                
  
               
                <section class="mb-4">
                  <p>
                    ™ & © 2021 Riot Games, Inc. Todos los derechos reservados. Riot Games, League of Legends y PvP.net son marcas comerciales o marcas registradas de Riot Games, Inc.
                  </p>
                </section>
       

              <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
                © 2020 Copyright:
                <a class="text-white" href="https://euw.leagueoflegends.com/es-es/champions/teemo/">Riotgames</a>
                <div class="row" style="margin-top: 30px;"></div>
  
                <img src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt968ee09c83b8f93d/5e855258b01b81301599af3b/usk-12.png?&height=100&disable=upscale" >
                <img src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt5183333a33f60552/5e855702d2b50e545115eb26/pegi-eu.png?&height=100&disable=upscale" >
              </div>
         
            </footer>
        
          </div>
        
          </div>
  </div>
   
  </div>
        </div>
      
    
     
    </div>

   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>

    
  </body>
</html>
