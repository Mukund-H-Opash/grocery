# grocery
grocery website html CSS and JavaScript 

# pull the code 
git pull origin main

# push the code 
git add .
git commit -m "Your commit message"
git push origin main


# pull lestest chnges 

git pull origin main --rebase

git add .
git rebase --continue
git push origin main


# act as pro coder and make class name start with  bd-  i submit my desing file also my html code wich is cover heder and footer so you have to just make between sectio as par given pdf file  and also made css for it also  html (<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Organic Grocery</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="../css/style.css" />
  </head>

  <body>
    <div class="header">
      <div class="top-header">
        <div class="text-left">
          Welcome to the best Troo Organic Grocery Store
        </div>

        <div class="text-center"><strong>50%</strong> Clearance Sale</div>

        <div class="social-icons">
          <div style="margin: 0px; text-wrap: nowrap; font-size: 1rem">
            Follow Us On
          </div>
          <div class="line"></div>
          <div class="social-icons-h">
            <span class="social-icon">
              <img src="../images/facebook.svg" alt="facebook" />
            </span>
            <span class="social-icon">
              <img src="../images/instagram.svg" alt="instagram" />
            </span>
            <span class="social-icon">
              <img src="../images/linkdin.svg" alt="linkedin" />
            </span>
            <span class="social-icon">
              <img src="../images/twitter.svg" alt="twitter" />
            </span>
          </div>
        </div>
      </div>

      <div class="serch-pannel">
        <div class="logo-banner">
          <img src="../images/Logo-Icon.svg" alt="logo" />
          <p><strong class="bold-green-text"> Organic </strong> Grocery</p>
        </div>
        <div class="serch-pannel-space"></div>
        <div class="serch-bar">
          <input type="search" placeholder="Search here..." />
          <button type="submit" class="search-button">
            <p>Search</p>
          </button>
        </div>

        <div class="contact-info">
          <div class="phone-number">
            <img src="../images/call.svg" alt="call" />
            <div class="contact-info-details-01">
              <p>Call Us on</p>
              <strong class="bold-green-text">+44 123 456 7890</strong>
            </div>
          </div>

          <div class="divider"></div>

          <div class="email-address">
            <img src="../images/email.svg" alt="email" />
            <div class="contact-info-details-02">
              <p>Email Us</p>
              <strong class="bold-green-text">info@troothemes.com</strong>
            </div>
          </div>
        </div>
      </div>

      <div class="divider02"></div>

      <div class="menu-wrap">
        <div class="menu-nav">
          <ul class="menu">
            <li class="menu-home">
              <a href="./index.html">Home</a>
            </li>

            <li class="menu-about">
              <a href="./about-us.html">About Us</a>
            </li>

            <li class="menu-shop">
              <a class="zero-right-margin">Shop</a>
              <img
                src="../images/down.svg"
                alt="dropdown"
                class="dropdown-icon"
              />

              <ul class="submenu-shop">
                <li class="submenu-shop-types">
                  <a>Shop Types</a>
                  <img
                    src="../images/down.svg"
                    alt="dropdown"
                    class="dropdown-icon"
                  />
                  <ul class="submenu-shop-types-list">
                    <li>
                      <a href="./our-products.html">Shop Right Sidebar</a>
                    </li>
                    <li><a href="./our-products.html">Shop Fullwidth</a></li>
                    <li><a href="./our-products.html">Shop Left Sidebar</a></li>
                  </ul>
                </li>
                <!-- chnage class name submenu-shop-types to submenu-woocommerce-pages -->
                <li class="submenu-shop-types">
                  <a>Product Types</a>
                  <img
                    src="../images/down.svg"
                    alt="dropdown"
                    class="dropdown-icon"
                  />
                  <ul class="submenu-product-types-list">
                    <li>
                      <a href="./product-detail.html">Shop Right Sidebar</a>
                    </li>
                    <li><a href="./product-detail.html">Shop Fullwidth</a></li>
                    <li>
                      <a href="./product-detail.html">Shop Left Sidebar</a>
                    </li>
                  </ul>
                </li>

                <li class="menu-single-product">
                  <a href="./product-detail.html">Single Product</a>
                </li>

                <li class="menu-product-category">
                  <a href="./our-products.html">Product Category</a>
                </li>

                <li class="menu-product-tag">
                  <a href="./our-products.html">Product Tag</a>
                </li>
                <!-- chnage class name submenu-shop-types to submenu-woocommerce-pages -->
                <li class="submenu-shop-types">
                  <a href="#">WooCommerce Pages</a>
                  <img
                    src="../images/down.svg"
                    alt="dropdown"
                    class="dropdown-icon"
                  />
                  <ul class="submenu-woocommerce-pages-list">
                    <li><a href="#">My Account</a></li>
                    <li><a href="./shopping_cart.html">Cart</a></li>
                    <li><a href="./checkkout.html">Checkout</a></li>
                  </ul>
                </li>
              </ul>
            </li>

            <li class="menu-products">
              <a href="./our-products.html">Products</a>
            </li>

            <li class="menu-pages">
              <a class="zero-right-margin">Pages</a>
              <img
                src="../images/down.svg"
                alt="dropdown"
                class="dropdown-icon"
              />
              <ul class="submenu-pages">
                <li><a href="./our-team.html">Our Team</a></li>
                <li><a href="./FAQs.html">FAQs</a></li>
                <li><a href="./testimonials.html">Testimonials</a></li>
                <li><a href="#">Order Tracking</a></li>
                <li><a href="#">Refund Policy</a></li>
                <li><a href="./coming-soon.html">Coming Soon</a></li>
                <li><a href="./404.html">404 Page</a></li>
              </ul>
            </li>

            <li class="menu-blog">
              <a class="zero-right-margin">Blog</a>
              <img
                src="../images/down.svg"
                alt="dropdown"
                class="dropdown-icon"
              />
              <ul class="submenu-blog">
                <li class="submenu-blogs-grid">
                  <a href="./blog-detail.html">Blogs Grid</a>
                  <img
                    src="../images/down.svg"
                    alt="dropdown"
                    class="dropdown-icon"
                  />
                  <ul class="submenu-blogs-grid-list">
                    <li><a href="./blog-detail.html">Blogs 2 Columns</a></li>
                    <li><a href="./blog-detail.html">Blogs 3 Column</a></li>
                    <li><a href="./blog-detail.html">Blogs 4 Columns</a></li>
                  </ul>
                </li>

                <li class="submenu-blogs-list">
                  <a>Blogs List</a>
                  <img
                    src="../images/down.svg"
                    alt="dropdown"
                    class="dropdown-icon"
                  />
                  <ul class="submenu-blogs-list-type">
                    <li>
                      <a href="./blog-detail.html">Blogs With Image Right</a>
                    </li>
                    <li>
                      <a href="./blog-detail.html">Blogs With Image Left</a>
                    </li>
                    <li><a href="./blog-detail.html">With Right Sidebar</a></li>
                    <li><a href="./blog-detail.html">With Left Sidebar</a></li>
                  </ul>
                </li>

                <li><a href="./blog.html">Blog Details</a></li>
                <li><a href="./blog.html">Author Page</a></li>
                <li><a href="./blog.html">Single Blog Category</a></li>
                <li><a href="./blog.html">Single Blog Tag</a></li>
              </ul>
            </li>

            <li class="menu-contact">
              <a href="./contact.html">Contact Us</a>
            </li>
          </ul>
        </div>

        <div class="header-button-icons">
          <a class="account-btn" href="#"> My Account </a>

          <a href="./checkkout.html" class="icon-link">
            <img src="../images/Wishlist.svg" alt="Wishlist" />
          </a>
          <a href="./shopping_cart.html" class="icon-link">
            <img src="../images/cart.svg" alt="Shopping cart" />
          </a>
        </div>
      </div>
    </div>
    <div class="main-content">
      <div class="content ab-content">
        <div class="ab-content-text contant-text">
          <div class="module-promo ab-module-promo">
            <div class="promo-description ab-promo-description">
              <h2>contact with us any time</h2>
              <a class="read-more" href="contact.html">
                <strong> Home - </strong>
                contact us
              </a>
            </div>
          </div>
        </div>
      </div>
    
      



      <section class="newsletter-section">
        <footer class="newsletter">
          <div class="container">
            <div class="Newsletter-heder">
              <h2 class="section-title-01">Subscribe to Newsletter</h2>
              <p class="section-description">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy tex
              </p>
            </div>

            <form class="newsletter-form">
              <input
                type="email"
                placeholder="Enter your email"
                class="email-input"
              />
              <button type="submit" class="subscribe-button">
                Subscribe Now
              </button>
            </form>
          </div>
        </footer>
      </section>

      <!-- Footer Section -->
      <div class="footer-section">
        <div class="footer-top">
          <div class="footer-contact">
            <div class="footer-logo"></div>
            <div class="contact-item">
              <span class="contact-icon">
                <img src="../images/call-us-Icon.svg" alt="call" />
              </span>
              <p class="contact-text">
                Call Us on<br />
                <strong>+44 123 456 7890</strong>
              </p>
            </div>
            <div class="contact-item">
              <span class="contact-icon">
                <img src="../images/email-Icon.svg" alt="email" />
              </span>
              <p class="contact-text">
                Email Us<br />
                <strong>contact@troothemes.com</strong>
              </p>
            </div>
          </div>
          <div class="vartical-line"></div>
          <div class="contact-item contact-item-social">
            <p class="contact-text">Follow Us On</p>
            <div class="horizonrol-line-001"></div>
            <div class="social-icons-f">
              <span class="social-icon-f"
                ><img src="../images/facebook.svg" alt="facebook"
              /></span>
              <span class="social-icon-f"
                ><img src="../images/instagram.svg" alt="instagram"
              /></span>
              <span class="social-icon-f"
                ><img src="../images/linkdin.svg" alt="linkdin"
              /></span>
              <span class="social-icon-f"
                ><img src="../images/twitter.svg" alt="twitter"
              /></span>
            </div>
          </div>
        </div>
        <div class="horizontol-line"></div>
        <div class="footer-middle">
          <div class="footer-column footer-column-01">
            <div class="footer-logo">
              <img src="../images/troo-grocery-logo.svg" alt="logo" />
              <h3 class="footer-title">troo Grocery</h3>
            </div>
            <p class="footer-description">
              Lorem Ipsum is simply dummy text of the since it is printing and
              typesetting’s the and it industry's standard dummy text ever since
              the 150.
            </p>
            <address class="footer-address">
              4516 School Street, Danbury,<br />
              CT, Canada, 458068
            </address>
          </div>
          <div class="footer-hyperlink">
            <div class="footer-column footer-coulmn-02">
              <h3 class="footer-title">Navigation</h3>
              <ul class="footer-links">
                <li><a href="index.html" class="footer-link">Homepage</a></li>
                <li>
                  <a href="./about_us.html" class="footer-link">About Us</a>
                </li>
                <li>
                  <a href="./our-products.html" class="footer-link"
                    >Our Products</a
                  >
                </li>
                <li>
                  <a href="./testimonials.html" class="footer-link"
                    >Our Testimonial</a
                  >
                </li>
                <li><a href="./blog.html" class="footer-link">Our Blogs</a></li>
              </ul>
            </div>

            <div class="footer-column footer-coulmn-02">
              <h3 class="footer-title">Customer Support</h3>
              <ul class="footer-links">
                <li>
                  <a href="./checkkout.html" class="footer-link">Order</a>
                </li>
                <li>
                  <a href="./shopping_cart.html" class="footer-link"
                    >Track Your Order</a
                  >
                </li>
                <li><a href="#" class="footer-link">Help & Support</a></li>
                <li><a href="#" class="footer-link">Shipping & Delivery</a></li>
                <li>
                  <a href="./contact.html" class="footer-link">Contact Us</a>
                </li>
              </ul>
            </div>

            <div class="footer-column footer-coulmn-02">
              <h3 class="footer-title">Categories</h3>
              <ul class="footer-links">
                <li>
                  <a href="./our-products.html" class="footer-link"
                    >Fresh Vegetables</a
                  >
                </li>
                <li>
                  <a href="./our-products.html" class="footer-link"
                    >Fresh Fruits</a
                  >
                </li>
                <li>
                  <a href="./our-products.html" class="footer-link"
                    >Fresh Beverage</a
                  >
                </li>
                <li>
                  <a href="./our-products.html" class="footer-link"
                    >Fresh Bakery Items</a
                  >
                </li>
                <li>
                  <a href="./our-products.html" class="footer-link"
                    >Neutral Drinks</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="footer-bottom">
          <p class="footer-copyright">
            Copyright © 2023. Themes. All rights reserved.
          </p>

          <div class="payment-methods">
            <span class="payment-icon"
              ><img src="../images/visa.svg" alt="visa"
            /></span>
            <span class="payment-icon">
              <img src="../images/master-card.svg" alt="mastercard"
            /></span>
            <span class="payment-icon"
              ><img src="../images/pay-pal.svg" alt="paypal"
            /></span>
            <span class="payment-icon"
              ><img src="../images/mestro.svg" alt="maestro"
            /></span>
            <span class="payment-icon"
              ><img src="../images/americon-express.svg" alt="american-express"
            /></span>
            <span class="payment-icon"
              ><img src="../images/visa-electron.svg" alt="visa-electron"
            /></span>
          </div>

          <ul class="footer-policy">
            <li><a href="#" class="policy-link">Privacy Policy</a></li>
            <li><a href="#" class="policy-link">Terms & Conditions</a></li>
          </ul>
        </div>
      </div>
    </div>
  </body>
</html>
)    use flex box properties and in image use path like (../images/and related name .svg ) do not use icon insted of use image  (for social media ) 

1)i think you forgot to add images so add it also 2) in  categories thre is left side name and right side number so the number you ca n see its images soadd it also 3) in tags there are more tags so add it 4)in reted blogs also there is image 5) in blogs there is 3 image so add it also any test style here  so blog have much more discription so add it also 5)
 ther is delivary banner also so make it  7)comment section 














 add details like working eith google hybridly and part time also full time employee at Opash software and technicle executiv at labgrownbox inc (Ny usa)