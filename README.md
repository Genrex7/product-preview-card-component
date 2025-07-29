# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component][product-preview-card-component] challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skill by building realistic projects.

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
  - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

## The challenge

User should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Frontend-Mentor/product-preview-card-component](./src/design/desktop-preview.jpg)

### Links

- Solution URL: [Github/Product-Preview-Card-Component](https://github.com/Genrex7/product-preview-card-component)
- Live Site URL: [Frontend-Mentor/Product-Preview-Card-Component]()

## My process

### Built with

- ![Vite][vite]
- ![NPM][npm]
- ![HTML][html]
- ![CSS][css]
- ![Tailwind CSS][tailwind-css]
- ![Google fonts][google-fonts]
- ![Flexbox][flexbox]

### What I learned

1.  **Responsive Images with Tailwind CSS**: One key thing I learned was how to switch images based on screen size using Tailwind's utility classes. This helped me create a better user experience across different devices.

    Using Tailwind’s hidden and block classes, I used responsive utility classes to show or hide images based on screen width. For example:

    ```html
    <div class="img_container lg:flex-1/2">
    	<img
    		src="src/images/image-product-mobile.jpg"
    		alt="Gabrielle perfume mobile image"
    		class="object-cover lg:hidden"
    	/>
    	<img
    		src="src/images/image-product-desktop.jpg"
    		alt="Gabrielle perfume desktop image"
    		class="hidden lg:block lg:w-full lg:h-full"
    	/>
    </div>
    ```

### Useful resources

- [Vite - DOCS](https://vitejs.dev/guide/) - This helped me understand how to set up a project using Vite and connect it to my HTML and CSS files.
- [Tailwind CSS - DOCS](https://tailwindcss.com/docs/installation/using-vite) - This helped me understand how to use tailwind css for styling the html page.
- [Google Fonts](https://fonts.google.com/) - A great resource for importing fonts easily and making text look unique.

## Author

- Frontend Mentor - [@Genrex7](https://www.frontendmentor.io/profile/Genrex7)
- Twitter - [@DeepakKMeena07](https://x.com/DeepakKMeena07)

<!-- LINKS -->

[fronendmentor]: https://img.shields.io/badge/Frontend%20Mentor-3F54A3?style=for-the-badge&logo=frontendmentor&logoColor=white
[recipe-page]: https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm
[vite]: https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white
[npm]: https://img.shields.io/badge/NPM-green?style=for-the-badge&logo=npm&logoColor=white
[html]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[css]: https://img.shields.io/badge/CSS-639?style=for-the-badge&logo=css&logoColor=fff
[tailwind-css]: https://img.shields.io/badge/Tailwind_CSS-000?style=for-the-badge&logo=tailwind-css&logoColor=00ADFF
[google-fonts]: https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white
[flexbox]: https://img.shields.io/badge/Flexbox-violet?style=for-the-badge&logo=flexbox&logoColor=white
[mobile-first-workflow]: https://img.shields.io/badge/Mobile%20First%20Workflow-000?style=for-the-badge&logo=mobile&logoColor=white
