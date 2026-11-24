# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)

## Overview

This is my solution for the qr-code-component challenge on Frontend Mentor.

### Screenshot

![](./Screenshot0.jpeg)

### Links

- Solution URL: [Solution](https://github.com/mh2000hm/qr-code-component-main)
- Live Site URL: [Live Site](https://mh2000hm.github.io/qr-code-component-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Figma

### What I learned

I learned to use rem units for font-size instead of px to improve accessibility. rem = px / base font size (default 16)
```css
.p {
  font-size: 1.375rem;
}
```

I learned how to properly structure your HTML document using <main> and <footer> just outside sticking to the bottom
```html
<body>
  <main></main>
  <footer></footer>
</body>
```
```css
body {
  display: flex;
  flex-direction: column;
}
main {
  flex: 1;
}
footer {
  margin-top: auto;
}
```

I learned how to wrap text incase the text overflows beyond its container
```css
.qr-card-title {
  inline-size: 256px;
  overflow-wrap: break-word;
  text-align: center;
}
```

### Continued development

I would like to get more practice with CSS Flexbox and CSS Grid.
I would also like to learn about advanced CSS selectors.

### Useful resources

- [Mozilla MDN](https://developer.mozilla.org/) - This helped me to style the page with CSS
- [PX to REM Converter](https://pixelsconverter.com/px-to-rem) - This helped me convert font-sizes from px to rem