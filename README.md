
# TinDog

TinDog is a fictional website designed to help dogs find their perfect match. The project is built using HTML, CSS, and Bootstrap, providing a modern and responsive design.

![TinDog Preview](images/iphone6.png)

## Features

- **Easy to Use:** The interface is user-friendly, so simple even your dog can navigate it.
- **Elite Clientele:** We serve the best dogs, providing top-tier matches.
- **Guaranteed to Work:** Your dog will find their true love or your money back.

## Sections

### Title Section

The title section includes a navigation bar and a catchy tagline.

```html
<section id="title">
  <div class="container-fluid">
    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand" href="">tindog</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#footer">Contact</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#pricing">Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#cta">Download</a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="row">
      <div class="col-lg-6">
        <h1>Meet new and interesting dogs nearby.</h1>
        <button type="button" class="btn btn-dark btn-lg download-button"><i class="fab fa-apple"></i> Download</button>
        <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fab fa-google-play"></i> Download</button>
      </div>
      <div class="col-lg-6">
        <img class="title-image" src="images/iphone6.png" alt="iphone-mockup">
      </div>
    </div>
  </div>
</section>
```

![Title Section](images/iphone6.png)

### Features Section

This section highlights TinDog's key features using icons and short descriptions.

```html
<section id="features">
  <div class="row">
    <div class="feature-box col-lg-4">
      <i class="icon fas fa-check-circle fa-4x"></i>
      <h3 class="feature-title">Easy to use.</h3>
      <p>So easy to use, even your dog could do it.</p>
    </div>
    <div class="feature-box col-lg-4">
      <i class="icon fas fa-bullseye fa-4x"></i>
      <h3 class="feature-title">Elite Clientele</h3>
      <p>We have all the dogs, the greatest dogs.</p>
    </div>
    <div class="feature-box col-lg-4">
      <i class="icon fas fa-heart fa-4x"></i>
      <h3 class="feature-title">Guaranteed to work.</h3>
      <p>Find the love of your dog's life or your money back.</p>
    </div>
  </div>
</section>
```

### Testimonials Section

Showcase customer testimonials with a carousel of feedback.

```html
<section id="testimonials">
  <div id="testimonial-carousel" class="carousel slide" data-ride="false">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <h2 class="testimonial-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
        <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
        <em>Pebbles, New York</em>
      </div>
      <div class="carousel-item">
        <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
        <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
        <em>Beverly, Illinois</em>
      </div>
    </div>
    <a class="carousel-control-prev" href="#testimonial-carousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#testimonial-carousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</section>
```

![Testimonial](images/dog-img.jpg)

### Press Section

Display logos of press outlets that have featured TinDog.

```html
<section id="press">
  <img class="press-logo" src="images/techcrunch.png" alt="techcrunch-logo">
  <img class="press-logo" src="images/tnw.png" alt="tnw-logo">
  <img class="press-logo" src="images/bizinsider.png" alt="bizinsider-logo">
  <img class="press-logo" src="images/mashable.png" alt="mashable-logo">
</section>
```

![Press Section](images/techcrunch.png)

### Pricing Section

Offer various pricing plans to cater to different user needs.

```html
<section id="pricing">
  <h2>A Plan for Every Dog's Needs</h2>
  <p>Simple and affordable price plans for your dog.</p>
  <div class="row">
    <div class="pricing-column col-lg-4 col-md-6">
      <div class="card">
        <div class="card-header">
          <h3>Chihuahua</h3>
        </div>
        <div class="card-body">
          <h2 class="price-text">Free</h2>
          <p>5 Matches Per Day</p>
          <p>10 Messages Per Day</p>
          <p>Unlimited App Usage</p>
          <button class="btn btn-lg btn-block btn-outline-primary" type="button">Sign Up</button>
        </div>
      </div>
    </div>
    <div class="pricing-column col-lg-4 col-md-6">
      <div class="card">
        <div class="card-header">
          <h3>Labrador</h3>
        </div>
        <div class="card-body">
          <h2 class="price-text">$49 / mo</h2>
          <p>Unlimited Matches</p>
          <p>Unlimited Messages</p>
          <p>Unlimited App Usage</p>
          <button class="btn btn-lg btn-block btn-primary" type="button">Sign Up</button>
        </div>
      </div>
    </div>
    <div class="pricing-column col-lg-4">
      <div class="card">
        <div class="card-header">
          <h3>Mastiff</h3>
        </div>
        <div class="card-body">
          <h2 class="price-text">$99 / mo</h2>
          <p>Unlimited Matches</p>
          <p>Unlimited Messages</p>
          <p>Priority Customer Support</p>
          <button class="btn btn-lg btn-block btn-primary" type="button">Sign Up</button>
        </div>
      </div>
    </div>
  </div>
</section>
```

### Call to Action (CTA) Section

Encourage users to download the TinDog app with compelling CTA buttons.

```html
<section id="cta">
  <h3 class="cta-heading">Find the True Love of Your Dog's Life Today.</h3>
  <button type="button" class="btn btn-lg btn-dark download-button"><i class="fab fa-apple"></i> Download</button>
  <button type="button" class="btn btn-lg btn-light download-button"><i class="fab fa-google-play"></i> Download</button>
</section>
```

## Footer

The footer includes social media icons and a copyright notice.

```html
<footer id="footer">
  <i class="social-icon fab fa-facebook-f"></i>
  <i class="social-icon fab fa-twitter"></i>
  <i class="social-icon fab fa-instagram"></i>
  <i class="social-icon fas fa-envelope"></i>
  <p>&copy; 2023 TinDog</p>
</footer>
```

## CSS Animations

### Gradient Background

The background of the site has a smooth gradient animation for a vibrant and dynamic look.

```css
.gradient-background {
  background: linear-gradient(300deg, #00bfff, #ff4c68, #ef8172);
  background-size: 180% 180%;
  animation: gradient-animation 18s ease infinite;
}

@keyframes gradient-animation {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
 
