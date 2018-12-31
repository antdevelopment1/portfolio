# April Copes | Portfolio Website
## [Live Website](http://aprilcopes.com)
---

## What Is This Project About
This website portfolio displays several projects I have built and contributed to most recently.

## Technologies used
* HTML
* CSS / Flexbox
* Vanilla JavaScript
* jQuery

## Site Walkthrough
<p>This is the landing page. In the background you will see am image of some of my favorites types of patterns called sacred geometry.</p>
<p align='center'>
    <img src='readme/images/landing-page.png'></img>
</p>
<p>This is the about section. Included is a short summary of my background.</p>
<p align='center'>
    <img src='readme/images/about-page.png'></img>
</p>
<br>
<br>

### Here are some of the projects I have built and contributed to over the last few months.

<p>Intent Manifesto is a place for user to actualize their dreams into reality.</p>
<p align='center'>
    <img src='readme/images/project1.png'></img>
</p>
<p>yumWorld is a React food applications for international enthusiasts looking to mix up their normal food choices by cooking food recipes from around the world.</p>
<p align='center'>
    <img src='readme/images/project2.png'></img>
</p>
<p>Speed TypeWriter Test App is a front end redesign of an online course. This project was converted from bootstrap to CSS Flexbox.</p>
<p align='center'>
    <img src='readme/images/project3.png'></img>
</p>
<p>For more information, I've included is a list of my current contact infornmation. Feel free to reach out with any questions and suggestions.</p>
<p align='center'>
    <img src='readme/images/project3.png'></img>
</p>


## Code Walkthrough / Featues

### Landing Page Features
<p>The landing page header and hero section fades in using css animations. Each link on the navbar has a transition on hover with opacity of the text becoming slightly dimmer. Upon clicking each link the page takes the user to the corresponding section. The background images stays fixed to create a scroll effect.</p>

<p>CDN used for css animations</p>

```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css">
    <link rel="stylesheet" href="./styles/styles.css">
    <title>Portfolio</title>
</head>
```

<p>CSS transitions for nav elements on hover</p>

```
.nav-container .nav li {
    /* outline: 1px solid blue; */
    /* display: flex; */
    padding: 13px 30px;
    letter-spacing: 1.5px;
    font-size: 25px;
}

.nav-container .nav li a {
    /* outline: 1px solid blue; */
    padding-bottom: 5px;
    transition: border-bottom .3s ease-out .2s, opacity .3s ease-in-out .3s;
    opacity: .8;
}

.nav-container .nav li a:hover,
.sitcky .nav li a:hover {
    border-bottom: 1px solid white;
    opacity: .6;
}
```

<p>Fixed background for background image in landing page</p>

```
.hero-section {
    display: flex;
    flex-direction: column;
    background-image: linear-gradient(rgba(0,0,0, .2), rgba(0,0,0,.9)), url(./../images/sacredg.jpg);
    background-position: center;
    background-attachment: fixed;
    background-size: cover;
    height: 100%;
    /* min-height: 100%; */
    justify-content: center;
    /* outline: 2px solid blue; */
}
```


## Built By April Copes and Lauren Wilkerson
All design layouts are original layout ideas. No libraries or frameworks were used for layout design. Layouts were built in pure HTML and CSS.

