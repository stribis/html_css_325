# WDD 325 - Front End Basics: HTML & CSS

This repository contains lesson materials and practical examples for the WDD 325 Front End Basics course, focusing on foundational HTML and CSS concepts.

## Course Overview

This module introduces students to the fundamental building blocks of web development:
- HTML structure and semantics
- CSS styling and selectors
- Best practices for front-end development

## Repository Structure

```
html_css/
├── 01_html_basics/
│   └── index.html          # Introduction to HTML elements and structure
├── 02_static_website/
│   ├── index.html          # Static website implementation
│   └── style.css           # Accompanying styles
├── 03_css_basics/
│   ├── index.html          # CSS styling examples
│   └── style.css           # CSS selectors and properties
├── 04_float_example/
│   └── index.html          # CSS Float layout demonstration
├── 05_flex_basics/
│   └── index.html          # Flexbox layout fundamentals
└── README.md               # This file
```

## Lessons

### 01 - HTML Basics
**File:** `01_html_basics/index.html`

Learn the fundamentals of HTML including:
- HTML document structure
- Essential HTML tags and elements
- Headings (`<h1>` through `<h6>`)
- Paragraphs and text formatting
- Links and navigation
- Lists (ordered and unordered)
- Images and media elements
- HTML comments and best practices

**Key Concepts Covered:**
- Start and end tags
- Self-closing elements
- HTML semantics
- Basic document structure

### 02 - Static Website
**Files:** `02_static_website/index.html`, `02_static_website/style.css`, `02_static_website/images/`

Build a complete static website based on a professional template design. This lesson focuses on creating a surf shop website ("SSURFER") with modern layout techniques and responsive design.

**Project Features:**
- **Navigation Bar**: Horizontal navigation with brand logo and menu items
- **Hero Section**: Full-screen background image with call-to-action
- **Product Showcase**: Grid layout displaying surfboard products with images and pricing
- **Professional Styling**: Modern button designs and typography

**Learning Objectives:**
- Implement CSS Flexbox for navigation and layout structure
- Create responsive hero sections with background images
- Apply CSS reset for consistent cross-browser styling
- Structure semantic HTML with proper article and section elements
- Style interactive elements (buttons, navigation links)
- Work with external images and proper alt text

**CSS Techniques Demonstrated:**
- **Flexbox Navigation**: `display: flex`, `justify-content: space-between`, `align-items: center`
- **Background Images**: `background-size: cover`, `background-position: center`
- **CSS Reset**: Universal selector with `box-sizing: border-box`
- **Button Styling**: Custom `.btn` class with padding and background colors
- **Layout Spacing**: Using `gap`, `padding`, and `margin` for proper spacing
- **Typography**: Font-family declarations and text styling

**Key Concepts Covered:**
- Semantic HTML structure with `<header>`, `<nav>`, `<section>`, and `<article>`
- CSS Flexbox for modern layout design
- Background image implementation and positioning
- Professional button and navigation styling
- Product card layout and design patterns

### 03 - CSS Basics
**Files:** `03_css_basics/index.html`, `03_css_basics/style.css`

Master CSS fundamentals including:
- CSS Reset and normalization
- Element selectors
- Class and ID selectors
- Combination selectors
- Child selectors
- Attribute selectors
- CSS properties and values
- Inline, internal, and external CSS

**CSS Selectors Demonstrated:**
- `*` - Universal selector
- `h1`, `li` - Element selectors
- `p, li` - Multiple element selector
- `ul a` - Descendant selector
- `.bold` - Class selector
- `#main-header` - ID selector
- `a[title]` - Attribute selector

### 04 - Float Example
**File:** `04_float_example/index.html`

Explore CSS Float properties and layout techniques:
- Understanding CSS float behavior
- Creating multi-column layouts with floats
- Float positioning (left and right)
- Clearing floated elements
- Building traditional webpage layouts
- Height and width percentage units

**Key Concepts Covered:**
- `float: left` and `float: right`
- `clear: both` property
- Box-sizing and CSS reset
- Creating sidebar layouts
- Viewport height units (vh)

### 05 - Flex Basics
**File:** `05_flex_basics/index.html`

Master CSS Flexbox fundamentals for modern layout design:
- Flexbox container and item properties
- Main axis and cross axis alignment
- Flexible layout distributions
- Responsive design with Flexbox
- Centering content with Flexbox

**Key Flexbox Properties Demonstrated:**
- `display: flex` - Creating flex containers
- `flex-direction` - Setting flex direction
- `justify-content` - Main axis alignment
- `align-items` - Cross axis alignment
- `space-between` - Distribution of items
- Flexbox for modern web layouts

## Getting Started

1. **Clone or download** this repository to your local machine
2. **Open each lesson folder** in your preferred code editor
3. **View HTML files** in your web browser to see the results
4. **Experiment** with the code - modify HTML structure and CSS styles
5. **Practice** by creating your own variations

## Prerequisites

- Basic understanding of file systems and directories
- A code editor (VS Code, Sublime Text, Atom, etc.)
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No prior programming experience required

## How to Use This Repository

1. **Start with Lesson 01** to understand HTML fundamentals
2. **Progress sequentially** through each lesson
3. **Open files in both your editor and browser** to see code and results
4. **Modify the examples** to test your understanding
5. **Create your own projects** based on the concepts learned

## Best Practices Demonstrated

- **HTML5 semantic structure** with proper DOCTYPE declaration
- **CSS Reset** for consistent cross-browser styling
- **Separation of concerns** - HTML for structure, CSS for presentation
- **Clean, readable code** with proper indentation and comments
- **Responsive viewport** meta tag for mobile compatibility

## Additional Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [W3Schools CSS Tutorial](https://www.w3schools.com/css/)

## Course Information

- **Course:** WDD 325 - Web Development Fundamentals
- **Institution:** SAE Institute
- **Level:** Beginner
- **Focus:** Front-End Development Basics

## License

This educational material is provided for learning purposes as part of the WDD 325 curriculum.

---

*Last updated: July 22, 2025*
