# Nucleaire Sound - Electronic Music Label Website

A contemporary, minimalist static website for Nucleaire Sound electronic music label, built with pure HTML, CSS, and vanilla JavaScript. Inspired by contemporary art museums and galleries.

## Features

- **Contemporary Design**: Sterile, minimal aesthetic with clean lines and geometric shapes
- **Sophisticated Color Palette**: White, black, dark grey with striking red accent (#E63946)
- **Museum-Inspired Layout**: Gallery-style grid layouts with generous white space
- **Fully Responsive**: Mobile-first approach that looks great on all devices
- **Subtle Animations**: Refined scroll-triggered animations and smooth transitions
- **Interactive Elements**: Minimal custom cursor effect and elegant hover states
- **Performance Optimized**: Pure HTML/CSS/JS with no framework overhead
- **Easy to Customize**: Clean, well-organized code with CSS variables for easy theming

## Structure

```
nucleaire-sound/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # All styles with CSS variables
├── js/
│   └── script.js      # Vanilla JavaScript for interactions
└── README.md          # This file
```

## Sections

1. **Hero Section**: Large, impactful landing section with logo animation
2. **About**: Information about the label with animated statistics
3. **Releases**: Grid of latest music releases with hover effects
4. **Artists**: Showcase of label artists
5. **Contact**: Contact information and submission form with social links

## Design Philosophy

The design follows a contemporary art museum aesthetic with:
- **Generous white space** for breathing room
- **Grid-based layouts** that echo gallery walls
- **Minimal color palette** with strategic red accents
- **Clean typography** with Helvetica Neue
- **Subtle interactions** that don't distract
- **High contrast** sections (white, light grey, dark grey, black)

## Customization

### Colors
Edit CSS variables in `css/style.css`:

```css
:root {
    --color-primary: #E63946;        /* Red accent */
    --color-bg-white: #FFFFFF;       /* White background */
    --color-bg-light: #F8F8F8;       /* Light grey background */
    --color-bg-dark: #1A1A1A;        /* Dark grey background */
    --color-bg-darker: #0D0D0D;      /* Almost black background */
    --color-text-dark: #0D0D0D;      /* Dark text */
    --color-text-light: #FFFFFF;     /* Light text */
    --color-text-muted: #666666;     /* Muted text */
}
```

### Content
- Update content directly in `index.html`
- Replace placeholder images with actual release artwork
- Modify statistics in the About section
- Update social media links in the Contact section

## Usage

Simply open `index.html` in a web browser. No build process or server required!

For development:
```bash
# Using Python's built-in server
python -m http.server 8000

# Or using PHP
php -S localhost:8000

# Or using Node.js http-server
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- Add actual music player integration (Spotify, SoundCloud, etc.)
- Connect contact form to email service
- Add blog/news section
- Implement event calendar
- Add artist detail pages

## License

© 2026 Nucleaire Sound. All rights reserved.
