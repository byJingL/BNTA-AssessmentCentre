# BNTA - Shop landing page assessment day solution

This is a solution to the Shop landing page BNTA assessment day which will allow you to put the HTML and CSS you've learned in practice with a stretch goal of adding a Dark Mode to your site.

## Table of contents

- [BNTA - Shop landing page assessment day solution](#bnta---shop-landing-page-assessment-day-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Authors](#authors)
  - [Acknowledgments](#acknowledgments)
  - [Disclaimer](#disclaimer)

## Overview

### The challenge

**Your users should be able to:**
- View product information about Jellycat plushies. 

### Screenshot

[The whole page preview is here](/pageshot.png)   

## My process

### Built with
- Semantic HTML5 markup
- CSS

### What I learned
1. change background color and text font
```css
.tertiary {
    background-color: #939B62;
 }
 .tertiary__article {
     font-family: Fantasy;
}
```
2. adding video, pictures
```html
<video width="640" height="360" controls src="https://www.jellycat.com/images/video/FAST_FOOD_VIDEO_MAIN.MP4" type = "video/MP4"></video>
```
3. horizontal scrolling of pictures
```html
 <section class = "ter-pic-container">
                         <section class = "ter-pic-row">
                         <img src="https://www.jellycat.com/images/products/medium/FABF6PEACH.jpg">
                         <img src="https://www.jellycat.com/images/products/medium/VV6T.jpg">
                         <img src="https://www.jellycat.com/images/products/medium/A2L.jpg">
                         </section>
                      </section>
```
```css
 .ter-pic-container {
    overflow: auto;
    white-space: nowrap;
    padding: 5px 70px 5px 20px;
    background: transparent;
    height: 100%;
    border-radius:15px;
 }

 .ter-pic-row{
    display:inline-block;
  }

.ter-pic-row img{
    margin-right:22px;
}
```
4. hyperlink text

```html
<p><a href="https://www.jellycat.com/best-sellers/" style="color: rgb(13, 0, 128); font-family: fantasy, sans-serif; font-size: 16px; text-align: center;">Most Loved</a></p>
```

5. resized the picture to fit the screen
```css
.hero>img {
    width: 100%;
    height: auto;
    object-fit: cover;
}
```


### Continued development
1. Learning Javascript for button functions, and for the video to play on hover
2. incorporating the dark mode with Javascript


### Useful resources
- [JellycatWebsite](https://www.jellycat.com/) - This website helped us find product pictures
- [Stackoverflow](https://stackoverflow.com/questions/10813408/html5-video-not-playing) - This helped us for how to make video play in a html file.
- [Color Hunt](https://colorhunt.co/) - This is a amazing website which have great color palettes.
- [W3Schools](https://www.w3schools.com/css/css_font.asp) - Very useful to pick a particular font of your liking.
- [CodePen.io](https://codepen.io/adityajanuardi/pen/YzydaVj) - This helped us to code the horizontal scroll, with an example and codes to play with.()
- [LighthouseProject](https://github.com/brightnetwork-technology-academy/C9b_assessment_centre/tree/main/project/Lighthouse) - We've learned how to structure our html and css file from this project.

## Authors

- Website Name - The Jellycat Shop
- Liman Li, Jing Lu, Intisar Sikder, Fiona Eshun


## Acknowledgments
We would like to express our sincere gratitude to our instructor, Mr. Zsolt, for his guidance and support. Also, a big thanks goes to every member of team jellycat for their work and support. This project cannot succeed without the effort of every one of us: Intisar created the hypertext link so the user can click on the caption of a picture and directly visit the Jellycat website, Jing shared the VS Code LiveShare link and her screen so that we can cooperate with each other and see the updates spontaneously through her screen, Fiona kindly added a video to the breaker section of the website to make it more vivid, and Liman designed the horizontal scroll so the user can view multiple products at the same time. 

## Disclaimer
The original project ideas are from [Bright Network Technology Academy](https://www.brightnetwork.co.uk/graduate-employer-company/bright-network-technology-academy/).