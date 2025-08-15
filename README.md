# Coffee Heaven - Multi-Page Website

A responsive multi-page website for Coffee Heaven, a cozy coffee shop located in Toronto, Ontario. This project showcases modern CSS techniques including advanced Flexbox layouts, CSS custom properties, responsive design patterns, accessibility features, and a comprehensive Canadian-themed experience across multiple pages.

## 🎯 Project Overview

Coffee Heaven is a complete multi-page website experience designed to create an inviting online presence for a local coffee shop. The design emphasizes warmth, community, and the authentic Canadian coffee experience, featuring a comprehensive menu page, detailed about section, visit information, and consistent Canadian-themed branding throughout.

## ✨ Features

### Design & Visual Effects
- **Responsive Design**: Mobile-first approach with progressive enhancement
- **Glass Morphism**: Backdrop filter effects on the hero title overlay
- **Interactive Animations**: Hover effects with smooth CSS transitions
- **Responsive Images**: Optimized images with multiple breakpoints using `<picture>` element

### Technical Implementation
- **CSS Grid Layout**: Three-row page structure (header | main | footer)
- **Advanced Flexbox**: Menu page single-column layout with flex-basis sizing
- **CSS Custom Properties**: Comprehensive design token system
- **Modern CSS**: Backdrop filters, transforms, transitions, and responsive patterns
- **Accessibility**: Focus states, semantic markup, and proper color contrast
- **SEO Optimization**: Meta descriptions, proper heading hierarchy, and alt text

### Content Sections
- **Header**: Brand logo and horizontal navigation menu with active page highlighting
- **Hero Section**: Full-width cover image with glass morphism overlay title
- **Feature Content**: Canadian flag component with hover animation and caption
- **Home Page**: Multi-paragraph introduction with call-to-action buttons
- **Menu Page**: Comprehensive Canadian-themed menu with flexbox layout and responsive cards
- **About Page**: Company story, values grid, and team information
- **Visit Us Page**: Location details, hours, contact info, and feature highlights
- **Footer**: Simple branding and copyright information with Canadian flag

## 🛠️ Technical Stack

- **HTML5**: Semantic markup with modern elements
- **CSS3**: Advanced styling with custom properties and modern layout techniques
- **Responsive Images**: Multiple image formats and sizes for optimal performance

## 📱 Responsive Breakpoints

| Breakpoint | Screen Width | Layout Changes |
|------------|--------------|----------------|
| Desktop    | > 1100px     | Horizontal navigation, two-column content |
| Tablet     | ≤ 1100px     | Vertical navigation, single-column content |
| Mobile     | ≤ 900px      | Increased font size, adjusted spacing |
| Small Mobile | ≤ 580px    | Maximum height adjustments |

## 🎨 Design System

### Color Palette
- **Primary Green**: `#4A704B` (Header/Footer background)
- **Accent Green**: `#1EEB16` (Hover states)
- **Background**: `hsl(118, 50%, 90%)` (Light sage green)
- **Text**: Deep purple `hsl(255, 85%, 23%)` for body content
- **Links**: Warm tan `#e3ac82` for navigation
- **Menu Background**: `hsl(26, 63%, 40%)` (Warm orange-brown for menu cards)
- **Canadian Flag Red**: `hsl(0, 80%, 50%)` (Authentic flag red for table rows)
- **Canadian Flag White**: `hsl(0, 0%, 100%)` (Pure white for contrast)
- **Accent Blue**: `#4010CC` (Deep blue for headings and accents)
- **Light Blue**: `hsl(240, 60%, 95%)` (Light blue for menu headings)

### Typography
- **Base Font**: System sans-serif stack
- **Base Size**: 11pt (scales to 12pt on mobile)
- **Heading**: 2rem bold for main title
- **Navigation**: 2rem bold for menu items

## 📁 Project Structure

```
CoffeeShop-website-static/
├── index.html              # Main landing page with hero section
├── menu.html               # Comprehensive Canadian-themed menu page
├── about.html              # Company story, values, and team information
├── visit-us.html           # Location, hours, contact, and features
├── style.css               # Comprehensive stylesheet with detailed comments
├── README.md               # Project documentation
├── LICENSE                 # Project license
└── img/                    # Image assets
    ├── Cover-image*.jpg    # Hero background images (multiple sizes)
    ├── canadian-flag.svg   # Feature component and menu icons
    └── Logo*.*             # Brand logos (multiple formats and sizes)
```

## 🔧 Development

### Local Development
1. Clone the repository
2. Open `index.html` in a modern web browser for the landing page
3. Navigate through all pages: `menu.html`, `about.html`, `visit-us.html`
4. No build process required - static HTML/CSS with modern features

### Code Organization
The CSS is organized into 9 main sections:
1. **Design System**: Custom properties and base styles
2. **Layout Shell**: Grid structure and main containers
3. **Header & Navigation**: Logo, menu components, and active states
4. **Hero Section**: Cover image and glass morphism overlay title
5. **Content Layout**: Responsive flexbox layout and components
6. **Responsive Design**: Media queries and breakpoints
7. **Menu Page Styles**: Flexbox layout with responsive cards and Canadian branding
8. **About & Visit Us Page Styles**: Consistent card layouts and content organization
9. **Enhanced Responsive Design**: Advanced mobile optimizations and accessibility

## 📖 Code Documentation

The codebase features comprehensive comments explaining:
- **Purpose**: What each section and property does
- **Technical Details**: Browser considerations and implementation notes
- **Design Decisions**: Why specific values and approaches were chosen
- **Relationships**: How different components work together

## 🌟 Key Features Explained

### Glass Morphism Effect
The hero title uses modern CSS effects:
```css
backdrop-filter: blur(4px);
background-color: rgba(255, 255, 255, 0.6);
```

### Interactive Flag Animation
The Canadian flag feature includes a hover scale effect:
```css
transform: scale(1.1);
transition: transform 0.3s ease-in-out;
```

### Flexible Navigation
Navigation items use flexbox for equal distribution:
```css
flex: 1; /* Equal space distribution */
```

## 🍁 Menu Page Features

### Modern Flexbox Layout
- **Single-Column Structure**: Title, main article, then menu cards in natural HTML order
- **Responsive Card Layout**: Menu cards use flex-basis for consistent sizing
- **Equal-Width Elements**: Main article and menu container align perfectly
- **Smart Wrapping**: Cards wrap responsively based on flex-basis and screen size

### Canadian-Themed Design
- **Flag Branding**: Canadian flag icons throughout all page headers
- **Color Scheme**: Canadian flag colors (red/white) for table rows and consistent theming
- **Authentic Names**: Menu items inspired by Canadian culture and traditions

### Interactive Menu Tables
- **Rounded Corners**: Modern table design with wrapper divs for border-radius support
- **Alternating Colors**: Red and white rows for Canadian theme
- **Responsive Layout**: Full-width cards on mobile, flexible wrapping on larger screens
- **Hover Effects**: Subtle card animations with translateY and enhanced shadows

### Menu Categories
1. **Canadian Coffee Creations**: Signature drinks like Maple Latte and Double Double
2. **Sweet Canadian Treats**: Traditional desserts like Nanaimo Bars and Butter Tarts
3. **Hearty Canadian Breakfasts**: Local favorites like Montreal Bagels and Bannock
4. **Canadian-Inspired Cold Drinks**: Seasonal beverages with Canadian flavors

### Enhanced User Experience
- **Accessibility**: Focus states, proper contrast ratios, and semantic markup
- **SEO Optimization**: Meta descriptions, proper heading hierarchy, and descriptive alt text
- **Performance**: Optimized CSS with efficient selectors and minimal redundancy

## 📄 License

This project is licensed under the terms specified in the LICENSE file.

## 👨‍💻 Author

**Matthew Taormina** - Coffee Heaven Website

---

*Built with modern CSS techniques and responsive design principles for an optimal user experience across all devices.*