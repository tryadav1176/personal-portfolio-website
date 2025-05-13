# Personal Portfolio Website

A modern, responsive portfolio website designed specifically for AI/ML Engineers and Data Scientists and Web Developers to showcase their skills, projects, and research.

## Features

- **Animated Sections**: Scroll animations using AOS (Animate On Scroll)
- **Skills Visualization**: Animated progress bars for showcasing skill proficiency
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Dark/Light Mode Toggle**: Allow visitors to switch between dark and light themes
- **Modern UI Components**: Cards, progress bars, and interactive elements
- **SEO-friendly Structure**: Properly structured HTML for better search engine visibility

## Getting Started

### Prerequisites

- A web browser
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone or download this repository
2. Customize the content in `index.html` to add your own information
3. Replace the placeholder images in the `assets/images/` directory with your own
4. Update links to your social media profiles and projects

### Customization

#### Personal Information

Edit the HTML file to include your own:
- Name
- Job title
- About me description
- Skills and proficiency levels
- Projects with descriptions and links
- Contact information

#### Colors and Theme

Modify the CSS variables in `style.css` to change the color scheme:

```css
:root {
  --primary: #2e5bff;   /* Primary color */
  --secondary: #6c63ff; /* Secondary color */
  --accent: #00f2fe;    /* Accent color */
  --text: #f0f0f0;      /* Text color */
  --dark: #121212;      /* Background color */
  --light-dark: #1e1e1e; /* Secondary background */
}
```

#### Particles Background

Adjust the particle animation by modifying the `particles-config.json` file.

## File Structure

```
portfolio/
├── index.html             # Main HTML file
├── style.css              # Stylesheet
├── script.js              # JavaScript functionality
├── particles-config.json  # Configuration for particles background
├── assets/
│   └── images/            # Directory for images
│       ├── profile.jpg    # Your profile photo
│       ├── project1.jpg   # Project thumbnails
│       ├── project2.jpg
│       └── project3.jpg
└── README.md              # This file
```

## Adding New Sections

To add new sections to your portfolio:

1. Create a new section in the HTML file following the existing pattern
2. Add CSS styles for your new section in `style.css`
3. If needed, add JavaScript functionality in `script.js`

## Technologies Used

- HTML5
- CSS3
- JavaScript
- [Particles.js](https://vincentgarreau.com/particles.js/) - For interactive background
- [AOS Library](https://michalsnik.github.io/aos/) - For scroll animations
- [Typed.js](https://github.com/mattboldt/typed.js/) - For typing animation
- [Font Awesome](https://fontawesome.com/) - For icons

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Font Awesome for the icons
- Google Fonts for typography
- AOS, Particles.js, and Typed.js libraries

---

**Note**: Remember to update all placeholder content with your actual information before deploying! 
