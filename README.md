# Zomato-clone-Landing-Page-

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Zomato logo in the tab -->
    <link
      rel="icon"
      type="image/x-icon"
      href="https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Zomato_logo.png/220px-Zomato_logo.png"
    />
    <!-- Font awesome icons -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
      integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <!-- Poppins font by google fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />
    <!-- Importing styles.css -->
    <link rel="stylesheet" href="/styles.css" />
    <title>Zomato Landing Page Clone </title>
  </head>
  <body>
      <!-- This is for hero-section -->
      <section class="hero__section">
        <header>
          <nav class="navbar">
            <a href="#">Get the App</a>
            <div class="navbar__menu_container">
              <a href="#" class="link">Inventor Relations</a>
              <a href="#" class="link">Add Restaurants</a>
              <a href="#" class="link">Login</a>
              <a href="#" class="link">Sign Up</a>
              <a href="#" class="user_icon">
                <i class="fa-solid fa-user"></i>
              </a>
            </div>
          </nav>
        </header>

        <div class="hero__section_container">
          <img src="./images/heroSectionLogo.png" alt="Zomato Logo" class="hero__section_logo"/>
          <img src="images/heroSectionLogo.png" alt="Zomato Logo" class="hero__section_logo"/>
          <h1 class="hero__section_title">Discover the best food & drinks in Hampi-Hospet</h1>
          <div class="hero__section_input_container">
            <input class="input_container_location" type="text" placeholder="Hampi-Hospet" />
            <input class="input_container_search" type="text" placeholder="Search for a restaurant, cuisine or a dish" />
          </div>
        </div>
      </section>
      <!-- This is for cards zomato offer -->
      <section class="container we__offer">
          <div class="we__offer_card">
              <img src="./images/item1.png" alt="card 1 img" />
              <img src="images/item1.png" alt="card 1 img" />
              <div class="we__offer_content">
                <h2>Order Online</h2>
                <p>Stay home and order to your doorstep</p>
              </div>
          </div>

          <div class="we__offer_card">
            <img src="./images/item2.png" alt="card 2 img" />
            <img src="images/item2.png" alt="card 2 img" />
            <div class="we__offer_content">
              <h2>Dining</h2>
              <p>View the citys favourite dining venue</p>
            </div>
        </div>

        <div class="we__offer_card">
          <img src="./images/item3.png" alt="card 3 img" />
          <img src="images/item3.png" alt="card 3 img" />
          <div class="we__offer_content">
            <h2>Nightlife and clubs</h2>
            <p>Explore the citys top nightlife outlets</p>
          </div>
      </div>

      <div class="we__offer_card">
        <img src="./images/item4.png" alt="card 4 img" />
        <img src="images/item4.png" alt="card 4 img" />
        <div class="we__offer_content">
          <h2>Order Online</h2>
          <p>Stay home and order to your doorstep</p>
        </div>
    </div>
      </section>
      <!-- Thisis for collection section -->
      <section class="container collections">
          <h1>Collection</h1>
          <div class="sub__heading_container">
            <span>Explore curated lists of top restaurants, cafes, pubs in Hospet-Hampi based on trends</span>
            <span>All collections in Hospet-Hampi</span>
          </div>
          <div class="collections_card_container">
            <div class="card card1">
            
              <div class="content">
                  <h4>Live Cricket Screening</h4>
                  <span>56 Places</span>
              </div>
              <div class="overlay"></div>
            </div>
            <div class="card card2">
              <div class="overlay"></div>
              <div class="content">
                  <h4>Malnad Special</h4>
                  <span>12 Places</span>
              </div>
            </div>
            <div class="card card3">
              <div class="overlay"></div>
              <div class="content">
                  <h4>Newly opened Restaurants</h4>
                  <span>36 Places</span>
              </div>
            </div>
            <div class="card card4">
              
              <div class="content">
                  <h4>Trending Pubs Near Me</h4>
                  <span>16 Places</span>
              </div>
              <div class="overlay"></div>
            </div>
          </div>
      </section>
      <!-- This is for get the app section -->
      <section class="container get__the_app">
        <div class="semiContainer">
            <div class="left">
              <img src="./images/mobileBanner.png" alt="Mobile Banner" />
              <img src="images/mobileBanner.png" alt="Mobile Banner" />
            </div>
            <div class="right">
              <h1>Get the Zomato App</h1>
              <p>We will send you a link, open it and download in your phone</p>
              <div class="radio__button_container">
                <div>
                  <input type="radio" id="email" name="download_app"/>
                  <label for="email" style="font-size: 14px;">Email</label>
                </div>
                <div>
                  <input type="radio" id="phone" name="download_app"/>
                  <label for="phone" style="font-size: 14px;">Phone</label>
                </div>
              </div>
              <div class="input_container">
                <input type="text" placeholder="Email"/>
                <button>Share App Link</button>
              </div>
              <div class="download__app_container">
                <h5>Download App From</h5>
                <diV>
                  <img src="./images/appleStore.png" alt="Apple Store" />
                  <img src="./images/playStore.png" alt="Playe Store" />
                  <img src="images/appleStore.png" alt="Apple Store" />
                  <img src="images/playStore.png" alt="Playe Store" />
                </diV>
              </div>
            </div>
        </div>
      </section>
      <!-- This is for the footer section -->
      <footer class="container footer">
          <div class="footer_section1">
              <img src="./images/logo.png" alt="zomato logo" />
              <img src="images/logo.png" alt="zomato logo" />
              <div class="section1__buttonContainer">
                  <button>
                    <img src="https://flagcdn.com/w40/in.png" alt="Indian Flag"  style="width: 15px"/>
                    India
                  </button>
                  <button><i class="fa fa-globe"></i>English</button>
              </div>
          </div>
          <div class="navigation_container">
            <div class="link__container">
              <h5>ABOUT ZOMATO</h5>
              <a class="footer__link" href="#">Who we are</a>
              <a class="footer__link" href="#">Blogs</a>
              <a class="footer__link" href="#">Work with us</a>
              <a class="footer__link" href="#">Investor Relations</a>
              <a class="footer__link" href="#">Report Fraud</a>
              <a class="footer__link" href="#">Contact Us</a>
            </div>
            <div class="link__container">
              <h5>ZOMAVERSE</h5>
              <a class="footer__link" href="#">Zomato</a>
              <a class="footer__link" href="#">Blinkit</a>
              <a class="footer__link" href="#">Feeding India</a>
              <a class="footer__link" href="#">Hyperpure</a>
              <a class="footer__link" href="#">Zomaland</a>
            </div>
            <div class="link__container">
              <h5>FOR RESTAURANTS</h5>
              <a class="footer__link" href="#">Partner With Us</a>
              <a class="footer__link" href="#">Apps for You</a>
              <br />
              <h5>FOR ENTERPRISES</h5>
              <a class="footer__link" href="#">Zomato For Work</a>
            </div>
            <div class="link__container">
              <h5>LEARN MORE</h5>
              <a class="footer__link" href="#">Privacy</a>
              <a class="footer__link" href="#">Security</a>
              <a class="footer__link" href="#">Terms</a>
              <a class="footer__link" href="#">Sitemap</a>
            </div>
            <div class="link__container">
                <h5>Social Media</h5>
                <div class="section__links_container">
                    <button><i class="fa-brands fa-linkedin-in"></i></button>
                    <button><i class="fa-brands fa-instagram"></i></button>
                    <button><i class="fa-brands fa-twitter"></i></button>
                    <button><i class="fa-brands fa-facebook"></i></button>
                    <button><i class="fa-brands fa-youtube"></i></button>
                </div>
                <br />
                <img src="./images/appleStore.png" alt="apple store" class="footer__section_logos" />
                <img src="./images/playStore.png" alt="play store" class="footer__section_logos" />
                <img src="images/appleStore.png" alt="apple store" class="footer__section_logos" />
                <img src="images/playStore.png" alt="play store" class="footer__section_logos" />
            </div>
          </div>
          <div>
          <div class="disclamer">
            By continuing past this page, you agree to our Terms of Service, Cookie Policy, Privacy Policy and Content Policies.
             All trademarks are properties of their respective owners. 2008-2023 © Zomato™ Ltd. All rights reserved.
          </div>
        </div>
      </footer>
  </body>
</html>

