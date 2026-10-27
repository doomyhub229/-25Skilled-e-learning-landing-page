# Skilled e-learning landing page

A responsive landing page for an e-learning platform, built as a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q).

## Overview

The page introduces the Skilled platform, highlights popular courses, and presents clear “Get Started” calls to action. It includes a hero section with responsive imagery, five course cards, and a footer.

### Screenshot

![Newsletter sign-up form solution](./assets/images/screenshot.jpg)

### Links

-[Solution URL]()
-[Live Site URL:]()

### Built with

- Semantic HTML5
- CSS3
- CSS Grid and Flexbox
- Media queries for responsive layouts
- CSS custom properties and gradients
- Google Fonts — Plus Jakarta Sans

## Responsive design

The layout starts with styles for smaller screens and uses media queries to adjust the presentation:

- **Mobile:** Stacked hero content and course cards.
- **Tablet (769–1024px):** A two-column hero and a two-column course grid.
- **Desktop (1024px and above):** A two-column hero and a three-column course grid.

The hero uses the HTML `<picture>` element to select different image assets for mobile, tablet, and desktop.

## Getting started

1. Download or clone this repository.
2. Keep `index.html`, `style.css`, and the `assets/` directory together.
3. Open `index.html` in a web browser.

No build tools or package installation are required.

## Project structure

```text
.
├── index.html
├── style.css
├── assets/
│   ├── logo-dark.svg
│   ├── logo-light.svg
│   ├── image-hero-mobile@2x.png
│   ├── image-hero-tablet@2x.png
│   ├── image-hero-desktop.png
│   └── icon-*.svg
└── README.md
```

*The assets listed above are referenced in the HTML; the `assets/` folder was not included in the files supplied for this README.*

## What I practiced

- Building a landing page with semantic HTML sections and course articles.
- Using CSS Grid and Flexbox to create adaptable layouts.
- Applying responsive images with `<picture>` and `<source>`.
- Creating reusable button styles and gradient backgrounds with CSS variables.
- Working with spacing and positioning across screen sizes.

## Notes

This is a static HTML/CSS project. The “Get Started” links currently use `href="#"` placeholders rather than navigating to course pages.

## Acknowledgments

- Challenge by [Frontend Mentor](https://www.frontendmentor.io/).
- Design and supplied visual assets belong to the challenge creators.

## Author

- Frontend Mentor - [@doomyhub229](https://www.frontendmentor.io/profile/doomyhub229)
- GitHub - [@doomyhub229](https://github.com/doomyhub229)