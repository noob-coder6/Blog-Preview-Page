# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

  - [The Challenge](#the-challenge)
  - [Links](#links)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The Challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- View the optimal layout for the component depending on their device's screen size

### Links

- Solution URL: [Project Solution](https://github.com/noob-coder6/Blog-Preview-Page.git)
- Live Site URL: [Blog Preview Page Website](https://noob-coder6.github.io/Blog-Preview-Page/)

### Built With

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox for layout
- Mobile-first workflow
- [Figtree](https://fonts.google.com/specimen/Figtree) - Google Font
- VS Code - Code editor
- Gemini Code Assist - AI assistance
- Claude AI - Learning and understanding

### What I Learned

This project helped me understand the fundamentals of HTML structure and CSS styling. Here are some key takeaways:

**1. Semantic HTML Structure**
```html
<article class="card">
  <div class="card__content">
    <!-- Content goes here -->
  </div>
</article>
```

**2. CSS Custom Properties for Maintainability**
```css
:root {
  --yellow: hsl(47, 88%, 63%);
  --grey-950: hsl(0, 0%, 7%);
}
```

**3. Flexbox for Centering**
```css
body {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}
```

**4. Creating Brutalist Design with Box Shadows**
```css
.card {
  box-shadow: 8px 8px 0px var(--grey-950);
  transition: box-shadow 0.3s ease-in-out;
}

.card:hover {
  box-shadow: 16px 16px 0px var(--grey-950);
}
```

This challenge particularly helped me understand:
- BEM naming convention for CSS classes
- Using Flexbox for positioning and alignment
- Creating smooth hover transitions
- Implementing responsive design with media queries
- The importance of semantic HTML for accessibility

### Continued Development

In future projects, I want to focus on:

- Advanced CSS animations and transitions
- CSS Grid for complex layouts
- JavaScript for interactive components
- Accessibility best practices
- Performance optimization techniques

## Author

- Frontend Mentor - [@noob-coder6](https://www.frontendmentor.io/profile/noob-coder6)
- GitHub - [@noob-coder6](https://github.com/noob-coder6)

## Acknowledgments

Special thanks to:
- Frontend Mentor for providing this challenge
- Gemini Code Assist for code refinement suggestions
- Claude AI for helping me understand new concepts and best practices
- The Frontend Mentor community for inspiration and feedback

---


