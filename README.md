# Ex-08 To create a web Portfolio CV using HTML CSS
## Aim:-
To create a web Portfolio CV using HTML CSS
## Algorithm:-
### Step 1:
index.html: The main HTML file.
### Step 2:
style.css: The CSS file for styling the portfolio.
### Step 3:
Add content to the portfolio
### Step 4:
Link the CSS file
### Step 5:
Style the portfolio using CSS
### Step 6:
Publish your portfolio
## Program:-
#### Developed By : Bharath V
#### Register Number : 212221230013
### Index.html
```html

  <!-- 
    - #HEADER
  -->
  
  <header class="header" data-header>
    <div class="container">
      <a href="#">
        <h1 class="logo">Portfolio</h1>
      </a>
      <button class="nav-toggle-btn" aria-label="Toggle Menu" data-nav-toggle-btn>
        <ion-icon name="menu-outline" class="menu-icon"></ion-icon>
        <ion-icon name="close-outline" class="close-icon"></ion-icon>
      </button>
      <nav class="navbar container">
        <ul class="navbar-list">
          <li>
            <a href="#home" class="navbar-link" data-nav-link>Home</a>
          </li>
          <li>
            <a href="#about" class="navbar-link" data-nav-link>About</a>
          </li>
          <li>
            <a href="#portfolio" class="navbar-link" data-nav-link>Portfolio</a>
          </li>
          <li>
            <a href="#skills" class="navbar-link" data-nav-link>Skills</a>
          </li>
          <li>
            <a href="#contact" class="navbar-link" data-nav-link>Contact</a>
          </li>
          <li>
            <a href="#blog" class="navbar-link" data-nav-link>Blog</a>
          </li>
          <li>
            <a href="#" class="btn btn-primary blue">Download</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
  <main>
    <article>

      <!-- 
        - #HERO
      -->

      <section class="hero" id="home">
        <div class="container">
          <div class="hero-banner">
            <img src="profile.jpg" width="800" height="864" loading="lazy" alt="My Photo"
              class="img-cover">
            <div class="elem elem-1">
              <p class="elem-title">4</p>
              <p class="elem-text">Years of Experience</p>
            </div>
            <div class="elem elem-2">
              <p class="elem-title">50+</p>
              <p class="elem-text">Projects Completed</p>
            </div>
            <div class="elem elem-3">
              <ion-icon name="trophy"></ion-icon>
            </div>
          </div>
          <div class="hero-content">
            <h2 class="hero-title">
              <span>Hello I'm</span>
              <strong>Bharath</strong> Web Developer from India
            </h2>
            <p class="hero-text">
              I completed B.tech Ai & Ds in saveetha engineering college.
            </p>
            <div class="btn-group">
              <a href="#contact" class="btn btn-primary blue">More info</a>
              <a href="#about" class="btn btn-primary blue">About Me</a>
            </div>
          </div>
        </div>
      </section>
      
      <!-- 
        - #ABOUT
      -->

      <section class="section about" id="about">
        <div class="container">
          <figure class="about-banner">
            <img src="./assets/images/about-banner.jpg" width="800" height="652" loading="lazy" alt="Ethan's Photo"
              class="img-cover">
            <img src="./assets/images/absolute-image.jpg" width="800" height="717" loading="lazy" alt="Ethan's Photo"
              class="abs-img">
            <div class="abs-icon abs-icon-1">
              <ion-icon name="logo-css3"></ion-icon>
            </div>
            <div class="abs-icon abs-icon-2">
              <ion-icon name="logo-javascript"></ion-icon>
            </div>
            <div class="abs-icon abs-icon-3">
              <ion-icon name="logo-angular"></ion-icon>
            </div>
          </figure>
          <div class="about-content">
            <p class="section-subtitle">I'm a Developer</p>
            <h2 class="h2 section-title">I Develop Application that Help People</h2>
            <a href="#portfolio" class="btn btn-primary blue">View Portfolio</a>
          </div>
        </div>
      </section>

      <!-- 
        - #PORTFOLIO
      -->

      <section class="section portfolio" id="portfolio">
        <div class="container">
          <h2 class="h2 section-title">My Amazing Works</h2>
          <ul class="portfolio-list">
            <li>
              <a href="#" class="portfolio-card" style="background-image: url('./assets/images/portfolio-1.jpg')">
                <div class="card-content">
                  <p class="card-subtitle">Youtube</p>
                  <h3 class="h3 card-title">Web Application for Desiverse</h3>
                </div>
              </a>
            </li>
            <li>
              <a href="#" class="portfolio-card" style="background-image: url('./assets/images/portfolio-2.jpg')">
                <div class="card-content">
                  <h3 class="h3 card-title">Web Application for Desiverse</h3>
                </div>
              </a>
            </li>
            <li>
              <a href="#" class="portfolio-card" style="background-image: url('./assets/images/portfolio-3.jpg')">
                <div class="card-content">
                  <h3 class="h3 card-title">Web Application for Desiverse</h3>
                </div>
              </a>
            </li>
          </ul>
        </div>
      </section>
      
      <!-- 
        - #CONTACT
      -->

      <section class="section contact" id="contact">
        <div class="container">
          <div class="contact-card">
            <p class="card-subtitle">contact us</p>
            <h2 class="h2 section-title">Drop Me a Line</h2>
            <div class="wrapper">
              <form action="" class="contact-form">
                <input type="text" name="name" placeholder="Name" required class="contact-input">
                <input type="email" name="email" placeholder="Email" required class="contact-input">
                <textarea name="message" placeholder="Message" required class="contact-input"></textarea>
                <button type="submit" class="btn-submit">Submit Message</button>
              </form>
              <ul class="contact-list">
                <li class="contact-item">
                  <div class="contact-icon">
                    <ion-icon name="location"></ion-icon>
                  </div>
                  <div>
                    <h3 class="contact-item-title">Address</h3>
                    <address class="contact-item-link">
                      Arakkonam,chennai.
                    </address>
                  </div>
                </li>
                <li class="contact-item">
                  <div class="contact-icon">
                    <ion-icon name="mail"></ion-icon>
                  </div>
                  <div>
                    <h3 class="contact-item-title">Email</h3>
                    <a href="bharath@gmail.com" class="contact-item-link">bharath@gmail.com</a>
                  </div>
                </li>
                <li class="contact-item">
                  <div class="contact-icon">
                    <ion-icon name="call"></ion-icon>
                  </div>
                  <div>
                    <h3 class="contact-item-title">Phone</h3>
                    <a href="755815364" class="contact-item-link">755 456 7890</a>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>

  <!-- 
    - #FOOTER
  -->

  <footer class="footer">
    <div class="container">
      <p class="copyright">
        &copy; 2022 <a href="#" class="copyright-link">Bharath</a>. All Rights Reseverd
      </p>
      <ul class="footer-list">
        <li>
          <a href="#" class="footer-link">Terms & Condition</a>
        </li>
        <li>
          <a href="#" class="footer-link">Privacy Policy</a>
        </li>
      </ul>
    </div>
  </footer>

  <!-- 
    - #BACK TO TOP
  -->
  <a href="#top" class="back-to-top" data-back-to-top>BACK TOP</a>
</body>
</html>
      
### Style.css
```css
:root {

/*-----------------------------------*\
  #HEADER
\*-----------------------------------*/

.header {
  position: fixed;
  padding-block: 15px;
  width: 100%;
  background-color: var(--space-cadet);
  height: 65px;
  box-shadow: var(--shadow);
  overflow: hidden;
  transition: 0.25s var(--cubic-out);
  z-index: 4;
}

.header.nav-active {
  height: 335px;
  transition-duration: 0.35s;
}

.header > .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  color: var(--white);
  font-family: var(--ff-poppins);
  font-size: 2.4rem;
}

/*-----------------------------------*\
  #HERO
\*-----------------------------------*/

.elem,
.rotate-img { display: none; }

.hero {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  padding-block: 100px var(--section-padding);
  min-height: 100vh;
  display: grid;
  place-items: center;
}

.hero-banner {
  width: 160px;
  height: 80px;
  background-color: var(--independence);
  border-radius: 40px;
  margin-inline: auto;
  margin-block-end: 30px;
}

.hero-banner img { border-radius: inherit; }

/*-----------------------------------*\
  #ABOUT
\*-----------------------------------*/

.abs-img,
.abs-icon { display: none; }

.about { padding-block-start: 120px; }

.about-banner {
  background-color: var(--independence);
  border-radius: var(--radius-10);
  margin-block-end: 30px;
}

/*-----------------------------------*\
  #PORTFOLIO
\*-----------------------------------*/

.portfolio .section-title { margin-block-end: 18px; }

.portfolio .section-text { margin-block-end: 80px; }

.portfolio-list {
  display: grid;
  gap: 60px;
}

.portfolio-card {
  background-color: var(--independence);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  padding: 120px 20px;
  border-radius: var(--radius-20);
  font-family: var(--ff-barlow);
  color: var(--white);
  font-weight: var(--fw-600);
  transition: var(--transition-2);
}

.portfolio-list > li:nth-child(even) .card-content { margin-inline-start: auto; }

/*-----------------------------------*\
  #CONTACT
\*-----------------------------------*/

.contact-card {
  background-color: var(--midnight-blue);
  padding: 50px 25px;
  border-radius: var(--radius-20);
}

.contact-card .card-subtitle {
  color: var(--orange-soda);
  font-family: var(--ff-barlow);
  font-size: var(--fs-4);
  font-weight: var(--fw-600);
}

.contact .section-title {
  text-align: left;
  margin-block-end: 30px;
}

.contact-form { margin-block-end: 50px; }

.contact-input {
  background-color: var(--white);
  color: var(--manatee);
  border-radius: var(--radius-5);
  padding: 15px 25px;
  font-size: var(--fs-5);
  margin-block-end: 15px;
}

/*-----------------------------------*\
  #BACK TO TOP
\*-----------------------------------*/

.back-to-top {
  color: var(--white);
  font-size: 1.3rem;
  position: fixed;
  bottom: 160px;
  right: -30px;
  transform: rotate(0.25turn);
  opacity: 0;
  visibility: hidden;
  transition: var(--transition-2);
  z-index: 1;
}

.back-to-top.active {
  right: -5px;
  opacity: 1;
  visibility: visible;
}

.back-to-top::after {
  content: "";
  position: absolute;
  top: 10px;
  left: calc(100% + 7px);
  width: 100px;
  height: 1px;
  background-color: var(--white);
}
```
## Output:-
![image](https://github.com/Bharath745/19AI545-Ex-01/assets/94508354/00e6f7e1-cd11-4212-8285-3533fd67eaa9)
![image](https://github.com/Bharath745/19AI545-Ex-01/assets/94508354/bced98f8-aad3-411d-b434-8d24d91c0bed)
![image](https://github.com/Bharath745/19AI545-Ex-01/assets/94508354/b3a20b7b-5418-4b9c-bd59-c598c17d8378)
![image](https://github.com/Bharath745/19AI545-Ex-01/assets/94508354/6574d9eb-9ce6-4ba3-8cba-e2ba94772f60)


## Result:-
Thus the program To created a web Portfolio/CV using HTML & CSS Successfully
