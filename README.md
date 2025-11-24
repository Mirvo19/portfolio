# Personal Portfolio Website

A clean, modern, and responsive portfolio website built with HTML, CSS, and vanilla JavaScript. This portfolio is designed to showcase your projects, skills, and contact information in a professional manner.

## Features

- **Fully Responsive**: Works on all devices (mobile, tablet, desktop)
- **Modern UI/UX**: Clean design with smooth animations
- **Project Showcase**: Display your projects with images, descriptions, and tech stacks
- **Skills Section**: Highlight your technical skills
- **Contact Information**: Easy way for visitors to get in touch
- **Dark Theme**: Easy on the eyes with a professional look

## Customization

### 1. Personal Information

Open `index.html` and update the following sections:

- **Name and Title**: Update in the hero section
- **About Me**: Update the description in the about section
- **Skills**: Update the skills in the about section
- **Social Links**: Update the links in the contact section

### 2. Projects

Edit the `projects` array in `script.js` to add your own projects. Each project should have:

```javascript
{
    title: 'Project Name',
    description: 'Project description',
    technologies: ['Tech 1', 'Tech 2', 'Tech 3'],
    image: 'path/to/image.jpg',
    demo: 'https://live-demo-link.com',
    code: 'https://github.com/yourusername/project-repo'
}
```

### 3. Styling

You can customize the colors, fonts, and other styles in `styles.css`. The main color variables are defined at the top of the file:

```css
:root {
    --primary-color: #64ffda;
    --secondary-color: #112240;
    --text-color: #8892b0;
    --light-text: #ccd6f6;
    --dark-bg: #0a192f;
    --light-bg: #112240;
    --transition: all 0.3s ease;
}
```

### 4. Favicon

Replace the default favicon by adding a file named `favicon.ico` to the root directory.

## Deployment

You can deploy this portfolio to any static hosting service. Some popular options include:

- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

### Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to Settings > Pages
4. Select the `main` branch and click "Save"
5. Your site will be live at `https://username.github.io/repository-name/`

## Browser Support

This portfolio is built with modern web standards and works best in the latest versions of Chrome, Firefox, Safari, and Edge.

## License

This project is open source and available under the [MIT License](LICENSE).
