# Marwan Rashwan - Portfolio Website

A modern, responsive portfolio website for an aspiring Data Analyst.

## 📁 Project Structure

```
portfolio/
│
├── index.html                  # Main homepage
├── about.html                  # About page (to be created)
│
├── css/
│   ├── reset.css              # CSS reset and base styles
│   ├── variables.css          # CSS custom properties (colors, etc.)
│   ├── global.css             # Global styles
│   ├── components.css         # Reusable component styles
│   └── pages.css              # Page-specific styles
│
├── js/
│   ├── theme-toggle.js        # Dark/light mode functionality
│   ├── navigation.js          # Mobile menu & navigation
│   └── analytics.js           # Google Analytics integration
│
├── assets/
│   ├── images/
│   │   ├── logo/
│   │   │   └── PortfolioLogo.png          # Site logo
│   │   ├── profile/
│   │   │   └── profile-photo.jpg          # Your profile photo
│   │   └── designs/
│   │       ├── cover-2.webp               # Design showcase images
│   │       ├── tall.webp
│   │       ├── square.webp
│   │       └── square-2.webp
│   └── fonts/
│       └── (custom fonts if needed)
│
└── README.md                   # This file
```

## 📄 File Details

### HTML Files

#### **index.html**
- Main landing page
- Contains hero section with call-to-action
- LinkedIn profile section
- Contact information
- Resume download button
- Links to all CSS and JS files

#### **about.html** (to be created)
- Detailed about section
- Work experience
- Education
- Skills
- Projects showcase

### CSS Files

#### **css/reset.css**
- CSS reset for consistent cross-browser styling
- Base typography scales (h1-h6, p, small)
- Basic element resets
- Smooth scrolling setup

#### **css/variables.css**
- All CSS custom properties (CSS variables)
- Color palette definitions:
  - Royal Blue (primary)
  - Hot Pink (secondary)
  - Golden Yellow (tertiary)
  - Butterfly Blue
  - Violet Eggplant
  - Various greys and neutrals
- Theme colors for dark/light modes
- Shadow definitions

#### **css/global.css** (optional - can be added)
- Layout utilities
- Spacing utilities
- Container styles

#### **css/components.css**
- **Navigation**: Navbar styles, responsive behavior
- **Buttons**: Primary and secondary button styles
- **Icon Wrapper**: Social media icon containers
- **Dark Mode Toggle**: Theme switcher styles
- **Mobile Menu**: Burger menu animation
- **Links**: Stylized link hover effects
- **Mouse Scroll Icon**: Animated scroll indicator

#### **css/pages.css**
- **Main Wrapper**: Page container styles
- **Hero Section**: Landing page hero styles
- **Designs Section**: Project showcase layout
- **Contact Section**: Contact form and info styles
- **Footer**: Footer styles

### JavaScript Files

#### **js/theme-toggle.js**
- Detects system color preference
- Saves user's theme choice to localStorage
- Switches between dark and light modes
- Updates CSS variables dynamically
- Listens for system theme changes

#### **js/navigation.js**
- Mobile menu toggle functionality
- Closes menu when clicking outside
- Handles responsive menu display
- Window resize event handling

#### **js/analytics.js**
- Google Analytics initialization
- Tracking code integration
- Event tracking setup

### Assets

#### **assets/images/logo/**
- `PortfolioLogo.png` - Your site logo/favicon
- Recommended size: 256x256px or 512x512px
- Format: PNG with transparency

#### **assets/images/profile/**
- `profile-photo.jpg` - Your professional headshot
- Recommended size: 400x400px minimum
- Format: JPG or WebP for best performance

#### **assets/images/designs/**
- Showcase images for your design/project work
- Formats: WebP for optimal performance
- `cover-2.webp` - Wide format image
- `tall.webp` - Vertical format image
- `square.webp` - Square format image
- `square-2.webp` - Another square format image

## 🚀 Setup Instructions

1. **Create the folder structure** as shown above

2. **Add your images:**
   - Place your logo in `assets/images/logo/`
   - Add your profile photo in `assets/images/profile/`
   - Add project images in `assets/images/designs/`

3. **Update email address:**
   - In `index.html`, change `M.Rashwan@nu.edu.eg` to your actual email

4. **Update social links:**
   - Replace GitHub link with your profile
   - Replace LinkedIn link with your profile
   - Replace Google Drive resume link with your own

5. **Update Google Analytics:**
   - In `js/analytics.js`, replace `G-H8BC1P6NJS` with your tracking ID
   - Or remove the file if not using analytics

## 🎨 Customization

### Colors
Edit `css/variables.css` to change:
- Primary color (default: Royal Blue)
- Secondary color (default: Hot Pink)
- Background colors
- Text colors

### Typography
Edit `css/reset.css` to change:
- Font families
- Font sizes
- Line heights

### Layout
Edit `css/pages.css` to change:
- Section spacing
- Container widths
- Responsive breakpoints

## 🌙 Dark Mode

The site includes automatic dark/light mode that:
- Detects system preference on first visit
- Saves user's manual choice
- Provides toggle switch in navigation
- Smoothly transitions between modes

## 📱 Responsive Design

Breakpoints:
- Mobile: < 62.5rem (1000px)
- Tablet: 62.5rem - 81.25rem (1000px - 1300px)
- Desktop: > 81.25rem (1300px)

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **Vanilla JavaScript** - No frameworks needed
- **Google Fonts** - Work Sans typography
- **Google Analytics** - Site tracking

## 📄 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

Personal portfolio project - all rights reserved.

## 👤 Author

**Marwan Rashwan**
- Email: MarwanRashwan@gmail.com
- LinkedIn: [marwanrashwan](https://www.linkedin.com/in/marwanrashwan/)
- GitHub: [MarwanMortada](https://github.com/MarwanMortada)

---

Built with 💙 by Marwan Rashwan
