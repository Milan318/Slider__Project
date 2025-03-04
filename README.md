# Image Slider Documentation

## Overview
This project is a simple image slider with navigation buttons and indicators. It cycles through a set of images with smooth transitions.

## Files Included
- `index.html` – The main HTML structure for the slider.
- `style.css` – Stylesheet for styling the slider.
- `script.js` – JavaScript functionality for the slider.
- `images/` – A folder containing images used in the slider.

## Features
- Automatic and manual navigation through images.
- Previous and next buttons for navigation.
- Dots for direct selection of images.
- Slide transition effects.

## HTML Structure
The `index.html` file contains:
- A `div.slider` that holds `div.slider-item` for each image.
- Navigation buttons (`prev` and `next`).
- An indicator displaying the current slide number.
- Dots for selecting specific slides.

## CSS Styling
- The `.slider` class styles the main container.
- `.slider-item` contains each image and applies fade effects.
- Navigation buttons are styled for usability.

## JavaScript Functionality (`script.js`)
- Functions to move between slides (`currSlide(n)`).
- Functionality to update active dots and slide indicators.
- Adds/removes active classes to control visibility.

## Hosting on GitHub Pages
1. Push your project to a GitHub repository.
2. Go to **Settings** > **Pages**.
3. Set the source to `main` (or your default branch) and save.
4. Access your site at `https://yourusername.github.io/repository-name/`.

## Live Demo
The live demo is available at:
**[Slider Project Live](https://slider-project-one.vercel.app/)**

