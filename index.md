<html lang="en">

<head>

  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="">
  <meta name="author" content="">

  <title>Shop Homepage - Start Bootstrap Template</title>

  <!-- Bootstrap core CSS -->
  <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">

  <!-- Custom styles for this template -->
  <link href="css/shop-homepage.css" rel="stylesheet">

</head>

<body>

  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">FABKIDS learn EXEMPLE 1</a>
        
      <!-- Crear Menu desplegable -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>       
        
        
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ml-auto">
            
          <!--BOTONS dintre del menu   
          podeu modificar-lis a la paraula Home, about... 
          també podeu afegirne o esvborrar-ne  --> 
          <li class="nav-item active">
            <a class="nav-link" href="#">Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
            
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
            
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>           
            
            
        </ul>
      </div>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container">

    <div class="row">  <!-- escollim la clase row per crear columna vertical -->

      <div class="col-lg-3">                <!-- TRIAR NOMBRE DE COLUUMNES = 3 -->

        <h1 class="my-4">HTML learn </h1>
          <!-- LLISTA tal com apareix al navegdor-->
        <div class="list-group">
          <a href="#" class="list-group-item">BUSCAR AL CODI</a>
          <a href="#" class="list-group-item">linia 72 </a>
          <a href="#" class="list-group-item">podeu fer modificacions</a>
          <a href="https://startbootstrap.com/templates/ " target="_blank" class="list-group-item">            
                  LINk exemples             
              
          </a>
        </div>

      </div>
      <!-- /.col-lg-3 -->

      <div class="col-lg-9">        <!-- NUMERO COLUMNES = 9 -->
          
          
          <!-- PER POSAR IMATGES -->
        <div id="carouselExampleIndicators" class="carousel slide my-4" data-ride="carousel">
            
            
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          </ol>
            
            <!-- Aqui dintre les imatges --> 
            
          <div class="carousel-inner" role="listbox">
            <div class="carousel-item active">
                
                <!-- IMATGE 1 -->
              <img class="d-block img-fluid" src="https://cdn.pp.slimpay.com/blog/2017/06/07122118/DZN-Blog-Hero-900x350-5KPIs.jpg" alt="First slide">
            </div>
            <div class="carousel-item">
              <img class="d-block img-fluid" src="http://www.liltfilms.com/wp-content/uploads/2012/11/cropped-home-office-macbookair-apple-brand-notebook-computer-top-uhd-4k-wallpapers-2880x1800-900x350.jpg" alt="Second slide">
            </div>
            <div class="carousel-item">
              <img class="d-block img-fluid" src="https://zeedup.com/wp-content/uploads/2016/12/amar-5-900x350.jpg" alt="Third slide">
            </div>
          </div>
            <!-- ----------------------------------------------   -->
            
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
        
          
        <!-- SECCIONS SOTA IMATGES -->
        <!-- AQUI eescriure anuncis-->
        <div class="row">       <!-- escollim la class row -->
            
            <!-- ANUNCI ROBOT -->

          <div class="col-lg-4 col-md-6 mb-4">   <!-- Escollim tamañs segons dimensio pantalla -->
              
            <div class="card h-100">  <!-- Per crear l'estil-->
                
                
                <!-- COPIAR enllaç imatge aqui dintre
                <a href="#">
                    <img class="card-img-top" src="pegar aqui" alt="">
                </a>
                -->
                
              <a href="#">
                  <img class="card-img-top" src="https://easyworks.es/wp-content/uploads/2018/04/FP-Innova-robot-5-min-700x400.jpg" alt="">
              </a>
                
              <div class="card-body">
                  
                <h4 class="card-title">     
                  <a href="#">MODIFICA'M</a>
                </h4>
                <h5>$24.99</h5>
                <p class="card-text">Futur robot que crearà naus espacials per simular aparició de vida a l'espai</p>
                  
              </div>
                
                
                
              <div class="card-footer">
                <small class="text-muted">&#9733; &#9733; &#9733; &#9733; &#9734;</small>
              </div>
                
            </div>
              
              
          </div>
            
            
            <!-- SEGUENT ANUNCI!!!! -->
            
            
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card h-100">
              <a href="#"><img class="card-img-top" src="https://www.codeinguru.com/furniture/wp-content/uploads/2018/08/1.jpg" alt=""></a>
              <div class="card-body">
                <h4 class="card-title">
                  <a href="#">VIATGE FABKIDS</a>
                </h4>
                <h5>$300</h5>
                <p class="card-text">
                    Anirem a les maldiven en avión gracies a la nostra pagina web!
                    <a href="https://visitmaldives.com/" target="_blank">Visit Maldives</a>
                </p>
              </div>
              <div class="card-footer">
                <small class="text-muted">&#9733; &#9733; &#9733; &#9733; &#9734;</small>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card h-100">
              <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
              <div class="card-body">
                <h4 class="card-title">
                  <a href="#">Item Three</a>
                </h4>
                <h5>$24.99</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam aspernatur!</p>
              </div>
              <div class="card-footer">
                <small class="text-muted">&#9733; &#9733; &#9733; &#9733; &#9734;</small>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card h-100">
              <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
              <div class="card-body">
                <h4 class="card-title">
                  <a href="#">Item Four</a>
                </h4>
                <h5>$24.99</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam aspernatur!</p>
              </div>
              <div class="card-footer">
                <small class="text-muted">&#9733; &#9733; &#9733; &#9733; &#9734;</small>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card h-100">
              <a href="#"><img class="card-img-top" src="http://placehold.it/700x400" alt=""></a>
              <div class="card-body">
                <h4 class="card-title">
                  <a href="#">Item Five</a>
                </h4>
                <h5>$24.99</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet numquam aspernatur! Lorem ipsum dolor sit amet.</p>
              </div>
              <div class="card-footer">
                <small class="text-muted">&#9733; &#9733; &#9733; &#9733; &#9734;</small>
              </div>
            </div>
          </div>

      

        </div>
        <!-- /.row -->

      </div>
      <!-- /.col-lg-9 -->

    </div>
    <!-- /.row -->

  </div>
  <!-- /.container -->

  <!-- Footer -->
  <footer class="py-5 bg-dark">
    <div class="container">
      <p class="m-0 text-center text-white">Copyright &copy; Your Website 2019</p>
    </div>
    <!-- /.container -->
  </footer>

  <!-- Bootstrap core JavaScript -->
  <script src="vendor/jquery/jquery.min.js"></script>
  <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

</body>

</html>
