# Module 2 - Working with CSS Challenge: Portfolio

## A webpage to showcase my skills and talents to prospective employers.

### Interesting features of this responsive HTML/CSS page:

* "Work" section images embedded in the HTML page rather than as a CSS background property. This enables the use of an alt tag and figure/figcaption tags - better for accessibility. The 02-hero-bg.jpg image was left as css property - it's decorative only. As well, it only appears with a larger screen. See @media queries below.

* Use of css grid and flex techniques. These are specific to the screen size.  See @media queries below.

* Use of @media queries - mobile first approach.

* Use of variable colors e.g. --altbkd: #adb3f0; Rather than using a color as the property, its function is used as its name. If a different look and feel is wanted - only the value of the property needs to be changed.

* Added "flex-direction: column" declaration for each li selecter in a ul list to appear on top of each other. For larger screen sizes "flex-direction: row" is used to allow li items to appear in a horizontal line. This is a good example of an @media query reversing/toggling the value of a property in the earlier (smaller/mobile) screensize.

* A separate "reset.css" page has been included.

* The HTML and CSS were validated: https://validator.w3.org/ https://jigsaw.w3.org/css-validator/.

* The page was evaluated for accessibility with the WebAim WAVE browser extension - https://wave.webaim.org/. The contrast issue - figcaption text - was fixed by applying a darker font colour.
  
### Issues:

These issues will be revisted:

* The grid and flex properties nearer the top of the page - even when the selector are used with specificity (e.g. with class or id or inheritance) in an attempt to prevent a "cascade" - interfere with later use of grid and flex causing some "funky" misbehaviour. Embedding the "Work" section images in the html started as a work-around, but actually, I think, it's a better accessible approach allowing for the use of the alt and figure/figcaption tags.
  
* Perhaps because of the above an attempt to use a responsive image - https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images - failed. I've left a commented-out placeholder in the html file.


