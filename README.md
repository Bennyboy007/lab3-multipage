# CSC 4035 Lab 3: CSS3 & Responsive Web Design

## Group Members
- Benson Chibwe
- Musa Chokwe

## Project Description
A multi-page responsive website demonstrating CSS3 features including Flexbox, Grid, animations, and media queries.

## Page Descriptions

### Home Page (`index.html`)
- Features a hero banner with welcome text
- Two-column layout using Flexbox (main content + sidebar)
- Consistent navigation across all pages
- Responsive design that collapses to single column on mobile

### Services Page (`services.html`)
- Displays four service cards using CSS Grid
- Each card includes an image, heading, and description
- Hover effects on cards with smooth transitions
- Responsive grid that changes from 2-column to 1-column layout on smaller screens

### Contact Page (`contact.html`)
- Styled HTML5 form with validation
- Responsive form layout that adjusts for different screen sizes
- Interactive elements with focus and hover states
- Subtle animations on form submission

## CSS Features Implemented

### Selectors Used
- Class selectors (`.nav-links`, `.service-card`)
- Descendant selectors (`nav ul li a`)
- Pseudo-classes (`:hover`, `:focus`)
- Attribute selectors (`input[type="text"]`)

### Layout Systems
- **Flexbox**:
  - Navigation menu
  - Home page layout (intro + sidebar)
  - Form element arrangement
- **CSS Grid**:
  - Services page card layout (2×2 grid)
  - Responsive grid adjustments at breakpoints

### Responsive Design
- Media queries at 3 breakpoints:
  1. `max-width: 1024px` (tablet landscape)
  2. `max-width: 768px` (tablet portrait)
  3. `max-width: 480px` (mobile)
- Responsive images (`max-width: 100%`)
- Fluid typography using `rem` units

### Animations & Transitions
- `@keyframes` animation for hero section fade-in
- Hover transitions for:
  - Navigation links (color change)
  - Service cards (lift effect)
  - Form buttons (background color change)
- Focus transitions for form inputs

