# NetCompute 2026 Website

Official website for the First Workshop on Computation over Heterogeneous Networks at IEEE INFOCOM 2026.

## Overview

NetCompute 2026 explores the intersection of computation and communication networks, bringing together researchers and practitioners to address challenges in distributed intelligence, edge computing, and networked systems.

**Workshop Details:**
- **Date:** May 18, 2026
- **Location:** Tokyo, Japan
- **Conference:** IEEE INFOCOM 2026

## Website Features

- **Modern, Responsive Design:** Fully responsive layout that works on desktop, tablet, and mobile devices
- **Clean Academic Aesthetic:** Professional blue-gray-white color palette inspired by IEEE conference pages
- **Interactive Elements:**
  - Sticky navigation with smooth scrolling
  - Collapsible topic cards in the Call for Papers section
  - Animated scroll effects
  - Mobile-friendly hamburger menu
- **Comprehensive Sections:**
  - Workshop scope and mission
  - 13 research topic areas
  - Organizer profiles
  - Important dates timeline
  - Tentative schedule
  - Venue information
  - Contact details

## Local Development

To view the website locally:

1. Clone this repository
2. Open `index.html` in your web browser
3. Or use a local web server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js http-server
   npx http-server
   ```

## Deployment to GitHub Pages

This website is ready for GitHub Pages deployment:

1. Ensure your repository is named `[username].github.io` or has a `gh-pages` branch
2. Push all files to your repository
3. Go to repository Settings → Pages
4. Select the branch to deploy (usually `main` or `gh-pages`)
5. Your site will be available at `https://[username].github.io/`

## File Structure

```
netcompute.github.io/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
├── favicon.svg         # Website icon (network + compute symbol)
└── README.md           # This file
```

## Customization Guide

### Updating Organizer Information

Edit the organizers section in `index.html` (around line 290). Replace placeholder images and add real contact links:

```html
<div class="organizer-photo">
    <img src="path/to/photo.jpg" alt="Name">
</div>
```

### Adding Submission Portal Link

Replace the placeholder `#` in the "Submit Paper" buttons with your actual submission portal URL:

```html
<a href="YOUR_SUBMISSION_PORTAL_URL" class="btn btn-secondary">Submit Paper</a>
```

### Modifying Important Dates

Edit the dates section in `index.html` (around line 460) to update deadlines.

### Updating Schedule

Modify the schedule section in `index.html` (around line 580) as your program takes shape.

### Changing Colors

Edit CSS variables in `styles.css` (lines 1-15):

```css
:root {
    --primary-blue: #2563eb;
    --dark-blue: #1e40af;
    /* ... other colors */
}
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with minimal dependencies
- Lazy-loading animations via Intersection Observer
- Smooth scrolling without external libraries
- Fast load times with vanilla JavaScript
- Responsive images and SVG favicon

## Accessibility

- Semantic HTML5 structure
- ARIA labels for interactive elements
- Keyboard navigation support
- Color contrast compliance
- Mobile-friendly touch targets

## Contact

For questions about the workshop or website:
- Email: organizers@netcompute2026.org
- Conference: [IEEE INFOCOM 2026](https://infocom2026.ieee-infocom.org/)

## License

© 2026 NetCompute Workshop. All rights reserved.

## Acknowledgments

Created for the IEEE INFOCOM 2026 Workshop on Computation over Heterogeneous Networks.

**Organizers:**
- Bhaskar Krishnamachari (USC)
- Jared Coleman (Loyola Marymount University)
- Carlee Joe-Wong (Carnegie Mellon University)