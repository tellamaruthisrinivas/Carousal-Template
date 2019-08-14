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
        <div class="container mt-5">
            <div class="row text-center">
                <div class="col-md-4">
                    <img src="benz.png" class="rounded-circle width-100" >
                    <h2>Heading</h2>
                    <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod. Nullam id dolor id nibh ultricies vehicula ut id elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.</p>
                    <button class="btn btn-secondary" type="submit">View details>></button>
                </div>
                <div class="col-md-4 ">
                    <img src="benz.png" class="rounded-circle width-100" >
                    <h2>Heading</h2>
                    <p>Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Cras mattis consectetur purus sit amet fermentum. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh.</p>
                    <button class="btn btn-secondary" type="submit">View details>></button>
                </div>
                <div class="col-md-4">
                    <img src="benz.png" class="rounded-circle width-100" >
                    <h2>Heading</h2>
                    <p>Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus</p>
                    <button class="btn btn-secondary" type="submit">View details>></button>
                </div>
            </div>
            <hr class="mt-5">
            <div class="row text-center mt-5">
                <div class="col-md-6 py-5">
                    <h1>First featurette heading.<span class="text-secondary">It’ll blow your mind.</span></h1>
                    <p class="text-secondary">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                <div class="col-md-6">
                    <img src="benz.png" class="bg-secondary" height="500px" width="500px">
                </div>
            </div>
             <hr class="mt-5">
            <div class="row text-center mt-5">
                <div class="col-md-6 py-5">
                    <img src="benz.png" class="bg-secondary" height="500px" width="500px">
                </div>
                <div class="col-md-6">
                    <h1>Oh yeah, it’s that good.<span class="text-secondary">See for yourself.</span></h1>
                    <p class="text-secondary">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo.</p>
                </div>
                
            </div>
             <hr class="mt-5">
            <div class="row text-center mt-5  ">
                <div class="col-md-6 py-5">
                    <h1>And lastly, this one. <span class="text-secondary">Checkmate.</span></h1>
                    <p class="text-secondary">Donec ullamcorper nulla non metus auctor fringilla. Vestibulum id ligula porta felis euismod semper. Praesent commodo cursus magna, vel scelerisque nisl consectetur. Fusce dapibus, tellus ac cursus commodo</p>
                </div>
                <div class="col-md-6">
                    <img src="benz.png" class="bg-secondary" height="500px" width="500px">
                </div>
            </div>
            <hr class="mt-5">
            <div class="footer mt-5 "><div class="row d-flex justify-content-between">
                
                <p>
                    © 2017-2019 Company, Inc. · 
                    <a href="#">Privacy</a>
                    <a href="#">Terms</a>
                </p>
                <p >
                    <a href="#">Back to top</a>
                </p>
                </div>
            </div>
        </div>
    </div>
</body>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
