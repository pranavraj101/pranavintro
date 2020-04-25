<!DOCTYPE html>
<html>

<head>
	<title>Pranav Raj</title>
	<link rel="stylesheet" type="text/css" href="projectstyle.css">
	<!--BootStrap-->
	<meta charset="utf-8">
	<meta name="viewport" content= width="150px" height="150px"e width="150px" height="150px"ial-scale=1, shrink-to-fit=no">

	<!-- Bootstrap CSS -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
		integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
		<script src='https://kit.fontawesome.com/a076d05399.js'></script>

	<!--Font-->
	<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@800&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Caveat:wght@700&display=swap" rel="stylesheet">
</head>

<body>
	<!--NavBar-->

	<nav class="navbar  navbar-expand-lg fixed-top navbar-dark bg-dark">
		<a class="navbar-brand" href="#">Pranav Raj</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
			aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
		</button>

		<div class="collapse navbar-collapse" id="navbarSupportedContent">
			<ul class="navbar-nav mr-auto">
				<li class="nav-item active">
					<a class="nav-link" href="#Home">Home <span class="sr-only">(current)</span></a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#About">About Me</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#Projects">My Projects</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#Blog">My Blog</a>
				</li>

			</ul>
			<!--<form class="form-inline my-2 my-lg-0">
				<input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
				<button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
			</form>-->
		</div>
	</nav>

	<!--Home-->
	<a name="Home"></a>
	<section class="design" class="container">
		<h2>Hi Guys, <br>I am Pranav Raj</h2>

		<h1><b>Front End Web Developer</b></h1>
		<span class="sq"></span>
		<!--For the the underline-->

		<br>
		<button type="button" id="btn1" class="btn btn-primary btn-link btn-lg ">
			<a href="http://www.google.co.in" >My Resume</a>
		</button>
		<button type="button" id="btn1" class="btn btn-primary btn-link btn-lg ">
			<a href="mailto:sinhapranavraj10142@gmail.com">Hire Me</a>
		</button>
	</section>



	<!--About Me-->
	<a name="About"></a>
	<br>
	<br>
	<br>
	<br>
	<br>
	<section id="About-Me" class="conr" id="about-me">
		<h2 class="text-center"> ABOUT </h2>
		<hr>
		<div class="row about">
			<div class="col-sm-3">
				<div class="container">
					<img class="img-fluid img-responsive" id="icon" src="https://image.flaticon.com/icons/svg/763/763812.svg" width="150px" height="150px">
					<h2 class="text about-content ">Fast</h2>
				</div>
				<p >Fast load times and lag free interaction,<br> my highest priority.</p>
			</div>
			<div class="col-sm-3">
				<div class="container">
					<img class="img-fluid img-responsive" id="icon" src="https://image.flaticon.com/icons/svg/2777/2777213.svg" width="150px" height="150px">
					<h2 class="text about-content" style="align-items: center;">Responsive</h2>
				</div>
				<p >My Layout will work on <br> any dive, big or small</p>
			</div>
			<div class="col-sm-3">
				<div class="container">
					<img class="img-fluid img-responsive" id="icon" src="https://www.flaticon.com/premium-icon/icons/svg/1492/1492658.svg" width="150px" height="150px">
					<h2 class="text about-content">Intuitive</h2>
				</div>
				<p >Strong preference for easy to use, <br> intuitive UX/UI</p>
			</div>
			<div class="col-sm-3">
				<div class="container">
					<img class="img-fluid img-responsive" id="icon" src="https://image.flaticon.com/icons/svg/758/758858.svg" width="150px" height="150px">
					<h2 class="text about-content">Dynamic</h2>
				</div>
				<p>Websites don't have to be static ,<br> I love making pages come to life.</p>
			</div>
		</div>
	<section class="container">
	<div class="row">
		<div class="col-sm-6">
			<img src="MySkills.png" alt="MySkills" class="img-fluid img-responsive">
		</div>
		<div class="about-design col-sm-6">
			<h2>About Me</h2>
			<p id="about-design">A passinate coder who wants <br> to rule the world with his code</p>
		</div>
		
	</div>
	</section>

	<!---Projects--->
	<a name="Projects"></a>
	<div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
		<ol class="carousel-indicators">
		  <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
		  <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
		  <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
		</ol>
		<div class="carousel-inner">
		  <div class="carousel-item active">
			<img src="https://images.unsplash.com/photo-1522542550221-31fd19575a2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" class="d-block w-100" alt="..." style="height: 100vh;">
			<div class="carousel-caption d-none d-md-block">
			  <h5 style="color: #333333;">Web Developer</h5>
			  <p style="color: #333333;">Working on a project for web development </p>
			</div>
		  </div>
		  <div class="carousel-item">
			<img src="https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" class="d-block w-100" alt="..." style="height: 100vh;">
			<div class="carousel-caption d-none d-md-block">
			  <h5>Android App development</h5>
			  <p>Working on a project for android app development.</p>
			</div>
		  </div>
		  <div class="carousel-item">
			<img src="https://images.unsplash.com/photo-1535378917042-10a22c95931a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1331&q=80" class="d-block w-100" alt="..." style="height: 100vh;">
			<div class="carousel-caption d-none d-md-block">
			  <h5>Artificial Intelligence</h5>
			  <p>Also working on a project based on Artificial Intelligence.</p>
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
<!----My Blog---->
	  <a name="Blog"></a>
	  <div class="container marketing blog-design">
		  <br><br><br><br>
		  <h3>My Blog</h3>
		  <br><br><br>
		<div class="row">
			<div class="col-lg-6">
			<img class="bd-placeholder-img " src="https://image.flaticon.com/icons/svg/2554/2554756.svg" alt="" style="width: 150px;">
			<br><br><br>
			<h4>The Educated Designer</h4>
			<br><br>
			<p class="blog">"With such a useful skills so interesting,so different, and yet so intrinsically connected, how could anyone choose to remain ignorant and still continue to thrive as a designer"</p>
			<br><br>
			<p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
			</div><!-- /.col-lg-4 -->
			<div class="col-lg-6">
			<img class="bd-placeholder-img " src="https://image.flaticon.com/icons/svg/1705/1705271.svg" alt="" style="width: 150px;">
			<br><br><br>
			<h4>Why Some Project Just Go Right</h4>
			<br><br>
			<p class="blog">"Like many web designers, I have spent a lot of time in worring why project go worng. Perhaps we should be asking what makes a project successful"</p>
			<br><br>
			<p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
			</div><!-- /.col-lg-4 -->
			<!--<div class="col-lg-4">
			<svg class="bd-placeholder-img rounded-circle img-svg3" width="140" height="140" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: 140x140"><title>Placeholder</title><rect width="100%" height="100%" fill="#777"></rect><text x="50%" y="50%" fill="#777" dy=".3em">140x140</text></svg>
			<h2>Heading</h2>
			<p>Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
			<p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
			</div></.col-lg-4 -->
		</div>
		</div>
		<br><br><br><br>
		
		<!---Footer--->
		<footer>
        	<div class="footer-top">
		        <div class="container">
		        	<div class="row">
		        		<div class="col-md-4 col-lg-4 footer-about wow fadeInUp animated" style="visibility: visible; animation-name: fadeInUp;">
		        			<p>
		        				
		        			</p>
	                    </div>
		        		<div class="col-md-4 col-lg-4 offset-lg-1 footer-contact wow fadeInDown animated" style="visibility: visible; animation-name: fadeInDown;">
		        			<h3>Contact</h3>
		                	<p><i class="fas fa-map-marker-alt"></i> Begusarai,Bihar,India</p>
		                	<p><i class="fas fa-phone"></i> Phone:+91 ***** *****</p>
		                	<p><i class="fas fa-envelope"></i> Email: <a href="mailto:sinhapranavraj10142@gmail.com">sinhapranavraj10142@gmail.com</a></p>
	                    </div>
	                    <div class="col-md-4 col-lg-3 footer-social wow fadeInUp animated" style="visibility: visible; animation-name: fadeInUp;">
	                    	<h3>Follow me</h3>
	                    	<p> 
								<a href="https://twitter.com/PranavR10857764"><i class="fab fa-twitter-square"></i></a> 
								<a href="https://github.com/pranavraj101"><i class="fab fa-github"></i></a> 
								<a href="https://www.instagram.com/thepranavsinha/"><i class="fab fa-instagram"></i></a> 
								<a href="https://www.linkedin.com/in/pranav-raj-4541b1194"><i class="fab fa-linkedin"></i></a>
	                    	</p>
	                    </div>
		            </div>
		        </div>
	        </div>
	        <div class="footer-bottom">
	        	<div class="container">
	        		<div class="row" >
						<div class="col-sm-4"></div>
						<div class="col-sm-4"></div>
						<div class="col-sm-4">
						   Created with &#128151; by Pranav Raj
						</div>
	           		</div>
	        	</div>
	        </div>
        </footer>
<!---Jscripts-->
	<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>

</body>

</html>
