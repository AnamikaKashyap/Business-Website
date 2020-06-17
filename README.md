//# Business-Website
<html>
<head>
<title>Business website</title>
<link rel = "stylesheet" href = "stile.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>


</head>
<body>

<!----NavigationBar---->
<section id="nav-bar">
<nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#"><img src="LOGO-Black.png" width="200px" height="200px"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#">DASHBOARD</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#about">ABOUT US</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#services">SERVICES</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#team">OUR TEAM</a>
      </li>
    <li class="nav-item">
        <a class="nav-link" href="#price">PRICE PLANS</a>
      </li>
<li class="nav-item">
        <a class="nav-link" href="#testimonials">TESTIMONIALS</a>
      </li>
<li class="nav-item">
        <a class="nav-link" href="#contact">CONTACT</a>
      </li>
   </ul>
  </div>
</nav>
</section>
   <!-----------Slider--------->
<div id = "slider">
<div id="headerSlider" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#headerSlider" data-slide-to="0" class="active"></li>
    <li data-target="#headerSlider" data-slide-to="1"></li>
    <li data-target="#headerSlider" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="GettyImages.jpg" class="d-block img-fluid" width = "100%" height="95%">
    <div class = "carousel-caption">
        <h5>How to make a Website</h5>
    </div>
</div>
    <div class="carousel-item">
      <img src="AdobeStock.jpeg" class="d-block img-fluid" width = "100%">
       <div class = "carousel-caption">
        <h5>Create Responsive Website</h5>
    </div>    
</div>
    <div class="carousel-item">
      <img src="wbsitedesign.jpg" class="d-block img-fluid" width = "100%">
    <div class = "carousel-caption">
        <h5>Business Website Design</h5>
    </div>
</div>
  </div>
  <a class="carousel-control-prev" href="#headerSlider" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#headerSlider" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>

<!----------About----------->
<section id = "about">
                            <div class = "container">
                                            <div class = "row">
<div class="col-md-6">
           <h2>About Us</h2>
                  <div class = "about-content">
                Hello Everyone , my name is Anamika Kashyap, i am a student of computer science branch,
                I am currently persuing my B.Tech from Ambalika Institute of management and technology.
                I have a lot interest in Web Development . I have created this Business Website myself 
                for further progress and development of my skills . I hope you will like it. Thankyou :)
                  </div>
                <button type = "button" class="btn btn-primary">Read more>>
                </button>
</div>
<div class="col-md-6 skills-bar">
                 <p>HTML</p>
                 <div class="progress">
                    <div class="progress-bar" style="width:80%;">80</div>
                 </div>

                 <p>CSS</p>
                 <div class="progress">
                    <div class="progress-bar" style="width:85%;">85</div>
                 </div>

                 <p>JAVASCRIPT</p>
                 <div class="progress">
                    <div class="progress-bar" style="width:75%;">75</div>
                 </div>
 
                 <p>WordPress</p>
                 <div class="progress">
                    <div class="progress-bar" style="width:50%;">50</div>
                 </div>
</div>
                                            </div>
                            </div>
</section>
<!----------Services-------------->
<section id="services">
                <div class="container">
                <h1>Our Services<h1>
                       <div class = "row services">
                             <div class="col-md-3 text-center">
                                  <div class = "icon">
                                        <i class="fa fa-desktop"></i>
                                      </div> 
                                        <h3>Web Development</h3>
                                        <p style="font-size:20px;">Lorem ipsum,
                                           or lipsum as it is sometimes known,
                                           is dummy text used in laying out print,
                                         </p>
                              </div>

                             <div class="col-md-3 text-center">
                                  <div class = "icon">
                                        <i class="fa fa-tablet"></i>
                                      </div> 
                                        <h3>App Development</h3>
                                        <p style="font-size:20px;">Lorem ipsum,
                                           or lipsum as it is sometimes known,
                                           is dummy text used in laying out print,
                                         </p>
                              </div>

                             <div class="col-md-3 text-center">
                                  <div class = "icon">
                                        <i class="fa fa-line-chart"></i>
                                      </div> 
                                        <h3>Digital Marketing</h3>
                                        <p style="font-size:20px;">Lorem ipsum,
                                           or lipsum as it is sometimes known,
                                           is dummy text used in laying out print,
                                         </p>
                              </div>

                             <div class="col-md-3 text-center">
                                  <div class = "icon">
                                        <i class="fa fa-paint-brush"></i>
                                      </div> 
                                        <h3>Graphics Designing</h3>
                                        <p style="font-size:20px;">Lorem ipsum,
                                           or lipsum as it is sometimes known,
                                           is dummy text used in laying out print,
                                         </p>
                              </div>
                
                        </div>
                 </div>
</section>
<!---------------Team Members------------------>
<section id="team">
     <div class="container">
     <h1>Our Team</h1>
        <div class="row">
            <div class="col-md-3 profile-pic text-center">
                  <div class="img-box">
                  <img src = "PIC.jpg" class="img-responsive">
                      <ul>
                          <a href="#"><li><i class="fa fa-facebook"></i></li></a>
                          <a href="#"><li><i class="fa fa-twitter"></i></li></a>
                          <a href="#"><li><i class="fa fa-linkedin"></i></li></a>
                      </ul>
                  </div>
                         <h2>Anamika Kashyap</h2>
                         <h3>Founder / CEO</h3>
                         <p>If you like this page then give your comments</p>
            </div>
            
            <div class="col-md-3 profile-pic text-center">
                  <div class="img-box">
                  <img src = "alia.jpg" class="img-responsive">
                      <ul>
                          <a href="#"><li><i class="fa fa-facebook"></i></li></a>
                          <a href="#"><li><i class="fa fa-twitter"></i></li></a>
                          <a href="#"><li><i class="fa fa-linkedin"></i></li></a>
                      </ul>
                  </div>
                         <h2>Alia Bhatt</h2>
                         <h3>Business Head</h3>
                         <p>If you like this page then give your comments</p>
            </div>

            <div class="col-md-3 profile-pic text-center">
                  <div class="img-box">
                  <img src = "sid.jpg" class="img-responsive">
                      <ul>
                          <a href="#"><li><i class="fa fa-facebook"></i></li></a>
                          <a href="#"><li><i class="fa fa-twitter"></i></li></a>
                          <a href="#"><li><i class="fa fa-linkedin"></i></li></a>
                      </ul>
                  </div>
                         <h2>Siddharth Malhotra</h2>
                         <h3>Marketing Head</h3>
                         <p>If you like this page then give your comments</p>
            </div>

            <div class="col-md-3 profile-pic text-center">
                  <div class="img-box">
                  <img src = "varun.jpg" class="img-responsive">
                      <ul>
                          <a href="#"><li><i class="fa fa-facebook"></i></li></a>
                          <a href="#"><li><i class="fa fa-twitter"></i></li></a>
                          <a href="#"><li><i class="fa fa-linkedin"></i></li></a>
                      </ul>
                  </div>
                         <h2>Varun Dhawan</h2>
                         <h3>UI Designer</h3>
                         <p>If you like this page then give your comments</p>
            </div>
        </div>
     </div>
</section>
<!------------promo---------------->
   <section id="promo">
     <div class ="container">
       <p>Get free domain name and Web Hosting</p>
       <a href = "#" class = "btn btn-primary">Contact Us</a>
     </div>
   </section>
<!-------------Price plans------------>
<section id = "price">
  <div class = "container">
    <h1>Price Plans</h1>
    <div class="row">
    <div class="col-md-3">
      <div class="single-price">
      <div class="price-head">
        <h2>Free</h2>
        <p>$0/<span>month</span></p>
      </div>
      <div class ="price-content">
        <ul>
          <li><i class="fa fa-check-circle"></i>5GB Space</li>
          <li><i class="fa fa-check-circle"></i>10GB Bandwidth</li>
          <li><i class="fa fa-times-circle"></i>15 Email Account</li>
          <li><i class="fa fa-times-circle"></i>Unlimited Domain</li>
          <li><i class="fa fa-times-circle"></i>Unlimited Support</li>
        </ul>
      </div>
      <div class = "price-button">
      <a class="buy-btn" href="#">Join Free</a>
      </div>
      </div>
    </div>



    <div class="col-md-3">
      <div class="single-price">
      <div class="price-head">
        <h2>Start up</h2>
        <p>$10/<span>month</span></p>
      </div>
      <div class ="price-content">
        <ul>
          <li><i class="fa fa-check-circle"></i>10GB Space</li>
          <li><i class="fa fa-check-circle"></i>100GB Bandwidth</li>
          <li><i class="fa fa-check-circle"></i>15 Email Account</li>
          <li><i class="fa fa-times-circle"></i>Unlimited Domain</li>
          <li><i class="fa fa-times-circle"></i>Unlimited Support</li>
        </ul>
      </div>
      <div class = "price-button">
      <a class="buy-btn" href="#">Buy Now</a>
      </div>
      </div>
    </div>


    <div class="col-md-3">
      <div class="single-price">
      <div class="price-head">
        <h2>Business Plan</h2>
        <p>$50/<span>month</span></p>
      </div>
      <div class ="price-content">
        <ul>
          <li><i class="fa fa-check-circle"></i>20GB Space</li>
          <li><i class="fa fa-check-circle"></i>200GB Bandwidth</li>
          <li><i class="fa fa-check-circle"></i>50 Email Account</li>
          <li><i class="fa fa-check-circle"></i>Unlimited Domain</li>
          <li><i class="fa fa-times-circle"></i>Unlimited Support</li>
        </ul>
      </div>
      <div class = "price-button">
      <a class="buy-btn" href="#">Buy Now</a>
      </div>
      </div>
    </div>


    <div class="col-md-3">
      <div class="single-price">
      <div class="price-head">
        <h2>Advanced</h2>
        <p>$100/<span>month</span></p>
      </div>
      <div class ="price-content">
        <ul>
          <li><i class="fa fa-check-circle"></i>20GB Space</li>
          <li><i class="fa fa-check-circle"></i>Unlimited Bandwidth</li>
          <li><i class="fa fa-check-circle"></i>Unlimited Account</li>
          <li><i class="fa fa-check-circle"></i>Unlimited Domain</li>
          <li><i class="fa fa-check-circle"></i>Unlimited Support</li>
        </ul>
      </div>
      <div class = "price-button">
      <a class="buy-btn" href="#">Buy Now</a>
      </div>
      </div>
    </div>


    </div>  
 </div>
</section>

<!------------Testiminials--------------->
<section id = "testimonials">
    <div class = "container">
      <h1>Testimonials</h1>
      <p class="text-center">Subscribe Our Website to get latest updates</p>
    </div>
    <div class = "row">
      <div class = "col-md-4 text-center">
        <div class = "profile"><img src = "anju.jpg" class = "user">
        <blockquote>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                Ut enim ad minim veniam,
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
       </blockquote>
        <h3>Anju Choudhary <span>Co Founder at XYZ</span></h3>
        </div>
      </div>

<div class = "col-md-4 text-center">
        <div class = "profile"><img src = "PIC.jpg" class = "user">
        <blockquote>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                Ut enim ad minim veniam,
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </blockquote>
        <h3>Anamika Kashyap <span>Founder /CEO at XYZ</span></h3>
        </div>
      </div>

<div class = "col-md-4 text-center">
        <div class = "profile"><img src = "aparna.jpg" class = "user">
        <blockquote>Lorem ipsum dolor sit amet,
                consectetur adipiscing elit,
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                Ut enim ad minim veniam,
                quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </blockquote>
        <h3>Aparna Srivastava <span>Manager at XYZ</span></h3>
        </div>
      </div>

      </div>
    </div>
</section>
<!-------------Get in Touch----------------->
<section id = "contact">
  <div class ="container">
  <h1>Get in touch</h1>
    <div class ="row">

      <div class ="col-md-6">
        <form class ="contact-form">
        <div class="form-group">
        <input type ="text" class ="form-control" placeholder ="Your-name">
        </div>
        
        <div class="form-group">
        <input type ="number" class ="form-control" placeholder ="Phone no.">
        </div>

        <div class="form-group">
        <input type ="email" class ="form-control" placeholder ="Email id">
        </div>

        <div class="form-group">
        <textarea class ="form-control" rows="4" placeholder ="Your-Message"></textarea>
        </div>

        <button type = "submit" class ="btn btn-primary">SEND MESSAGE</button>

        </form>
      </div>
       <div class ="col-md-6 contact-info">
         <div class= "follow"><b>Address:</b><i class="fa fa-map-marker"></i>XYZ Road, Thakurganj, Lucknow India</div>
         <div class= "follow"><b>Phone:</b><i class="fa fa-phone"></i>+1 1234567890</div>
         <div class= "follow"><b>Email:</b><i class="fa fa-envelop-o"></i>anamika@website.com</div>
         <div class= "follow"><label><b>Get social:</b></label>
          <a href = "#"><i class="fa fa-facebook"></i></a> 
          <a href = "#"><i class="fa fa-youtube-play"></i></a> 
          <a href = "#"><i class="fa fa-twitter"></i></a> 
          <a href = "#"><i class="fa fa-google-plus"></i></a> 
         </div>
      
       </div>
    </div>
  </div>
</section>
                      <!--------------Footer------------>
<section id = "footer">
<div class = "container text-center">
  <p>Made With <i class="fa fa-heart-o"></i> by Anamika Kashyap</p>
<div>
</section>
<!------------footer end--------------->
<script>

</script>
</body>
</html>












