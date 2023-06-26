# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://heartfelt-tartufo-eb7a3a.netlify.app/)
- Live Site URL: [Add live site URL here](https://heartfelt-tartufo-eb7a3a.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I review a lot of things about flex-box and grid, I also learned how to make an adaptative circle, how to make gradients,
how to fade colors, etc

```html

```

```css
.circle {
  margin: 0 auto;

  width: 50%; /* Adjust the width and height as per your requirements */
  height: 0;
  padding-bottom: 50%; /* Creates a square based on the width */
  background-image: linear-gradient(
    to bottom,
    var(--LightRoyalBlue),
    var(--LightSlateBlue)
  ); /* Replace with your desired background color */
  border-radius: 50%;
  display: flex;
  flex-direction: column;

  align-items: center;
}
.result {
  background-image: linear-gradient(
    to bottom,
    var(--LightSlateBlue),
    var(--LightRoyalBlue)
  );
  border-radius: 1rem;
}
```

```

```

### Continued development

- I have to improve the way in which I adjust positions with fles and grid

### Useful resources

- [Example resource 1](https://chat.openai.com/) - this helped me with the sytax I didn´t know.

## Author

- Website - [Daniel Sebastian Badillo Neira](https://heartfelt-tartufo-eb7a3a.netlify.app/)
- Frontend Mentor - [@SebastianBadillo](https://www.frontendmentor.io/profile/SebastianBadillo)

## Acknowledgments
