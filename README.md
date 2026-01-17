# Frontend Mentor - Fylo Data Storage Component

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZytS5s). 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size.
- See hover states for all interactive elements on the page.


### Links

- Solution URL: [https://github.com/marc-techdev/fylo-data-storage-component-master]
- Live Site URL: [https://marc-techdev.github.io/fylo-data-storage-component-master/]

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- [Tailwind CSS v4](https://tailwindcss.com/) - CSS-first framework
- [Node.js](https://nodejs.org/) - For the build process

### What I learned

In this project, I explored the new **Tailwind CSS v4** "CSS-first" configuration. I learned how to use the `@theme` block to define custom colors and gradients directly in CSS without needing a `tailwind.config.js` file.

One of the main challenges was creating the custom "speech bubble" tooltip. I used a combination of `md:rounded-br-none` and a CSS border triangle to achieve the sharp corner effect seen on desktop:

```html
<div class="rounded-xl md:rounded-br-none relative">
  <div class="absolute right-0 -bottom-4 w-0 h-0 border-t-white ..."></div>
</div>