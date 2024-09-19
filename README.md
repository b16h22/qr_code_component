# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

(screenshots/qr_code_component_screenshot.png)

### Links

- Solution URL: [Github Repo](https://github.com/b16h22/qr_code_component_solution)
- Live Site URL: [Github Pages](https://b16h22.github.io/qr_code_component_solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned how to center a <div> element horizontally and vertically without providing hard values for padding or margin, with the help CSS flexbox. Initially I was using CSS position and transform property to achieve this but flexbox is a much cleaner solution.

```css
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
```

### Useful resources

- [CSS Align](https://www.w3schools.com/css/css_align.asp) - This is a good article that helped me understand different methods to align elements in an HTML layout.

## Author

- Frontend Mentor - [@b16h22](https://www.frontendmentor.io/profile/b16h22)
