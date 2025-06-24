# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This template provides a professional showcase for developers, designers, and creatives to display their work and skills.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Smooth Scrolling**: Seamless navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Social Links**: Easy integration with social media profiles
- **Skills Showcase**: Visual representation of technical skills
- **Project Gallery**: Beautiful project cards with links to live demos and code

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and experience statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Featured projects with descriptions and links
5. **Contact Section**: Contact information and contact form

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content to match your personal information

## Customization

### Personal Information

Edit the following files to customize your portfolio:

#### `index.html`

- Update the title in the `<head>` section
- Change "John Doe" to your name throughout the file
- Update the hero subtitle and description
- Modify the about section content
- Add your own projects to the projects section
- Update contact information and social media links

#### `styles.css`

- Change the color scheme by modifying CSS variables
- Adjust fonts by updating the Google Fonts import
- Modify spacing and layout as needed

#### `script.js`

- Update form handling logic if needed
- Modify animations and interactions

### Color Scheme

The current color scheme uses:

- Primary Blue: `#2563eb`
- Secondary Purple: `#7c3aed`
- Accent Yellow: `#fbbf24`
- Text Colors: Various shades of gray

To change colors, update the CSS variables in `styles.css`.

### Adding Projects

To add a new project, copy the project card structure in the HTML:

```html
<div class="project-card">
  <div class="project-image">
    <i class="fas fa-icon-name"></i>
  </div>
  <div class="project-content">
    <h3>Project Name</h3>
    <p>Project description goes here.</p>
    <div class="project-tech">
      <span>Technology 1</span>
      <span>Technology 2</span>
    </div>
    <div class="project-links">
      <a href="#" class="project-link"
        ><i class="fas fa-external-link-alt"></i> Live Demo</a
      >
      <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>
```

### Adding Skills

To add new skills, update the skills section in the HTML:

```html
<div class="skill-item">
  <i class="fab fa-technology-icon"></i>
  <span>Skill Name</span>
</div>
```

## Browser Support

This portfolio website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

The website is optimized for performance with:

- Minimal JavaScript
- Optimized CSS
- Fast loading times
- Smooth animations

## Deployment

You can deploy this portfolio website to any static hosting service:

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your main branch as source
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop the project folder to Netlify
2. Your site will be deployed instantly
3. You'll get a custom URL

### Vercel

1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them with the community.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

## Credits

- Fonts: [Google Fonts](https://fonts.google.com/) (Inter)
- Icons: [Font Awesome](https://fontawesome.com/)
- Design Inspiration: Modern portfolio design trends
