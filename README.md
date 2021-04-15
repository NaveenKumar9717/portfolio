<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <link rel="icon" href="favicon.ico">
        <link rel="stylesheet" href="assets/css/styles.css">

        <!-- =====BOX ICONS===== -->
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>
        <link href="assets/css/all.css" rel="stylesheet">
        
        <title>Portfolio website complete Web</title>
    </head>
    <body>
        <!--===== HEADER =====-->
        <header class="l-header">
            <div class="scroll-progress-indicator"></div>
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Naveen</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                       
                        <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main Blog">
            <!--===== HOME =====-->
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title">Hi,<br>I'am <span class="home__title-color">Naveen</span><br>Web Developer</h1>

                   <a href="tel:8178647180" class="button">Call me <i class="fas fa-phone"></i></a>
                </div>

                <div class="home__social">
                    <a href="https://www.linkedin.com/in/naveen-kumar-290b81189/" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="https://www.hackerrank.com/naveencruz20" class="home__social-icon"><i class="fab  fa-hackerrank"></i></a>
                    <a href="https://github.com/NaveenKumar9717" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="home__img">    
                    <img  src="assets/img/PF.jpg" alt="">
                </div>
            </section>

            <!--===== ABOUT =====-->
            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="assets/img/ToonProfilr.jpeg" alt="Profile">
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am Naveen</h2>
                        <p class="about__text">Web developer and Compitative Proggramer from DTU persuing Mathematics & Computing.</p>           
                    </div>                                   
                </div>
            </section>

            <!--===== SKILLS =====-->
            <section class="skills section" id="skills">
                <h2 class="section-title">Skills</h2>

                <div class="skills__container bd-grid">          
                    <div>
                        <h2 class="skills__subtitle">Profesional Skills</h2>
                        <p class="skills__text">Below are the top skills on which I had worked from last 2 yers specially in javascript.</p>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-html5 skills__icon'></i>
                                <span class="skills__name">HTML5</span>
                            </div>
                            <div class="skills__bar skills__html">

                            </div>
                            <div>
                                <span class="skills__percentage">95%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-css3 skills__icon'></i>
                                <span class="skills__name">CSS3</span>
                            </div>
                            <div class="skills__bar skills__css">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">80%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-javascript skills__icon' ></i>
                                <span class="skills__name">JAVASCRIPT</span>
                            </div>
                            <div class="skills__bar skills__js">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">62%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxs-paint skills__icon'></i>
                                <span class="skills__name">NODEJS&SQL</span>
                            </div>
                            <div class="skills__bar skills__ux">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">78%</span>
                            </div>
                        </div>
                    </div>
                    
                    <div>              
                        <img src="assets/img/work3.jpg" alt="" class="skills__img">
                    </div>
                </div>
            </section>

            <!--===== WORK =====-->
            <section class="work section" id="work">
                <h2 class="section-title">Work</h2>

                <div class="work__container bd-grid">
                    <div class="work__img" >
                        <a href="https://naveenkumar9717.github.io/Tindog/"><img src="assets/img/Tindog.png" alt=""></a>
                        <h2 style ="text-align: center; margin-top: 10%;">Tindog</h2>
                    </div>
                    <div class="work__img">
                        <a href="https://naveenkumar9717.github.io/Sccissor_Paper_Stone_gmae/"><img src="assets/img/Papper_scissor.png" alt=""></a>
                        <h2 style ="text-align: center; margin-top: 10%;">Game By Me</h2>
                    </div>
                    <div class="work__img">
                        <a href="https://naveenkumar9717.github.io/ShopEasy/Index.html"><img src="assets/img/ecommerce.png" alt=""></a>
                        <h2 style ="text-align: center; margin-top: 10%;">Ecom.Website by Me</h2>
                    </div>
                    
                </div>
            </section>

            <!--===== CONTACT =====-->
            <section class="contact section" id="contact">
                <h2 class="section-title">Contact</h2>

                <div class="contact__container bd-grid">
                    <form action="" class="contact__form">
                        <input type="text" placeholder="My:8178647180" class="contact__input">
                        <input type="mail" placeholder="Email : Naveencruz20@gmail.com" class="contact__input">
                        <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                        <input type="button" value="Enter" class="contact__button button">
                        <!-- <h2 class ="contact__input">Conatc : 8178647180</h2> -->
                    </form>
                </div>
            </section>
        </main>

        <!--===== FOOTER =====-->
        <footer class="footer">
            <p class="footer__title">Naveen</p>
            <div class="footer__social">
                <a href="https://www.facebook.com/naveen.cruz.1" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
            </div>
            <p>&#169; 2020 Made with <i style ="color: crimson;" class="fas fa-heart"></i> by NaveenKumar9717</p>
        </footer>


        <!--===== SCROLL REVEAL =====-->
        <script src="https://unpkg.com/scrollreveal"></script>

        <!--===== MAIN JS =====-->
        <script src="assets/js/main.js"></script>
    </body>
</html>

