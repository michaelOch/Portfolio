<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <!-- Bootstrap -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <!-- Animate CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- Custom Styles -->
    <link rel="stylesheet" href="./css/index.css" >
</head>
<body>
    <header class="header-section">
        <div class="container header-section_upper">
            <div class="d-flex align-items-center position-relative header-section_upper-wrapper">
                <div class="mr-2 avatar-wrapper">
                    <img class="d-block" src="./img/profile-avatar.png" alt="profile avatar" >
                </div>
                <div class="">
                    <h1>
                        I'm <br>
                        UI/UX <br>
                        DESIGNER
                    </h1>
                </div>
            </div>
        </div>
        <!-- Navbar -->
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container">
                <a class="navbar-brand navbar-brand_custom" href="#">MENU</a>
                <button class="navbar-toggler border-0" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <i class="fa fa-reorder text-orange"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavDropdown">
                    <ul class="navbar-nav navbar-nav_custom">
                        <li class="nav-item nav-link_disappear">
                            <a class="nav-link px-4 text-orange" href="">HOME</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link px-4" href="#about">ABOUT</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link px-4" href="#education">EDUCATION</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link px-4" href="#portfolio">PORTFOLIO</a>
                        </li>
                        <li class="nav-item nav-link_disappear">
                            <a class="nav-link" href="#what">WHAT I DO</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link px-4" href="#contact">CONTACT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <!-- About Section -->
    <section class="about-section">
        <div class="container">
            <div class="row">
                <div class="col-md-6 mt-2">
                    <img class="d-block w-100 h-100" src="./img/about_me.png" alt="" >
                </div>
                <div class="col-md-6 mt-2">
                    <span class="pb-2 caption" id="about">ABOUT ME</span>
                    <p class="my-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ducimus nemo, eius rerum praesentium provident consequatur. Qui et quas est, aspernatur atque obcaecati magnam doloribus, vitae, laudantium ex earum dicta eaque. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt repudiandae architecto vero tenetur quaerat corrupti eaque, earum ut rem, dolor possimus ullam? Perspiciatis, ullam doloribus inventore mollitia cum fugit porro!</p>
                    <button type="submit" class="btn-orange mr-2">Download Resume</button>
                    <button type="submit" class="btn-black">Hire Me</button>
                </div>
            </div>
        </div>
    </section>
    <!-- Education Section -->
    <section class="education-section">
        <div class="container text-center">
            <span class="pb-2 caption" id="education">EDUCATION</span>
            <div class="grid-wrapper mt-5">
                <div class="wow animate__animated animate__bounce animate__slideInRight education-section_junior text-left">
                    <h6>Junior (WEAC)</h6>
                    <p>All Saints School</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Felis tincidunt orci, metus, aenean arcu. Vitae maecenas convallis tincidunt mauris.</p>
                </div>
                <div class="wow animate__animated animate__bounce animate__slideInLeft education-section_senior text-left">
                    <h6>Science (WEAC)</h6>
                    <p>Federal Science and Technical College</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Felis tincidunt orci, metus, aenean arcu. Vitae maecenas convallis tincidunt mauris.</p>
                </div>
                <div class="wow animate__animated animate__bounce animate__slideInRight education-section_bsc text-left">
                    <h6>Computer Science (Bsc)</h6>
                    <p>Covenant University</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Felis tincidunt orci, metus, aenean arcu. Vitae maecenas convallis tincidunt mauris.</p>
                </div>
                <div class="position-relative education-section_year1 p-2">
                    <h3 class="rotate rotate-up">2011</h3>
                </div>
                <div class="position-relative education-section_year2 p-2">
                    <h3 class="rotate rotate-up">2014</h3>
                </div>
                <div class="position-relative education-section_year3 p-2">
                    <h3 class="rotate rotate-up">2018</h3>
                </div>
                <div class="position-relative vertical-line">
                    <hr class="rotate rotate-up" />
                    <img class="ellipse1" src="./img/ellipse.png" alt="ellipse" >
                    <img class="ellipse2" src="./img/ellipse.png" alt="ellipse" >
                    <img class="ellipse3" src="./img/ellipse.png" alt="ellipse" >
                </div>
            </div>
        </div>
    </section>
    <!-- Portfolio Section -->
    <section class="portfolio-section">
        <div class="container text-center">
            <span class="pb-2 caption" id="portfolio">PORTFOLIO</span>
            <div class="portfolio-wrapper mt-5">
                <div class="wow animate__animated animate__bounce animate__bounceInUp portfolio-1">
                    <img class="" src="./img/portfolio_1.jpg" alt="" >
                </div>
                <div class="wow animate__animated animate__bounce animate__bounceInUp portfolio-2">
                    <img class="" src="./img/portfolio_2.jpg" alt="" >
                </div>
                <div class="wow animate__animated animate__bounce animate__bounceInUp portfolio-3">
                    <img class="" src="./img/portfolio_3.jpg" alt="" >
                </div>
                <div class="wow animate__animated animate__bounce animate__bounceInUp portfolio-4">
                    <img class="" src="./img/portfolio_4.jpg" alt="" >
                </div>
                <div class="wow animate__animated animate__bounce animate__bounceInUp portfolio-5">
                    <img class="" src="./img/portfolio_5.jpg" alt="" >
                </div>
                <div class="wow animate__animated animate__bounce animate__bounceInUp portfolio-6">
                    <img class="" src="./img/portfolio_6.jpg" alt="" >
                </div>
            </div>
            <button type="button" class="btn-orange">Load More</button>
        </div>
    </section>
    <!-- What I Do Section -->
    <section class="what-section">
        <div class="container text-center">
            <span class="pb-2 caption" id="what">WHAT I DO</span>
            <div class="row mt-5">
                <div class="col-md-3 mt-2 wow animate__animated animate__bounce animate__bounceInUp">
                    <div class="card card-body box-wrapper h-100 h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="image-overlay" src="./img/what1_1.png" alt="" >
                            <img class="d-block mx-auto image" src="./img/what1_2.png" alt="" >
                        </div>
                        <h6 class="text-center">Web Development</h6>
                        <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem praesentium facilis quidem.</p>
                    </div>
                </div>
                <div class="col-md-3 mt-2 wow animate__animated animate__bounce animate__bounceInUp">
                    <div class="card card-body box-wrapper h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="image-overlay" src="./img/what2_1.png" alt="" >
                            <img class="d-block mx-auto image" src="./img/what2_2.png" alt="" >
                            <img class="image-overlay_top" src="./img/what2_3.png" alt="" >
                        </div>
                        <h6 class="text-center">Web/App Design</h6>
                        <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem praesentium facilis quidem.</p>
                    </div>
                </div>
                <div class="col-md-3 mt-2 wow animate__animated animate__bounce animate__bounceInUp">
                    <div class="card card-body box-wrapper h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="image-overlay" src="./img/what3_1.png" alt="" >
                            <img class="d-block mx-auto image" src="./img/what3_2.png" alt="" >
                            <img class="image-overlay_bottom" src="./img/what3_3.png" alt="" >
                        </div>
                        <h6 class="text-center">Graphic Design</h6>
                        <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem praesentium facilis quidem.</p>
                    </div>
                </div>
                <div class="col-md-3 mt-2 wow animate__animated animate__bounce animate__bounceInUp">
                    <div class="card card-body box-wrapper h-100">
                        <div class="position-relative mt-5 mb-3">
                            <img class="image-overlay" src="./img/what4_1.png" alt="" >
                            <img class="d-block mx-auto image" src="./img/what4_2.png" alt="" >
                            <img class="image-overlay_left" src="./img/what4_3.png" alt="" >
                        </div>
                        <h6 class="text-center">Logo Making</h6>
                        <p class="text-left">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem praesentium facilis quidem.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section class="contact-section">
        <div class="container text-center">
            <span class="pb-2 caption" id="contact">GET IN TOUCH</span>
            <div class="row mt-5">
                <div class="col-md-6 mt-2">
                    <form>
                        <div class="form-row">
                            <div class="col-md-5 mb-3">
                                <input type="text" class="form-control" placeholder="First name">
                            </div>
                            <div class="col-md-7 mb-3">
                                <input type="text" class="form-control" placeholder="Last name">
                            </div>
                        </div>
                        <div class="form-group">
                            <input type="text" class="form-control" placeholder="Subject">
                        </div>
                        <div class="form-group">
                            <textarea class="form-control" rows="12" placeholder="Message"></textarea>
                        </div>
                        <button type="submit" class="btn-orange">Submit</button>
                    </form>
                </div>
                <div class="col-md-6 mt-2 card card-body contact-section_right">
                    <img class="d-block mx-auto mb-3" src="./img/contact-avatar.png" alt="avatar" >
                    <h5 class="text-center mb-3">LET'S WORK TOGETHER</h5>
                    <div class="d-flex justify-content-center">
                        <div class="bg-white rounded-circle p-2 mx-2">
                            <a href=""><i class="fa fa-skype text-dark" aria-hidden="true"></i></a>
                        </div>
                        <div class="bg-white rounded-circle p-2 mx-2">
                            <a href=""><i class="fa fa-twitter text-dark" aria-hidden="true"></i></a>
                        </div>
                        <div class="bg-white rounded-circle p-2 mx-2">
                            <a href=""><i class="fa fa-linkedin text-dark" aria-hidden="true"></i></a>
                        </div>
                        <div class="bg-white rounded-circle p-2 mx-2">
                            <a href=""><i class="fa fa-envelope text-dark" aria-hidden="true"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer Section -->
    <footer class="footer-section">
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <div class="">Copyright &copy; 2020</div>
                <div class="d-flex align-items-center">
                    <ul class="mb-0">
                        <li class="mx-2">FACEBOOK</li>
                        <li class="mx-2">INSTAGRAM</li>
                        <li class="mx-2">TWITTER</li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <!-- WOW JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js" integrity="sha256-z6FznuNG1jo9PP3/jBjL6P3tvLMtSwiVAowZPOgo56U=" crossorigin="anonymous"></script>
    <script>
        new WOW().init();
    </script>
    <script>
        $('.navbar-collapse a').click(function(){
            $(".navbar-collapse").collapse('hide');
        });
    </script>
</body>
</html>