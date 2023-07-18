<script setup>

// Site Default
const siteDefault = {
  logo: 'SoftLand',
  url: 'index.html'
}

// Nav Items
const navigation = ["Home", "About Us", "How It Works", "Features", "Contact Us"]
const navUrl = {
  aboutUrl: '#about',
  howWorksUrl: '#howworks',
  featureUrl: '#feature',
  contactUrl: '#contact-us'
}

// Hero Section
const heroSection = {
  title: 'Promote Your App with SoftLand',
  description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
}
const heroPhoneImg = [
  'assets/img/phone_1.png',
  'assets/img/phone_2.png'
]
const heroBtn = {
  text: 'Get started',
  url: '#'
}
// About Section 
const siteAbout = 'Save your time to using SoftLand'
const cardTitle = [
  'Explore Your Team',
  'Digital Whiteboard',
  'Design To Development'
]
const cardDesc = [
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.',
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.',
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.'
]

// How It Works Section
const howIt = {
  title: 'How It Works?',
  image: 'assets/img/undraw_svg_1.svg',
}

const stepNum = ["01", "02", "03"]
const stepTitle = [
  'Sign Up',
  'Create Profile',
  'Enjoy the app'
]
const stepDesc = [
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.',
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.',
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem, optio.'
]

// Feature Section
const featureTitle = 'Our Features'
const featureWidgetTitle = [
  'Seamlessly Communicate',
  'Gather Feedback'
]
const featureWidgetDesc = [
  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur at reprehenderit optio, laudantium eius quod, eum maxime molestiae porro omnis. Dolores aspernatur delectus impedit incidunt dolore mollitia esse natus beatae.',

  'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur at reprehenderit optio, laudantium eius quod, eum maxime molestiae porro omnis. Dolores aspernatur delectus impedit incidunt dolore mollitia esse natus beatae.'
]
const featureBtnText = 'Download Now'
const featureImg = [
  'assets/img/undraw_svg_2.svg',
  'assets/img/undraw_svg_3.svg'
]

// Testimonial Start
const testimonialTitle = 'Review From Our Users'
const star = 'bi bi-star-fill'

const reviewInfo = {
  title: 'Excelent App!',
  comment: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius ea delectus pariatur, numquam',
  image: 'assets/img/person_2.jpg',
  userName: 'John Doe',
  userDesig: 'App User' 
}

// Contact Section
const contactTitle = 'Contact Us'
const formInfo = {
  title: 'Contact Form',
  desc: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam necessitatibus incidunt ut officiis explicabo inventore.'
}
const aboutData = {
  widgetName: ['Address', 'Phone', 'Email'],
  widgetValue: ['203 Fake St. Mountain View, San Francisco, California, USA', '+1 232 3235 324', 'youremail@domain.com']
}
const formData = ['Name', 'Email', 'Subject', 'Message']
const formInpuType = ['text', 'email', 'submit']
const formInpuName = ['name', 'email', 'subject', 'subject']
const sentMessage = [
  'Loading',
  'Something went wrong',
  'Your message has been sent. Thank you!'
]
const sendBtnValue = 'Send Message'


// CTA Section
const ctaTitle = 'Starts Publishing Your Apps'
const ctaBtnIcon = ['bx bxl-apple', 'bx bxl-play-store']
const ctaBtnText = ['App store', 'Google play']

// Footer Section
const footerWidgetTitle = ['About SoftLand', 'Navigation', 'Services', 'Downloads']

const footerDesc = 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius ea delectus pariatur, numquam aperiam dolore nam optio dolorem facilis itaque voluptatum recusandae deleniti minus animi.'

const socialIcons = {
  twitter: 'bi bi-twitter',
  facebook: 'bi bi-facebook',
  instagram: 'bi bi-instagram',
  linkdin: 'bi bi-linkedin'
}

const footerWidget1 = ['Pricing', 'Features', 'Blog', 'Contact']
const footerWidgetUrl1 = [
  '#',
  '#',
  '#',
  '#'
]
const footerWidget2 = ['Team', 'Collaboration', 'Todos', 'Events']
const footerWidgetUrl2 = [
  '#',
  '#',
  '#',
  '#'
]
const footerDownload = {
  appStore: 'Get from the App Store',
  playStore: 'Get from the Play Store',
  appStoreLink: '#',
  playStoreLink: '#'
}

// Copyright Section
const copyrightText = 'Copyright SoftLand. All Rights Reserved'

</script>

<template>
  <!-- ======= Header ======= -->
  <header id="header" class="fixed-top d-flex align-items-center">
    <div class="container d-flex justify-content-between align-items-center">
      <div class="logo">
        <h1>
          <a :href="siteDefault.url"> {{ siteDefault.logo }} </a>
        </h1>
      </div>

      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="active " :href="siteDefault.url">{{ navigation[0] }}</a></li>
          <li><a :href="navUrl.aboutUrl">{{ navigation[1] }}</a></li>
          <li><a :href="navUrl.howWorksUrl">{{ navigation[2] }}</a></li>
          <li><a :href="navUrl.featureUrl">{{ navigation[3] }}</a></li>
          <li><a :href="navUrl.contactUrl">{{ navigation[4] }}</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

    </div>
  </header>
  <!-- End Header -->

  <!-- ======= Hero Section ======= -->
  <section class="hero-section" id="hero">
    <div class="wave">
      <svg width="100%" height="355px" viewBox="0 0 1920 355" version="1.1" xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink">
        <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
          <g id="Apple-TV" transform="translate(0.000000, -402.000000)" fill="#FFFFFF">
            <path
              d="M0,439.134243 C175.04074,464.89273 327.944386,477.771974 458.710937,477.771974 C654.860765,477.771974 870.645295,442.632362 1205.9828,410.192501 C1429.54114,388.565926 1667.54687,411.092417 1920,477.771974 L1920,757 L1017.15166,757 L0,757 L0,439.134243 Z"
              id="Path">
            </path>
          </g>
        </g>
      </svg>

    </div>

    <div class="container">
      <div class="row align-items-center">
        <div class="col-12 hero-text-image">
          <div class="row">
            <div class="col-lg-8 text-center text-lg-start">
              <h1 data-aos="fade-right">{{ heroSection.title }}</h1>
              <p class="mb-5" data-aos="fade-right" data-aos-delay="100">{{ heroSection.description }}</p>
              <p data-aos="fade-right" data-aos-delay="200" data-aos-offset="-500">
                <a target="_blank" :href="heroBtn.url" class="btn btn-outline-white">
                  {{ heroBtn.text }}
                </a>
              </p>
            </div>
            <div class="col-lg-4 iphone-wrap">
              <img :src="heroPhoneImg[0]" alt="Image" class="phone-1" data-aos="fade-right">
              <img :src="heroPhoneImg[1]" alt="Image" class="phone-2" data-aos="fade-right" data-aos-delay="200">
            </div>
          </div>
        </div>
      </div>
    </div>

  </section>
  <!-- End Hero -->

  <main id="main">

    <!-- ======= Home Section ======= -->
    <section id="about" class="section">
      <div class="container">

        <div class="row justify-content-center text-center mb-5">
          <div class="col-md-5" data-aos="fade-up">
            <h2 class="section-heading">{{ siteAbout }}</h2>
          </div>
        </div>

        <div class="row">
          <div class="col-md-4" data-aos="fade-up" data-aos-delay="">
            <div class="feature-1 text-center">
              <div class="wrap-icon icon-1">
                <i class="bi bi-people"></i>
              </div>
              <h3 class="mb-3">{{ cardTitle[0] }}</h3>
              <p>{{ cardDesc[0] }}</p>
            </div>
          </div>
          <div class="col-md-4" data-aos="fade-up" data-aos-delay="100">
            <div class="feature-1 text-center">
              <div class="wrap-icon icon-1">
                <i class="bi bi-brightness-high"></i>
              </div>
              <h3 class="mb-3">{{ cardTitle[1] }}</h3>
              <p>{{ cardDesc[1] }}</p>
            </div>
          </div>
          <div class="col-md-4" data-aos="fade-up" data-aos-delay="200">
            <div class="feature-1 text-center">
              <div class="wrap-icon icon-1">
                <i class="bi bi-bar-chart"></i>
              </div>
              <h3 class="mb-3">{{ cardTitle[2] }}</h3>
              <p>{{ cardDesc[2] }}</p>
            </div>
          </div>
        </div>

      </div>
    </section>

<!-- How It Works Start -->
    <section id="howworks" class="section">
      <div class="container">
        <div class="row justify-content-center text-center mb-5">
          <div class="col-md-5" data-aos="fade-up">
            <h2 class="section-heading">{{ howIt.title }}</h2>
          </div>
        </div>
        <div class="row justify-content-center text-center mb-5" data-aos="fade">
          <div class="col-md-6 mb-5">
            <img :src="howIt.image" alt="Image" class="img-fluid">
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <div class="step">
              <span class="number">{{ stepNum[0] }}</span>
              <h3>{{ stepTitle[0] }}</h3>
              <p>{{ stepDesc[0] }}</p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="step">
              <span class="number">{{ stepNum[1] }}</span>
              <h3>{{ stepTitle[1] }}</h3>
              <p>{{ stepDesc[1] }}</p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="step">
              <span class="number">{{ stepNum[2] }}</span>
              <h3>{{ stepTitle[2] }}</h3>
              <p>{{ stepDesc[2] }}</p>
            </div>
          </div>
        </div>
      </div>

    </section>

<!-- Feature Start -->
    <section id="feature" class="section">
      <div class="container">
        <div class="row justify-content-center text-center mb-5">
          <div class="col-md-5" data-aos="fade-up">
            <h2 class="section-heading">{{ featureTitle }}</h2>
          </div>
        </div>
        <div class="row align-items-center">
          <div class="col-md-4 me-auto">
            <h2 class="mb-4">{{ featureWidgetTitle[0] }}</h2>
            <p class="mb-4">{{ featureWidgetDesc[0] }}</p>
            <p><a href="#" class="btn btn-primary">{{ featureBtnText }}</a></p>
          </div>
          <div class="col-md-6" data-aos="fade-left">
            <img :src="featureImg[0]" alt="Image" class="img-fluid">
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-4 ms-auto order-2">
            <h2 class="mb-4">{{ featureWidgetTitle[1] }}</h2>
            <p class="mb-4">{{ featureWidgetDesc[1] }}</p>
            <p><a href="#" class="btn btn-primary">{{ featureBtnText }}</a></p>
          </div>
          <div class="col-md-6" data-aos="fade-right">
            <img :src=featureImg[1] alt="Image" class="img-fluid">
          </div>
        </div>
      </div>
    </section>

    <!-- ======= Testimonials Section ======= -->
    <section class="section border-top border-bottom">
      <div class="container">
        <div class="row justify-content-center text-center mb-5">
          <div class="col-md-4">
            <h2 class="section-heading">{{testimonialTitle}}</h2>
          </div>
        </div>
        <div class="row justify-content-center text-center">
          <div class="col-md-7">

            <div class="testimonials-slider swiper" data-aos="fade-up" data-aos-delay="100">
              <div class="swiper-wrapper">

                <div class="swiper-slide">
                  <div class="review text-center">
                    <p class="stars">
                      <span :class=star></span>
                      <span :class=star></span>
                      <span :class=star></span>
                      <span :class=star></span>
                      <span :class= star class="muted"></span>
                    </p>
                    <h3>{{ reviewInfo.title }}</h3>
                    <blockquote>
                      <p>{{ reviewInfo.comment }}</p>
                    </blockquote>

                    <p class="review-user">
                      <img :src="reviewInfo.image" alt="Image" class="img-fluid rounded-circle mb-3">
                      <span class="d-block"> {{ reviewInfo.userName }}
                        <span class="text-black"></span>, &mdash; {{reviewInfo.userDesig}}
                      </span>
                    </p>

                  </div>
                </div><!-- End testimonial item -->

                <div class="swiper-slide">
                  <div class="review text-center">
                    <p class="stars">
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill muted"></span>
                    </p>
                    <h3>This App is easy to use!</h3>
                    <blockquote>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius ea delectus pariatur, numquam
                        aperiam dolore nam optio dolorem facilis itaque voluptatum recusandae deleniti minus animi,
                        provident voluptates consectetur maiores quos.</p>
                    </blockquote>

                    <p class="review-user">
                      <img src="assets/img/person_2.jpg" alt="Image" class="img-fluid rounded-circle mb-3">
                      <span class="d-block">
                        <span class="text-black">Johan Smith</span>, &mdash; App User
                      </span>
                    </p>

                  </div>
                </div><!-- End testimonial item -->

                <div class="swiper-slide">
                  <div class="review text-center">
                    <p class="stars">
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill"></span>
                      <span class="bi bi-star-fill muted"></span>
                    </p>
                    <h3>Awesome functionality!</h3>
                    <blockquote>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eius ea delectus pariatur, numquam
                        aperiam dolore nam optio dolorem facilis itaque voluptatum recusandae deleniti minus animi,
                        provident voluptates consectetur maiores quos.</p>
                    </blockquote>

                    <p class="review-user">
                      <img src="assets/img/person_3.jpg" alt="Image" class="img-fluid rounded-circle mb-3">
                      <span class="d-block">
                        <span class="text-black">Jean Thunberg</span>, &mdash; App User
                      </span>
                    </p>

                  </div>
                </div><!-- End testimonial item -->

              </div>
              <div class="swiper-pagination"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Testimonials Section -->

    <!-- ======= Contact Us Section ======= -->
    <section id="contact-us" class="section">
      <div class="container">
        <div class="row justify-content-center text-center mb-5">
          <div class="col-md-4">
            <h2 class="section-heading">{{ contactTitle }}</h2>
          </div>
        </div>
        <div class="row mb-5 align-items-end">
          <div class="col-md-6" data-aos="fade-up">

            <h2>{{formInfo.title}}</h2>
            <p class="mb-0">{{ formInfo.desc }}</p>
          </div>

        </div>

        <div class="row">
          <div class="col-md-4 ms-auto order-2" data-aos="fade-up">
            <ul class="list-unstyled">
              <li class="mb-3">
                <strong class="d-block mb-1">{{aboutData.widgetName[0]}}</strong>
                <span>{{aboutData.widgetValue[0]}}</span>
              </li>
              <li class="mb-3">
                <strong class="d-block mb-1">{{aboutData.widgetName[1]}}</strong>
                <span>{{aboutData.widgetValue[1]}}</span>
              </li>
              <li class="mb-3">
                <strong class="d-block mb-1">{{aboutData.widgetName[2]}}</strong>
                <span>{{aboutData.widgetValue[2]}}</span>
              </li>
            </ul>
          </div>

          <div class="col-md-6 mb-5 mb-md-0" data-aos="fade-up">
            <form action="forms/contact.php" method="post" role="form" class="php-email-form">

              <div class="row">
                <div class="col-md-6 form-group">
                  <label for="name">{{formData[0]}}</label>
                  <input :type='formInpuType.text' name="name" class="form-control" id="name" required>
                </div>
                <div class="col-md-6 form-group mt-3 mt-md-0">
                  <label for="name">{{formData[1]}}</label>
                  <input :type='formInpuType.email' class="form-control" name="email" id="email" required>
                </div>
                <div class="col-md-12 form-group mt-3">
                  <label for="name">{{formData[2]}}</label>
                  <input :type='formInpuType.text' class="form-control" name="subject" id="subject" required>
                </div>
                <div class="col-md-12 form-group mt-3">
                  <label for="name">{{formData[3]}}</label>
                  <textarea class="form-control" name="message" required></textarea>
                </div>

                <div class="col-md-12 mb-3">
                  <div class="loading">{{sentMessage[0]}}</div>
                  <div class="error-message">{{sentMessage[1]}}</div>
                  <div class="sent-message">{{sentMessage[2]}}</div>
                </div>

                <div class="col-md-6 form-group">
                  <input :type='formInpuType[2]' class="btn btn-primary d-block w-100" :value="sendBtnValue">
                </div>
              </div>

            </form>
          </div>

        </div>
      </div>
    </section>
    <!-- End Of Contact Us  -->

    <!-- ======= CTA Section ======= -->
    <section class="section cta-section">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-6 me-auto text-center text-md-start mb-5 mb-md-0">
            <h2>{{ ctaTitle }}</h2>
          </div>
          <div class="col-md-5 text-center text-md-end">
            <p>
              <a href="#" class="btn d-inline-flex align-items-center">
                <i :class='ctaBtnIcon[0]'></i>
                <span>{{ ctaBtnText[0] }}</span>
              </a> 
              <a href="#" class="btn d-inline-flex align-items-center">
                <i :class='ctaBtnIcon[1]'></i>
                <span>{{ ctaBtnText[1] }}</span>
              </a>
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- End CTA Section -->

  </main>
  <!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer class="footer" role="contentinfo">
    <div class="container">
      <div class="row">
        <div class="col-md-4 mb-4 mb-md-0">
          <h3>{{ footerWidgetTitle[0] }}</h3>
          <p>{{ footerDesc }}</p>
          <p class="social">
            <a href="#"><span :class="socialIcons.twitter"></span></a>
            <a href="#"><span :class="socialIcons.facebook"></span></a>
            <a href="#"><span :class="socialIcons.instagram"></span></a>
            <a href="#"><span :class="socialIcons.linkdin"></span></a>
          </p>
        </div>
        <div class="col-md-7 ms-auto">
          <div class="row site-section pt-0">
            <div class="col-md-4 mb-4 mb-md-0">
              <h3>{{ footerWidgetTitle[1] }}</h3>
              <ul class="list-unstyled">
                <li><a :href='footerWidgetUrl1[0]'>{{ footerWidget1[0] }}</a></li>
                <li><a :href='footerWidgetUrl1[1]'>{{ footerWidget1[1] }}</a></li>
                <li><a :href='footerWidgetUrl1[2]'>{{ footerWidget1[2] }}</a></li>
                <li><a :href='footerWidgetUrl1[3]'>{{ footerWidget1[3] }}</a></li>
              </ul>
            </div>
            <div class="col-md-4 mb-4 mb-md-0">
              <h3>{{footerWidgetTitle[2]}}</h3>
              <ul class="list-unstyled">
                <li><a :href='footerWidget2[0]'>{{ footerWidget2[0] }}</a></li>
                <li><a :href='footerWidget2[1]'>{{ footerWidget2[1] }}</a></li>
                <li><a :href='footerWidget2[2]'>{{footerWidget2[2]}}</a></li>
                <li><a :href='footerWidget2[3]'>{{ footerWidget2[3] }}</a></li>
              </ul>
            </div>
            <div class="col-md-4 mb-4 mb-md-0">
              <h3>{{ footerWidgetTitle[3] }}</h3>
              <ul class="list-unstyled">
                <li><a :href='footerDownload.appStoreLink'>{{ footerDownload.appStore }}</a></li>
                <li><a :href='footerDownload.playStoreLink'>{{ footerDownload.playStore }}</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <div class="row justify-content-center text-center">
        <div class="col-md-7">
          <p class="copyright"> &copy; {{ copyrightText }} </p>
        </div>
      </div>

    </div>
  </footer>
</template>

<style scoped>

</style>
