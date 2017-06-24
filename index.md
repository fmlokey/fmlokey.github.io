<!DOCTYPE html>
<html lang="en">
<head>
  <title>Mountain Ford Dealership</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
    /* Remove the navbar's default rounded borders and increase the bottom margin */
    .navbar {
      margin-bottom: 50px;
      border-radius: 0;
    }
    
	 body {
         background-image: url("blackleatherl.jpg");
         background-color: #0d0d0;
         color: white;
         font-family: "Arial", "Sans-serif";
    }  
    panel {
	    background-color: #1a1a1a;
		color: black;
		}
    
	.panel-footer {
	   background-color: #1a1a1a;
	   color: white;
	   }
	
    .panel-body {
		background-color: #1a1a1a;
		color: white;
	}	
    .carousel-inner img {
      width: 100%; /* Set width to 100% */
      margin: auto;
      min-height:200px;
	}

	/* Hide the carousel text when the screen is less than 600 pixels wide */
	@media (max-width: 600px) {
    .carousel-caption {
      display: none;
		}
	}
    /* Add a blackish background color and some padding to the footer */
    footer {
      background-color: #0d0d0;
      padding: 25px;
    }
  </style>
</head>
<body>

<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
	  <li data-target="#myCarousel" data-slide-to="2"></li>
	  <li data-target="#myCarousel" data-slide-to="3"></li>
	  <li data-target="#myCarousel" data-slide-to="4"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="source.png" alt="Image" style="height:300px;width:auto">
        <div class="carousel-caption">
          <h3>32 Models on the Lot</h3>
          <p>Come Test Drive One Today</p>
        </div>
      </div>
	  
	  <div class="item">
        <img src="f250.jpg" alt="Image" style="height:300px;width:auto">
        <div class="carousel-caption">
          <h3>22 Models on the Lot</h3>
          <p>Come Test Drive One Today</p>
        </div>
      </div>
	  
	  <div class="item">
        <img src="ruxer-ford-f150-2555x593.jpg" alt="Image" style="height:300px;width:auto">
        <div class="carousel-caption">
          <h3>17 Models on the Lot</h3>
          <p>Come Test Drive One Today</p>
        </div>
      </div>
	  
      <div class="item">
        <img src="2016-Explorer-SUV_04.jpg" alt="Image" style="height:300px;width:auto" >
        <div class="carousel-caption">
          <h3>25 Models on the Lot</h3>
          <p>Come Test Drive One Today</p>
        </div>
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
</div>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">
	  <img src="fordemblem.jpg" alt="Ford" class="img-circle" height=100% width="auto"></a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#">Onsite Vehicle Sales</a></li>
		<li><a href="#">Online Vehicle Sales</a></li>
        <li><a href="#">Service</a></li>
        <li><a href="#">Ford Home</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#"><span class="glyphicon glyphicon-user"></span> Your Account</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">F250 TRUCKS</div>
        <div class="panel-body"><img src="24522.jpg" class="img-responsive" style="height:150px" float="center" alt="Image" */ image from page  https://www.cargurus.com/Cars/new/nl-New-Ford-F-250-Super-Duty-Philadelphia-d341_L30895  */ ></div>
        <div class="panel-footer">$32,535 Starting MSRP<br>$472 Monthly Lease<br>Fuel Economy based on fuel type/model<br>Seating for 6<br>Click for more information</div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">FOCUS</div>
        <div class="panel-body"><img src="New-model-of-Fordfocus.jpg" class="img-responsive" style="height:150px" float="center" alt="Image" */ image from page  http://cars-life.net/ford-focus-4-2017-model-year/  */ ></div>
        <div class="panel-footer">$17,225 Starting MSRP<br>$189 Monthly Lease<br>26/36 EPA-Estimated MPG City/Hwy<br>Seating for 5<br>Click for more information</div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">FUSION</div>
        <div class="panel-body"><img src="2017-ford-fusion-se-fwd-sedan-angular-front.png" class="img-responsive" style="height:150px" floats="center" alt="Image" */ image from page  http://cars-life.net/ford-focus-4-2017-model-year/  */  ></div>
        <div class="panel-footer">$22,120 Starting MSRP<br>$199 Monthly Lease<br>21/32 EPA-Estimated MPG City/Hwy<br>Seating for 5<br>Click for more information</div>
      </div>
    </div>
  </div>
</div><br>

<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">F150 TRUCKS</div>
        <div class="panel-body"><img src="2017-Ford-F-Series-F-150.jpg" class="img-responsive" style="height:150px" float="center" alt="Image" /*  image from page http://popularamericancars.com/2017-ford-f-series/  */></div>
        <div class="panel-footer">$26,540 Starting MSRP<br>$299 Monthly Lease<br>18/25EPA-Estimated MPG City/Hwy<br>Seating for 6<br>Click for more information</div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">MUSTANGS</div>
        <div class="panel-body"><img src="2017-Ford-Mustang-Mach-1-Engine-and-Performance6.jpg" class="img-responsive" style="height:150px" float="center" alt="Image" */ image from page http://2017releasedates.com/2017-ford-mustang-mach-1-engine-and-performance/  */   ></div>
        <div class="panel-footer">$24,915 Starting MSRP<br>$303 Monthly Lease<br>18/27 EPA-Estimated MPG City/Hwy<br>Seating for 4<br>Click for more information</div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">EXPLORER</div>
        <div class="panel-body"><img src="2017-Ford-Explorer-XLT-Sport-Changes.jpg" class="img-responsive" style="height:150px" float="center" alt="Image" */ image from page http://www.newfordredesign.com/2017-ford-explorer-xlt-sport-2016-chicago-auto-show/ */ ></div>
        <div class="panel-footer">$31,660 Starting MSRP<br>$332 Monthly Lease<br>17/24 EPA-Estimated MPG City/Hwy<br>Seating for 7<br>Click for more information</div>
      </div>
    </div>
  </div>
</div><br><br>

<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">TAKE OUR SURVEY</div>
        <div class="panel-body"><a href="http://ps11.pstcc.edu/~c2375a01/lab3Lokey.html"  role="button"><img src="fordemblem.jpg" class="img-responsive" style="height:150px" float="center" alt="Image"  */ image from page http://buypanicdisorderpill.com/files8/new-ford-logo-black.html */ ></a></div>
        <div class="panel-footer">Help us better serve you by taking our survey.</div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">CONTACT ONLINE SALES</div>
        <div class="panel-body">Online Sales: Thomas Harvey<br>Phone: 687-987-5678<br>Email: ThomasHarveyFord@gmail.com<br>
			Online Sales: Bonnie Smith<br>Phone: 687-987-5664<br>Email: BonnieSmithFord@gmail.com<br><br>Email: OnlineSalesFord@gmail.com</div>
        <div class="panel-footer">Online Sales Open 24/7</div>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">IN THE NEWS</div>
        <div class="panel-body"><img src="inthenews.jpg" class="img-responsive" style="height:150px" floats="center" alt="Image" */ image from page https://mfour.com/tag/mobile/  */ ></div>
        <div class="panel-footer">See what is being said about us in the media and press.</div>
      </div>
    </div>
  </div>
</div><br>

<footer class="container-fluid text-center">
  <p>Online Store Copyright</p>
  <form class="form-inline">To be contacted by a sales associate:
    <input type="email" class="form-control" size="50" placeholder="Email Address">
    <button type="button" class="btn btn-danger">Contact Me</button>
  </form>
</footer>

</body>
</html>

