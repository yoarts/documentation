<p class="lead">Thank you for purchasing my template. If you have any questions that are beyond the scope of this help file, please feel free to email via my user page contact form [here](http://themeforest.net/user/yoarts).</p>


# HTML Structure
This template is a responsive layout with 9 sections. All of the information within the main content area is nested within a div with an id of "main". The general template structure is the same throughout the template. Here is the general structure.

``` html
<div id="page">
  <header id="header" class="site-header"></header>
  <main id="main" class="site-main">
    <section id="carousel-1" class="carousel slide section-slide" data-ride="carousel"></section>
    <section class="section section-center cta"></section>
    <section id="features" class="section section-center section-hilite section-features"></section>
    <section id="portfolio" class="section section-portfolio"></section>
    <section id="testimonials" class="section section-center section-hilite section-testimonial"></section>
    <section id="pricing" class="section section-center section-pricing"></section>
    <section id="team" class="section section-center section-hilite section-team"></section>
    <section id="blog" class="section section-blog"></section>
    <section id="clients" class="section section-hilite section-our-clients"></section>
    <section id="contact" class="section section-center section-cta"></section>
  </main>
  <footer id="footer" class="site-footer"></footer>
</div>
```

Each section need have class of "section" to apply global section style.

**What class names mean?**

If you would like to align center the text & content, you would add class of "section-center"

I.E.

``` html
<section id="section-id" class="section section-center">
```

If you would like to hilite a section, you would add class of "section-hilite"

I.E.

``` html
<section id="section-id" class="section section-hilite">
```

# LESS / CSS Files

We are using LESS (http://www.lesscss.org/)  to style this template. The CSS file is compiled from LESS by one of those tools: https://github.com/less/less.js/wiki/GUI-compilers-that-use-LESS.js

We are writing on 4 LESS file located in `assets/less/` folder:

* **template.less**: Main LESS file, where is using to importing all resources
* **theme.less**: Using to overide Bootstrap elements
* **style.less**: Using to write layout, structure of this template
* **variable.less**: Define some custom variables of this template

# JavaScript

This theme imports six Javascript files.

* HTML5 shim: IE8 support of HTML5 elements
* Respond.js: IE8 support of media queries
* jQuery
* Bootstrap
* Single Page Nav
* My Custom Script

#Sources and Credits

I've used the following images, icons or other files as listed. All resources below using for demo purpose only (Download package replaced by blank images)

* Vintage Logo by Tom Anders: https://creativemarket.com/TomAnders/6294-Vintage-LogoInisgnia-Collection-2
* Background by Liam Mckay: https://creativemarket.com/blog/2013/04/23/earth-day-challenge-winners
* Flat Design Icons Set by Pixeden: http://dribbble.com/shots/1016855--%20Flat-Design-Icons-Set-Vol1
* Avatars by Faceyourmanga: http://www.faceyourmanga.com/
* Portfolio Items:
* http://dribbble.com/shots/1163244-Egypt-Dunes
* http://dribbble.com/shots/1215122-Ballicons-original-flat-icons-set
* http://dribbble.com/shots/1012382-Washing-Icons-Free-icon-set
* http://dribbble.com/shots/1064834-Flat-Trophy-Icon
* http://dribbble.com/shots/829545–PSD-iMac-MacBook-Retina
* http://dribbble.com/shots/1101808-Free-iPhone-Mockup-PSD-White
* http://dribbble.com/shots/1291675-Nexus-5-Mockup-PSD
* http://dribbble.com/shots/638171-For-sometimes
* http://dribbble.com/shots/482917-Creative-Suite-Icons

Once again, thank you so much for purchasing this template. As I said at the beginning, I'd be glad to help you if you have any questions relating to this template. No guarantees, but I'll do my best to assist. If you have a more general question relating to the themes on ThemeForest, you might consider visiting the forums and asking your question in the "Item Discussion" section.