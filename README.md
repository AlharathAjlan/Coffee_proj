# Coffee Shop Website Projects

This repository contains two different coffee shop website implementations with different approaches and features.

## Project Overview

### 1. Coffee-website-proj2
A modern, responsive coffee shop website with elegant styling and print-friendly features.

![Coffee-website-proj2 Screenshot](coffee-proj-No-2-index-html.png)

### 2. coffee-website
An alternative implementation with additional JavaScript functionality and modular CSS structure.

![coffee-website Screenshot](coffee-proj-No-1-index-html.png)

## Project Structure

### Coffee-website-proj2
```
Coffee-website-proj2/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet (11KB)
├── bachground.png      # Header background image (2.1MB)
├── 2(1).png            # About section image (1.8MB)
├── Espresso1.png       # Product image 1 (146KB)
├── Espresso2.png       # Product image 2 (135KB)
├── Espresso3.png       # Product image 3 (221KB)
└── 1.png               # Additional image (172KB)
```

### coffee-website
```
coffee-website/
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── js/                 # JavaScript files directory
└── styles/             # CSS files directory
```

## Features Comparison

### Coffee-website-proj2
- **Responsive Design**: Adapts to all screen sizes (desktop, tablet, mobile)
- **Print-Friendly**: Optimized for printing menus and content
- **Modern UI**: Clean, elegant design with smooth transitions
- **Interactive Elements**: Hover effects and animations
- **Beautiful Typography**: Uses Playfair Display for headings
- **CSS Animations**: Fade-in effects for header elements
- **Card Hover Effects**: Product cards with scale and shadow transitions

### coffee-website
- **Modular CSS**: Organized styles in separate files
- **JavaScript Functionality**: Enhanced interactivity
- **Responsive Design**: Mobile-first approach
- **Component-Based Structure**: Reusable UI components

## CSS Features

### Color Scheme (Coffee-website-proj2)
- Main Color: `#deab5f` (Golden brown)
- Primary Color: `#312e2e` (Dark gray)
- Background: `#100e0f` (Almost black)
- Text: White and various grays
- Accent Color: `#e67e22` (Orange)

### CSS Variables
The project uses CSS variables for consistent styling:
- `--main-color`: Golden brown for primary elements
- `--primary-color`: Dark gray for backgrounds
- `--accent-color`: Orange for hover states
- `--text-light`: Light text color
- `--text-dark`: Dark text color
- `--shadow`: Box shadow for elements
- `--transition`: Standard transition timing

### Responsive Breakpoints
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px
- Small Mobile: < 480px
- Extra Small: < 320px

### Print Styles
The Coffee-website-proj2 includes special print styles that activate when printing:
- Removes unnecessary elements (nav, buttons)
- Optimizes layout for paper
- Adds print-specific elements (prices, subtitles)
- Maintains brand colors and typography
- Ensures proper page breaks

## Sections (Coffee-website-proj2)

1. **Navigation**
   - Fixed position
   - Responsive menu
   - Hover effects

2. **Header**
   - Full-screen background
   - Main heading
   - Call-to-action button

3. **Our Story**
   - Image with hover effect
   - Decorative line
   - Responsive text

4. **Coffee Section**
   - Two-column layout on desktop
   - Single column on mobile
   - Image with hover scale effect
   - Responsive text sizing

5. **Products**
   - Card-based layout with hover effects
   - Price display with brand color
   - Image hover animations
   - Responsive grid system

6. **Contact Form**
   - Clean input fields with focus effects
   - Responsive layout
   - Full-width submit button
   - Form validation styling

7. **Footer**
   - Three-column responsive grid
   - Brand colors with accent spans
   - Hover effects on containers
   - Copyright information

## Usage

### Viewing the Websites
1. Open `index.html` in a web browser for either project
2. The websites will automatically adapt to your screen size
3. Test the responsive navigation by resizing your browser window

### Mobile Navigation
1. On mobile devices or narrow browser windows, the navigation collapses to a hamburger menu
2. Click the hamburger icon to expand the menu
3. The menu items have smooth transitions and hover effects

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Responsive Features

### Desktop (>1024px)
- Full layout with maximum spacing
- Maximum image sizes
- Original font sizes
- Multi-column layouts

### Tablet (768px - 1024px)
- Adjusted image sizes
- Reduced font sizes
- Modified layouts with appropriate spacing
- Maintained multi-column structure

### Mobile (<768px)
- Single column layout
- Smaller images
- Stacked elements
- Adjusted spacing
- Hamburger menu navigation

### Small Mobile (<480px)
- Minimal padding
- Smallest font sizes
- Optimized for very small screens
- Simplified layouts

### Extra Small (<320px)
- Further reduced font sizes
- Minimal spacing
- Optimized for the smallest mobile screens

## Development

### Coffee-website-proj2
This project uses a single CSS file approach with:
- CSS variables for consistent styling
- Media queries for responsiveness
- Animations and transitions
- Mobile-first responsive design
- Hamburger menu for mobile navigation

### coffee-website
This project uses a modular approach with separate CSS files and JavaScript for enhanced functionality.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Fonts for Playfair Display and Poppins
- Images from various sources
- Inspiration from coffee shop websites and design trends 
