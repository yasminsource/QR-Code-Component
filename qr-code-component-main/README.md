# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges helps me improve my coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges helps me improve my coding skills by building realistic projects. 

### Screenshot

![Project Screenshot](./images/Screenshot%202026-07-30%20at%2021-17-40%20Frontend%20Mentor%20QR%20code%20component.png)



### Links

- Solution URL: (https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
Hi! It took me around 6 hours to setup my Fronend Mentor projects, coding this challenge, along with writing README.

### Built with

- HTML5 
- CSS 



### What I learned
The major things that I learned is responsive design to make the QR code can be displayed in mobile phone under CSS:
```@media screen and (max-width: 400px) {
    .qrcode {
        margin: 2rem auto;
        padding: 1rem;
    }
}
```

I also learned how to utilize var in a color for easier reference:
```:root {
    --white: hsl(0, 0%, 100%);
    --slate300: hsl(212, 45%, 89%);
    --slate500: hsl(216, 15%, 48%);
    --slate900: hsl(218, 44%, 22%);
}
```

### Continued development

After trying to recreate the link of QR Code Component, I found that box-shadow is the CSS attributes that I struggled to do the most as the shadow reference as I struggling to grasp the exact thickness of the shadow, I also struggle to determine how many numbers that I should make to replicate the shadows.


### Useful resources

- [MDN CSS - Box Shadow Generator](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Backgrounds_and_borders/Box-shadow_generator) - This helped me to understand the concepts of box shadow as the live preview of the code really appear fast as I tried to edit the box shadow input. 

### AI Collaboration

- I just found out that I can use Github Copilot while coding in VSCode while I am trying to do challenge by Frontend Mentor. Before joining it, I have tried few times coding in VSCode but always unable to setup Github Copilot.
- I used the Github Copilot for generating boilerplates for my CSS files. 
- What worked well with Github Copilot is the easier color selection, font selection, the paragraph, the box shadow format, and left and right margin. What didn't work with Github copilot boilerplates are the top and bottom margin settings, padding settings, setting root and body tag, and the size of the QR code itself.


## Author

- Website - [Yasmin Nurjanah](https://www.your-site.com)
- Frontend Mentor - [@yasminsource](https://www.frontendmentor.io/profile/yasminsource))
- Twitter - [@vyawct](https://www.twitter.com/vyawct)
- Discord - @yasmin_82595


