# Headphones Landing Page Project

This project implements a responsive headphones landing page based on a Figma design. The project includes multiple versions showcasing progressive enhancement from basic HTML/CSS to advanced features with animations and mobile responsiveness.

## Project Structure

```
headphones/
├── 0-index.html          # Basic header/hero section
├── 0-styles.css
├── 1-index.html          # Added "What we do" section
├── 1-styles.css
├── 2-index.html          # Added "Our results" section
├── 2-styles.css
├── 3-index.html          # Added contact form
├── 3-styles.css
├── 4-index.html          # Added footer (complete page)
├── 4-styles.css
├── 6-index.html          # Pentagon shapes with CSS
├── 6-styles.css
├── 7-index.html          # Added animations
├── 7-styles.css
├── 8-index.html          # Added hamburger menu
├── 8-styles.css
├── 8-script.js           # JavaScript for mobile menu
└── README.md
```

## Features

### Technical Requirements Met:
- ✅ **Responsive Design**: Switches to mobile version at 480px or less
- ✅ **Hover Effects**: Links hover/active color: #FF6565
- ✅ **Button Interactions**: Button hover/active opacity: 0.9
- ✅ **Max Width**: Content max-width of 1000px, centered
- ✅ **CSS Reset**: Clean styling foundation
- ✅ **CSS Variables**: Maintainable color and font system
- ✅ **Generic Selectors**: Reusable CSS components

### Progressive Enhancement:

#### Version 0-1: Foundation
- Header with navigation
- Hero section with call-to-action
- Responsive design basics

#### Version 1: Services Section
- "What we do" section
- Custom font icons integration
- Grid layout for services

#### Version 2: Results Section
- "Our results speak for themselves"
- Pentagon background images
- Reusable component structure

#### Version 3: Contact Form
- Contact form with validation
- Form styling and interactions
- Input field animations

#### Version 4: Complete Page
- Footer with social links
- Complete page structure
- Full responsive design

#### Version 6: CSS Shapes
- Pentagon shapes created with pure CSS
- No image dependencies for shapes
- CSS clip-path implementation

#### Version 7: Animations
- Fade-in animations for sections
- Hover effects with scaling and rotation
- Staggered animation delays
- Smooth transitions

#### Version 8: Mobile Menu
- Hamburger menu for mobile devices
- JavaScript-powered menu toggle
- Smooth scrolling navigation
- Touch-friendly interactions

## Design Specifications

### Colors:
- Primary: #FF6565 (Red/Orange)
- Text (Light): #FFFFFF (White)
- Text (Dark): #071629 (Dark Blue)
- Background (Dark): #071629
- Background (Light): #FFFFFF

### Typography:
- Font Family: 'Source Sans Pro', sans-serif
- Various weights: 400, 600, 700

### Layout:
- Max content width: 1000px
- Mobile breakpoint: 480px
- Grid-based responsive design

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- CSS Grid and Flexbox support required
- CSS clip-path support for pentagon shapes

## Usage

1. Open any of the HTML files in a web browser
2. For the complete experience, use `8-index.html`
3. Resize browser window to test responsive behavior
4. Test mobile menu functionality on small screens

## Development Notes

- Built with semantic HTML5
- CSS follows BEM-like naming conventions
- JavaScript uses vanilla ES6+ features
- No external dependencies required
- Optimized for performance and accessibility

## Assets Required

The following assets should be placed in the same directory:
- `logo_headphones.png` - Main logo
- `headphones_hero_1.jpg` - Hero background image
- `headphones_hero_2.jpg` - Results section background
- `pentagone.png` - Pentagon shape (for versions 2-4)
- Font files in `fonts/` directory for custom icons

## Accessibility Features

- Semantic HTML structure
- ARIA labels for interactive elements
- Keyboard navigation support
- Screen reader friendly
- High contrast color scheme
- Touch-friendly mobile interface

