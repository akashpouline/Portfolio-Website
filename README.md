# Portfolio-Website
Designed and developed a dynamic and responsive portfolio website using HTML, CSS and JavaScript, showcasing a collection of personal projects and skills, while emphasizing user experience and creative design.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Personal Portfolio Website Design | Codehal</title>


    <!-- box icons -->
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet" />

    <!-- custom css -->
    <link rel="stylesheet" href="css/style.css" />
  </head>

  <body>

    <!-- header design -->
    <header class ="header">
      <a href="#" class="logo">Portfolio</a>

      <i class='bx bx-menu' id="menu-icon"></i>

      <nav class="navbar">
        <a href="#home" class="active">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
      </header>

    <!-- home section design -->
    <section class="home" id="home">
      <div class="home-content">
        <h3>Hello, It's Me</h3>
        <h1>Akash Pouline</h1>
        <h3>And I'm a <span class="multiple-text"></span></h3>
        <p>A quick learner in adaptive new technologies and environment. 
          I am a tech geek who is passionate about technologies,
          My approach integrates fostering innovation.</p>
          <div class="social-media">
            <a href="#"><i class='bx bxl-facebook'></i></a>
            <a href="#"><i class='bx bxl-twitter' ></i></a>
            <a href="#"><i class='bx bxl-instagram' ></i></a>
            <a href="#"><i class='bx bxl-linkedin' ></i></a>
            </div>
            <a href="#" class="btn">Download CV</a>
            </div>

            <div class="home-img">
              <img src="image/home.png" alt="">
            </div>
            </section>
      
    <!-- about section design -->
    <section class="about" id="about">
      <div class="about-img">
        <img src="images/about.png" alt="">
      </div>

      <div class="about-content">
        <h2 class=""heading>About <span>Me</span></h2>
        <h3>Frontend Developer!</h3>
        <p>I am a tech geek who is passionate about technologies Frontend development is a critical aspect of web development, as the user interface is what users interact with directly.
          A well-designed and responsive frontend can significantly 
           impact the user experience and the success of a website or web application.</p>
           <a href="#" class="btn">Read More</a>
      </div>
    </section>

    <!-- services section design -->
    <section class="services" id="services">
      <h2 class="heading">Our <span>Services</span></h2>

      <div class="services-container">
        <div class="services-box">
          <i class='bx bx-code-alt' ></i>
          <h3>Web Development</h3>
          <p>A quick learner in adaptive new technologies and environment. 
            I am a tech geek who is passionate about technologies,
            My approach integrates fostering innovation.</p>
            <a href="#" class="btn">Read More</a>
        </div>

        <div class="services-box">
          <i class='bx bxs-paint'></i>
          <h3>Graphic Design</h3>
          <p>A quick learner in adaptive new technologies and environment. 
            I am a tech geek who is passionate about technologies,
            My approach integrates fostering innovation.</p>
            <a href="#" class="btn">Read More</a>
        </div>

        <div class="services-box">
          <i class='bx bx-bar-chart-alt'></i>
          <h3>Digital Marketing</h3>
          <p>A quick learner in adaptive new technologies and environment. 
            I am a tech geek who is passionate about technologies,
            My approach integrates fostering innovation.</p>
            <a href="#" class="btn">Read More</a>
        </div>
      </div>
    </section>

    <!-- portfolio section design -->
    <section class="portfolio" id="portfolio">
      <h2 class="heading">Latest <span>Project</span></h2>

      <div class="portfolio-container">
        <div class="portfolio-box">
          <img src="images/portfolio1.jpg" alt="">
          <div class="portfolio-layer">
            <h4>Web Design</h4>
            <p>We're Collaborate with other professionals to showcase joint projects.
              Our teamwork and your ability to work in diverse environments.</p>
              <a href="#"><i class='bx bx-link-external'></i></a>
          </div>
        </div>

        <div class="portfolio-box">
          <img src="images/portfolio2.jpg" alt="">
          <div class="portfolio-layer">
            <h4>Web Design</h4>
            <p>We're Collaborate with other professionals to showcase joint projects.
              Our teamwork and your ability to work in diverse environments.</p>
              <a href="#"><i class='bx bx-link-external'></i></a>
      </div>
        </div>

        <div class="portfolio-box">
          <img src="images/portfolio3.jpg" alt="">
          <div class="portfolio-layer">
            <h4>Web Design</h4>
            <p>We're Collaborate with other professionals to showcase joint projects.
              Our teamwork and your ability to work in diverse environments.</p>
              <a href="#"><i class='bx bx-link-external'></i></a>
      </div>
        </div>

        <div class="portfolio-box">
          <img src="images/portfolio4.jpg" alt="">
          <div class="portfolio-layer">
            <h4>Web Design</h4>
            <p>We're Collaborate with other professionals to showcase joint projects.
              Our teamwork and your ability to work in diverse environments.</p>
              <a href="#"><i class='bx bx-link-external'></i></a>
      </div>
        </div>

        <div class="portfolio-box">
          <img src="images/portfolio5.jpg" alt="">
          <div class="portfolio-layer">
            <h4>Web Design</h4>
            <p>We're Collaborate with other professionals to showcase joint projects.
              Our teamwork and your ability to work in diverse environments.</p>
              <a href="#"><i class='bx bx-link-external'></i></a>
      </div>
        </div>
    </section>

    <!-- contact section design -->
    <section class="contact" id="contact">
      <h2 class="heading">Contact <span>Me!</span></h2>

      <form action="#">
        <div class="input-box"></div>
        <input type="text" placeholder="Full Name">
        <input type="email" placeholder="Email Address">
      </div>
      <div class="input-box"></div>
        <input type="number" placeholder="Mobile Number">
        <input type="text" placeholder="Email Subject">
      </div>
      <textarea name="" id="" cols="30" rows="10" placeholder="Your Message"></textarea>
      <input type="submit" value="Send Message" class="btn">
      </form>
    </section>

    <!-- footer design -->
    <footer class="footer">
      <div class="footer-text">
        <p>Copyright &copy; 2023 by Codehal | All Rights Reserved.</p>
      </div>

      <div class=".footer-iconTop">
        <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
      </div>
      </footer>


      <!-- scroll reveal -->
      <script src="https://unpkg.com/scrollreveal"></script>

    <!-- typed js -->
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>

    <!-- custom js -->
    <script src="js/script.js"></script>
  </body>

</html>


@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    border: none;
    outline: none;
    scroll-behavior: smooth;
    font-family: 'Poppins', sans-serif;
}

:root {
    --bg-color: #1f242d;
    --second-bg-color: #323946;
    --text-color: #fff;
    --main-color: #0ef;
}

html {
    font-size: 62.5%;
    overflow-x: hidden;
}

body {
    background-color: var(--bg-color);
    color: var(--text-color);
}

section {
    min-height: 100vh;
    padding: 10rem 9%  2rem;
}

.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 2rem 9%;
    background: var(--bf--color);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.header.sticky {
    border-bottom: .1rem solid rgba(0, 0, 0, .2);
}

.logo {
    font-size: 2.5rem;
    color: var(--text-color);
    font-weight: 600;
    cursor: default;
}

.navbar a {
    font-size: 1.7rem;
    color: var(--text-color);
    margin-left: 4rem;
    transition: .3s;
}

.navbar a:hover,
.navbar a.active {
    color: var(--main-color);
}

#menu-icon {
    font: size 3.6rem;
    color: var(--text-color);
    display: none;
}

.home {
    display: flex;
    justify-content: center;
    align-items: center;
}

.home-img img{
    width: 35vw;
    animation: floatImage 4s ease-in-out infinite;
}

@keyframes floatImage {
    0% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-2.4rem);
    }

    100% {
        transform: translateY(0);
    }
}

.home-content h3 {
    font-size: 3.2rem;
    font-weight: 700;
}

.home-content h3:nth-of-type(2) {
    margin-bottom: 2rem;
}

span {
    color: var(--main-color);
}

.home-content h1 {
    font-size: 5.6rem;
    font-weight: 700;
    line-height: 1.3;
}

.home-content p {
    font-size: 1.6rem;
}

.social-media a {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 4rem;
    height: 4rem;
    background: transparent;
    border: .2rem solid var(--main-color);
    border-radius: 50%;
    font-size: 2rem;
    color: var(--main-color);
    margin: 3rem 1.5rem 3rem 0;
    transition: .5s ease;
}

.social-media a:hover {
    background: var(--main-color);
    color: var(--second-bg-color);
    box-shadow: 0 0 1rem var(--main-color);
}

.btn {
    display: inline-block;
    padding: 1rem 2.8rem;
    background: var(--main-color);
    border-radius: 4rem;
    box-shadow: 0 0 1rem var(--main-color);
    font-size: 1.6rem;
    color: var(--second-bg-color);
    letter-spacing: .1rem;
    font-weight: 600;
    transition: .5s ease;;
}

.btn:hover {
    box-shadow: none;
}

.about {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2rem;
    background: var(--second-bg-color);
}

.about-img img {
    width: 35vw;
}

.heading {
    text-align: center;
    font-size: 4.5rem;
}

.about-content h2 {
    text-align: left;
    line-height: 1.2;
}

.about-content h3 {
    font-size: 2.6rem;
}

.about-content p {
    font-size: 1.6rem;
    margin: 2rem 0 3rem;
}

.services h2 {
    margin-bottom: 5rem;
}

.services-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 2rem;
}

.services-container .services-box {
    flex: 1 1 30rem;
    background: var(--second-bg-color);
    padding: 3rem 2rem 4rem;
    border-radius: 2rem;
    text-align: center;
    border: 2rem solid var(--bg-color);
    transition: .5s ease;
}

.services-container .services-box:hover {
    border-color: var(--main-color);
    transform: scale(1.02);
}

.services-box i {
    font-size: 7rem;
    color: var(--main-color);
}

.services-box h3 {
    font-size: 2.6rem;
}

.services-box p {
    font-size: 1.6rem;
    margin: 1rem 0 3rem;
}

.portfolio {
    background: var(--second-bg-color);
}

.portfolio h2 {
    margin-bottom: 4rem;
}

.portfolio-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    align-items: center;
    gap: 2.5rem;
}

.portfolio-container {
    position: relative;
    border-radius: 2rem;
    box-shadow: 0 0 1rem var(--bg-color);
    overflow: hidden;
    display: flex;
}

.portfolio-box img {
    width: 100%;
    transition: .5s ease;
}

portfolio-box:hover img {
    transform: scale(1.1);
}

.portfolio-box .portfolio-layer {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(0, 0, 0, .1), var(--main-color));
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    text-align: center;
    padding: 0 4rem;
    transform: translateY(100%);
    transition: .5s ease;
}

.portfolio-box:hover .portfolio-layer{
    transform: translateY(0);
}
.portfolio-layer h4 {
   font-size: 3rem;
}

.portfolio-layer p {
    font-size: 1.6rem;
    margin: .3rem 0 1rem;
}

.portfolio-layer a {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 5rem;
    height: 5rem;
    background: var(--text-color);
    border-radius: 50%;
}

.portfolio-layer a i {
    font-size: 2rem;
    color: var(--second-bg-color);
}


.contact h2 {
    margin-bottom: 3rem;
}

.contact form {
    max-width: 70rem;
    margin: 1rem auto;
    text-align: center;
    margin-bottom: 3rem;
}

.contact form .input-box {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.contact form .input-box input,
.contact form textarea {
    width: 100%;
    padding: 1.5rem;
    font-size: 1.6rem;
    color: var(--text-color);
    background: var(--second-bg-color);
    border-radius: .8rem;
    margin: .7rem 0;
}

.contact form .input-box input {
    width: 49%;
}

.contact form textarea {
    resize: none;
}

.contact form .btn {
   margin-top: 2rem;
   cursor: pointer;
}

.footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 2rem 9%;
    background: var(--second-bg-color);
}

.footer-text p {
    font-size: 1.6rem;
}

.footer-iconTop a {
 display: inline-flex;
 justify-content: center;
 align-items: center;
 padding: .8rem;
 background: var(--main-color);
 border-radius: .8rem;
 transition: .5s ease;
}

.footer-iconTop a:hover {
    box-shadow: 0 0 1rem var(--main-color);
}

.footer-iconTop a i {
    font-size: 2.4rem;
    color: var(--second-bg-color);
}


 /* BREAKPOINTS */
  @media (max-width: 1200px) {
    html {
        font-size: 55%
    }
}

 @media (max-width: 991px) {
    .header {
        padding: 2rem 3%;
    }

    section {
        padding: 10rem 3% 2rem;
    }

    .services {
        padding-bottom: 7rem;
    }
    
    .portfolio {
        padding-bottom: 7rem;
    }

  .contact {
    min-height: auto;
  }

    .footer {
        padding: 2rem 3%;
    }
 }

  @media (max-width: 768px) {
    #menu-icon {
        display: block;
    }

    .navbar {
        position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        padding: 1rem 3%;
        background: var(--bg-color);
        border-top: .1rem solid rgba(0, 0, 0, .2);
        box-shadow: 0 .5rem 1rem rgba(0, 0, 0, .2);
        display: none;
    }

    .navbar.active {
        display: block;
    }

    .navbar a {
        display: block;
        font-size: 2rem;
        margin: 3rem 0;
    }

    .home {
        flex-direction: column;
    }

    .home-content h3 {
        font-size: 2.6rem;
    }

    .home content h1 {
        font-size: 5rem;
    }

    .home-img img {
        width: 70vw;
        margin-top: 4rem;
    }

    .about {
        flex-direction: column-reverse;
    }

    .about img {
        width: 70vw;
        margin-top: 4rem;
    }

    .services h2 {
        margin-bottom: 3rem;
    }

    .portfolio h2 {
        margin-bottom: 3rem;
    }

    .portfolio-container {
        grid-template-columns: repeat(2, 1fr);
    }
    }

    @media (max-width: 617px) {
        .portfolio-container {
            grid-template-columns: 1fr;
        }
    }

    @media (max-width: 450px) {
    html  {
    font-size: 50%;
    }

    .contact form .input-box input {
    width: 100%;
 }
 }

    @media (max-width: 365px) {
        .home-img img {
            width: 90vw;
        }

        .about-img img {
            width: 90vw;
        }

        .footer {
            flex-direction: column-reverse;
        }

        .footer p {
            text-align: center;
            margin-top: 2rem;
        }
    }

    /*==================== toggle icon navbar ====================*/
let menuIcon = document.querySelector('#menu-icon');
let navbar = document.querySelector('.navbar');

menuIcon.onclick = () => {
    menuIcon.classList.toggle('bx-x');
    navbar.classList.toggle('active');
};

/*==================== scroll sections active link ====================*/
let sections = document.querySelectorAll('section');
let navLinks = document.querySelectorAll('header nav a');

window.onscroll = () => {
    sections.forEach(sec => {
        let top = window.scrollY;
        let offset = sec.offsetTop - 150;
        let height = sec.offsetHeight;
        let id = sec.getAttribute('id');

        if(top >= offset && top < offset + height) {
            navLinks.forEach(links => {
                links.classList.remove('active');
                document.querySelector('header nav a[href*=' + id +']').classList.add('active');
            });
        }; 
     });
    /*==================== sticky navbar ====================*/
    let header = document.querySelector('header');

    header.classList.toggle('sticky', window.scrollY > 100);

    /*==================== remove toggle icon and navbar when click navbar link (scroll) ====================*/
    menuIcon.classList.remove('bx-x');
    navbar.classList.remove('active');
    };


/*==================== scroll reveal ====================*/
ScrollReveal({
     reset: true,
     distance: '80px',
     duration: 2000,
     delay: 200
});

ScrollReveal().reveal('.home-content, .heading', { origin: 'top'});
ScrollReveal().reveal('.home-img, .services-container, .portfolio-box, .contact form', { origin: 'bottom'});
ScrollReveal().reveal('.home-content h1, .about-img', { origin: 'left'});
ScrollReveal().reveal('.home-content h1, .about-content', { origin: 'right'});


/*==================== typed js ====================*/
const typed = new Typed('.multiple-text', {
    strings: ['Frontend Developer', 'Student', 'Blogger', ],
    typeSpeed: 100,
    backSpeed: 100,
    backDelay: 1000,
    loop: true,
});
