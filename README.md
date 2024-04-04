# Bikcraft - Responsive & Accessible Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/64ad377b-3aac-4164-8866-73622eddffa3/deploy-status)](https://app.netlify.com/sites/bikcraft-accessibility-project/deploys)

This repository contains the code for Bikcraft, a project focused on demonstrating responsiveness and accessibility principles in web design.

## CSS Validation

The CSS code in this project has been validated according to the standards set by the W3C CSS Validator. You can verify the validity of the CSS by clicking on the badge below:

[![Valid CSS](https://jigsaw.w3.org/css-validator/images/vcss)](https://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fbikcraft-accessibility-project.netlify.app%2F&usermedium=all&vextwarning=&warning=1)

## Accessibility Features

- **Semantic HTML Elements**: Implemented semantic elements like `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, and `<footer>` for better accessibility and screen reader compatibility.
- **ARIA Roles and Attributes**: Used ARIA roles and attributes such as `aria-label` to enhance accessibility for screen reader users and improve the usability of interactive elements.
- **Tabindex Attribute**: Applied the `tabindex` attribute to elements like images and buttons to define their keyboard navigation order and ensure they are accessible to users navigating with a keyboard.
- **Descriptive Alt Attributes**: All images include descriptive `alt` attributes to provide alternative text for screen readers, enhancing accessibility for visually impaired users.
- **Keyboard Accessibility**: Ensured all interactive elements are keyboard accessible and focusable, improving usability for users who rely on keyboard navigation.
- **Color Contrast**: Checked and adjusted color contrast ratios to ensure text readability for users with visual impairments.

## Responsiveness Implementation

- **Media Queries**: Utilized media queries in the `style.css` file to create responsive designs that adapt to various screen sizes and resolutions.
- **New Media Query Syntax**: Used the new syntax for media queries with `@media (width <= 1000px)` to specify responsive styles based on viewport width, improving clarity and readability of the CSS code.
- **Responsive Images**: Implemented CSS techniques to ensure images resize proportionally and maintain aspect ratio across different devices, enhancing the user experience.
- **Flexbox/Grid Layout**: Utilized CSS Flexbox and Grid layout for creating flexible and responsive page structures that adjust dynamically based on viewport size.

## Testing

The code has been thoroughly tested for accessibility using the WAVE Web Accessibility Evaluation Tool to ensure compliance with accessibility standards.

## Lighthouse Score

![Screenshot_6](https://github.com/tatilimongi/Bikcraft/assets/117868187/2d59c5cf-1366-4444-a512-6cec5181668b)
