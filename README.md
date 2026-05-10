
## Technologies Used

- HTML5 - Semantic markup
- CSS3 - Styling with CSS Variables, Flexbox, Grid, and animations
- JavaScript (Vanilla) - Interactivity and animations
- Font Awesome 6.4.0 - Icons
- IntersectionObserver API - Performance optimization for scroll animations

## Color Scheme

The portfolio uses a vibrant modern color palette defined in CSS variables:

- Primary: #ff006e (Pink)
- Secondary: #00d9ff (Cyan)
- Accent: #8338ec (Purple)
- Success: #06ffa5 (Green)
- Dark Background: #0a0e27
- Light Background: #ffffff

## Sections

1. **Navigation** - Fixed navbar with theme toggle and smooth scroll links
2. **Hero Section** - Profile image with introduction and call-to-action buttons
3. **About** - Personal information and education details
4. **Achievements** - Notable accomplishments and badges
5. **Skills** - Technical skills with progress bars (React, Node.js, MongoDB, Java, DSA, JavaScript)
6. **Projects** - Featured projects with descriptions and links
7. **Contact** - Contact information and contact form
8. **Footer** - Copyright information

## Core Functionality

### Theme Toggle
- Switches between dark and light mode
- Saves preference to localStorage
- Icon updates based on current theme

### Navigation
- Smooth scrolling to sections
- Active link highlighting on scroll
- Mobile hamburger menu

### Animations
- Hero section elements slide in on page load
- Skill bars animate when scrolled into view
- Cards fade in and slide up using IntersectionObserver
- Progress bar updates with scroll position
- Hover effects on interactive elements

### Contact Form
- Validates all fields before submission
- Shows success message on submission
- Resets form after submission

## Responsive Breakpoints

- Desktop: Full layout with 2-column grids
- Tablet (768px): Single column layout with adjusted font sizes
- Mobile (480px): Optimized spacing and smaller text

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## How to Use

1. Clone the repository
2. Open `index.html` in your web browser
3. No build process or dependencies required
4. Customize the content in `index.html` with your own information
5. Modify colors and styles in `styles.css`
6. Add additional functionality in `script.js` as needed

## Customization

To customize the portfolio:

1. Update personal information in the HTML
2. Replace `profile.jpg` with your own image
3. Modify the color variables in `:root` section of `styles.css`
4. Update social media links and contact information
5. Add or remove project cards as needed
6. Adjust skill percentages in the skills section

## Future Enhancements

- Connect contact form to backend service
- Add project filtering by technology
- Implement blog section
- Add testimonials section
- SEO optimization
- Analytics integration

## Author

Kanchan Bisht - Full Stack Developer & MCA Student

## License

This project is open source and available for personal use.
