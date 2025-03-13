# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR).

## Table of contents 

- [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./preview.png)

### Links

Live Site URL: [GitHub Pages]()

## My process

### Built with

- Semantic HTML 5 markup
- CSS logic properties
- Mobile-first workflow
- Flexbox and Grid
- RWD
- Sass
- BEM
- Accessibility

### What I learned

I implemented fluid typography in Sass using mixins and functions. It enables responsive font sizing that adjusts based on the viewport width while maintaining a smooth transition between different breakpoints.

```
@import 'fluid-typography';

$font-family: 'Red Hat Display', sans-serif;
$text-preset-1: (
    font-size: (
        font-size-1: (fs: 2.5rem, vw: $viewport-mobile),
        font-size-2: (fs: 3rem, vw: $viewport-tablet),
        font-size-3: (fs: 4rem, vw: $viewport-desktop),
    ),
    styles: (
        font-family: $font-family,
        font-weight: 900,
        line-height: 110%,
        letter-spacing: 0,
        text-align: center,
    )
);

.header__title {
        @include fluid-typography($text-preset-1);
        color: $slate-900;
    }
```

## Author

- LinkedIn [KonradJam](www.linkedin.com/in/konradjam)
- X [KonradJam_](https://x.com/KonradJam_)
- Frontend Mentor [KonradJam](https://www.frontendmentor.io/profile/KonradJam)
- Codewars [KonradJam](https://www.codewars.com/users/KonradJam)
- CodePen [KonradJam](https://codepen.io/konradjam)