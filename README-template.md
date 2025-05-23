# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
This challenge requires the developer to order and organize several cards into a grid for a clean presentation
### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: (https://github.com/Magaztu/week2)
- Live Site URL: (https://magaztu.github.io/week2/)

## My process
I started designing the cards, then focused on the grid's order and arrangement.
Afterwards I stylized the text and gave format to the cards.
Finally added the images, all this while considering the mobile design of course.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I'm proud of everything and learned a lot!!
When it comes to CSS, I'm mostly proud of being able to manage the @media rule and also grid-template-areas.
About HTML, I started hot giving an ID to important stuf and making good use of containers, which allowed me to write less code while also maintaining my ability to stylize everything. Span was the goat here fr fr.

Maybe using a span container just to stylize the subtitles was an overkill but oh well.
```html
<div id="Jonathan-box">
      <span class="aligner">
        <img src="./../images/image-jonathan.jpg" alt="This is a profile picture" class="pfp">
        <span class="header">
          Jonathan Walters <br>
          <span class="subtitle">
            Verified Graduate
          </span>
        </span>
      </span>
      <h4>
        The team was very supportive and kept me motivated
      </h4>
      <p>
        “ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer 
        for a big company. This was one of the best investments I’ve made in myself. ”
      
      </p>
    </div>
```
```css
 @media (max-width: 768px) {
    .border-er {display: flex; flex-direction: column;}
    #quote-image {display: none;}
    }
```

### Continued development

Getting to know more CSS styles ofc! And other quirky HTML5 tags and attributes. Though I think from now onwards I'll be using CSS frameworks a lot more.

## Author

- Website - [I'll add one someday I swear lol](https://www.me-me-me.com)
- Frontend Mentor - [@Magaztu](https://www.frontendmentor.io/profile/Magaztu)


## Acknowledgments

My goat the internet, every concern I got, every internet result I shall get.
Oh and also every documentation out there on CSS rules and styles, you're the best!!
