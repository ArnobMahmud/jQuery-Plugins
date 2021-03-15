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
