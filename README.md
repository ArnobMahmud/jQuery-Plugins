# jQuery-Plugins 

<b>Project based most useable jQuery Plugins structure implement in work directory files.</b>

<h3> (i) AOS Plugin </h3>

**1. Link `bootstrap.css` file via cdn.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```      
**2. Make link between `aos.css` and `index.html` files.**
``` html
    <!-- AOS CSS -->
    <link rel="stylesheet" href="css/aos.css">
```
**3. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**4. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**5. Link `aos.js` file.**
``` html
    <!-- AOS JS -->
    <script src="js/aos.js"></script>
```
**6. Link `custom.js` file.**
```html
    <!-- Custom JS -->
    <script src=" js/custom.js"></script>
```
**7. Customize your `custom.js` file based on your project.**
``` js
AOS.init();

// You can also pass an optional settings object
// below listed default settings
AOS.init({
  // Global settings:
  disable: false, // accepts following values: 'phone', 'tablet', 'mobile', boolean, expression or function
  startEvent: "DOMContentLoaded", // name of the event dispatched on the document, that AOS should initialize on
  initClassName: "aos-init", // class applied after initialization
  animatedClassName: "aos-animate", // class applied on animation
  useClassNames: false, // if true, will add content of `data-aos` as classes on scroll
  disableMutationObserver: false, // disables automatic mutations' detections (advanced)
  debounceDelay: 50, // the delay on debounce used while resizing window (advanced)
  throttleDelay: 99, // the delay on throttle used while scrolling the page (advanced)

  // Settings that can be overridden on per-element basis, by `data-aos-*` attributes:
  offset: 120, // offset (in px) from the original trigger point
  delay: 0, // values from 0 to 3000, with step 50ms
  duration: 400, // values from 0 to 3000, with step 50ms
  easing: "ease", // default easing for AOS animations
  once: false, // whether animation should happen only once - while scrolling down
  mirror: true, // whether elements should animate out while scrolling past them
  anchorPlacement: "top-bottom", // defines which position of the element regarding to window should trigger the animation
});
```

<h3> (ii) CounterUp Plugin </h3>

**1. Link `bootstrap.css` file via cdn.js.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
**2. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**3. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**4. Link WayPoints via cdn.**
``` html
    <!-- waypoints cdn  -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.js"></script>
```
**4. Link `rcounter.js` file.**
```html
    <!-- rCounter JS  -->
    <script src="js/jquery.rcounter.js"></script>
```
**5. Link `custom.js` file.**
```html
    <!-- Custom JS -->
    <script src=" js/custom.js"></script>
```
**6. Customize your `custom.js` file based on your project.**
``` js
$(".count").rCounter({
  duration: 40,
});
```
<h3> (iii) LightBox Plugin </h3>

**1. Link `bootstrap.css` file via cdn.js.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
**2. Link `slick.css` file.**
``` html
    <!-- Slick CSS -->
    <link rel="stylesheet" href="css/slick.css">
```
**3. Link `slick-theme.css` file.**
``` html
    <!-- Slick Theme CSS -->
    <link rel="stylesheet" href="css/slick-theme.css">
```
**4. Link `lightbox.min.css` file.**
``` html
    <!-- LightBox CSS -->
    <link rel="stylesheet" href="css/lightbox.min.css">
```
**5. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**6. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**7. Link jQuery `lightbox.min.js` file.**
``` html
    <!-- LightBox JS -->
    <script src="js/lightbox.min.js"></script>
```
**8. Link jQuery `lightbox-plus-jquery.min.js` file.**
``` html
    <!-- LightBox JQuery Supporter -->
    <script src="js/lightbox-plus-jquery.min.js"></script>
```
**9. Link jQuery `slick.min.js` file.**
``` html    
    <!-- Slick JS -->
    <script src="js/slick.min.js"></script>
```
**10. Link `custom.js` file.**
``` html
    <!-- Custom JS -->
    <script src="js/custom.js"></script>
```
**11. Customize your `custom.js` file based on your project.**
``` js
$(document).ready(function () {
  $(".gallery").slick({
    infinite: true,
    slidesToShow: 3,
    slidesToScroll: 3,
    slidesToShow: 3,
    slidesToScroll: 1,
    autoplay: true,
    autoplaySpeed: 1500,
  });
});

lightbox.option({
  resizeDuration: 200,
  wrapAround: true,
});
```

<h3> (iv) Owl Carousel Plugin </h3>

**1. Link `bootstrap.css` file via cdn.js.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
**2. Link `owl.carousel.css` file.**
``` html
    <!-- Owl Carousel CSS -->
    <link rel="stylesheet" href="css/owl.carousel.css">
```
**3. Link `owl.theme.default.css` file.**
``` html
    <!-- Owl Carousel Default CSS -->
    <link rel="stylesheet" href="css/owl.theme.default.css">
```
**4. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**5. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**5. Link `owl.carousel.min.js` file.**
``` html
    <!-- Owl Carousel JS -->
    <script src="js/owl.carousel.min.js"></script>
```
**5. Link `custom.js` file.**
``` html
    <!-- Custom JS -->
    <script src="js/custom.js"></script>
```
**6. Customize your `custom.js` file based on your project.**
``` js
$('.owl-carousel').owlCarousel({
    loop:true,
    margin:10,
    nav:true,
    responsive:{
        0:{
            items:1
        },
        600:{
            items:3
        },
        1000:{
            items:5
        }
    }
})
```
<h3> (v) Particles Plugin </h3>

**1. Link `bootstrap.css` file via cdn.js.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
**2. Create a Id named `particles-js`.**
``` html
    <!-- Slider -->
    <section class="banner">
        <div id="particles-js"></div>
    </section>
    <!-- Slider -->
```
**3. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**4. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**5. Link `particles.min.js` file.**
``` html
    <!-- Particles JS -->
    <script src="js/particles.min.js"></script>
```
**6. Link `app.js` file.**
``` html
    <!-- App  JS -->
    <script src="js/app.js"></script>
```
**7. Link `custom.js` file.**
``` html
    <!-- Custom JS -->
    <script src="js/custom.js"></script>
```
<h3> (vi) Slick Plugin </h3>

**1. Link `bootstrap.css` file via cdn.js.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
**2. Link `slick.css` file.**
``` html
    <!-- Slick CSS -->
    <link rel="stylesheet" href="css/slick.css">
```
**3. Link `slick-theme.css` file.**
``` html
    <!-- Slick Theme CSS -->
    <link rel="stylesheet" href="css/slick-theme.css">
``` 
**4. Create a class named `gallery` which will be controlled by the jQuery function.**
``` html
<div class="gallery_box">
```
**5. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**6. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**7. Link `slick.min.js` file.**
``` html
    <!-- Slick JS -->
    <script src="js/slick.min.js"></script>
```
**8. Link `custom.js` file.**
``` html
    <!-- Custom JS -->
    <script src="js/custom.js"></script>
```
**9. Customize `custom.js` file based on your project.**
```js
$(document).ready(function () {
  $(".gallery").slick({
    infinite: true,
    slidesToShow: 3,
    slidesToScroll: 3,
    slidesToShow: 3,
    slidesToScroll: 1,
    autoplay: true,
    autoplaySpeed: 1500,
  });
});
```
<h3> (vii) Typed Plugin </h3>

**1. Link `bootstrap.css` file via cdn.js.**
``` html
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
**2. Declare a class inside `<span>` element.**
``` html
    <!-- Slider -->
    <div class="container">
        <h1>
            I'm <span class="text"></span>
        </h1>
    </div>
```
**3. Link Bootstrap Bundle JS.**
``` html
    <!-- Option 1: Bootstrap Bundle JS cdn-->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
```
**4. Link jQuery Library via cdn.**
``` html
    <!-- jQuery Library cdn  -->
    <script src="http://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc="
        crossorigin="anonymous"></script>
```
**5. Link `typed.min.js` file.**
``` html
    <!-- Typed JS  -->
    <script src="js/typed.min.js"></script>
```
**6. Link `typed.min.js` file via cdn.js.**
``` html
    <!-- Typed cdn -->
    <script src="https://cdn.jsdelivr.net/npm/typed.js@latest/lib/typed.min.js"></script>
```
**7. Link `custom.js` file.**
``` html
    <!-- Custom JS -->
    <script src="js/custom.js"></script>
```
**8. Customize the `custom.js` file based on your project.**
``` js
var typed = new Typed(".text", {
  /**
   * @property {array} strings strings to be typed
   * @property {string} stringsElement ID of element containing string children
   */
  strings: [
    "Arnob Mahmud.",
    "a Front-end Developer.",
    "an Android + iOS Developer.",
    "Freelancer.",
  ],
  stringsElement: null,

  /**
   * @property {number} typeSpeed type speed in milliseconds
   */
  typeSpeed: 50,

  /**
   * @property {number} startDelay time before typing starts in milliseconds
   */
  startDelay: 0,

  /**
   * @property {number} backSpeed backspacing speed in milliseconds
   */
  backSpeed: 50,

  /**
   * @property {boolean} smartBackspace only backspace what doesn't match the previous string
   */
  smartBackspace: true,

  /**
   * @property {boolean} shuffle shuffle the strings
   */
  shuffle: false,

  /**
   * @property {number} backDelay time before backspacing in milliseconds
   */
  backDelay: 700,

  /**
   * @property {boolean} fadeOut Fade out instead of backspace
   * @property {string} fadeOutClass css class for fade animation
   * @property {boolean} fadeOutDelay Fade out delay in milliseconds
   */
  fadeOut: false,
  fadeOutClass: "typed-fade-out",
  fadeOutDelay: 500,

  /**
   * @property {boolean} loop loop strings
   * @property {number} loopCount amount of loops
   */
  loop: true,
  loopCount: Infinity,

  /**
   * @property {boolean} showCursor show cursor
   * @property {string} cursorChar character for cursor
   * @property {boolean} autoInsertCss insert CSS for cursor and fadeOut into HTML <head>
   */
  showCursor: true,
  cursorChar: "|",
  autoInsertCss: true,

  /**
   * @property {string} attr attribute for typing
   * Ex: input placeholder, value, or just HTML text
   */
  attr: null,

  /**
   * @property {boolean} bindInputFocusEvents bind to focus and blur if el is text input
   */
  bindInputFocusEvents: false,

  /**
   * @property {string} contentType 'html' or 'null' for plaintext
   */
  contentType: "html",
});
```
