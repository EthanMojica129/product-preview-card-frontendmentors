# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](ttps://www.frontendmentor.io/solutions/responsive-product-preview-card--SRPtrbkaN)
- Live Site URL: [Add live site URL here](https://product-preview-card-frontendmentors.vercel.app/)

## My process

I started with  the delimitation of the HTML. Then I started to work the main css component. Then I noticed that I would need some media queries for the smaller screen size. Mostly in relation to the width of the elements. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox



### What I learned

This is my first solo project using css and html. I learned a lot of how to use media queries. I feel really proud of this part: 

```css
@media only screen and (max-width: 1024px){
    h1{
        width: 250%;
    }
    p{
        width: 245%;
    }
    h1, h2, p{
        text-align: left;
        margin: 1rem auto !important;
    }
    h1, h2, p{
        height: 70%;
        margin: 1rem;
    }
    article{
        margin: auto 1rem;
    }
    .old{
        margin: 2rem!important;

    }
    .button{
        align-self: center;
        margin: auto 2rem;
        width: 150%;
    }
```    

I am still learning so I hope I get better. This is currently my first month learning how to code. 
### Continued development

I will continue to learn how to do better media queries and also to better use flexbox and grid layout.

### Useful resources

- [CSS-tricks flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flexbox-properties) - This helped me to understand a little bit better the organization of my flexbox. 



## Author

- Website - [Ethan Mojica](https://github.com/EthanMojica129)
- Frontend Mentor - [@EthanMojica129](https://www.frontendmentor.io/profile/EthanMojica129)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


## Acknowledgments

To Belen c: she is the reason I'm learning how to code. 
