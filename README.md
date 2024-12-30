# aptech_demo-1



<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>PayPal-Style Navbar</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light sticky-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">PayPal</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarScroll">
          <ul class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Personal
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
            <li class="nav-item">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Small Business
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
              </li>
            <li class="nav-item">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Enterprise
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
              </li>
              
          <form class="d-flex ms-3" role="search">
            <button class="btn btn-outline-success mx-2" type="submit">help</button>
            <button class="btn btn-outline-success mx-2" type="submit">Login</button>
            <button class="btn btn-primary " type="submit">Sign up</button>
          </form>
        </div>
      </div>
    </nav>

    <section class="home">
        <div class="home-content">
            <h1>The New Paypal</h1>
            <h1>App is here</h1>
            <div class="social-media">
                <a href="#" style="--i:7"><i class='bx bxl-facebook' ></i></a>
                <a href="#" style="--i:8"><i class='bx bxl-twitter' ></i></a>
                <a href="#" style="--i:9"><i class='bx bxl-instagram-alt' ></i></a>
            </div>
            <a href="#" class="button">Learn more about the new features</a>
        </div>

        <!-- <div class="home-img">
            <img src="home.png" alt="">
        </div> -->
        <img src="https://www.paypalobjects.com/marketing/web/shared/qrc-sms/device-hero.png" alt="device" class="device-mobile">
    </section>
    
    <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="images.png"
              class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <p class="display-5 fw-bold text-body-emphasis lh-1 mb-3">PayPal is a widely used online payment platform that allows individuals and businesses to make payments and money transfers over the internet.</p>
              <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <button class="btn btn-primary rounded-pill px-3" type="button">Send</button> <input type="email"
                  class="form-control" id="floatingInput" placeholder="Phone Number">
              </div>
          </div>
        </div>
      </div>

      <div class="row featurette">
        <div class="col-md-7">
          <h1 class="featurette-heading fw-normal lh-1">Buy now, pay later with Pay in <br> <br></h1>
            <h4><p>
              Want something now but the sale ends before payday? <br>Choose Pay in 4 at checkout with millions of online
              stores <br>and split the cost into 4 interest-free payments.</p>
          </h4>
        </div>
        <div class="col-md-5">
          <img src="https://www.paypalobjects.com/marketing/web/us/home/BNPL-img.jpg" alt="" height="500" width="500">
        </div>
      </div>
  
      <br class="featurette-divider">
      <div class="row featurette">
        <div class="col-md-7 order-md-2">
          <h1 class="featurette-heading fw-normal lh-1">Buy now, pay later with Pay in <br> <br></h1>
           <h4><p>
              Want something now but the sale ends before payday? <br>Choose Pay in 4 at checkout with millions of online
              stores <br>and split the cost into 4 interest-free payments.</p>
          </h4>
        </div>
        <div class="col-md-5 order-md-1">
          <img src="https://www.paypalobjects.com/marketing/web/us/home/crypto-img.jpg" alt="" height="450" width="450">
        </div>
      </div>
  
      <br class="featurette-divider">
      <div class="row featurette">
        <div class="col-md-7">
          <h1 class="featurette-heading fw-normal lh-1">Buy now, pay later with Pay in <br> <br></h1>
            <h4><p>
              Want something now but the sale ends before payday? <br>Choose Pay in 4 at checkout with millions of online
              stores <br>and split the cost into 4 interest-free payments.</p>
          </h4>
        </div>
        <div class="col-md-5">
          <img src="https://www.paypalobjects.com/marketing/web/us/home/touchfree-img.jpg" alt="" height="450"
            width="450">
        </div>
      </div>
  
      <br class="featurette-divider">
      <div class="row featurette">
        <div class="col-md-7 order-md-2">
          <h1 class="featurette-heading fw-normal lh-1">Buy now, pay later with Pay in <br> <br></h1>
            <h4><p>
              Want something now but the sale ends before payday? <br>Choose Pay in 4 at checkout with millions of online
              stores <br>and split the cost into 4 interest-free payments.</p>
          </h4>
        </div>
        <div class="col-md-5 order-md-1">
          <img src="https://www.paypalobjects.com/marketing/web/us/home/sendmoney-img.jpg" alt="" height="450"
            width="450">
        </div>
      </div>
      <br class="featurette-divider">
      <div class="row featurette">
        <div class="col-md-7">
          <h1 class="featurette-heading fw-normal lh-1">Buy now, pay later with Pay in <br> <br></h1>
            <h4><p>
              Want something now but the sale ends before payday? <br>Choose Pay in 4 at checkout with millions of online
              stores <br>and split the cost into 4 interest-free payments.</p>
          </h4>
        </div>
        <div class="col-md-5">
          <img src="https://www.paypalobjects.com/marketing/web/us/home/give-img.jpg" alt="" height="450"
            width="450">
        </div>
      </div>
       <section class="footer">
        <footer class="py-3 my-4">
          <ul class="nav justify-content-center border-bottom pb-3 mb-3">
            <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">Home</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">Features</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">Pricing</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">FAQs</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-body-secondary">About</a></li>
          </ul>
          <p class="text-center text-body-secondary">PayPal © 2024 Company, Inc</p>
        </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
