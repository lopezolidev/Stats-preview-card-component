# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
- Mobile

![Screenshot from 2022-07-24 19-52-50](https://user-images.githubusercontent.com/94415170/180671075-1075405d-e3c8-4fa6-bc15-196838ec7a55.png)

- Desktop
![Screenshot from 2022-07-24 19-52-25](https://user-images.githubusercontent.com/94415170/180671098-befa62bd-5e2b-4ed5-893a-d7f8b07e413d.png)

### Links

- [Solution](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-component-using-flexbox-uioN-DU32g)
-  [Live Site](https://rockwatch.github.io/Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using extensively flexbox for almost all the layout helped  me to structure easily blocks of text. Also the coloring property from background-color helped me to paint the main image.

That property can be seen here in the image code: 
```css
main  .image-container  span {

height: 100%;

width: 100%;

background: url('./images/image-header-mobile.jpg');

background-position: center;

background-repeat: no-repeat;

background-size: cover;

border-top-left-radius: 0.5rem;

border-top-right-radius: 0.5rem;

background-color: hsl(277, 44%, 28%);

background-blend-mode: soft-light;

}
```


### Continued development

I'm looking forward to improve my layout skills, implementing grid and overcoming sizing issues of certain containers, in this part regarding the main text container that wasn't that easy to define it's dimensions without the overflow of inner containers.

### Useful resources

- [HTML and CSS course](https://platzi.com/cursos/html-css/) - Excellent HTML and CSS course
- [Mobile First course](https://platzi.com/cursos/mobile-first/) - This course helped me to structure content in a responsive layout.
- [Frontend Developer course -theory](https://platzi.com/cursos/frontend-developer/) - This gave me a general insight over how to structure a frontend project and all the tools that exist in a broad sense.
- [Frontend Developer course - practice](https://platzi.com/cursos/frontend-developer-practico/) - The practical approach to the concept displayed in the previous course.

## Author


- Frontend Mentor - [@rockwatch](https://www.frontendmentor.io/profile/rockwatch)
- Twitter - [@tanensergio](https://www.twitter.com/tanensergio)

## Acknowledgments

I'd like to thank [Platzi](https://platzi.com/home) for all the knowledge I've found useful, their mission to help Latinamerica to eliminate poverty thanks to education and their incredible teachers. 

