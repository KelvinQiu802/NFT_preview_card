# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![screenshot](https://imgbed.codingkelvin.fun/uPic/ftJqU9.png)
![hover](https://imgbed.codingkelvin.fun/uPic/Gx1Hr5.png)
### Links
- [Click me to visit the Live Site](https://practice.codingkelvin.fun/nft_preview_card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned
**1. @font-face**

```css
@font-face {
  font-family: "Open Sans";
  src: url("/fonts/OpenSans-Regular-webfont.woff") format("woff"),
       url("/fonts/OpenSans-Regular-webfont.ttf") format("ttf");
  font-style: normal;
  font-weight: normal;
}
```

**2. font-variation-settings**

In this project, I tried to use a `Variable Font`, which uses `font-variation-settings` to set style and weight.

```css
/* Set values for variable font axis names */
font-variation-settings: "XHGT" 0.7;
```
| Axis Tag       | CSS Property                                                 |
| :------------- | :----------------------------------------------------------- |
| "wght"         | [`font-weight`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-weight) |
| "wdth"         | [`font-stretch`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-stretch) |
| "slnt" (slant) | [`font-style`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-style): `oblique + angle` |
| "ital"         | [`font-style`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-style): `italic` |
| "opsz"         | [`font-optical-sizing` (en-US)](https://developer.mozilla.org/en-US/docs/Web/CSS/font-optical-sizing) |

**3. letter-spacing**

A little change of letter-spacing can make a big difference in visuals.

```css
letter-spacing: 1px;
```



### Useful resources

- [How to host your own fonts made simple](https://www.youtube.com/watch?v=KzqQXDbDvus) - A Youtube video that teaches you how to use fonts on the website.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- My Blog - [Kelvin Qiu](https://www.codingkelvin.fun)
