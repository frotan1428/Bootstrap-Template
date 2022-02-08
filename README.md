<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Bootsrap </title>
  <link rel="stylesheet" href="css/bootstrap.min.css"/>
  				<script src="js/jquery-3.6.0.min.js"></script>
  				<script src="js/bootstrap.min.js"></script>
  		<link rel="stylesheet" href="css/style.css"/>
      	<script src="js/all.js"></script>


</head>

<body>
  <section id="title">
    <div class="container-fluid">
      <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="#">Tingdo</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#footer">Cantact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#pricing">pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
            </li>
          </ul>

        </div>
      </nav>

      <div class="row">
        <div class="col-lg-6">
          <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
          <button class="btn btn-dark btn-lg download-button" type="button"> <i class="fab fa-apple"></i> Download </button>
          <button class="btn btn-outline-light btn-lg download-button" type="button"><i class="fab fa-google-play"></i> Download</button>
        </div>
        <div class="col-lg-6">
          <img  class="title-image" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div>

    </div>

  </section>


  <!-- Features -->

  <section id="features">
  <div class="container-fluid">

    <div class="row">
      <div class="features-Box col-lg-4">
        <i class="icon fas fa-check-circle fa-4x"></i>
        <h3>Easy to use.</h3>
        <p>So easy to use, even your dog could do it.</p>
      </div>
      <div class="features-Box col-lg-4">
        <i class="icon fas fa-bullseye fa-4x"></i>
        <h3>Elite Clientele</h3>
        <p>We have all the dogs, the greatest dogs.</p>
      </div>
      <div class="features-Box col-lg-4">
        <i class="icon fas fa-heart fa-4x"></i>
        <h3>Guaranteed to work.</h3>
        <p>Find the love of your dog's life or your money back.</p>
      </div>
    </div>

  </div>

  </section>


  <!-- Testimonials -->

  <section id="testimonials">


    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active container-fluid">
      <h2 class="testimonials-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
      <img class="testimonials-image" src="images/dog-img.jpg" alt="dog-profile">
      <em>Pebbles, New York</em>
    </div>
    <div class="carousel-item container-fluid">
      <h2 class="testimonials-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
        <img class="testimonials-image" src="images/lady-img.jpg" alt="lady-profile">
        <em>Beverly, Illinois</em>
    </div>
    <div class="carousel-item container-fluid">
      <h2 class="testimonials-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
        <img class="testimonials-image" src="images/lady-img.jpg" alt="lady-profile">
        <em>Beverly, Illinois</em>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-logo"src="images/techcrunch.png" alt="tc-logo">
    <img class="press-logo"src="images/tnw.png" alt="tnw-logo">
    <img class="press-logo"src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo"src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
      <h2 class="section-heading">A Plan for Every Dog's Needs</h2>
      <p>Simple and affordable price plans for your and your dog.</p>
    </div>

    <div class="row">
      <div class="pricing-column col-lg-4 col-md-6 ">
        <div class="card mb-4 shadow-sm">
          <div class="card-header">
          <h3 class="features-title">Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2 class="pricing-text">Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button type="button" class="btn btn-lg btn-block btn-outline-primary">sign Up</button>
          </div>
        </div>
      </div>
      <div class="pricing-column col-lg-4 col-md-6 ">
        <div class="card mb-4 shadow-sm">
        <div class="card-header">
        <h3 class="features-title">Labrador</h3>
        </div>
        <div class="card-body">
          <h2 class="pricing-text">$49 / mo</h2>
          <p>Unlimited Matches</p>
          <p>Unlimited Messages</p>
          <p>Unlimited App Usage</p>
          <button type="button" class="btn btn-lg btn-block btn-primary">sign Up</button>
        </div>
        </div>
      </div>
      <div class="pricing-column col-lg-4 col-md-6 ">
      <div class="card mb-4 shadow-sm">
        <div class="card-header">
        <h3 class="features-title">Mastiff</h3>
        </div>
        <div class="card-body">
          <h2 class="pricing-text">$99 / mo</h2>
          <p>Pirority Listing</p>
          <p>Unlimited Matches</p>
          <p>Unlimited Messages</p>
          <button type="button" class="btn btn-lg btn-block btn-dark">sign Up</button>
        </div>
        </div>
      </div>

    </div>
  </section>


  <!-- Call to Action -->

  <section id="cta">
    <div class="container-fluid">

    <h3 class="big-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button class="btn btn-dark btn-lg download-button" type="button"> <i class="fab fa-apple"></i> Download </button>
    <button class="btn btn-outline-light btn-lg download-button" type="button"><i class="fab fa-google-play"></i> Download</button>

  </div>
  </section>


  <!-- Footer -->
<div class="container-fluid">
  <footer id="footer">
    <i class="social-icon fab fa-facebook-f fa-3x"></i>
    <i class="social-icon fab fa-twitter fa-3x"></i>
    <i class="social-icon fab fa-instagram fa-3x"></i>
    <i class="social-icon fab fa-facebook fa-3x"></i>

    <p>© Copyright TinDog</p>

  </footer>
</div>

</body>

</html>
