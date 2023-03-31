# nft-challenge
2cnd challenge from frontend mentors
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Working prototype from Figma.

https://www.figma.com/proto/t6TJuYtXeJC1TDGuKOt3Sw/NFT-challenge?page-id=0%3A1&node-id=13%3A2&viewport=241%2C48%2C0.29&scaling=min-zoom&starting-point-node-id=13%3A2


![](./screenshot.jpg)

![image](https://user-images.githubusercontent.com/18378642/229095490-151d288b-0610-4b0e-9c04-c53f32c2ecb2.png)




### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: https://nft-preview-card-bbm.netlify.app
- how to fix a footer to the bottom of the page: https://dev.to/nehalahmadkhan/how-to-make-footer-stick-to-bottom-of-web-page-3i14

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


- [Styled Components](https://styled-components.com/) - For styles



### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

Using svg to make the graphics more responsive.

```html
 <svg class="overlay" width="48" height="48" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M0 0h48v48H0z"/><path d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z" fill="#FFF" fill-rule="nonzero"/></g></svg>
```
Using css to creat a hover effect on a image.
```css
.overlay {
    width: 19.13em;
    height: 18.81em;
    border-radius: 11px;
    margin-top: 1.30em;
    margin-left: 1.3em;
    position: relative;
    padding-top: 35%;
    padding-left: 35%;
    background: rgba(90, 207, 210, .5);
    opacity: 0;
    transition: 1s ease-in-out;
    -webkit-transition: 1s ease-in-out;
    -moz-transition: 1s ease-in-out;
    -ms-transition: 1s ease-in-out;
    -o-transition: 1s ease-in-out;
}

.overlay:hover {
    opacity: 1.0;
    cursor: pointer;
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
