# Web-Empoderadas
//Página web estilo Carrusel de Patrones Hermosos, No a la Violencia contra la Mujer del Equipo 11
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
    <meta name="generator" content="Hugo 0.55.4">
    <title>Mujer Empoderada</title>

    <link rel="canonical" href="https://getbootstrap.comdocs/4.3/examples/carousel/">

    

    <!-- Bootstrap core CSS -->
<link href="docs/4.3/dist/css/bootstrap.css" rel="stylesheet">



    <!-- Favicons -->
<link rel="apple-touch-icon" href="docs/4.3/assets/img/favicons/apple-touch-icon.png" sizes="180x180">
<link rel="icon" href="docs/4.3/assets/img/favicons/favicon-32x32.png" sizes="32x32" type="image/png">
<link rel="icon" href="docs/4.3/assets/img/favicons/favicon-16x16.png" sizes="16x16" type="image/png">
<link rel="manifest" href="docs/4.3/assets/img/favicons/manifest.json">
<link rel="mask-icon" href="docs/4.3/assets/img/favicons/safari-pinned-tab.svg" color="#563d7c">
<link rel="icon" href="docs/4.3/assets/img/favicons/favicon.ico">
<meta name="msapplication-config" content="docs/4.3/assets/img/favicons/browserconfig.xml">
<meta name="theme-color" content="#563d7c">


    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
    </style>

    
    <!-- Custom styles for this template -->
    <link href="carousel.css" rel="stylesheet">
  </head>
  <body>
    
<header>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <a class="navbar-brand" href="#">Empoderadas</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarCollapse">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Nosotras <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Objetivos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Apoyo</a>
        </li>
      </ul>
      <form class="form-inline mt-2 mt-md-0">
        <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Búsqueda</button>
      </form>
    </div>
  </nav>
</header>

<main role="main">

  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="stop.jpg"  alt="...">

        <div class="container">
          <div class="carousel-caption text-left">
            <h1>No más abusos</h1>
            <p>Toda mujer merece respeto, libertad y dignidad</p>
            <p><a class="btn btn-lg btn-primary" href="#" role="button">Infómate más</a></p>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <img src="lluvia.jpg" alt="...">

        <div class="container">
          <div class="carousel-caption">
            <h1>Tú puedes cambiar tu historia</h1>
            <p>Puedes ser la Protagonista Principal de tu propia vida</p>
            <p><a class="btn btn-lg btn-primary" href="#" role="button">Aprende como</a></p>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <img src="amigas.jpg" alt="...">

        <div class="container">
          <div class="carousel-caption text-right">
            <h1>No estás sola</h1>
            <p>Muchas mujeres como tú han salido de una situación de violencia</p>
            <p><a class="btn btn-lg btn-primary" href="#" role="button">Pasos a tomar</a></p>
          </div>
        </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>


  <!-- Marketing messaging and featurettes
  ================================================== -->
  <!-- Wrap the rest of the page in another container to center all the content. -->

  <div class="container marketing">

    <!-- Three columns of text below the carousel -->
    <div class="row">
      <div class="col-lg-4">
        <img src="triste.jpg"svg class="bd-placeholder-img rounded-circle" width="140" height="140" xmlns="http://www.w3.org/2000/svg" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" role="img"><title>Placeholder</title><rect width="100%" height="100%" fill="#777"/><text x="50%" y="50%" fill="#777" dy=".3em"></text></svg>

        <h2>Violencia Psicológica</h2>
        <p>Son palabras, desvalorización y daño que hiere el alma. No son marcas físicas pero lesionan tu dignidad y tu autoestima</p>
        <p><a class="btn btn-secondary" href="#" role="button">¿Esta es tu situación? &raquo;</a></p>
      </div><!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img src="golpe.jpg" svg class="bd-placeholder-img rounded-circle" width="140" height="140" xmlns="http://www.w3.org/2000/svg" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" role="img"><title>Placeholder</title><rect width="100%" height="100%" fill="#777"/><text x="50%" y="50%" fill="#777" dy=".3em"></text></svg>

        <h2>Violencia Física</h2>
        <p>Los golpes y las lesiones no siempre vienen de una vez, a menudo los agresores van aumentando el nivel de violencia gradualmente.</p>
        <p><a class="btn btn-secondary" href="#" role="button">¿Es tu caso? &raquo;</a></p>
      </div><!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img src="abuso.jpg" svg class="bd-placeholder-img rounded-circle" width="140" height="140" xmlns="http://www.w3.org/2000/svg" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" role="img"><title>Placeholder</title><rect width="100%" height="100%" fill="#777"/><text x="50%" y="50%" fill="#777" dy=".3em"></text></svg>

        <h2>Violencia Sexual</h2>
        <p>Este tipo de agresión no distingue edad, condición social, no tiene justificación y causa daños graves</p>
        <p><a class="btn btn-secondary" href="#" role="button">¿Has sido víctima de esto? &raquo;</a></p>
      </div><!-- /.col-lg-4 -->
    </div><!-- /.row -->


    <!-- START THE FEATURETTES -->

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">Desigualdad Económica <span class="text-muted">Los recursos no son equitativos</span></h2>
        <p class="lead">Investigaciones a nivel mundial denotan el desbalance económico, ya que las mujeres obtienen un sueldo menor al hombre por realizar el mismo trabajo.</p>
      </div>
      <div class="col-md-5">
        <img src="computadora.jpg" width="400" height="400"  xmlns="http://www.w3.org/2000/svg"  preserveAspectRatio="xMidYMid slice" role="img"><title>Placeholder</title><rect width="100%" height="100%" fill="#eee"/><text x="50%" y="50%" fill="#aaa" dy=".3em"></text></svg>

      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7 order-md-2">
        <h2 class="featurette-heading">Desbalance Patrimonial <span class="text-muted"> que causa dependencia</span></h2>
        <p class="lead">Muchos sistemas gubernamentales ponen muchas trabas para que una mujer adquiera una propiedad, causando que no tenga independencia y por consecuencia sea sometida.</p>
      </div>
      <div class="col-md-5 order-md-1">
        <img src="asustada.jpg"bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="400" height="400" xmlns="http://www.w3.org/2000/svg" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice" role="img"><title></title><rect width="100%" height="100%" fill="#eee"/><text x="50%" y="50%" fill="#aaa" dy=".3em"></text></svg>

      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">Discriminación <span class="text-muted">Cultural, Racial y Social</span></h2>
        <p class="lead">Muchas mujeres viven diariamente discriminación y esto no permite un óptimo desarrollo con igualdad de oportunidades.</p>
      </div>
      <div class="col-md-5">
        <img src="feliz cultura.jpg" bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="400" height="400" xmlns="http://www.w3.org/2000/svg" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice" role="img"><title></title><rect width="100%" height="100%" fill="#eee"/><text x="50%" y="50%" fill="#aaa" dy=".3em"></text></svg>

      </div>
    </div>

    <hr class="featurette-divider">

    <!-- /END THE FEATURETTES -->

  </div><!-- /.container -->


  <!-- FOOTER -->
  <footer class="container">
    <p class="float-right"><a href="#">Ir arriba</a></p>
    <p>&copy; 2022 Patrones Hermosos &middot; <a href="#">4ta Generación</a> &middot; <a href="#">Grupo 11</a></p>
  </footer>
</main>


    
      
        <script src="docs/4.3/dist/js/bootstrap.bundle.js"></script>
      

      
    
  </body>
</html>

