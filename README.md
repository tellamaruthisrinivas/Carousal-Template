<head>
    <title>Carousel Template · Bootstrap</title>
    <link href="boot.png" rel="icon">
</head>
<body>
    <div class="container-fluid ">
        <div class="row bg-dark pt-3 pb-3">
            <div class="col-md-6 d-flex align-item-center">
                <a href="#" class="text-white"><h6>Carousa</h6></a>&nbsp;&nbsp;&nbsp;
                <a href="#" class="text-white"><h6>Home</h6></a>&nbsp;&nbsp;&nbsp;
                <a href="#" class="text-secondary"><h6>Link</h6></a>&nbsp;&nbsp;&nbsp;
                <a href="#" class="text-secondary"><h6>Disabled</h6></a>
            </div>
            <div class="col-md-3 offset-md-3 d-flex">
                <div class="form-inline">
                    <input class="form-control" placeholder="Search" width="100px">
                </div>
                <button class="btn btn-outline-success ml-2 " type="submit">Search</button>
            </div>
        </div>
        <div class="bd-example bg-secondary">
          <div id="carouselExampleCaptions " class="carousel slide" data-ride="carousel">
              <ol class="carousel-indicators">
                  <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
                  <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
                  <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
              </ol>
              <div class="carousel-inner">
                  <div class="carousel-item active">
                      <img src="benz.png" class="d-block w-50" >
                      <div class="carousel-caption d-none d-md-block text-left">
                          <h2>Example headline</h2>
                          <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                          <button class="btn btn-primary " type="submit">Sign up today</button>
                      </div>
                  </div>
                  <div class="carousel-item">
                      <img src="benz.png" class="d-block w-50" >
                      <div class="carousel-caption d-none d-md-block text-center">
                          <h3>Another example headline.</h3>
                          <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                          <button class="btn btn-primary " type="submit">Learn More</button>
                      </div>
                  </div>
                  <div class="carousel-item">
                      <img src="benz.png" class="d-block w-50" >
                      <div class="carousel-caption d-none d-md-block text-right">
                          <h1>One more for good measure.</h1>
                          <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit</p>
                          <button class="btn btn-primary " type="submit">Browse Today </button>
                      </div>
                  </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only">Next</span>
              </a>
          </div>
        </div>
         <div class="row">
            <div class="col-md-4"></div>
            <div class="col-md-4"></div>
            <div class="col-md-4"></div>
        </div>
