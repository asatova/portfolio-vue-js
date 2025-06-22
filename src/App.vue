<template>
  <!-- Header -->
  <header>
    <nav class="container-nav">
      <div class="logo">
        <a href="#home">
          <img class="logo" src="/logo.png" alt="Logo" />
     
        </a>
    
      </div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <a href="https://t.me/asatova_Zarnigor" class="contact-btn" target="_blank">CONTACT</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero gradient-bg">
    <div class="container">
      <div class="hero-content" data-aos="fade-up">
        <h1> I create websites that work for your business.</h1>
        <p>Custom websites, smart plugins, and solid project designs — all tailored to your goals.</p>
        <a href="#services" class="contact-btn" style="font-size: 1.1rem; padding: 1rem 2rem;">
          Explore Services
        </a>
      </div>
    </div>
    
    <!-- Floating particles -->
    <div class="particle" style="top: 20%; left: 10%; width: 10px; height: 10px; animation-delay: 0s;"></div>
    <div class="particle" style="top: 50%; right: 15%; width: 8px; height: 8px; animation-delay: 2s;"></div>
    <div class="particle" style="bottom: 30%; left: 20%; width: 12px; height: 12px; animation-delay: 4s;"></div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <div class="container">
      <h2 class="section-title" data-aos="fade-up">What I Offer</h2>
      <p class="services-subtitle" data-aos="fade-up" data-aos-delay="200"></p>
      
      <div class="services-grid">
        <div class="service-card" data-aos="fade-up" data-aos-delay="100">
          <div class="service-icon">
            <i class="fas fa-code"></i>
          </div>
          <h3>What I Offer</h3>
          <p>Custom Vue.js development solutions for modern web applications.</p>
          <ul class="service-list">
            <li>Vue.js Applications</li>
            <li>Component Development</li>
            <li>SPA Development</li>
            <li>Performance Optimization</li>
            <li>Custom Vue Plugins</li>
          </ul>
        </div>

        <div class="service-card" data-aos="fade-up" data-aos-delay="200">
          <div class="service-icon">
            <i class="fas fa-trophy"></i>
          </div>
          <h3>3+ years of hands-on experience</h3>
          <p>Proven track record in delivering high-quality web solutions.</p>
          <ul class="service-list">
            <li>Enterprise Applications</li>
            <li>E-commerce Solutions</li>
            <li>Portfolio Websites</li>
            <li>Landing Pages</li>
            <li>Web Applications</li>
          </ul>
        </div>

        <div class="service-card" data-aos="fade-up" data-aos-delay="300">
          <div class="service-icon">
            <i class="fas fa-palette"></i>
          </div>
          <h3>Attention to detail in both design and functionality</h3>
          <p>Pixel-perfect designs with seamless user experiences.</p>
          <ul class="service-list">
            <li>Responsive Design</li>
            <li>UI/UX Implementation</li>
            <li>Cross-browser Compatibility</li>
            <li>Mobile-first Approach</li>
            <li>Accessibility Standards</li>
          </ul>
        </div>

        <div class="service-card" data-aos="fade-up" data-aos-delay="400">
          <div class="service-icon">
            <i class="fas fa-rocket"></i>
          </div>
          <h3>Clean, maintainable and scalable code</h3>
          <p>Code that stands the test of time and grows with your business.</p>
          <ul class="service-list">
            <li>Clean Architecture</li>
            <li>Code Documentation</li>
            <li>Testing Implementation</li>
            <li>Performance Optimization</li>
            <li>Best Practices</li>
          </ul>
        </div>

        <div class="service-card" data-aos="fade-up" data-aos-delay="500">
          <div class="service-icon">
            <i class="fas fa-comments"></i>
          </div>
          <h3>Reliable communication</h3>
          <p>Always transparent with project updates and timelines.</p>
          <ul class="service-list">
            <li>Regular Updates</li>
            <li>Clear Communication</li>
            <li>Project Management</li>
            <li>Timeline Adherence</li>
            <li>24/7 Support</li>
          </ul>
        </div>
        
        <div class="service-card" data-aos="fade-up" data-aos-delay="400">
          <div class="service-icon">
        <i class="fas fa-chalkboard-teacher"></i>
          </div>
          <h3>Mentorship and Knowledge Sharing</h3>
          <p>I guide junior developers by sharing practical experience, real projects, and career insights.</p>
          <ul class="service-list">
            <li>Guiding junior developers</li>
            <li>Teaching through real project examples</li>
            <li>Career advice and direction</li>
            <li>Code reviews and improvement tips</li>
            <li>Portfolio building support</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <div class="container">
      <div class="about-content">
        <div class="about-text" data-aos="fade-right">
          <h2>Get to know me!</h2>
          <p>I am a Frontend Web Developer building the Front-end of Websites and Web Applications that leads to the success of the overall product.</p>
          <p>I love sharing content related to the stuff that I have learned over the years in Web Development so it can help other people of the Dev Community.</p>
          <p>I'm open to Job opportunities where I can contribute, learn and grow. If you have a good opportunity that matches my skills and experience, don't hesitate to contact me.</p>
        </div>
        <div class="about-image" data-aos="fade-left">
          <div class="about-image-placeholder">
            <img src="/my-img.png" alt="My Image" />
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Technologies Section -->
  <section id="technologies" class="technologies">
    <div class="container">
      <h2 class="section-title" data-aos="fade-up">Technologies I work with:</h2>
      <div class="tech-grid">
        <div class="tech-item" data-aos="fade-up" data-aos-delay="100">
          <div class="tech-icon vue-icon">
            <i class="fab fa-vuejs"></i>
          </div>
          <h4>Vue.js</h4>
        </div>
        <div class="tech-item" data-aos="fade-up" data-aos-delay="200">
          <div class="tech-icon react-icon">
            <i class="fab fa-react"></i>
          </div>
          <h4>React</h4>
        </div>
        <div class="tech-item" data-aos="fade-up" data-aos-delay="300">
          <div class="tech-icon js-icon">
            <i class="fab fa-js-square"></i>
          </div>
          <h4>JavaScript</h4>
        </div>
        <div class="tech-item" data-aos="fade-up" data-aos-delay="400">
          <div class="tech-icon html-icon">
            <i class="fab fa-php"></i>
          </div>
          <h4>PHP</h4>
        </div>
        <div class="tech-item" data-aos="fade-up" data-aos-delay="500">
          <div class="tech-icon css-icon">
            <i class="fab fa-css3-alt"></i>
          </div>
          <h4>CSS3</h4>
        </div>
        <div class="tech-item" data-aos="fade-up" data-aos-delay="600">
          <div class="tech-icon node-icon">
            <i class="fab fa-wordpress"></i>
          </div>
          <h4>Wordpress</h4>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <div class="container">
      <h2 class="section-title" data-aos="fade-up">Recent Projects</h2>
      <div class="projects-grid">
        <div class="project-card" data-aos="fade-up" data-aos-delay="100">
          <div class="project-image">
             <img class="pr-img" src="/alta.png" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>Alta-dental group</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://altadentalgrou.wpenginepowered.com" target="_blank" class="project-btn">View Project</a>
          </div>
        </div>

        <div class="project-card" data-aos="fade-up" data-aos-delay="200">
        <div class="project-image">
             <img class="pr-img" src="/avtech.png" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>acs.uz</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://acs.uz/"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>

        <div class="project-card" data-aos="fade-up" data-aos-delay="300">
         <div class="project-image">
             <img class="pr-img" src="/mehr-shifo.png" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>mehrshifo.uz</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://mehrshifo.uz/"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>

        <div class="project-card" data-aos="fade-up" data-aos-delay="400">
        <div class="project-image">
             <img class="pr-img" src="/eastock.png" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>eastock.uz</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://eastock.uz/"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>

        <div class="project-card" data-aos="fade-up" data-aos-delay="500">
          <div class="project-image">
             <img class="pr-img" src="/catalpa.webp" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>catalpaoptical.com</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://catalpaoptical.com"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>

        <div class="project-card" data-aos="fade-up" data-aos-delay="600">
         <div class="project-image">
             <img class="pr-img" src="/oniks.jpg" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>oniks.pro</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://oniks.pro"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>
     <div class="project-card" data-aos="fade-up" data-aos-delay="500">
          <div class="project-image">
             <img class="pr-img" src="/rendering.webp" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>3d rendering new york</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://interiordesignsny.com"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>
     <div class="project-card" data-aos="fade-up" data-aos-delay="500">
          <div class="project-image">
             <img class="pr-img" src="/wewashh.webp" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>wewashhamptons.com</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://wewashhamptons.com/"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>
          <div class="project-card" data-aos="fade-up" data-aos-delay="500">
          <div class="project-image">
             <img class="pr-img" src="/traffic.jpg" alt="My Image" />
          </div>
          <div class="project-content">
            <h3>Traffic ticket New York</h3>
            <p>Professional corporate website with modern design</p>
            <a href="https://845tickets.com/"target="_blank" class="project-btn">View Project</a>
          </div>
        </div>




      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact gradient-bg">
    <div class="container">
      <div class="contact-content" data-aos="fade-up">
        <h2>Feel free to Contact me and I will get back to you as soon as possible</h2>
        <p>Made with passion and a bit of caffeine</p>
         </div>
  <a href="https://t.me/asatova_Zarnigor" target="_blank" class="footer-icon">
   <i class="fab fa-telegram"></i>
  </a>
  <a href="https://www.linkedin.com/in/zarnigor-asatova-171b4027b/" target="_blank" class="footer-icon">
   <i class="fab fa-linkedin"></i>
  </a>
  <a href="https://github.com/asatova" target="_blank" class="footer-icon">
   <i class="fab fa-github"></i>
  </a>
    </div>
  </section>
</template>

<script>




export default {
  name: 'App',
  data() {
    return {
      form: {
        name: '',
        email: '',
        subject: '',
        message: ''
      }
    }
  },
  methods: {
    submitForm() {
      if (!this.form.name || !this.form.email || !this.form.subject || !this.form.message) {
        alert('Please fill in all fields');
        return;
      }
      
      alert('Thank you for your message! I will get back to you soon.');
      
      this.form = {
        name: '',
        email: '',
        subject: '',
        message: ''
      };
    }
  },
  mounted() {
    // AOS initialization
    if (typeof AOS !== 'undefined') {
      AOS.init({
        duration: 1000,
        once: true,
        offset: 100
      });
    }

    // Smooth scrolling
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
          });
        }
      });
    });

    // Header scroll effect
    window.addEventListener('scroll', function() {
      const header = document.querySelector('header');
      if (window.scrollY > 100) {
        header.style.background = 'rgba(255, 255, 255, 0.98)';
        header.style.boxShadow = '0 2px 30px rgba(0,0,0,0.15)';
      } else {
        header.style.background = 'rgba(255, 255, 255, 0.95)';
        header.style.boxShadow = '0 2px 20px rgba(0,0,0,0.1)';
      }
    });
  }
}
</script>
