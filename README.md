# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This is the second challenge that I have taken on from the Frontend Mentor website. This challenge was considerably more difficult than the first, however I still feel confident that my solution is close to the desired outcome. I learned many new skills and techniques that I will use in my future projects, and I feel as though I am a better programmer because of this challenge.

This was a fun and challenging experience, and after completing this I feel ready to take on my next challenge!

### Links

- Solution URL: [Solution on Frontend Mentor]()
- Live Site URL: [Live Site](https://ins140.github.io/Product-Preview-Card/)

## My process

I started with designing the HTML first and then developing the CSS starting with basics like fonts and colors. The next step was formatting the contents with Flexbox and adding the proper margins, padding, etc. I made the desktop version of the component first and then developed the mobile version later. However, I know that Mobile First is always the way to go, so I rearranged my code to fit this standard.

During my testing I used a live server to watch my updates come to life as I made them, but I have since removed those files to shorten the website code.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During this challenge I really got acquainted with CSS Flexbox. I hadn't used the technique much in my previous projects, but the scope of it's utility became clear during the development of this page.

Another technique that was foreign to me before this challenge was the @media entry. Using this to determine how the CSS displays depending on the size of the screen showed me the complexity of designing websites for both desktop and mobile. I also learned through my studies that it is always best to practice Mobile First.

```css
.container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

@media screen and (min-width: 600px) {
  .container {
    flex-direction: column;
  }
}
```

### Continued development

This was my second time using CSS Flexbox to create responsive websites. I still have much to learn about these techniques, however I feel as though this project was a huge step in the development of my understanding. I plan to continue my studies of HTML and CSS to better understand the processes required to develop an accessible and responsive website.

### Useful resources

- [W3Schools](https://www.w3schools.com) - The absolute best resource for anything CSS. It has been an absolutely invaluable resource during my studies.

## Author

- Github - [INS140](https://github.com/INS140)
- Frontend Mentor - [@INS140](https://www.frontendmentor.io/profile/INS140)
