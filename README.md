# Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS (SCSS), and JavaScript. This portfolio showcases web development skills with an interactive design and dark/light theme toggle.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Mode Toggle**: Built-in theme switcher for user comfort and accessibility
- **Smooth Navigation**: Interactive navigation between different portfolio sections
- **Modern UI**: Clean and professional design with smooth animations and transitions
- **Font Awesome Icons**: Integration of Font Awesome icons for visual enhancement
- **Google Fonts**: Uses Poppins font family for a modern appearance

## 📁 Project Structure

```
Portfolio/
├── app.js              # JavaScript for interactivity and theme switching
├── index.html          # Main HTML file
├── README.md          # Project documentation
├── styles/
│   ├── styles.scss    # SCSS source file
│   ├── styles.css     # Compiled CSS styles
│   └── _media.scss    # Media queries for responsive design
└── img/
    └── photomy.jpg    # Profile image
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3 & SCSS**: Styling with pre-processor for organization
- **JavaScript (ES6)**: Client-side interactivity
- **Font Awesome 5.15.4**: Icon library
- **Google Fonts**: Typography (Poppins)

## 📖 How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/supritR21/Portfolio.git
   cd Portfolio
   ```

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

3. **Access the Website**
   - Navigate to `http://localhost:8000` (or applicable port)

## ⚙️ Customization

### Update Personal Information
Edit the relevant sections in `index.html`:
- Replace the name, title, and description in the header section
- Update the profile image path in the `<img>` tag
- Modify social links and contact information

### Modify Styles
- Edit `styles/styles.scss` to customize colors, fonts, and layout
- Compile SCSS to CSS using your preferred build tool:
  ```bash
  sass styles/styles.scss styles/styles.css
  ```

### Add Sections
- Add new sections to `index.html` within the `<main>` element
- Create corresponding styling in `styles.scss`
- Update navigation controls to link to new sections

## 🎨 Features in Detail

### Dark/Light Mode
The theme toggle button allows users to switch between dark and light modes. The preference is applied to the entire page body with the `.light-mode` class.

### Interactive Navigation
- Click on navigation buttons (`.control`) to switch between sections
- Active button and corresponding section are highlighted
- Smooth transitions between sections

### Responsive Design
- Built with mobile-first approach
- Defined breakpoints in `_media.scss` for various screen sizes
- Flexbox and CSS Grid for flexible layouts

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔗 Resources

- [Font Awesome Icons](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [SCSS Documentation](https://sass-lang.com/)

## 📝 License

This project is open source and available for personal and educational use.

## 👤 Author

**Suprit Raj**
- Web Developer
- Computer Science Engineering Student

---

Feel free to customize this portfolio template for your own use. Happy coding! 🎉