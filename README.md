# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

### Live page

[https://nicozoid.github.io/product-preview-card-component](https://nicozoid.github.io/product-preview-card-component)


### Built with

Hand-coded CSS & HTML. No AI. 

*(Consciously restricting myself to aid my learning)*

### What I learned

- Creating classes that correspond with the Figma file text styles is quicker (when building from a Figma file) than creating variables for each sub-element of the text style. Mirroring the Figma structure just makes everything more straightforward.
- `overflow: hidden` seems to be the CSS equivalent of the 'clip content' checkbox in Figma.
- It's possible to specify class sub-types through reference only to the raw html tag (e.g. `button img` defines rules for images within buttons). I didn't realise that until this project!

My refined process flow seems to work well:
*Mobile only until final stage*
1. Create HTML — should correspond with Figma frame hierarchy
1. Create empty CSS classes corresponding with the frames, using BEM naming system
1. Create variables
1. Text styles: define classes, import fonts
1. Populate all CSS classes
1. Define hover states and transitions
1. Adjust the CSS as needed for tablet and desktop