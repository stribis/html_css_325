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
│   ├── style.css           # Accompanying styles
│   └── fonts/              # Local font files (Roboto)
├── 03_css_basics/
│   ├── index.html          # CSS styling examples
│   └── style.css           # CSS selectors and properties
├── 04_float_example/
│   └── index.html          # CSS Float layout demonstration
├── 05_flex_basics/
│   └── index.html          # Flexbox layout fundamentals
├── 06_gradients/
│   ├── index.html          # CSS gradient demonstrations
│   ├── style.css           # Basic gradient examples
│   └── flags/              # Flag recreation exercise
│       ├── index.html      # Multiple flag implementations
│       └── style.css       # Advanced gradients and pseudo-elements
├── 07_positioning/
│   └── index.html          # CSS positioning properties and techniques
├── 08_font_icons_extended/
│   └── index.html          # Advanced Font Awesome icon implementations
├── 09_box-shadow_exercise/
│   └── index.html          # Box-shadow layering and visual effects
├── 10_tables/
│   └── index.html          # HTML tables and CSS table styling
├── 11_forms/
│   └── index.html          # HTML forms and form styling
├── 12_video_and_audio/
│   ├── index.html          # HTML5 video and audio elements
│   └── media/              # Video and audio files
├── 13_dropdown_navigation/
│   ├── index.html          # CSS dropdown navigation menus
│   └── style.css           # Navigation styling and hover effects
├── 14_example_project/
│   ├── index.html          # Multi-page project homepage
│   ├── about.html          # About page
│   ├── products.html       # Products page
│   ├── store.html          # Store page
│   └── assets/             # Organized project assets
│       ├── css/
│       │   └── main.css    # Structured CSS with nesting
│       ├── fonts/          # Custom font files (Lora, Raleway)
│       └── images/         # Project images and backgrounds
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
**Files:** `02_static_website/index.html`, `02_static_website/style.css`, `02_static_website/images/`, `02_static_website/fonts/`

Build a complete static website based on a professional template design. This lesson focuses on creating a surf shop website ("SSURFER") with modern layout techniques, responsive design, and advanced typography.

**Project Features:**
- **Navigation Bar**: Horizontal navigation with brand logo and menu items
- **Hero Section**: Full-screen background image with call-to-action
- **Product Showcase**: Grid layout displaying surfboard products with images and pricing
- **Professional Styling**: Modern button designs and typography
- **Custom Typography**: Google Fonts integration and local font implementation
- **Icon Integration**: Font Awesome icon library implementation

**Learning Objectives:**
- Implement CSS Flexbox for navigation and layout structure
- Create responsive hero sections with background images
- Apply CSS reset for consistent cross-browser styling
- Structure semantic HTML with proper article and section elements
- Style interactive elements (buttons, navigation links)
- Work with external images and proper alt text
- Integrate Google Fonts using @import and link methods
- Implement local font files and font-face declarations
- Utilize Font Awesome for scalable vector icons

**CSS Techniques Demonstrated:**
- **Flexbox Navigation**: `display: flex`, `justify-content: space-between`, `align-items: center`
- **Background Images**: `background-size: cover`, `background-position: center`
- **CSS Reset**: Universal selector with `box-sizing: border-box`
- **Button Styling**: Custom `.btn` class with padding and background colors
- **Layout Spacing**: Using `gap`, `padding`, and `margin` for proper spacing
- **Typography**: Font-family declarations and text styling
- **Google Fonts**: External font loading via CDN and @import
- **Local Fonts**: Custom font files with @font-face declarations
- **Icon Fonts**: Font Awesome CDN integration and icon usage

**Key Concepts Covered:**
- Semantic HTML structure with `<header>`, `<nav>`, `<section>`, and `<article>`
- CSS Flexbox for modern layout design
- Background image implementation and positioning
- Professional button and navigation styling
- Product card layout and design patterns
- Web typography best practices and font loading strategies
- Icon fonts vs SVG considerations
- Performance implications of external font loading

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

### 06 - CSS Gradients
**Files:** `06_gradients/index.html`, `06_gradients/style.css`, `06_gradients/flags/`

Explore advanced CSS gradient techniques and creative applications through practical exercises. This lesson demonstrates the power of CSS gradients for creating complex visual designs using minimal HTML markup.

**Project Features:**
- **Basic Gradients**: Linear gradients with direction control
- **Color Stops**: Precise color positioning and hard transitions
- **Flag Recreation**: International flags created with single div elements
- **Advanced Techniques**: Pseudo-elements for complex designs
- **Geometric Shapes**: Triangles and crosses using CSS borders and positioning

**Flag Implementations:**
- **Colombia**: Horizontal stripes with specific proportions
- **Italy**: Vertical stripes using directional gradients
- **Tanzania**: Diagonal gradients with multiple color stops
- **USA**: Repeating gradients with pseudo-element overlay
- **Zimbabwe**: Complex multi-stripe design with geometric overlays
- **Switzerland**: Cross design using pseudo-elements and positioning

**Learning Objectives:**
- Master linear gradient syntax and direction control
- Implement precise color stops for hard transitions
- Utilize pseudo-elements (::before and ::after) for complex designs
- Create geometric shapes using CSS borders and transforms
- Apply absolute positioning for layered designs
- Understand gradient performance and browser support

**CSS Techniques Demonstrated:**
- **Linear Gradients**: `linear-gradient()` with various directions
- **Color Stops**: Percentage-based color positioning
- **Repeating Gradients**: `repeating-linear-gradient()` for patterns
- **Pseudo Elements**: `::before` and `::after` for additional design layers
- **CSS Triangles**: Border manipulation for geometric shapes
- **Absolute Positioning**: Precise element placement and layering
- **Transform Properties**: `translate()` for centering and positioning
- **Z-index**: Layer stacking for complex designs

**Key Concepts Covered:**
- CSS gradient syntax and browser compatibility
- Color theory and flag design principles
- Pseudo-element best practices and limitations
- CSS-only graphic design techniques
- Performance considerations for complex CSS designs
- Mathematical precision in CSS layouts (percentage calculations)

### 07 - CSS Positioning
**File:** `07_positioning/index.html`

Master CSS positioning properties for precise element placement and layout control. This lesson covers all positioning values and their practical applications in modern web design.

**Learning Objectives:**
- Understand the CSS positioning context and coordinate system
- Master static, relative, absolute, and fixed positioning
- Implement sticky positioning for modern scroll effects
- Control element stacking with z-index
- Create overlays, modals, and complex layouts
- Position elements relative to viewport and containers

**CSS Positioning Properties Demonstrated:**
- **Static Positioning**: Default document flow behavior
- **Relative Positioning**: Offset from natural position
- **Absolute Positioning**: Positioned relative to nearest positioned ancestor
- **Fixed Positioning**: Positioned relative to viewport
- **Sticky Positioning**: Hybrid relative/fixed positioning
- **Z-index Stacking**: Layer control and stacking contexts

**Key Concepts Covered:**
- Document flow and positioning contexts
- Coordinate system (top, right, bottom, left)
- Containing blocks and positioned ancestors
- Stacking contexts and z-index behavior
- Practical applications for navigation and UI elements

### 08 - Font Icons Extended
**File:** `08_font_icons_extended/index.html`

Expand your knowledge of icon fonts with advanced Font Awesome implementations and best practices. This lesson demonstrates professional icon usage patterns and accessibility considerations.

**Learning Objectives:**
- Implement advanced Font Awesome icon techniques
- Understand icon sizing and scaling methods
- Apply icons in navigation and UI components
- Master icon stacking and layering
- Implement accessibility best practices for icons
- Explore alternative icon libraries and SVG icons

**Font Awesome Techniques Demonstrated:**
- **Icon Sizing**: fa-xs, fa-sm, fa-lg, fa-2x through fa-10x
- **Icon Rotation**: fa-rotate-90, fa-rotate-180, fa-rotate-270
- **Icon Animation**: fa-spin, fa-pulse animations
- **Icon Stacking**: fa-stack for layered icon effects
- **Brand Icons**: Social media and company brand icons
- **Accessibility**: Proper aria-label and screen reader support

**Key Concepts Covered:**
- Icon font vs SVG performance considerations
- Semantic vs decorative icon usage
- ARIA attributes for accessibility
- Icon loading and fallback strategies
- Custom icon font creation workflow

### 09 - Box Shadow Exercise
**File:** `09_box-shadow_exercise/index.html`

Explore advanced CSS box-shadow techniques to create depth, layering, and visual effects. This hands-on exercise demonstrates multiple shadow layering for dramatic visual impact.

**Project Features:**
- **Multiple Shadow Layering**: Stacking shadows for depth effects
- **Alternating Shadow Patterns**: Black and white shadow combinations
- **Progressive Shadow Sizing**: Incrementally increasing shadow distances
- **Photo Frame Effects**: Simulating physical photo stacking
- **Visual Depth Creation**: 3D-like effects using pure CSS

**Learning Objectives:**
- Master box-shadow syntax and parameters
- Layer multiple shadows for complex effects
- Create realistic depth and lighting effects
- Understand shadow performance implications
- Apply shadows for UI enhancement and visual hierarchy

**Box Shadow Techniques Demonstrated:**
- **Multiple Shadows**: Comma-separated shadow declarations
- **Shadow Parameters**: offset-x, offset-y, blur-radius, spread-radius, color
- **Progressive Effects**: Systematic shadow progression
- **Color Combinations**: Strategic use of light and dark shadows
- **Performance Optimization**: Efficient shadow implementation

**CSS Properties Covered:**
```css
box-shadow: 
  5px 5px 10px 0 black,
  10px 10px 0 0 white,
  15px 15px 10px 0 black,
  20px 20px 0 0 white,
  25px 25px 10px 0 black,
  30px 30px 0 0 white,
  35px 35px 10px 0 black;
```

**Key Concepts Covered:**
- Box-shadow syntax and browser support
- Shadow stacking and layering principles
- Visual hierarchy through depth effects
- Performance considerations for complex shadows
- Alternative approaches using pseudo-elements
- Accessibility implications of shadow effects

### 10 - HTML Tables
**File:** `10_tables/index.html`

Master HTML table creation and CSS table styling for presenting tabular data effectively. This lesson covers semantic table markup, accessibility best practices, and modern styling techniques.

**Learning Objectives:**
- Understand when and how to use HTML tables appropriately
- Create semantic table structure with proper markup
- Implement table headers, captions, and accessibility features
- Apply CSS styling for professional table presentation
- Handle responsive table design challenges
- Use table-specific CSS properties for layout control

**HTML Table Elements Demonstrated:**
- **Table Structure**: `<table>`, `<thead>`, `<tbody>`, `<tfoot>`
- **Table Rows and Cells**: `<tr>`, `<th>`, `<td>`
- **Table Captions**: `<caption>` for table descriptions
- **Column Groups**: `<colgroup>` and `<col>` for column styling
- **Cell Spanning**: `colspan` and `rowspan` attributes
- **Accessibility**: `scope` attributes and proper header associations

**CSS Table Styling Techniques:**
- **Border Control**: `border-collapse`, `border-spacing` properties
- **Cell Styling**: `padding`, `text-align`, `vertical-align`
- **Zebra Striping**: `:nth-child()` selectors for alternating rows
- **Hover Effects**: Interactive row and cell highlighting
- **Responsive Design**: Techniques for mobile-friendly tables
- **Table Layout**: `table-layout` property for performance

**Key Concepts Covered:**
- Semantic markup vs layout tables (historical context)
- Accessibility best practices for screen readers
- Table performance considerations and optimization
- Responsive table design patterns
- CSS grid vs tables for layout (when to use each)
- Data presentation best practices

### 11 - HTML Forms
**File:** `11_forms/index.html`

Master HTML form creation and styling for user input collection. This lesson covers semantic form markup, input types, validation, and modern form styling techniques.

**Learning Objectives:**
- Create semantic and accessible HTML forms
- Implement various input types and form controls
- Apply form validation attributes and techniques
- Style forms with modern CSS for better user experience
- Understand form accessibility best practices
- Handle form layout and responsive design

**HTML Form Elements Demonstrated:**
- **Form Structure**: `<form>`, `<fieldset>`, `<legend>`
- **Input Types**: `text`, `email`, `password`, `number`, `tel`, `url`
- **Form Controls**: `<textarea>`, `<select>`, `<button>`
- **Labels and Accessibility**: `<label>` associations and `for` attributes
- **Validation**: `required`, `pattern`, `min`, `max` attributes
- **Submit Handling**: Form submission and button types

**CSS Form Styling Techniques:**
- **Layout Control**: Flexbox for form organization
- **Input Styling**: Custom padding, borders, and focus states
- **Button Design**: Modern button styling with hover effects
- **Form Backgrounds**: Gradient backgrounds and visual appeal
- **Responsive Design**: Mobile-friendly form layouts
- **Visual Hierarchy**: Typography and spacing for clarity

**Key Concepts Covered:**
- Form accessibility and screen reader compatibility
- Client-side validation vs server-side validation
- Modern form design principles and user experience
- CSS pseudo-classes for form states (:focus, :hover, :invalid)
- Progressive enhancement for form functionality

### 12 - Video and Audio
**Files:** `12_video_and_audio/index.html`, `12_video_and_audio/media/`

Explore HTML5 multimedia elements for embedding video and audio content. This lesson covers semantic media markup, file formats, and accessibility considerations.

**Learning Objectives:**
- Implement HTML5 video and audio elements
- Understand different media file formats and browser support
- Provide fallback content for accessibility
- Control media playback with attributes
- Optimize media for web delivery
- Implement responsive media design

**HTML5 Media Elements Demonstrated:**
- **Video Element**: `<video>` with controls and attributes
- **Audio Element**: `<audio>` for sound content
- **Source Elements**: `<source>` for multiple format support
- **Media Attributes**: `controls`, `autoplay`, `loop`, `muted`
- **Fallback Content**: Accessible alternatives for unsupported browsers
- **Media File Types**: MP4, OGG, and format considerations

**Media Implementation Techniques:**
- **Multiple Sources**: Providing different formats for browser compatibility
- **Accessibility**: Fallback links and descriptive content
- **Performance**: File size optimization and loading strategies
- **User Experience**: Native browser controls vs custom players
- **Responsive Media**: Flexible sizing for different devices

**Key Concepts Covered:**
- HTML5 media browser support and compatibility
- Video and audio file format considerations
- Accessibility requirements for multimedia content
- Performance implications of embedded media
- Copyright and licensing considerations for web media

### 13 - Dropdown Navigation
**Files:** `13_dropdown_navigation/index.html`, `13_dropdown_navigation/style.css`

Create interactive dropdown navigation menus using CSS hover effects and positioning. This lesson demonstrates advanced navigation patterns and user interface design.

**Learning Objectives:**
- Build hierarchical navigation structures
- Implement CSS-only dropdown functionality
- Apply absolute positioning for dropdown menus
- Create smooth hover interactions
- Design accessible navigation systems
- Handle responsive navigation challenges

**Navigation Techniques Demonstrated:**
- **Nested Lists**: Semantic HTML structure for hierarchical menus
- **CSS Positioning**: `absolute` and `relative` positioning for dropdowns
- **Visibility Control**: `visibility` property for smooth show/hide effects
- **Hover States**: `:hover` pseudo-class for interactive triggers
- **Flexbox Layout**: Modern layout techniques for menu organization
- **Visual Styling**: Background colors, spacing, and typography

**CSS Properties and Concepts:**
```css
.nav-toggle {
  position: relative;
}

.dropdown-nav {
  position: absolute;
  visibility: hidden;
}

.nav-toggle:hover .dropdown-nav {
  visibility: visible;
}
```

**Key Concepts Covered:**
- CSS positioning contexts and stacking
- Hover state management and user experience
- Accessibility considerations for dropdown menus
- Performance implications of CSS-only interactions
- Alternative approaches using JavaScript for enhanced functionality
- Mobile navigation patterns and responsive design

### 14 - Multi-Page Project Example (In Progress)
**Files:** `14_example_project/index.html`, `14_example_project/about.html`, `14_example_project/products.html`, `14_example_project/store.html`, `14_example_project/assets/css/main.css`

Build a comprehensive multi-page business website demonstrating professional project structure, advanced CSS techniques, and modern development practices. This ongoing lesson focuses on practical application of all previously learned concepts.

**Project Features:**
- **Multi-Page Structure**: Homepage, About, Products, and Store pages
- **Professional Layout**: Coffee shop business theme with consistent branding
- **Asset Organization**: Structured folder hierarchy for scalability
- **Advanced Typography**: Custom fonts (Lora, Raleway) with @font-face
- **Modern CSS Techniques**: CSS nesting and reusable class patterns
- **Visual Design**: Background overlays and sophisticated color schemes

**Learning Objectives (Current Session):**
- Implement professional project file structure and organization
- Create reusable CSS classes for consistent styling across pages
- Apply CSS nesting for better code organization and readability
- Understand CSS nesting browser compatibility considerations
- Structure multi-page navigation with consistent header/footer patterns
- Organize assets (CSS, fonts, images) in a scalable folder structure

**Upcoming Session Goals:**
- Implement CSS custom properties (variables) for design consistency
- Complete responsive design implementation
- Finalize all page layouts and content
- Apply advanced CSS features and optimizations

**CSS Techniques Demonstrated:**
- **CSS Nesting**: Modern nested selector syntax for organized code
```css
.main-navigation {
  background: rgba(47, 23, 15, 0.9);
  
  > ul {
    display: flex;
    justify-content: center;
    
    a {
      color: rgba(255, 255, 255, 0.7);
      &:hover {
        color: rgba(255, 255, 255, 0.5);
      }
    }
  }
}
```
- **@font-face Implementation**: Local font loading with fallbacks
- **Background Overlays**: Layered backgrounds with gradients and images
- **Reusable Classes**: `.heading-upper`, `.heading-lower` for consistent typography
- **Semantic HTML Structure**: Proper use of header, nav, main, section elements

**Project Structure Best Practices:**
- **Asset Organization**: Separate folders for CSS, fonts, and images
- **Naming Conventions**: Consistent class naming and file organization
- **CSS Architecture**: Structured stylesheet with logical section organization
- **Multi-Page Consistency**: Shared components and styling patterns
- **Performance Considerations**: Optimized asset loading and CSS efficiency

**Key Concepts Covered:**
- Professional web project file structure and organization
- CSS nesting syntax and browser compatibility considerations
- Multi-page website development workflow
- Asset management and optimization strategies
- Modern CSS architecture and maintainable code patterns
- Typography implementation with custom fonts and hierarchical styling

**Technologies and Techniques In Focus:**
- CSS Nesting (modern browser feature)
- Custom Properties/Variables (upcoming session)
- @font-face for custom typography
- Background image and gradient combinations
- Semantic HTML5 structure
- Professional asset organization

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

*Last updated: August 11, 2025*
