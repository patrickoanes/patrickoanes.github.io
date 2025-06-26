# Patrick Oanes Portfolio

A modern, responsive portfolio website built with HTML, Tailwind CSS, and JavaScript.

## 📁 Project Structure

```
patrickoanes.github.io/
├── index.html              # Original single-file version
├── index-new.html          # New modular version (recommended)
├── sections/               # Modular section files
│   ├── header.html         # Navigation header
│   ├── home.html           # Home/hero section
│   ├── about.html          # About section with tech stack, certifications, employment
│   ├── works.html          # Portfolio/works section
│   └── contact.html        # Contact section with social links
├── assets/
│   └── images/
│       ├── logo.svg
│       └── profile.jpg
└── README.md
```

## 🚀 How to Use

### Option 1: Modular Version (Recommended)
Use `index-new.html` for better maintainability:
- Each section is in its own file under `sections/`
- Easier to edit individual sections
- Better code organization
- Uses JavaScript to dynamically load sections

### Option 2: Single File Version
Use `index.html` for simplicity:
- Everything in one file
- No external dependencies for loading
- Easier to deploy

## 🛠️ Development

### Editing Sections
To modify a specific section, edit the corresponding file in the `sections/` folder:

- **Header/Navigation**: `sections/header.html`
- **Home/Hero**: `sections/home.html`
- **About**: `sections/about.html`
- **Works/Portfolio**: `sections/works.html`
- **Contact**: `sections/contact.html`

### Adding New Sections
1. Create a new HTML file in the `sections/` folder
2. Add your section content
3. Update `index-new.html` to include the new section:
   ```html
   <div id="new-section"></div>
   ```
4. Add the load call in the JavaScript:
   ```javascript
   loadSection('new-section', 'sections/new-section.html');
   ```

## 🎨 Features

- **Responsive Design**: Works on all devices
- **Modern UI**: Clean, professional design with Tailwind CSS
- **Smooth Animations**: CSS animations and hover effects
- **Accessible**: Proper semantic HTML and ARIA labels
- **Fast Loading**: Optimized for performance
- **Modular**: Easy to maintain and update

## 📧 Contact Information

- **Email**: oanespatrickjason@gmail.com
- **LinkedIn**: [Patrick Jason Oanes](https://www.linkedin.com/in/patrick-jason-oanes/)
- **GitHub**: [patrickoanes](https://github.com/patrickoanes)

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS
- JavaScript (ES6+)
- Devicon for tech stack icons
- Animate.css for animations

## 📝 License

This project is open source and available under the [MIT License](LICENSE). 