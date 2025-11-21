# myPortfolio

A clean, modern, and responsive portfolio website designed to showcase 1-3 projects.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean design with smooth animations and transitions
- **Project Showcase**: Grid layout for displaying up to 3 projects with cards
- **Smooth Scrolling**: Navigation with smooth scroll to different sections
- **Interactive Elements**: Hover effects and fade-in animations
- **Easy to Customize**: Simple HTML/CSS/JS structure with clear sections

## Getting Started

1. Clone this repository or download the files
2. Open `index.html` in your web browser
3. Customize the content with your own information

## Customization Guide

### Personal Information

Edit `index.html` to update:
- Hero title and subtitle (lines 23-24)
- About section text (line 32)
- Contact links (lines 113-115)

### Projects

Each project card in the `#projects` section (starting at line 38) includes:
- **Project Image**: Replace the placeholder with your project screenshot
- **Project Title**: Update the `<h3>` tag
- **Description**: Update the `<p>` tag with project details
- **Technology Tags**: Modify the `<span class="tag">` elements
- **Project Link**: Update the `href` attribute with your project URL

### Colors

Customize the color scheme in `styles.css` by modifying the CSS custom properties in the `:root` section (lines 7-14):
```css
--primary-color: #2563eb;     /* Main blue color */
--secondary-color: #1e40af;   /* Darker blue */
--text-color: #1f2937;        /* Main text color */
--text-light: #6b7280;        /* Secondary text color */
```

### Adding/Removing Projects

To display fewer than 3 projects:
- Simply remove unwanted project card `<div class="project-card">` sections from `index.html`

To add more projects:
- Copy an existing project card and paste it within the `<div class="projects-grid">` section
- Update the content accordingly

## Structure

```
myPortfolio/
├── index.html      # Main HTML file
├── styles.css      # CSS styles and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # Documentation
```

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your own portfolio!