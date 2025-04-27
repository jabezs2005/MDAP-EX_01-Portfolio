# MDAP-EX_01-Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### Index.html
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jabby's Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="./responsive.css">
    <!-- boxicon css link -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <!-- Link Swiper's CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css" />
    </head>
    <body>
        <div class="overlay"></div>
        <header>
            <a href="#" class="logo"><span>J</span>abby</a>
            <ul class="navlist">
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="right-header">
                    <a href="#" class="btn">Let's chat <i  class='bx bx-message-dots'></i></a>
                    <div class="menu-icon">
                        <div class="bar"></div>
                    </div>
                </div>
        </header>

        <section class="home" id="home">
            <div class="hero-info">
                <h3>Welcome To My World</h3>
                <h1>Hi I'm Jabez</h1>

                <div class="text-animate">
                <h2>Frontend Developer</h2>
                </div>

                <p>Lorem ipsum dolor sit amet consectetur 
                adipisicing elit. Odio consequuntur sit dolorem 
                eum id repellendus totam, repudiandae veritatis 
                nulla corrupti impedit, accusantium blanditiis
                minus eius reprehenderit atque. Maiores, ratione 
                impedit.</p>

                <div class="btn-box">
                <a href="jabsudha2005@gamil.com" class="btn">Hire Me Now ! <i class='bx bx-right-arrow-alt'></i></a>
                <a href="#" target="_blank" class="btn d-CV">Download CV <i class='bx bx-download'></i></a>
                </div>

                <div class="social-media">
                <div class="bg-icon">
                    <a href="#"><i class='bx bxl-instagram'></i></a>
                    <span></span>
                    </div>

                    <div class="bg-icon"><a href="#"><i class='bx bxl-github'></i></a>
                    <span></span>
                    </div>

                    <div class="bg-icon">
                    <a href="#"><i class='bx bxl-twitter'></i></a>
                    <span></span>
                    </div>

                    <div class="bg-icon">
                    <a href="#"><i class='bx bxl-facebook'></i></a>
                    <span></span>
                    </div>
                    </div>
                    </div>
                    <div class="img-hero">
                    <img src="img/hero.png" alt="">
                    <div class="rotate-text">
                    <div class="text">
                    <p>I'm Web Developer And I'm UI/UX Designer And I'm Editor</p>
                    </div>
                    <span><i></i></span>
                    </div>
                    </div>
                    </section>

                    <section class="about" id="about">
                    <div class="about-img">
                    <img src="img/aboutMe.png" alt="" class="aboutHero">
                    <div class="showcase-ring">
                    <img src="shapes/ring.png" class="ring">
                    <img src="shapes/circle.png" class="circle">    
                    </div>
                    </div>
                    <div class="about-content">
                    <h2 class="heading">About Me</h2>
                    <h3>2 Year's Experience on Product Design</h3>
                    <p>Lorem ipsum dolor sit, amet consectetur 
                    adipisicing elit. Ex modi quas nisi eum 
                    odit totam dolor, distinctio ipsum enim 
                    alias deleniti consectetur doloremque! Modi 
                    omnis illum vero, eos sequi eius.</p>
                    <div class="about-btn">
                    <button class="active">Main Skills</button>
                    <button>Awards</button>
                    <button>Education</button>
                    </div>
                    <div class="content-btn">
                    <div class="content">
                    <div class="text-box">
                    <p>User Experience Design - UI / UX</p>   
                    <span>Delight the user and make it work.</span>  
                    </div>
                    <div class="text-box">
                    <p>Web & User Interface Design - Development</p>
                    <span>Website , Web Experience , ...</span>
                    </div>
                    <div class="text-box">
                    <p>Interaction Design - Animation</p>
                    <span>I Like to move it move it</span>
                    </div>
                    </div>

                    <div class="content">
                    <div class="text-box">
                    <p>Web Design Award</p>
                    <span>Award for creativity and user experience.</span>
                    </div>
                    <div class="text-box">
                    <p>Code and Development Award</p>
                    <span>Expectional Coding skills and development 
                    techniques</span>
                    </div>
                    <div class="text-box">
                    <p>Hackathons and Coding Competitions</p>
                    <span>Participating in hackathons and coding.</span>
                    </div>
                    </div>

                    <div class="content">
                    <div class="text-box">
                    <p>Online Courses and Bootcamps</p>
                    <span>Delight the user and make it work.</span>
                    </div>
                    <div class="text-box">
                    <p>Internships and Work Experience</p>
                    <span>Website , Web Experience , ...</span>
                    </div>
                    <div class="text-box">
                    <p>Bachelor's Degree in Computer Science</p>
                    <span>I Like to move it move it</span>
                    </div>
                    </div>
                    </div>
                    <div class="cvContent">
                    <a href="img/resume.pdf" target="_blank" class="btn d-CV">Download CV<i class='bx bx-download'></i></a>
                    </div>
                    </div>
                    </section>
                    
                    <section class="services" id="services">
                    <div class="main-text">
                    <h2 class="heading">My Services</h2>
                    <span>what i will do for you</span>
                    </div>
                    
                    <div class="allServices">
                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bx-layer'></i>
                    <span></span>
                    </div>
                    <h3>App Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur 
                    adipisicing elit. Esse similique corporis 
                    facilis blanditiis quis, et consequatur, 
                    cupiditate facere aperiam, neque quidem maxime 
                    hic accusantium explicabo consequuntur nihil 
                    perferendis distinctio soluta.</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>

                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bx-code-alt'></i>
                    <span></span>
                    </div>
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, 
                    adipisicing elit. Exercitationem vero 
                    eaque molestiae, magni quod praesentium 
                    amet nisi enim dicta atque saepe, ut laudantium 
                    optio animi vel quisquam cumque in! Obcaecati?</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>

                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bx-desktop'></i>
                    <span></span>
                    </div>
                    <h3>UI / UX Design</h3>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing 
                    elit. Eum esse ea omnis. Optio fugiat ipsa dicta, 
                    provident dolorum explicabo perferendis excepturi, 
                    voluptatum, sunt placeat porro ipsum quas eos delectus 
                    praesentium.</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>
                   
                    <div class="servicesItem">
                    <div class="icon-services">
                    <i class='bx bxs-party'></i>
                    <span></span>
                    </div>
                    <h3>Digital Marketing</h3>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing 
                    elit. Repellendus nam laudantium ut architecto illum 
                    perferendis modi eius saepe quae dolor mollitia voluptatum 
                    nihil incidunt dicta, deleniti atque dignissimos aut vitae!</p>
                    <a href="#" class="readMore">Read More</a>
                    </div>
                    </div>

                    <div class="proposal">
                    <div class="text-box">
                    <span>Get It Touch</span>
                    <h3>Have a Project On Your Mind</h3>
                    <a href="#contact" class="btn">Conatct Me</a>
                    </div>
                    <img src="img/support.png" class="first">
                    </div>

                    <div class="showcase">
                    <img src="shapes/ring.png" class="ring">
                    <img src="shapes/circle.png" class="circle">
                    <img src="shapes/circle.png" class="circle2">
                    <img src="shapes/circle.png" class="circle3">
                    <img src="shapes/half-ring.png" class="half-ring">
                    </div>
                    </section>

                    <section class="portfolio" id="portfolio">
                    <div class="main-text">
                    <h2 class="heading">My Services</h2>
                    <span>what i will do for you</span>
                    </div>
                    <div class="fillter-buttons">
                    <button class="button mixitup-control-active" data-filter="all">All Work</button>
                    <button class="button" data-filter=".web">web
                    Development</button>
                    <button class="button" data-filter=".uiux">UI/UX
                    Design</button>
                    <button class="button" data-filter=".
                    branding">Branding Design</button>
                    </div>

                    <div class="portfolio-gallery">
                    <div class="portfolio-box mix uiux">
                    <div class="portfolio-content">
                    <h3>UI/UX Design</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod iste ipsum, 
                    et dolores perferendis quaerat eveniet adipisci nam fugit sapiente excepturi.</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/1.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix web">
                    <div class="portfolio-content">
                    <h3>Web Design</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus illo necessitatibus 
                    architecto deserunt? Velit totam quidem itaque nobis maiores magni iusto ad recusandae repellendus!</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/2.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix web">
                    <div class="portfolio-content">
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus adipisci ratione voluptatibus omnis 
                    deserunt recusandae magnam, incidunt illo! Dolore beatae non atque praesentium qui excepturi! Labore?</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/3.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix web">
                    <div class="portfolio-content">
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cupiditate quae perspiciatis ab omnis. 
                    Ea, nulla? Totam error deleniti quisquam sunt aliquam maiores quae aperiam explicabo, perferendis tenetur!</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>

                    <div class="portfolio-img">
                    <img src="img/portfolio/4.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix uiux">
                    <div class="portfolio-content">
                    <h3>UI/UX Design</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repellendus natus repellat ex, consectetur eveniet, 
                    placeat provident obcaecati, dolore sapiente nesciunt perspiciatis voluptatem quod consequatur beatae quidem?</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/5.jpg" alt="">
                    </div>
                    </div>

                    <div class="portfolio-box mix branding">
                    <div class="pprtfolio-content">
                    <h3>Web Development</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae totam, placeat asperiores, beatae, voluptate 
                    vero libero quam eos nihil soluta assumenda quos labore quasi possimus? Beatae ad et magnam porro!</p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    <div class="portfolio-img">
                    <img src="img/portfolio/6.jpg" alt="">
                    </div>
                    </div>
                    </div>

                    </section>

                    <section class="blog" id="blog">
                    <div class="main-text">
                    <h2 class="heading">Blog</h2>
                    <span>Latest News & Post</span>
                    </div>

                    <div class="blog-box swiper myswiper">
                    <div class="cards swiper-wrapper">
                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/1.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">sunday, Jan 14, 2023</span>
                    <p class="excerpt">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facilis, officiis eaque! Id autem omnis qui deleniti 
                    delectus ipsa in, alias quia temporibus porro at quos nostrum officia sapiente magnam dolores.
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/2.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14,2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Itaque doloremque fugit ex ea recusandae exercitationem 
                    dolorum similique vero hic ratione incidunt architecto nihil accusantium, quaerat, fugiat perferendis officia.
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/3.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14,2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore inventore consequatur maiores quas, repellat quibusdam 
                    provident. Tempora, soluta error culpa dicta quaerat nisi porro inventore iure facere, a aliquam mollitia?
                    </p>
                    <a herf="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/4.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14, 2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum, debitis provident. Similique possimus nihil, veritatis autem iste 
                    fugit cumque commodi asperiores. Neque molestias veritatis adipisci, asperiores voluptatem tempore odio optio!
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/5.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14, 2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sapiente vitae qui quam asperiores voluptatibus possimus ullam quos, 
                    non molestias? Dolores recusandae ullam sequi ducimus quos dolorem adipisci optio aperiam nemo?
                    </p> 
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    <div class="card swiper-slide">
                    <div class="card-top">
                    <img src="img/blog/6.jpg" alt="">
                    </div>
                    <div class="card-info">
                    <h2>Mobile App Landing Page</h2>
                    <span class="date">Sunday, Jan 14, 2024</span>
                    <p class="excerpt">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nostrum et voluptate consectetur facilis, eligendi quidem officia 
                    perferendis tenetur. Error iusto, excepturi suscipit quae repudiandae consequuntur ut beatae cum deserunt fugiat.
                    </p>
                    <a href="#" class="readMore">Explore More</a>
                    </div>
                    </div>

                    </div>
                    </div>

                    <div class="swiper-pagination"></div>

                    <div class="showcase">
                    <img src="shapes/ring.png" class="ring">
                    <img src="shapes/second-circle.png" class="second-circle">
                    <img src="shapes/half-ring.png" class="half-ring">
                    </div>

                    </section>

                    <section class="down-box" id="content">
                    <div class="contactSkills">
                    <div class="contact-info">
                    <div class="main-text">
                    <h2 class="heading">Contact Me</h2>
                    <span>get in touch with</span>
                    </div>
                    <form action="#">
                    <div class="input-box">
                    <input type="text" placeholder="First Name">
                    <input type="text" placeholder="Last Name">
                    </div>
                    <input type="email" placeholder="Email">
                    <input type="text" placeholder="Subject">
                    <textarea name="#" id="" cols="30" rows="10">
                    </textarea>
                    <div class="formBtn">
                    <button type="submit" class="btn">Send Message</button>
                    </div>
                    </form>
                    </div>
                    <div class="skills">
                    <div class="container">
                    <div class="skillBox">
                    <div class="main-text">
                    <h2 class="heading">My Skills</h2>
                    <span>Let Me Help</span>
                    </div>
                    <div class="skill-wrap">
                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xmlns="https://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">
                    <defs>
                    <linearGradient if="GradientColor">
                    <stop offset="0%" stop-color="##e91e63" />
                    <stop offset="100%" stop-color="#673ab7" />
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75" 
                    stroke-linecap="round" />
                    </svg>
                    <h2 class="counter">
                    <span data-target="89">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                    HTML
                    </div>
                    </div>

                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xmlns="https://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">
                    <defs>
                    <linearGradient id="GradientColor">
                    <stop offset="0%" stop-color="#e91e63" />
                    <stop offset="100%" stop-color="#673ab7" />
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75" 
                    stroke-linecap="round" />
                    </svg>
                    <h2 class="counter">
                    <span data-target="47">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                    CSS 
                    </div>
                    </div>

                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xlmns="http://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">
                    <defs>
                    <linearGradient id="GradientColor">
                    <Stop offset="0%" stop-color="#e91e63"/>
                    <stop offset="100%" stop-color="#673ab7"/>
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75"
                    stroke-linecap="round" />
                    </svg>
                    <h2 class="counter">
                    <span data-target="56">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                     JavaScript   
                     </div>
                     </div>

                    <div class="skill">
                    <div class="outer-circle">
                    <div class="inner-circle">
                    <svg xlmns="https://www.w3.org/2000/svg" version="1.
                    1" width="180px" height="180px">.
                    <defs>
                    <linearGradient id="GradientColor">
                    <stop offset="0%" stop-color="#e91e63"/>
                    <stop offset="100%" stop-color="#673ab7">
                    </linearGradient>
                    </defs>
                    <circle cx="85" cy="85" r="75" stroke-linecap="round"/>
                    </svg>
                    <h2 class="counter">
                    <span data-target="19">0</span>%
                    </h2>
                    </div>
                    </div>
                    <div class="sk-title">
                    UI/UX Design
                    </div>
                    </div>
                    </div>
                    </div>
                    </div>
                    </div>
                    </section>

                    <footer>
                    <p>Copyright 2025 by<span> Jabez S 
                        </span> || All Right Reserved.</p>
                    </footer>

                    <div id="progress">
                    <span id="progress-value">
                    <i class="bx bxs-chevrons-up"></i>
                    </span>
                    </div>
    <!-- scroll reveal  -->
    <script src="https://unpkg.com/scrollreveal"></script>
    <!-- Swiper JS -->
    <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
    <!-- mixitup cdn js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mixitup/3.3.1/mixitup.min.js"></script>
    <script src="script.js"></script>
    </body>
    </html>
```
### Responsive.CSS
```

/*======================= @keyframes ============================ */

@keyframes moveText{
    0%,10%,100%{
        background-position: -24rem 0;
    }

    65%,85%{
        background-position: 0rem 0;
    }
}

@keyframes moveCursorText{
    0%,10%,100%{
        width: 0;
    }

    65%,78%,85%{
        width: 100%;
        opacity: 1;
    }

    75%,85%{
        opacity: 0;
    }
}

@keyframes animate{
    0%{
        transform: rotate(0deg);
    }
    100%{
        transform: rotate(360deg);
    }
}

@keyframes rotateText{
    0%{
        transform: rotate(360deg);
    }
    100%{
        transform: rotate(0deg);
    }
}

@keyframes progress{
   to{
    stroke-dashoffset: var(--target);
   }
}

@keyframes floatImage{
    0%{
        transform: translateY(0);
    }
    50%{
        transform: translateY(-22px);
    }
    100%{
        transform: translateY(0);
    }
}




/*======================= BrakPoints ============================ */

@media(max-width:1200px){
    html{
        font-size: 95%;
    }
}

@media(max-width:991px){
    header,section,footer{
        padding-left: 3%;
        padding-right: 3%;
    }
    .home,.portfolio-box{
        flex-direction: column-reverse;
    }
    .about,.contactSkills{
        flex-direction: column;
    }
    .about .about-img .aboutHero{
        width: 100%;
    }
    .proposal img{
        width: 52vw;
    }
    .portfolio-img img{
        width: 100%;
        height: 100%;
    }
    .portfolio-gallery{
        grid-template-columns: repeat(auto-fill,minmax(250px , 1fr));
    }
    .img-hero{
        margin-top: 3rem;
    }
}

@media(max-width:768px){
    .proposal{
        display: none;
    }
    .menu-icon .bar,.menu-icon::after,.menu-icon::before{
        display: block;
    }
    ul.navlist{
        position: absolute;
        top: -1000px;
        transition: all .3s ease;
        width: 100%;
        text-align: center;
        display: block;
        background: var(--gradient-white-bg);
        left: 0;
        border-top: 2px solid rgba(248, 202, 202, .7);
    }
    ul.navlist a{
        font-size: 1.5rem;
        margin: 1rem 0;
    }
    .navlist.active{
        top: 100%;
    }
    .overlay{
        width: 100vw;
        height: 100vh;
        top: 0;
        left: 0;
        position: fixed;
        background: rgba(0,0,0,0.5);
        z-index: 8;
        opacity: 0;
        transform: .3s;
        pointer-events: none;
    }
    body.open .overlay{
        opacity: 1;
        pointer-events: auto;
    }
    .btn{
        padding: 10px;
    }
    .home{
        grid-gap: 0;
    }
    .fillter-buttons button{
        padding: 10px;
        font-size: .8rem;
    }
}

.about-img .ring{
    position: absolute;
    top: 22%;
    right: 1%;
}

.about-img .circle{
    position: absolute;
    top: 0%;
    left: 0%;
}


.about-content{
    padding: 3rem 0;
}
.bg-icon span{
    position: absolute;
    width: 50px;
    height: 50px;
    background: var(--gradient-color-bg);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: animate 1s linear infinite;
}

.img-hero{
    position: relative;
    animation: floatImage 4s ease-in-out infinite;
    animation-delay: 3s;
}

.img-hero img{
    position: relative;
    width: 400px;
    height: auto;
    z-index: 10;
}

.rotate-text{
    position: absolute;
    top: 4%;
    left: -53px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    padding: 2rem;
}

.skill{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.outer-circle{
    width: 170px;
    height: 170px;
    position: relative;
    margin-bottom: 1rem;
    padding: 20px;
    border-radius: 50%;
    box-shadow: rgba(50,50,93,0.25)0px 6px 12px -2px,
    rgba(0,0,0,0.3)0px 3px 7px -3px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.inner-circle{
    width: 130px;
    height: 130px;
    border-radius: 50%;
    box-shadow: rgba(204,219,232)3px 3px 6px 0px inset,
    rgba(255,255,255,0.5)-3px -3px 6px 1px inset;
}
:root{
    --bg-color:#e3edf7;
    --gradient-white-bg:linear-gradient(0deg,#fff 0%,#edf4fa 51%,#e5eef7 100%);
    --gradient-color-bg:linear-gradient(180deg,rgba(247,1,120,1)0%,
                                                rgba(160,8,156,1)51%,
                                                rgba(99,13,178,1)100%);
    --main-color:#e6006d;
    --font-color:#90979f;
    --hover-box-shadow:rgba(0,0,0,0.19)0px 10px 20px,
                       rgba(0,0,0,0.23)0px 6px 6px;     
    --gradient-white-bg2:linear-gradient(98deg,#e5eef7 0%,#fff 100%);                                                          
}

.outer-circle svg{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.about-content h2{
    color: var(--main-color);
}

@media(max-width:530px){
    html{
        font-size: 80%;
    }
    section{
        padding: 50px 3%;
    }
    .contact-info form .input-box{
        display: block;
    }
    .input-box input {
        width: 100%;
    }
    .rotate-text{
        display: none;
    }
    .img-hero img{
        width: 100%;
    }
    .text-animate{
        width: 23.8rem;
    }
    .btn-box{
        width: 266px;
        margin-bottom: 3rem;
    }
    .about-btn button{
        padding: 10px 15px;
    }
    .fillter-buttons{
        display: grid;
        grid-gap: 1rem;
    }
    .fillter-buttons button{
        width: 100%;
        padding: 13px;
    }
}

.allServices{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px , auto));
    align-items: center;
    gap: 2rem;
    position: relative;
    z-index: 1;
}

.servicesItem{
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
                  rgba(0,0,0,0.06)0px 1px 2px 0px;
    padding: 2rem 1rem;
    border-radius: 10px;
    background: var(--gradient-white-bg2);
    text-align: center;
}

.icon-services{
    display: inline-flex;
    position: relative;
}

.icon-services i{
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
                  rgba(0,0,0,0.06)0px 1px 2px 0px;
    padding: .5rem;
    border-radius: 50%;
    background: var(--gradient-color-bg);
    width: 70px;
    height: 70px;
    color: #fff;
    font-size: 2.5rem;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    transition: .4s;
    z-index: 1;
}

.servicesItem:hover i{
    outline: 1px solid var(--main-color);
    transform: scale(1.2);
}

.icon-services span{
    position: absolute;
    width: 80px;
    height: 80px;
    left: -5px;
    top: -5px;
    background: var(--gradient-color-bg);
    border-radius: 50%;
    animation: animate 1s linear infinite;
}

.servicesItem h3{
    margin: 1rem 0 0.5rem;
}

.servicesItem p{
    margin-bottom: 1.5rem;
    font-size: .9rem;
    color: var(--font-color);
}

 .readMore{
    background: var(--gradient-white-bg2);
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
                  rgba(0,0,0,0.06)0px 1px 2px 0px;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 1rem;
    font-weight: 500;
    color: #000;
    margin-right: .8rem;
    cursor: pointer;              
}

.navlist li{
    margin: 0 1rem;
}

.navlist li a{
    display: inline-flex;
    font-weight: 600;
}

.navlist li a:hover,.navlist li a.active{
    background: var(--gradient-color-bg);
    -webkit-background-clip: text;
    color: transparent;
}

.right-header{
    display: flex;
    align-items: center;
    justify-content: end;
    grid-gap: .8rem;
}

.btn{
    background: var(--gradient-color-bg);
    color: #fff;
    padding: 8px 10px;
    border-radius: 5px;
    font-weight: 500;
    transition: all .3s ease;
}

.btn:hover,.btn-box .d-CV:hover{
    box-shadow: var(--hover-box-shadow);
}

.menu-icon{
    position: relative;
    display: block;
    width: 30px;
    height: 30px;
    cursor: pointer;
    /* background: blue; */
}

.text-animate{
    width: 22.8rem;
    position: relative;
}

.social-media{
    display: flex;
    justify-content: space-between;
    width: 220px;
    height: 45px;
}

.social-media a{
    width: 42px;
    height: 42px;
    font-size: 1.5rem;
    color: var(--main-color);
    background: #fff;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    transition: .4s;
    border-radius: 50%;
    z-index: 1;
}


.social-media a:hover{
    background: var(--gradient-color-bg);
    color: #fff;
}

.bg-icon{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}

.rotate-text span{
    position: relative;
    width: 442px;
    height: 442px;
    background: red;
    border: 6px solid #eaeef0;
    border-radius: 50%;
    z-index: 1;
    overflow: hidden;
}

.text-animate h2{
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 1rem;
    color: transparent;
    -webkit-text-stroke: 0.1vw #770753;
    background: var(--gradient-color-bg);
    background-repeat: no-repeat;
    -webkit-background-clip: text;
    background-position: 0 0;
    transition: .6s;
    letter-spacing: 2px;
    animation: moveText 3s linear infinite;
    animation-delay: 2s;
}

.text-box p{
    font-size: 1.1rem;
    font-weight: 500;
}

.about-btn{
    margin: .8rem 0;
}

.about-btn button,.cvContent a{
    background: var(--gradient-white-bg2);
    padding: 10px 20px;
    border-radius: 5px;
    border: none;
    font-size: 1rem;
    font-weight: 500;
    color: #000;
    box-shadow: rgba(60,64,67,0.3)0px 1px 2px 0,
                  rgba(60,64,67,0.15)0px 2px 6px 2px;
    margin-right: .5rem;
    cursor: pointer;
    transition: all .3s ease;
}

.proposal{
    position: relative;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    background: var(--gradient-white-bg2);
    box-shadow: rgba(0,0,0,0.1)0px 1px 3px 0,
    rgba(0,0,0,0.06)0px 1px 2px 0px;
    margin-top: 8rem;
    border-radius: 10px;
    padding: 0rem 2rem;
    z-index: 1;
}

.proposal img{
    width: 40vw;
    height: auto;
    margin: -4rem 0 0;
    z-index: 2;
}

.services .text-box span{
    font-size: 1.2rem;
    font-weight: 600;
}

.services .text-box h3{
    margin-top: 1rem;
    margin-bottom: 2rem;
    font-size: 2.3rem;
    font-weight: 800;
}

.services .text-box .btn{
    padding: 10px 20px;
}


.services .showcase .ring{
    width: 100px;
    height: auto;
    position: absolute;
    top: 2%;
    left: -3%;
}


.about-btn button.active{
    background: var(--gradient-color-bg);
    color: #ffff;
}

.text-box{
    margin: .8rem 0;
}


.fillter-buttons button:hover,button.mixitup-control-active{
    background: var(--gradient-color-bg);
    color: #fff;
}

.portfolio-gallery{
    display: grid;
    grid-template-columns: repeat(auto-fill,minmax(370px , 1fr));
    gap: 1rem;
}

.portfolio-img img{
    display: block;
    width: 100%;
    height: 160px;
    transition: .3s;
}

.portfolio-box{
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: .5rem;
    padding: .5rem;
    box-shadow: rgba(0,0,0,0.18)0px 2px 4px;
    background: var(--gradient-white-bg2);
    border-radius: 10px;
    transition: all .3s ease;
}

.card img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: .3s;
    display: block;
}

.card:hover img{
    transform: scale(1.1);
}

.card-info{
    padding-bottom: .5rem;
}

.card-info h2{
    font-size: 1.2rem;
    margin-top: 1rem;
}

.data{
    display: block;
    margin: .2rem 0;
}

.card .excerpt{
    color: var(--font-color);
    margin-bottom: 1.5rem;
}

.swiper-pagination{
    position: relative !important;
    margin-top: 3rem;
}

.swiper-pagination-bullet{
    height: 10px !important;
    width: 30px !important;
    border-radius: 25px !important;
    background: var(--gradient-color-bg) !important;
}

.portfolio-content{
    width: 100%;
    padding-left: .5rem;
    padding-bottom: .5rem;
}

.portfolio-img{
    width: 100%;
    border-radius: 5px;
    overflow: hidden;
}
.contact-info form .input-box{
    display: flex;
    justify-content: space-between;
}

.input-box input{
    width: 49%;
}

form input:focus,form textarea:focus{
    filter: brightness(100%);
    background: #d2e9ff;
    border: 2px solid #f8caca;
}
```
## OUTPUT
![alt text](<O-portfolio/img/Screenshot 2025-04-23 103012.png>)
![alt text](<O-portfolio/img/Screenshot 2025-04-23 103048.png>)
![alt text](<O-portfolio/img/Screenshot 2025-04-23 103058.png>)
![alt text](<O-portfolio/img/Screenshot 2025-04-23 103119.png>)
![alt text](<O-portfolio/img/Screenshot 2025-04-23 103133.png>)
![alt text](<O-portfolio/img/Screenshot 2025-04-23 103133.png>)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
