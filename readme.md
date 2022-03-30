# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshots](#screenshots)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the app depending on their device's screen size
-   See hover states for all interactive elements on the page
-   Select and submit a number rating
-   See the "Thank you" card state after submitting a rating

### Screenshots

Dark mode:

![Dark mode](./wwwroot/images/screenshot-dark.jpg)

Light mode:

![Light mode](./wwwroot/images/screenshot-light.jpg)

### Links

-   Solution URL: [https://github.com/marklnz/BlazorRatingCard](https://github.com/marklnz/BlazorRatingCard)
-   Live Site URL: [https://markl.nz/BlazorRatingCard](https://markl.nz/BlazorRatingCard)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow
-   Automated detection of light/dark mode using `prefers-color-scheme` media query
-   [Blazor WASM](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor/) - Microsoft's SPA framework that allows compilation of C# code to Web Assembly

### What I learned

This was a fun experiment that allowed me to test where I'm at with my CSS skills. I've done a fair amount of CSS over the years but most of this has involved using pre-built CSS frameworks. With this challenge I wrote the CSS from scratch and learnt a bit about using CSS Custom Properties in particular.

As I'm a big fan of the Blazor WASM framework also, I thought I'd go down that path rather once I'd done the basic challenge with Javascript, which was my first step. Thanks to the ability of Blazor to control the DOM, as well as to respond to events, I was able to build this version without using javascript at all.

I also took the opportunity to build the rating card as a component rather than including the markup and styles in the main "site".

Finally, I was able to experiment with the `prefers-color-scheme` media query to detect light/dark mode from the OS, and set colors accordingly.

I have also hosted the demo site in Github Pages and utilised Github Actions to build and deploy it. There were some learnings there due to the fact that this is the first time I've hosted a Blazor WASM site on Github Pages, as well as my first attempt at using Github Actions.

### Continued development

I will continue to experiment with the light/dark mode settings by adding a toggle indicator that allows the user to change between the two without needing to resort to using the browser developer tools or the OS to change it.

I would also like to use this project to learn more about packaging components for Blazor. I have the markup, C# code, and css styles grouped together currently, but I do not yet have the images located with the component itself. I intend to co-locate these and will also look at packaging the component in a separate component library and referencing it from the main site project.

### Useful resources

-   [How do I deploy a Blazor WebAssembly application to GitHub pages?](https://www.syncfusion.com/faq/blazor/host-and-deploy/how-do-i-deploy-a-blazor-webassembly-application-to-github-pages) - This blog entry from Syncfusion helped me work out the kinks in the deployment to Github pages. Because Pages is primarily intended for use with the Jekyll site generator, there are a couple of gotchas when deploying Blazor and this blog covered it all for me.
-   [Nice resource on a light/dark mode toggle from Thomas Steiner on http://web.dev](https://web.dev/prefers-color-scheme/#dark-mode-but-add-an-opt-out) - A very thorough article that includes
    reasoning on why dark mode is worth supporting, as well as links to a custom web component Thomas has built that provides users with a toggle on the page itself.
-   [Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) All about CSS Custom Properties from the Mozilla Developer Network

## Author

-   Website - [Mark Lawrence](https://markl.nz)
-   Frontend Mentor - [@marklnz](https://www.frontendmentor.io/profile/marklnz)

## Acknowledgments

I'd just like to acknowledge [Frontend Mentor](https://www.frontendmentor.io), for publishing these challenges. It's a great resource both to challenge yourself, and to get inspiration from.
