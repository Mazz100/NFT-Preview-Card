# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./equilibrium_screenshot.PNG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://nft-preview-card-pink-xi.vercel.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://sass-lang.com//) - For styles


### What I learned

- I learned to have an interactive element for any active state, whether a text or an image.
- I learned how to use the overflow property with a border radius to eliminate sharp corners outside of the parent class.


```html
<button class="etherium-button">
  <img src="images/image-equilibrium.jpg" alt="equilibrium card">
</button>
```
```css
.proud-of-this-css {
 .etherium-button {
    border: none;
    padding: 0;
    border-radius: 8px;
    overflow: hidden;
}
}
```