# TestHTML-FILES-AS-MD-FIILES
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Bootstrap 4 theme for developers and startups</title>
    <!-- Meta -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bootstrap 4 landing page template for developers and startups">
    <meta name="author" content="Xiaoying Riley at 3rd Wave Media">    
    <link rel="shortcut icon" href="favicon.ico">  
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'>
    <!-- FontAwesome JS -->
    <script defer src="https://use.fontawesome.com/releases/v5.1.0/js/all.js" integrity="sha384-3LK/3kTpDE/Pkp8gTNp2gR/2gOiwQ6QaO7Td0zV76UFJVhqLl4Vl3KL1We6q6wR9" crossorigin="anonymous"></script>
    <!-- Global CSS -->
    <link rel="stylesheet" href="assets/plugins/bootstrap/css/bootstrap.min.css">   
    <!-- Theme CSS -->  
    <link id="theme-style" rel="stylesheet" href="assets/css/styles.css">
    
</head> 

<body>
    <!-- ******HEADER****** --> 
    <header id="header" class="header">  
        <div class="container">       
            <h1 class="logo">
                <a class="scrollto" href="#hero">
                    <span class="logo-icon-wrapper"><img class="logo-icon" src="assets/images/logo-icon.svg" alt="icon"></span>
                    <span class="text"><span class="highlight">APP</span>KIT</span></a>
            </h1><!--//logo-->
            <nav class="main-nav navbar-expand-md float-right navbar-inverse" role="navigation">
                
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-collapse">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button><!--//nav-toggle-->
                
                <div id="navbar-collapse" class="navbar-collapse collapse">
                    <ul class="nav navbar-nav">
                        <li class="nav-item"><a class="active nav-link scrollto" href="#about">About</a></li>
                        <li class="nav-item"><a class="nav-link scrollto" href="#testimonials">Testimonials</a></li>
                        <li class="nav-item"><a class="nav-link scrollto" href="#features">Features</a></li>                        
                        <li class="nav-item"><a class="nav-link scrollto" href="#team">Team</a></li>
                        <li class="nav-item"><a class="nav-link scrollto" href="#pricing">Pricing</a></li>
                        <li class="nav-item"><a class="nav-link scrollto" href="#contact">Contact</a></li>
                    </ul><!--//nav-->
                </div><!--//navabr-collapse-->
            </nav><!--//main-nav-->                     
        </div><!--//container-->
    </header><!--//header-->
    
    <div id="hero" class="hero-section">
        
        <div id="hero-carousel" class="hero-carousel carousel carousel-fade slide" data-ride="carousel" data-interval="10000">
            
            <div class="figure-holder-wrapper">
        		<div class="container">
            		<div class="row justify-content-end">
                		<div class="figure-holder">
                	        <img class="figure-image img-fluid" src="assets/images/imac.png" alt="image" />
                        </div><!--//figure-holder-->
            		</div><!--//row-->
        		</div><!--//container-->
    		</div><!--//figure-holder-wrapper-->
            
			<!-- Indicators -->
			<ol class="carousel-indicators">
				<li class="active" data-slide-to="0" data-target="#hero-carousel"></li>
				<li data-slide-to="1" data-target="#hero-carousel"></li>
				<li data-slide-to="2" data-target="#hero-carousel"></li>
			</ol>
			
			<!-- Wrapper for slides -->
			<div class="carousel-inner">
    			
				<div class="carousel-item item-1 active">
					<div class="item-content container">
    					<div class="item-content-inner">
    				        
				            <h2 class="heading">AppKit Landing is the perfect landing page template <br class="d-none d-md-block">for your product</h2>
				            <p class="intro">It helps you to build a beautiful and effective landing page to promote your product or side project!</p>
				            <a class="btn btn-primary btn-cta" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">Download Now</a>
    				        
    					</div><!--//item-content-inner-->
					</div><!--//item-content-->
				</div><!--//item-->
				
				<div class="carousel-item item-2">
					<div class="item-content container">
						<div class="item-content-inner">
    				        
				            <h2 class="heading">Bootstrap Lover?</h2>
				            <p class="intro">AppKit Landing is built on Bootstrap 4 and SASS so it's quick and easy to customise!</p>
				            <a class="btn btn-primary btn-cta" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">Find out more</a>
    				        
    					</div><!--//item-content-inner-->
					</div>
				</div><!--//item-->
				
				<div class="carousel-item item-3">
					<div class="item-content container">
						<div class="item-content-inner">
    				        
				            <h2 class="heading">Ready to build outstanding product?</h2>
				            <p class="intro">Get AppKit Landing today and it will help you promote your product effectively!</p>
				            <a class="btn btn-primary btn-cta" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">Get Started</a>
    				        
    					</div><!--//item-content-inner-->
					</div>
				</div><!--//item-->
			</div><!--//carousel-inner-->

		</div><!--//carousel-->
    </div><!--//hero-->
    
    <div id="about" class="about-section">
        <div class="container text-center">
            <h2 class="section-title">Why Use AppKit Landing?</h2>
            <p class="intro">Appkit Landing uses modern front-end technologies and is packed with useful components and widgets to speed up your development</p>
            <ul class="technologies list-inline">
                <li class="list-inline-item"><img src="assets/images/logo-html5.svg" alt="HTML5"></li>
                <li class="list-inline-item"><img src="assets/images/logo-css3.svg" alt="CSS3"></li>
                <li class="list-inline-item"><img src="assets/images/logo-bootstrap.svg" alt="Bootstrap"></li>
                <li class="list-inline-item"><img src="assets/images/logo-sass.svg" alt="Sass"></li>
                <li class="list-inline-item"><img src="assets/images/logo-jquery.svg" alt="jQuery"></li>
            </ul>
            
            <div class="items-wrapper row">
                <div class="item col-md-4 col-12">
                    <div class="item-inner">
                        <div class="figure-holder">
                            <img class="figure-image" src="assets/images/figure-1.png" alt="image">
                        </div><!--//figure-holder-->
                        <h3 class="item-title">Benefit Lorem Ipsum</h3>
                        <div class="item-desc">
                            List one of your product's benefits here. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
                        </div><!--//item-desc-->
                    </div><!--//item-inner-->
                </div><!--//item-->
                <div class="item col-md-4 col-12">
                    <div class="item-inner">
                        <div class="figure-holder">
                            <img class="figure-image" src="assets/images/figure-2.png" alt="image">
                        </div><!--//figure-holder-->
                        <h3 class="item-title">Benefit Corporis</h3>
                        <div class="item-desc">
                            List one of your product's benefits here. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. </div><!--//item-desc-->
                    </div><!--//item-inner-->
                </div><!--//item-->
                <div class="item col-md-4 col-12">
                    <div class="item-inner">
                        <div class="figure-holder">
                            <img class="figure-image" src="assets/images/figure-3.png" alt="image">
                        </div><!--//figure-holder-->
                        <h3 class="item-title">Benefit Imperdiet</h3>
                        <div class="item-desc">
                            List one of your product's benefits here. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. </div><!--//item-desc-->
                    </div><!--//item-inner-->
                </div><!--//item-->
            </div><!--//items-wrapper-->
        </div><!--//container-->
    </div><!--//about-section-->
    
    <div id="testimonials" class="testimonials-section">
        <div class="container">
            <h2 class="section-title text-center">Many Happy Customers</h2>
            <div class="item mx-auto">
                <div class="profile-holder">
                    <img class="profile-image" src="assets/images/profile-1.png" alt="profile">
                </div>
                <div class="quote-holder">
                    <blockquote class="quote">
                        <p>Testimonial goes here Donec felis odio, sagittis eu cursus ac, porttitor eu purus. In a bibendum dui. Nullam id est sed felis rutrum tincidunt eu nec nisi morbi euismod semper neque sed lobortis.</p>
                        <div class="quote-source">
                            <span class="name">@JohnK,</span>
                            <span class="meta">San Francisco</span>
                        </div><!--//quote-source-->
                    </blockquote>
                </div><!--//quote-holder-->
            </div><!--//item-->
            <div class="item item-reversed mx-auto">
                <div class="profile-holder">
                    <img class="profile-image" src="assets/images/profile-2.png" alt="profile">
                </div>
                <div class="quote-holder">
                    <blockquote class="quote">
                        <p>Testimonial goes here fermentum sed pharetra in, aliquet sodales quam. Ut sed turpis quis orci viverra aliquet interdum ut ipsum. </p>
                        <div class="quote-source">
                            <span class="name">@LisaWhite,</span>
                            <span class="meta">London</span>
                        </div><!--//quote-source-->
                    </blockquote>
                </div><!--//quote-holder-->
            </div><!--//item-->
            <div class="item mx-auto">
                <div class="profile-holder">
                    <img class="profile-image" src="assets/images/profile-3.png" alt="profile">
                </div>
                <div class="quote-holder">
                    <blockquote class="quote">
                        <p>Testimonial goes here vestibulum non hendrerit lorem, luctus tincidunt erat. Sed pharetra aliquam posuere. Pellentesque sollicitudin.</p>
                        <div class="quote-source">
                            <span class="name">@MattH,</span>
                            <span class="meta">Berlin</span>
                        </div><!--//quote-source-->
                    </blockquote>
                </div><!--//quote-holder-->
            </div><!--//item-->
            <div class="item item-reversed mx-auto">
                <div class="profile-holder">
                    <img class="profile-image" src="assets/images/profile-4.png" alt="profile">
                </div>
                <div class="quote-holder">
                    <blockquote class="quote">
                        <p>Testimonial goes here lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis</p>
                         <div class="quote-source">
                            <span class="name">@RyanW,</span>
                            <span class="meta">Paris</span>
                        </div><!--//quote-source-->
                    </blockquote>
                    
                </div><!--//quote-holder-->
            </div><!--//item-->
        </div><!--//container-->
    </div><!--//testimonials-->
    
    <div id="features" class="features-section">
        <div class="container text-center">
            <h2 class="section-title">Discover Features</h2>
            <p class="intro">You can use this section to list your product features. The screenshots used here were taken from <a href="https://www.uxfordev.com/" target="_blank">Bootstrap admin theme AppKit</a></p>
            
            <div class="tabbed-area row">
                
                <!-- Nav tabs -->
                <div class="feature-nav nav nav-pill flex-column col-lg-4 col-md-6 col-12 order-0 order-md-1" role="tablist" aria-orientation="vertical">
                     <a class="nav-link active mb-lg-3" href="#feature-1" aria-controls="feature-1" data-toggle="pill" role="tab" aria-selected="true"><i class="fas fa-magic"></i>20+ Use Case-based App Pages</a>
                     <a class="nav-link mb-lg-3" href="#feature-2" aria-controls="feature-2" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-cubes"></i>100+ Components and Widgets</a>
                     <a class="nav-link mb-lg-3" href="#feature-3" aria-controls="feature-3" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-chart-bar"></i>Useful Chart Libraries</a>
                     <a class="nav-link mb-lg-3" href="#feature-4" aria-controls="feature-4" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-code"></i>Valid HTML5 + CSS3</a>
                     <a class="nav-link mb-lg-3" href="#feature-5" aria-controls="feature-5" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-rocket"></i>Built on Bootstrap</a>
                     <a class="nav-link mb-lg-3" href="#feature-6" aria-controls="feature-6" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-mobile-alt"></i>Fully Responsive</a>
                     <a class="nav-link mb-lg-3" href="#feature-7" aria-controls="feature-7" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-star"></i>Beautiful UI</a>
                     <a class="nav-link mb-lg-3" href="#feature-8" aria-controls="feature-8" data-toggle="pill" role="tab" aria-selected="false"><i class="fas fa-heart"></i>Free Updates &amp; Support</a>                   
                </div>
                
                <!-- Tab panes -->
                <div class="feature-content tab-content col-lg-8 col-md-6 col-12 order-1 order-md-0">
                    <div role="tabpanel" class="tab-pane fade show active" id="feature-1">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-1.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-2">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-2.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-3">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-3.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-4">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-4.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-5">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-5.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-6">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-6.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-7">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-7.png" alt="screenshot" ></a>
                    </div>
                    <div role="tabpanel" class="tab-pane fade" id="feature-8">
                        <a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank"><img class="img-fluid" src="assets/images/feature-8.png" alt="screenshot" ></a>
                    </div>
                    
                </div><!--//feature-content-->

                
            </div><!--//tabbed-area-->
            
        </div><!--//container-->
    </div><!--//features-->
    
    <div class="team-section" id="team">
        <div class="container text-center">
            <h2 class="section-title">Our Team</h2>
            <div class="story">
                <p>Introduce your team here. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.  Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue</p>
            </div>
            <div class="members-wrapper row">
                <div class="item col-md-6 col-12">
                    <div class="item-inner">
                        <div class="profile mb-2">
                            <img class="profile-image" src="assets/images/team-1.png" alt="Xiaoying Riley" />
                        </div>
                        
                        <div class="member-content">
                            <h3 class="member-name">Xiaoying Riley</h3>
                            <div class="member-title">Full-Stack Designer</div>
                            <ul class="social list-inline">
                                <li class="list-inline-item"><a class="twitter" href="https://twitter.com/3rdwave_themes" target="_blank"><i class="fab fa-twitter"></i></a></li>
                                
                                <li class="list-inline-item"><a class="facebook" href="https://www.facebook.com/3rdwavethemes/" target="_blank"><i class="fab fa-facebook-f"></i></a></li>
                                <li class="list-inline-item"><a class="github" href="https://github.com/xriley" target="_blank"><i class="fab fa-github"></i></a></li>
                                <li class="list-inline-item"><a class="dribbble" href="https://dribbble.com/Xiaoying" target="_blank"><i class="fab fa-dribbble"></i></a></li>
                               <li class="list-inline-item"><a class="medium" href="https://uk.linkedin.com/in/xiaoying" target="_blank"><i class="fab fa-medium-m"></i></a></li>
                                
                            </ul>
                            <div class="member-desc">
                               <p>Xiaoying is the UX/UI designer behind AppKit Landing. She makes <a href="https://themes.3rdwavemedia.com/bootstrap-templates/free/" target="_blank">free Bootstrap themes</a> for developers. You can find her sharing useful UX and webdev related content on <a href="https://twitter.com/3rdwave_themes" target="_blank">Twitter</a> and <a href="https://www.facebook.com/3rdwavethemes/" target="_blank">Facebook</a>. Follow her if you like what she does!</p>
                            </div><!--//member-desc-->
                        </div><!--//member-content-->
                    </div><!--//item-inner-->
                </div><!--//item-->
                <div class="item col-md-6 col-12">
                    <div class="item-inner">
                        <div class="profile mb-2">
                            <img class="profile-image" src="assets/images/team-2.png" alt="Tom Najdek" />
                        </div>
                        
                        <div class="member-content">
                            <h3 class="member-name">Tomasz Najdek</h3>
                            <div class="member-title">Full-Stack Developer</div>
                            <ul class="social list-inline">
                                <li class="list-inline-item"><a class="twitter" href="http://twitter.com/tnajdek" target="_blank"><i class="fab fa-twitter"></i></a></li>
                                <li class="list-inline-item"><a href="https://www.doppnet.com/" target="_blank"><i class="fas fa-globe"></i></a></li>
                                <li class="list-inline-item"><a class="github" href="https://github.com/tnajdek" target="_blank"><i class="fab fa-github"></i></a></li>
                               
                                
                            </ul>
                            <div class="member-desc">
                                <p>Tom is a full-stack developer specialising in building large, scalable and user-friendly web apps. Follow him on <a href="https://twitter.com/tnajdek" target="_blank">Twitter</a> for fresh developer tips and check out his <a href="https://github.com/tnajdek" target="_blank">Github</a> for useful open-source tools.
</p>
                            </div><!--//member-desc-->
                        </div><!--//member-content-->
                    </div><!--//item-inner-->
                </div><!--//item-->
            </div><!--//members-wrapper-->
        </div>
    </div><!--//team-section-->
    
    <div id="pricing" class="pricing-section">
        <div class="container text-center">
            <h2 class="section-title">Pricing</h2>
            <div class="intro">AppKit Landing's future updates are 100% FREE for existing customers</div>
            <div class="pricing-wrapper row">
                <div class="item item-1 col-md-4 col-12">
                    <div class="item-inner">
                        <h3 class="item-heading">FREE<br><span class="item-heading-desc">(CC BY 3.0)</span></h3>
                        <div class="price-figure">
                            <span class="currency">$</span><span class="number">0</span>
                        </div><!--//price-figure-->
                        <ul class="list-unstyled mb-3">
	                        <li class="mb-2"><i class="fas fa-check"></i> Single installation</li>
	                        <li class="mb-2"><i class="fas fa-check"></i> Multiple installations</li>
                            <li class="mb-2"><i class="fas fa-times"></i> Use without attribution link</li>
                        </ul>
                        <div class="mb-3"><a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">License Details</a></div>
                        <a class="btn btn-cta" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/">Get it now</a>
                        
                    </div><!--//item-inner-->
                </div><!--//item-->
                <div class="item item-2 col-md-4 col-12">
                    <div class="item-inner">
                        <h3 class="item-heading">Single Application<br><span class="item-heading-desc">(Commercial License)</span></h3>
                       
                        <div class="price-figure">
                            <span class="currency">$</span><span class="number">29</span>
                        </div><!--//price-figure-->
                        <ul class="list-unstyled mb-3">
	                        <li class="mb-2"><i class="fas fa-check"></i> Single installation</li>
	                        <li class="mb-2"><i class="fas fa-times"></i> Multiple installations</li>
	                        <li class="mb-2"><i class="fas fa-check"></i> Use without attribution link</li>
                        </ul>
                        <div class="mb-3"><a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">License Details</a></div>
                        <a class="btn btn-cta" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/">Get it now</a>
                        
                    </div><!--//item-inner-->
                </div><!--//item-->
                
                <div class="item item-3 col-md-4 col-12">
                    <div class="item-inner">
                        <h3 class="item-heading">Multiple Applications<br><span class="item-heading-desc">(Commercial License)</span></h3>
                        <div class="price-figure">
                            <span class="currency">$</span><span class="number">99</span>
                        </div><!--//price-figure-->
                        <ul class="list-unstyled mb-3">
	                        <li class="mb-2"><i class="fas fa-check"></i> Single installation</li>
	                        <li class="mb-2"><i class="fas fa-check"></i> Multiple installations</li>
	                        <li class="mb-2"><i class="fas fa-check"></i> Use without attribution link</li>
                        </ul>
                        <div class="mb-3"><a href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">License Details</a></div>
                        <a class="btn btn-cta" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/" target="_blank">Get it now</a>
                        
                    </div><!--//item-inner-->
                </div><!--//item-->
            </div><!--//pricing-wrapper-->
            
        </div><!--//container-->
    </div><!--//pricing-section-->
    <div id="contact" class="contact-section">
        <div class="container text-center">
            <h2 class="section-title">Contact Us</h2>
            <div class="contact-content">
                <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis.</p>
                
            </div>
            <a class="btn btn-cta btn-primary" href="https://themes.3rdwavemedia.com/bootstrap-templates/startup/appkit-landing-free-bootstrap-theme-for-developers-and-startups/">Get in Touch</a>
            
        </div><!--//container-->
    </div><!--//contact-section-->
    
    <footer class="footer text-center">
        <div class="container">
            <!--/* This template is released under the Creative Commons Attribution 3.0 License. Please keep the attribution link below when using for your own project. Thank you for your support. :) If you'd like to use the template without the attribution, you can buy the commercial license via our website: themes.3rdwavemedia.com */-->
            <small class="copyright">Designed with <i class="fas fa-heart"></i> by <a href="https://themes.3rdwavemedia.com/" target="_blank">Xiaoying Riley</a> for developers</small>
            
            
        </div><!--//container-->
    </footer>
     
    <!-- Javascript -->          
    <script type="text/javascript" src="assets/plugins/jquery-3.3.1.min.js"></script>
    <script type="text/javascript" src="assets/plugins/bootstrap/js/bootstrap.min.js"></script>
    <script type="text/javascript" src="assets/plugins/jquery-scrollTo/jquery.scrollTo.min.js"></script>     
    <script type="text/javascript" src="assets/js/main.js"></script> 
       
</body>
</html> 

