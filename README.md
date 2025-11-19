# Grid, Transforms & Animations — Feature Card Gallery Tutorial

An interactive, self-paced tutorial teaching students CSS Grid, Transforms, and Animations through building a responsive feature card gallery.

## 📚 Overview

This tutorial guides students through creating a modern, animated card gallery—a common component in product landing pages. Students learn by doing, with built-in progress tracking, hints, research checkpoints, and reflection prompts.

**Live Tutorial:** Open `index.html` in a browser to start learning.

**Estimated Time:** 90-120 minutes

## 🎯 Learning Objectives

By completing this tutorial, students will be able to:

- Create responsive grid layouts using `auto-fit` and `minmax()`
- Apply CSS transforms for interactive hover states
- Combine multiple transforms effectively
- Create keyframe animations with staggered timing
- Use CSS custom properties (variables) for theming
- Implement video elements in web layouts
- Respect user motion preferences for accessibility

## 🗂️ File Structure

```
grid-transforms-animations-tutorial/
├── index.html                    # Main tutorial interface
├── tutorial-styles.css           # Tutorial UI styling (lime green theme)
├── tutorial.js                   # Progress tracking, hints, reflections
├── codepen-starter-html.html     # Starter HTML for CodePen
├── codepen-starter-css.css       # Starter CSS with pre-written card styles
└── README.md                     # This file
```

## 🚀 Getting Started

### For Students

1. **Open the tutorial:** Open `index.html` in your web browser
2. **Set up CodePen:** 
   - Create a new Pen at [codepen.io](https://codepen.io)
   - Copy contents of `codepen-starter-html.html` into the HTML panel
   - Copy contents of `codepen-starter-css.css` into the CSS panel
3. **Follow along:** Complete Parts A-F in order, checking off items as you go
4. **Save your work:** Fork your Pen and submit the URL when complete

### For Instructors

1. **Host the tutorial:** Upload files to your web server or LMS
2. **Share the link:** Students access `index.html` directly
3. **Review submissions:** Students submit their CodePen URLs
4. **Optional:** Customize the tutorial by editing `index.html`

## 📖 Tutorial Structure

### Part A — Grid Foundation
- Create a responsive grid using `display: grid`
- Use `auto-fit` and `minmax()` for automatic responsiveness
- Set appropriate gap spacing

### Part B — Card Structure & Content
- **B1:** Build semantic card components with HTML
- **B2:** Learn CSS custom properties (variables) for theming
- Pre-written card styles included (students focus on content)

### Part C — Transform Basics
- Add smooth hover effects using `transform`
- Implement `translateY()` and `scale()`
- Use `transition` for smooth animations

### Part D — Unique Transforms
- Apply different transforms to each card
- Explore `rotate()`, `skew()`, and combined transforms
- Create visual variety

### Part E — Keyframe Animations
- Define `@keyframes` for entrance animations
- Apply staggered `animation-delay` to cards
- Use `animation-fill-mode` for persistent states

### Part F — Reduced Motion (Optional)
- Implement `@media (prefers-reduced-motion: reduce)`
- Respect user accessibility preferences
- Maintain usability without animations

## ✨ Features

### Interactive Learning
- **Progress Tracking:** Visual progress bar shows completion (0-100%)
- **Self-Paced:** Students work at their own speed
- **Hints:** Click "Show Hint" for guidance (not full solutions)
- **Checkboxes:** Self-report completion of each requirement

### Research & Reflection
- **Research Checkpoints:** Students explore MDN docs and take notes
- **Reflection Prompts:** Critical thinking questions after each part
- **Export Function:** "Copy All Reflections" button for easy submission

### Modern Design
- **Lime Green Theme:** High-contrast, accessible color scheme
- **Sticky Header:** Progress bar always visible while scrolling
- **Responsive Layout:** Works on desktop, tablet, and mobile
- **GPU-Accelerated:** Smooth scrolling with no visual hiccups

## 🎨 Customization

### Changing Colors

Edit CSS variables in `tutorial-styles.css`:

```css
:root {
  --primary-color: #ec4899;      /* Change lime to pink */
  --secondary-color: #8b5cf6;    /* Purple accent */
  --bg-primary: #0f172a;         /* Dark background */
  --text-primary: #f8fafc;       /* Light text */
}
```

### Adding Content

To add a new tutorial section:

1. Copy an existing `<section class="tutorial-section">` in `index.html`
2. Update the section ID, heading, and content
3. Add a new step to `Progress.TOTAL_STEPS` in `tutorial.js`
4. Update the progress bar calculation

### Modifying Starter Code

Edit `codepen-starter-html.html` and `codepen-starter-css.css` to change what students start with. The current setup includes:

- **HTML:** Basic structure with workspace container
- **CSS:** Pre-written card styles, CSS variables, placeholder comments

## 🧪 Testing

### Manual Testing Checklist

- [ ] Progress bar updates when checking "Mark as complete"
- [ ] Hints toggle open/closed correctly
- [ ] Research note textareas save to localStorage
- [ ] "Copy All Reflections" includes all text
- [ ] "Reset Progress" clears all checkboxes and localStorage
- [ ] Sticky header doesn't have visual hiccups when scrolling
- [ ] All links open in new tabs
- [ ] Tutorial is readable on mobile devices

### Browser Compatibility

Tested and working in:
- Chrome 120+
- Firefox 121+
- Safari 17+
- Edge 120+

## 📝 Submission Instructions

Students should:

1. Complete all parts (A-E required, F optional)
2. Click "Copy All Reflections" button
3. Paste reflections into their CodePen (HTML tab, as comments)
4. Fork the Pen to save their work
5. Submit the Pen URL to Canvas

## 🛠️ Technical Details

### Dependencies

- **None!** Pure HTML, CSS, and vanilla JavaScript
- No build process required
- No external libraries or frameworks

### Browser Storage

Uses `localStorage` to save:
- Completed steps (checkbox states)
- Reflection text (textarea content)
- Research notes (textarea content)

**Storage Keys:**
- `grid-tutorial-completed`: Set of completed step IDs
- `grid-tutorial-reflections`: Object of reflection text by step ID

### Accessibility Features

- Semantic HTML5 elements (`<article>`, `<section>`, `<header>`)
- ARIA labels on interactive elements
- Keyboard navigation support
- High contrast color scheme (WCAG AA compliant)
- Respects `prefers-reduced-motion` (taught in Part F)

## 🤝 Contributing

To improve this tutorial:

1. Fork the repository
2. Make your changes
3. Test thoroughly in multiple browsers
4. Submit a pull request with a clear description

## 📄 License

This tutorial is provided for educational use. Feel free to adapt and modify for your classroom needs.

## 🙋 Support

For questions or issues:
- Check the tutorial's built-in hints
- Review the MDN documentation links provided
- Contact your instructor

---

**Version:** 2.0  
**Last Updated:** November 2025  
**Author:** [Your Name/Institution]
