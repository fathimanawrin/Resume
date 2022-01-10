# Portfolio Template

### My Resume ✨.





## Features

- Clean, Simple and Modern UI Design.
- Uses No CSS or JavaScript Frameworks or libraries as dependencies.
- Built with only HTML, CSS and a bit of JavaScript 🔨.
- Well Organized Documentation.
- Keyboard support.
- Fully Responsive.
- Loads fast ⚡.



### Header

In all of the places where you're supposed to fill your information you'll find HTML comments. As shown below just replace what is already in the opening and closing tags below the comment with your information.

```html
<div class="header__text-box row">
    <div class="header__text">
        <h1 class="heading-primary">
        <!-- Replace the following name with your name -->
        <span>Syed Ali Hussnain</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>A Web Developer based in Lahore, Pakistan.</p>
        <a href="#contact" class="btn btn--pink">Get in touch</a>
    </div>
</div>
```

### Work Section

Each div with class `work__box` represents a project, replace the contents of the all the tags with the information of your projects.

```html
<div class="work__box">
    <div class="work__text">
    <h3>Portfolio Template</h3>
    <p>
       Fathima Nawrin
    </p>
    <ul class="work__list">
        <li>HTML</li>
        <li>SCSS</li>
        <li>JavaScript</li>
        <li>Parcel</li>
    </ul>

    <div class="work__links">
        <a href="#" class="link__text">
        Visit Site <span>&rarr;</span>
        </a> 
        <a href="https://github.com/nisarhassan12/portfolio" target="_blank">
        <img src="./images/github.svg" class="work__code" alt="GitHub">
        </a>
    </div>
    </div>
    <div class="work__image-box">
        <img
            src="./images/project-1.png"
            class="work__image"
            alt="Project 1"
        />
    </div>
</div>
```

For changing the screenshot:
- first place the image in `images/` folder and then in HTML replace the name in `src` with the name of your image.

- Recommended size for project image (1366 x 767px) also make sure the size of all  project images is the same.

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="shortcut icon" type="image/png" href="./images/favicon.png" />

  <!-- Put your site title here -->
  <title>
    Fathima Nawrin | A Web Developer,Srilanka.
  </title>

  <meta name="description" content="Add small description of yourslef.">
  <!-- Add some coding keywords below, Ex: (React, CSS etc) -->
  <meta name="keywords" content="Put your name, skills and some coding keywords" />
  <link rel="stylesheet" href="index.css" />
</head>

<body>

  <!-- ***** Header ***** -->

  <header class="header" role="banner" id="top">
    <div class="row">
      <nav class="nav" role="navigation">
        <ul class="nav__items">
          <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
          <li class="nav__item"><a href="#clients" class="nav__link">Education</a></li>
          <li class="nav__item">
            <a href="#about" class="nav__link">About</a>
          </li>
          <li class="nav__item">
            <a href="#contact" class="nav__link">Contact</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="header__text-box row">
      <div class="header__text">
        <h1 class="heading-primary">
          <!-- Replace the following name with your name -->
          <span>Fathima Nawrin</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>A Web Developer, Srilankan.</p>
        <a href="#contact" class="btn btn--pink">Get in touch</a>
      </div>
    </div>
  </header>

  <main role="main">

    <!-- ***** Work ***** -->

    <section class="work" id="work">
      <div class="row">
        <h2>My Work</h2>
        <div class="work__boxes">

          <!-- Each div with the work__box class is a project. -->

          <div class="work__box">
            <div class="work__text">
              <h3>Online Bus Reservation system</h3>
              <p>
                Created an online platform that will be useful for the passenger, bus owner, and bus conductor to manage the process effectively and efficiently inside the long journey buses.

                Technologies used: MySQL, React, Yii2 PHP Framework.
              </p>
              <ul class="work__list">
                <li>React</li>
                <li>Yii2 PHP Framework</li>
                <li> MySQL</li>
               
              </ul>

              <div class="work__links">
                <a href="https://github.com/fathimanawrin/Softwareproject" target="_blank" class="link__text">
                  Visit Site <span>&rarr;</span>
                </a>
                <a href="https://github.com/fathimanawrin" title="View Source Code" target="_blank">
                  <img src="./images/github.svg" class="work__code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="./images/project-1.jpeg" class="work__image" alt="Project 1" />
            </div>
          </div>

          <div class="work__box">
            <div class="work__text">
              <h3>Rewarding Plastic Recycler Machine</h3>
              <p>
                Rewarding plastic recycler is a special type of plastic recycling Machine which shreds the plastics inserted to it and rewarding back its user with a reward of his/her opinion such as money, water or charging time.
              </p>
              <ul class="work__list">
                <li>Atmega32 microcontroller language</li>
                <li>Atmel Studio</li>
              </ul>

              <div class="work__links">
                <a href="#" class="link__text">
                  Visit Site <span>&rarr;</span>
                </a>
                <a href="#">
                  <img src="./images/github.svg" class="work__code" title="View Source Code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="./images/project-2.jpeg" class="work__image" alt="Project 1" />
            </div>
          </div>

            
    </section>

  <!-- ***** Clients ***** -->

    <section class="client" id="clients">
      <div class="row">
        <h2>Education</h2>
        <h1><b>B.SC.(HONS.)DEGREE IN INFORMATION TECHNOLOGY</b> </h1>
          <h1>2018 - 2022</h1> </br>
          <h1><i>Faculty of Information Technology,Moratuwa,Kadubbetha</i></h1>
          
        After A/l result i selected to university of moratuwa faculty of information technology to 2018 batch .This course duration is approximately 4 year include with internship</h1>
      </br> </br>
      <h1><b> G.C.E ADVANCE LEVEL (2017)</b></h1>    </br>
        3A passes.
      </br>
        Z-score- 1.7710 college 
      </br> </br>  
      <h1><b>  AWARD AND ACHEIVEMENT</b></h1>
    </br> 
          Semi Finalist of Idealize 2021 powered by Ideamart.
          Participated (Team)  </br> 
          Organized by AIESEC in University of Moratuwa.
    </br>    </br>
          Participated in HACKMORAL 3.0 -MINI HACKATHON
          Organized by INTECS, Faculty of Information Technology, University Of
          Moratuwa. (2021) 
        



        
        
    </section>

    <!-- ***** About ***** -->3

    <section class="about" id="about">
      <div class="row">
        <h2>About Me</h2>
        <div class="about__content">
          <div class="about__text">
            <!-- Replace the below paragraph with info about yourself -->
            <p>
              I am Fathima Nawrin from Rathnapura and 23 years old Undergraduate student of university of Moratuwa.The graduation year is 2022 .I am a speed leaner and IT enthusastist.creative wrighting is my hobby.i love coding and travelling .
            </p>
            <!-- Provide a link to your resume -->
            <a href="#" class="btn">My Resume</a>
          </div>

          <div class="about__photo-container">
            <!-- Add a nice photo of yourself -->
            <img class="about__photo" src="./images/fathimanawrin.jpeg" alt="" />
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- ***** Contact ***** -->

  <section class="contact" id="contact">
    <div class="row">
      <h2>Get in Touch</h2>
      <div class="contact__info">
        <p>
          Are you looking for a fast-performing and user-friendly website to
          represent your product or business? or looking for any kind of
          consultation? or want to ask questions? or have some advice for me
          or just want to say "Hi 👋" in any case feel free to Let me know. I
          will do my best to respond back. 😊 The quickest way to reach out to
          me is via an email.
        </p>
        <!-- Replace the email with yours -->
        <a href="mailto:fathimanawrin2@gmail.com" class="btn">fathimanawrin2@gmail.com</a>
      </div>
    </div>
  </section>

  <!-- ***** Footer ***** -->

  <footer role="contentinfo" class="footer">
    <div class="row">
      <!-- Update the links to point to your accounts -->
      <ul class="footer__social-links">
        
        <li class="footer__social-link-item">
          <a href="https://github.com/fathimanawrin" title="Link to Github Profile">
            <img src="./images/github.svg" class="footer__social-image" alt="Github">
          </a>
        </li>
       
        <li class="footer__social-link-item">
          <a href="https://www.linkedin.com/in/nawrin22/">
            <img src="./images/linkedin.svg" title="Link to Linkedin Profile" class="footer__social-image" alt="Linkedin">
          </a>
        </li>
      </ul>

      <!-- If you give me some credit by keeping the below paragraph, will be huge for me 😊 Thanks. -->
      <p>
        &copy; 2020 - Template designed & developed by <a href="file:///C:/Users/comnet/Desktop/resume/portfolio-template/index.html#contact" class="link">Nawrin</a>.
      </p>
    
    </div>
  </footer>

  <a href="#top" class="back-to-top" title="Back to Top">
    <img src="./images/arrow-up.svg" alt="Back to Top" class="back-to-top__image"/>
  </a>
  <script src="./index.js"></script>
</body>

</html>
