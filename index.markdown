---
layout: default
title: Home
---

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1 class="display-3 fw-bold mb-4">Welcome to NoynaSec</h1>
    <p class="lead mb-4">A clean, modern, and responsive Bootstrap-powered Jekyll website</p>
    <a href="#about" class="btn btn-light btn-lg">Learn More</a>
  </div>
</section>

<!-- About Section -->
<section id="about" class="py-5">
  <div class="container">
    <div class="row">
      <div class="col-lg-8 mx-auto">
        <h2 class="text-center mb-4">About Us</h2>
        <p class="lead text-center">
          We create beautiful and functional web experiences using modern technologies.
        </p>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
      </div>
    </div>
  </div>
</section>

<!-- Services Section -->
<section id="services" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Our Services</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 text-center">
          <div class="card-body">
            <div class="mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-code-slash text-primary" viewBox="0 0 16 16">
                <path d="M10.478 1.647a.5.5 0 1 0-.956-.294l-4 13a.5.5 0 0 0 .956.294l4-13zM4.854 4.146a.5.5 0 0 1 0 .708L1.707 8l3.147 3.146a.5.5 0 0 1-.708.708l-3.5-3.5a.5.5 0 0 1 0-.708l3.5-3.5a.5.5 0 0 1 .708 0zm6.292 0a.5.5 0 0 0 0 .708L14.293 8l-3.147 3.146a.5.5 0 0 0 .708.708l3.5-3.5a.5.5 0 0 0 0-.708l-3.5-3.5a.5.5 0 0 0-.708 0z"/>
              </svg>
            </div>
            <h5 class="card-title">Web Development</h5>
            <p class="card-text">Custom websites built with the latest technologies and best practices.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 text-center">
          <div class="card-body">
            <div class="mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-phone text-primary" viewBox="0 0 16 16">
                <path d="M11 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h6zM5 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2H5z"/>
                <path d="M8 14a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"/>
              </svg>
            </div>
            <h5 class="card-title">Mobile Design</h5>
            <p class="card-text">Responsive designs that look great on all devices and screen sizes.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 text-center">
          <div class="card-body">
            <div class="mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-lightbulb text-primary" viewBox="0 0 16 16">
                <path d="M2 6a6 6 0 1 1 10.174 4.31c-.203.196-.359.4-.453.619l-.762 1.769A.5.5 0 0 1 10.5 13a.5.5 0 0 1 0 1 .5.5 0 0 1 0 1l-.224.447a1 1 0 0 1-.894.553H6.618a1 1 0 0 1-.894-.553L5.5 15a.5.5 0 0 1 0-1 .5.5 0 0 1 0-1 .5.5 0 0 1-.46-.302l-.761-1.77a1.964 1.964 0 0 0-.453-.618A5.984 5.984 0 0 1 2 6zm6-5a5 5 0 0 0-3.479 8.592c.263.254.514.564.676.941L5.83 12h4.342l.632-1.467c.162-.377.413-.687.676-.941A5 5 0 0 0 8 1z"/>
              </svg>
            </div>
            <h5 class="card-title">Consulting</h5>
            <p class="card-text">Expert advice to help you make the right technology decisions.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5">
  <div class="container">
    <div class="row">
      <div class="col-lg-6 mx-auto text-center">
        <h2 class="mb-4">Get In Touch</h2>
        <p class="mb-4">Have a project in mind? We'd love to hear from you.</p>
        <a href="mailto:{{ site.email }}" class="btn btn-primary btn-lg">Contact Us</a>
      </div>
    </div>
  </div>
</section>

