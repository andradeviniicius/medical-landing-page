<template>
  <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
    <div class="container">
      <a class="navbar-brand logo-text" href="#">Med + Care</a>
      <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
        <ul class="navbar-nav ms-auto navbar-nav-scroll">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#header">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#details">Details</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="dropdown01" data-bs-toggle="dropdown"
              aria-expanded="false">More</a>
            <ul class="dropdown-menu" aria-labelledby="dropdown01">
              <li><a class="dropdown-item" href="#">About Us</a></li>
              <li>
                <div class="dropdown-divider"></div>
              </li>
              <li><a class="dropdown-item" href="#">Contact</a></li>
            </ul>
          </li>
        </ul>
        <span class="nav-item">
          <a class="btn-solid-sm" href="#contact">Book Appointment</a>
        </span>
      </div>
    </div>
  </nav>
  <header id="header" class="header">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <h1 class="h1-large">Schedule Your Medical Appointments</h1>
            <p class="p-large">
              Book appointments with ease and convenience. Get the care you need
              today.
            </p>
            <a class="btn-solid-lg" href="#services">Our Services</a>
          </div>
        </div>
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="assets/images/main-doctor.png" alt="medical professional" style="" />
          </div>
        </div>
      </div>
    </div>
  </header>
  <div id="services" class="cards-1 bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2>Explore Our Medical Services</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">
          <div class="card">
            <div class="d-flex align-items-center flex-column">

              <div class="card-icon">
                <span class="fas fa-stethoscope"></span>
              </div>
              <div class="card-body">
                <h5 class="card-title">General Checkups</h5>
                <p>
                  Regular health checkups are essential for maintaining your
                  well-being.
                </p>
                <a class="read-more no-line" href="#">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="d-flex align-items-center flex-column">
              <div class="card-icon red">
                <span class="far fa-heart"></span>
              </div>
              <div class="card-body">
                <h5 class="card-title">Cardiology Services</h5>
                <p>Specialized care for heart-related conditions and diseases.</p>
                <a class="read-more no-line" href="#">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="d-flex align-items-center flex-column">

              <div class="card-icon green">
                <span class="fas fa-user-md"></span>
              </div>
              <div class="card-body">
                <h5 class="card-title">Specialist Consultations</h5>
                <p>
                  Consult with experienced specialists for specific medical needs.
                </p>
                <a class="read-more no-line" href="#">Learn more <span class="fas fa-long-arrow-alt-right"></span></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="details" class="basic-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="assets/images/details-1.png" alt="medical equipment" />
          </div>
        </div>
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <div class="section-title">WHAT WE OFFER</div>
            <h2>Comprehensive Healthcare Services</h2>
            <p>
              Our medical professionals provide top-notch care and treatments
              for your well-being.
            </p>
            <a class="btn-solid-reg" href="#contact">Contact Us</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="basic-2">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-xl-5">
          <div class="text-container">
            <div class="section-title">ABOUT OUR MEDICAL SERVICE</div>
            <h2>Decades of Medical Expertise</h2>
            <p>
              Our team of experienced medical professionals has been dedicated
              to providing high-quality healthcare services for many years. We
              are committed to your health and well-being, offering top-notch
              medical care to all our patients. In sit amet nisi eget massa
              condimentum lobortis eget ac eros. In hac habitasse platea
              dictumst. Aenean molestie mauris eget sapien sagittis, a bibendum
              magna tincidunt.
            </p>
            <a class="btn-outline-reg" href="#">Learn More</a>
          </div>
        </div>
        <div class="col-lg-6 col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="assets/images/details-2.png" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="features" class="accordion-1">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <h2 class="h2-heading">Key Medical Service Features</h2>
          <p class="p-heading">
            Our medical service offers a range of essential features to ensure
            your well-being and health. Suspendisse vitae enim arcu. Aliquam
            convallis risus a felis blandit, at mollis nisi bibendum. Aliquam
            nec purus at ex blandit posuere nec a odio. Proin lacinia dolor
            justo.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-5">
          <div class="accordion" id="accordionExample">
            <div class="accordion-item">
              <div class="accordion-icon">
                <span class="fas fa-tv"></span>
              </div>
              <div class="accordion-header" id="headingOne">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne"
                  aria-expanded="true" aria-controls="collapseOne">
                  Comprehensive Medical Analysis
                </button>
              </div>
              <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  We conduct thorough medical analyses and design personalized
                  healthcare plans tailored to your needs. Mauris ornare libero
                  et pharetra hendrerit. Cura elementum lectus quis tellus
                  pretium, vitae lobortis dui sagittis aliquam et enim vel semon
                  anticus.
                </div>
              </div>
            </div>

            <div class="accordion-item">
              <div class="accordion-icon blue">
                <span class="fas fa-microphone"></span>
              </div>
              <div class="accordion-header" id="headingTwo">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo"
                  aria-expanded="false" aria-controls="collapseTwo">
                  Identifying Health Opportunities
                </button>
              </div>
              <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  We help you discover potential health opportunities and
                  provide guidance on how to address them. Mauris ornare libero
                  et pharetra hendrerit. Cura elementum lectus quis tellus
                  pretium, vitae lobortis dui sagittis aliquam et enim vel semon
                  anticus.
                </div>
              </div>
            </div>

            <div class="accordion-item">
              <div class="accordion-icon purple">
                <span class="fas fa-video"></span>
              </div>
              <div class="accordion-header" id="headingThree">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree"
                  aria-expanded="false" aria-controls="collapseThree">
                  Productive Health Campaigns
                </button>
              </div>
              <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  We work on preparing effective health campaigns to promote
                  your overall well-being. Mauris ornare libero et pharetra
                  hendrerit. Cura elementum lectus quis tellus pretium, vitae
                  lobortis dui sagittis aliquam et enim vel semon anticus.
                </div>
              </div>
            </div>

            <div class="accordion-item">
              <div class="accordion-icon orange">
                <span class="fas fa-tools"></span>
              </div>
              <div class="accordion-header" id="headingFour">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour"
                  aria-expanded="false" aria-controls="collapseFour">
                  Continuous Monitoring and Adjustment
                </button>
              </div>
              <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour"
                data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  We continuously evaluate your health campaign's progress and
                  make adjustments to ensure the best outcomes. Mauris ornare
                  libero et pharetra hendrerit. Cura elementum lectus quis
                  tellus pretium, vitae lobortis dui sagittis aliquam et enim
                  vel semon anticus.
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-7">
          <div class="image-container">
            <img class="img-fluid" src="assets/images/features-dashboard.png" alt="alternative" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="cards-2 bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h2 class="h2-heading">Customer testimonials</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12">
          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">
                The medical care I received was exceptional. I'm grateful for
                the dedicated team.
              </p>
              <div class="testimonial-author">Roe Smith</div>
            </div>
            <div class="gradient-floor red-to-blue"></div>
          </div>

          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">
                The staff is friendly and professional. They made me feel
                comfortable throughout my treatment
              </p>
              <div class="testimonial-author">Sam Bloom</div>
            </div>
            <div class="gradient-floor blue-to-purple"></div>
          </div>

          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">
                I can't thank the medical service enough for their support
                during my recovery
              </p>
              <div class="testimonial-author">Bill McKenzie</div>
            </div>
            <div class="gradient-floor purple-to-green"></div>
          </div>

          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">
                Their expertise and care have made a significant difference in
                my life.
              </p>
              <div class="testimonial-author">Vanya Dropper</div>
            </div>
            <div class="gradient-floor red-to-blue"></div>
          </div>

          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">
                I appreciate the personalized approach to my health. Highly
                recommend!
              </p>
              <div class="testimonial-author">Lefty Brown</div>
            </div>
            <div class="gradient-floor blue-to-purple"></div>
          </div>

          <div class="card">
            <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
            <div class="card-body">
              <p class="testimonial-text">
                The medical team is top-notch. They truly go above and beyond
                for their patients.
              </p>
              <div class="testimonial-author">Susane Blake</div>
            </div>
            <div class="gradient-floor purple-to-green"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="slider-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h4>
            Trusted by over <span class="blue">5000</span> customers worldwide
          </h4>
          <hr class="section-divider" />

          <div class="slider-container">
            <div class="swiper-container image-slider">
              <div class="swiper-wrapper">
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-1.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-2.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-3.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-4.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-5.png" alt="alternative" />
                </div>
                <div class="swiper-slide">
                  <img class="img-fluid" src="assets/images/customer-logo-6.png" alt="alternative" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="basic-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="text-container">
            <h2>Find the Right Medical Service for Your Needs</h2>
            <p class="p-large">
              We understand the importance of your health. Our team is dedicated to providing top-quality medical services
              to ensure your well-being.
            </p>
            <a class="btn-solid-lg" href="#contact">Get Free Consultation</a>

          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="contact" class="form-1">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="text-container">
            <div class="section-title">REQUEST A FREE CONSULTATION</div>
            <h2>Submit the form for a consultation</h2>
            <p>
              We are here to assist you with your medical concerns. Our team is dedicated to your health and well-being.
            </p>
            <ul class="list-unstyled li-space-lg">
              <li class="d-flex">
                <i class="fas fa-square"></i>
                <div class="flex-grow-1">
                  We provide expert guidance and care to address your healthcare needs.
                </div>
              </li>
              <li class="d-flex">
                <i class="fas fa-square"></i>
                <div class="flex-grow-1">
                  Our experienced medical professionals are ready to assist you.
                </div>
              </li>
              <li class="d-flex">
                <i class="fas fa-square"></i>
                <div class="flex-grow-1">
                  Get in touch with us today to schedule your free consultation.
                </div>
              </li>
            </ul>
          </div>

        </div>
        <div class="col-lg-6">
          <form>
            <div class="form-group">
              <input type="text" class="form-control-input" placeholder="Name" required />
            </div>
            <div class="form-group">
              <input type="email" class="form-control-input" placeholder="Email" required />
            </div>
            <div class="form-group">
              <input type="tel" class="form-control-input" placeholder="Your Phone" required />
            </div>
            <div class="form-group">
              <button type="submit" class="form-control-submit-button">
                Submit
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
  <div class="footer bg-gray">
    <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <h4>
            If you want to find out which are the right influencers for your
            product marketing campaigns then follow us
          </h4>
          <div class="social-container">
            <span class="fa-stack">
              <a href="#your-link">
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-facebook-f fa-stack-1x"></i>
              </a>
            </span>
            <span class="fa-stack">
              <a href="#your-link">
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-twitter fa-stack-1x"></i>
              </a>
            </span>
            <span class="fa-stack">
              <a href="#your-link">
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-pinterest-p fa-stack-1x"></i>
              </a>
            </span>
            <span class="fa-stack">
              <a href="#your-link">
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-instagram fa-stack-1x"></i>
              </a>
            </span>
            <span class="fa-stack">
              <a href="#your-link">
                <i class="fas fa-circle fa-stack-2x"></i>
                <i class="fab fa-youtube fa-stack-1x"></i>
              </a>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="copyright bg-gray">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-md-12 col-sm-12">
          <ul class="list-unstyled li-space-lg p-small">
            <li><a href="#">Article Details</a></li>
            <li><a href="#">Terms & Conditions</a></li>
            <li><a href="#">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-12 col-sm-12">
          <p class="p-small statement">
            Copyright © <a href="#">Masuk Mia </a>
          </p>
        </div>
        <div class="col-lg-3 col-md-12 col-sm-12">
          <p class="p-small statement">
            Distributed by
            <a href="https://masukmia.com" target="_blank">Masuk Mia </a>
          </p>
        </div>
      </div>
    </div>
  </div>
  <button id="myBtn">
    <img src="assets/images/up-arrow.png" alt="alternative" />
  </button>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
