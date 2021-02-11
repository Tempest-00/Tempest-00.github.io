<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vasquez Services</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@800&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,400;0,700;0,900;1,400;1,700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>

<nav>
    <input type="checkbox" id="check">
    <label for="check" class="checkbtn">
        <i class="fas fa-bars"></i>
    </label>
    <!--<label for="" class="logo">Vasquez Services</label>-->
    <a href="index.html" class="logo-link"><img class= "header-logo" src="/Projects/VASQTAX/icons/Logo.png" alt="Vasquez Services, 781-599-8877"> </a>
    <ul>
        <li><a href="apply.html">Apply To File!</a></li>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="forms.html">Forms</a></li>
        <li><a href="FAQ.html">FAQ</a></li>
        <li><a href="index.html#contact">Contact</a></li>
    </ul>
</nav>
    <p class="notice">Notice: <br>
        Due to Covid-19 restrictions, all filings will be made through
            distance work, or through scheduled appointment, unless stated otherwise. <br>
            Thank you for your patience.</p>
<main>
   <section class="hero">
       <header class="hero-text">
           <h1 class="hero-title">Personal Tax Filings, <br>with experienced people.</h1>
        </header>
            <div class="hero-p-container">
                <div class="greenlines"> <hr> <hr> </div>
                <p class="hero-p"> Vasquez Services has been serving clients for 20 years. Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis quis, ratione exercitationem in necessitatibus ullam, nulla id deleniti ipsum minus laudantium dolore commodi sed optio, voluptas doloribus harum officiis? Eaque!</p>
            </div>
       <!--<div class="herotron__hero-portrait"> 
           <img src="/Projects/VASQTAX/imgs/portraitsquare.png" alt="portrait of mario vasquez">
           <h4>Mario Vasquez-Owner</h4> -->
       </div>
   </section>

   <section id="services" class="services">
       <header>
           <h2 class="section-title">Our Services</h2>
       </header>
       <div class="serv-grid">
        <a href="#" class="btn2 serv-btn">
          <div class="service">  
            <img src="/Projects/VASQTAX/icons/Taxes.svg" alt="" class="serv-img">
              <h4>Tax Preparations</h4>
          </div> </a>

          <a href="#" class="btn2 serv-btn">
          <div class="service">
            <img src="/Projects/VASQTAX/icons/Notarizations.svg" alt="" class="serv-img">
              <h4>Notarizations</h4>
          </div> </a>
          
          <a href="#" class="btn2 serv-btn">
          <div class="service">
            <img src="/Projects/VASQTAX/icons/Translations.svg" alt="" class="serv-img">
              <h4>Translations</h4>
          </div> </a>
          
          <a href="#" class="btn serv-btn">
          <div class="service">
            <img src="/Projects/VASQTAX/icons/Immigration.svg" alt="" class="serv-img">
              <h4>Immigration Papers</h4>
          </div> </a>

          <a href="services.html" class="serv-all">
            <div class="">
                <h4>See all of our services</h4>
            </div> </a>
        </div>
   </section>

   <section id="about" class="about-us">
        <header>
            <h2 class="section-title"> About Us</h2>
        </header>
        <div class="abt-article1">
            <img  class="abt-portrait" src="/Projects/VASQTAX/imgs/portraitsquare.png" alt="Portrait of Mario Vasquez">
            <div><h3>Who we are</h3>
            <p>Mario Vasquez, the owner of Vasquez Services, has been serving the populus for over 20 years. Highly experienced and thorough with every tax filing, translation, or financial advisory, a staple point of Mario's work method is to make sure each client is personally taken care of.</p> 
            <br>
            <p>Mario, with a masters of national finances, an engineer, and long-time business owner.</p> </div>
        </div>
        <div class="abt-article2">
            <img class="abt-office" src="/Projects/VASQTAX/imgs/building.PNG" alt="">
            <div><h3>Where we are</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Pariatur iusto illum ad beatae laboriosam voluptatem atque sit fugiat perspiciatis eos eveniet, adipisci consectetur ut, laborum accusamus aspernatur quis mollitia. Nam?</p>
            <br>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eveniet alias distinctio quis praesentium ipsam, earum aut vel beatae culpa aliquid hic et soluta cumque maiores dicta illo! Debitis, molestias? Impedit.</p>
            </div>
        </div>
   </section>

   <section  id="contact" class="contact-us">
      <header>
        <h2 class="section-title">Contact Us</h2>
      </header>
      <p>Feel free to inquire with us, we respond to all messages during normal business hours.</p>
      <p><em>Fields marked with an asterisk (*) are required</em></p>
    <div class="form-container">
      <form id="contact-form" name="contact" data-name="Contact Form"  method="GET" action="VSformresults.html">
        <div class="contact-form-grid">
          <div id="contact-block">
            <label for="first-name">First Name *</label>
            <input type="text" class="contact-input" name="first-name" data-name="First Name" id="first-name" required="">
          </div>
          <div id="contact-block">
            <label for="last-name">Last Name *</label>
            <input type="text" class="contact-input" name="last-name" data-name="Last Name" id="last-name" required="">
          </div>
          <div id="contact-block">
            <label for="email">Email *</label>
            <input type="email" class="contact-input" name="email" data-name="Email" id="email" placeholder="Ex. VasquezServices@pm.me" required="">
          </div>
          <div id="contact-block">
            <label for="phonenumber">Phone number</label>
            <input type="tel" class="contact-input" name="phonenumber" data-name="Contact Phone Number" id="phonenumber"  placeholder="Ex. (781)-599-8877" pattern="[0-9]{3}-{0-9}{3}-[0-9]{4}">
          </div>
          <div id="contact-block">
            <label for="message">Message *</label>
            <textarea data-name="Message" id="message" name="message" class="contact-input" placeholder="Ask any questions here."></textarea>
          </div>
        </div>
        <input type="submit" value="Submit" data-wait="Please wait..." class="submit-button">
        <input type="reset" value="Reset" class="reset-button">
      </form>
      <div class="contact-form-done">
        <div> Thank you! Your submission has been recieved!</div>
      </div>
      <div class="contact-form-fail">
        <div>Something went wrong while submitting the form. Please try again.</div>
      </div>
    </div>
          <!--<input type="text" class="contact-input" maxlength="256" name="" data-name="" id="" required=""></div> -->
   </section>

</main>

   <footer>
    <ul role="list" class=footer-nav>
        <li class="list-item"><a href="#" class="footer-link">Home</a></li>
        <li class="list-item"><a href="#about" class="footer-link">About</a></li>
        <li class="list-item"><a href="#contact" class="footer-link">Contact</a></li>
        <li class="list-item"><a href="FAQ.html" class="footer-link">FAQ</a></li>
        <li class="list-item"><a href="forms.html" class="footer-link">Forms</a></li>
        <li class="list-item"><a href="services.html" class="footer-link">Services</a></li>
      </ul>

    <ul class="footer-social">
        <li><a class="social-link" href="#"> 
          <img 
          src="/Projects/VASQTAX/icons/facebookicon.svg" 
          class="footer-icon" 
          aria-label="Facebook"> 
          </a></li>
        
          <li><a class="social-link" href="https://goo.gl/maps/aE9fYRKy14jyf4wv5"> 
          <img src="/Projects/VASQTAX/icons/gmaps.svg" 
          class="footer-icon" 
          aria-label="GoogleMaps"> 
         </a></li>
    </ul>
   <!-- <p style="">Copyright © 2020 Vasquez Services. All rights reserved.</p> -->
   </footer>
  </body>

 
</html>
