# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

In this section I learned how to organize my divs into containers. I used to eye ball everything on the page. I would try to move each line of code using padding and margins. Instead I learned move the entire container with all the items in it at once. I had a good practice using grid, changing the sizes of the grid and changing the postions. Using Flex gave me the ability to move the items in the containers around.

```css
.  @media(min-width:640px){
    .container{
        grid-template-columns: repeat(2,1fr);
        max-width: 1200px;
        margin: 60px auto;
    }
  }

  @media(min-width:1280px){
    .container{
        grid-template-columns: repeat(4,1fr);
    }
  }```


### Continued development

I want to continue learning how to ogranize my grids and change the sizes. I still need practice using flex and all the properties of flex. After watching a couple of youtube videos they organize their grids in a simple way and less work. This project took me four hours to complete I want to finish within a hour. I will continue using frontend mentor challenges as practice and try to complete them within a hour. 

### Useful resources

- [Example resource 1] (https://www.w3schools.com/css/css3_flexbox_items.asp) - This helped me orgainizing my items using flexbox.
- [Example resource 2] (https://www.w3schools.com/css/css_grid_container.asp) - This website taught me how to use grid-containers and has great example and explainations of all the properties.


## Author

Alex Fonseca



