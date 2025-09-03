# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
The goal of this challenge was to build a clean and responsive QR code component that closely matches the provided design.

In this solution, I applied:

Semantic HTML structure to ensure accessibility and readability.

Container and sub-container classes to organize the layout and separate content clearly.

CSS styling for typography, colors, spacing, and visual hierarchy to replicate the design mockup.

Responsive design using media queries to ensure the component works well on smaller screens (down to 320px).

Consistent CSS organization for maintainability and easier updates.

This challenge was a valuable opportunity to practice structuring layouts with containers, applying responsive styling, and refining attention to detail when converting a design into code.

### Screenshot
![screenshot for desktop](./Screenshot%202025-09-03%20at%2013-07-27%20Frontend%20Mentor%20QR%20code%20component.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2013-08-48%20Frontend%20Mentor%20QR%20code%20component.png)

### Links
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/Qr-Code-Component/)


## My process
1. Setup

Downloaded the starter files and extracted them into a new project folder named qr-code-component-main.
Reviewed the provided design mockups and instructions to understand the requirements.

2. Structure

Built the HTML structure using semantic tags and organized all elements inside a #container for clear layout and maintainability.

Placed the QR code image and relevant text inside the container.

This structure ensured the component is easy to style and maintain.

3. Styling

Added base styles for the body, headings, container, and image.

Styled the QR code and text to match the design mockup.

Implemented responsive styling for smaller screens:

@media screen and (max-width: 400px) {
    #container {
        width: 80%;
    }

    #container img {
        width: 100%;
    }
}


This ensured the QR code and content scale correctly on mobile devices.

4. Finishing Up

Cleaned up CSS by grouping selectors logically.

Tested the component across different screen sizes to ensure responsiveness.

Wrote the README and prepared the project for deployment.

### Built with

- Semantic HTML5 markup (div, img, p, etc.) for clear structure and accessibility

- Container-based layout (#container) to organize and group all elements

- CSS styling for typography, colors, spacing, and visual alignment

- Responsive design using media queries to ensure the component displays correctly on screens down to 400px

- Consistent CSS organization for maintainability and scalability

## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.

