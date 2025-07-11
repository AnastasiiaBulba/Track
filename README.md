# Traffic Trap - Multi-Page Gaming Website

A modern, responsive website for the Traffic Trap driving game, built with pure HTML, CSS, and JavaScript.

## 🎮 Features

- **Responsive Design**: Mobile-first approach with breakpoints at 360px, 768px, and 1280px
- **Dynamic Content**: All content loaded from JSON files for easy management
- **Modern UI**: Clean, modern design with smooth animations and hover effects
- **Form Validation**: Real-time form validation with user feedback
- **Cookie Management**: GDPR-compliant cookie consent system
- **Mobile Menu**: Hamburger menu for mobile devices
- **Game Integration**: Embedded game iframe from GameMonetize

## 📁 Project Structure

```
Track/
├── index.html                 # Home page
├── contacts.html           # Contact page
├── news.html              # News page
├── disclaimer.html        # Legal disclaimer
├── privacy.html           # Privacy policy
├── cookies.html           # Cookie policy
├── css/
│   ├── reset.css            # CSS reset
│   ├── main.css             # Main styles and variables
│   ├── home.css             # Home page styles
│   ├── news.css             # News page styles
│   ├── contact.css          # Contact page styles
│   └── legal.css            # Legal pages styles
├── js/
│   ├── main.js              # Main JavaScript file
│   ├── cookieBar.js         # Cookie functionality
│   ├── mobileMenu.js        # Mobile menu
│   ├── dataLoader.js        # JSON content loader
│   ├── formValidation.js    # Form validation
│   ├── newsExpander.js      # News expand/collapse
│   └── modal.js             # Modal functionality
├── data/
│   └── content.json         # All website content
└── assets/
    └── favicon.ico          # Website favicon
├── unique_partials/
│   ├── header.html        # Header partial
│   ├── footer.html        # Footer partial
│   └── contact-info.html  # Contact info partial
```

## 🚀 Technologies Used

- **HTML5**: Semantic markup with proper structure
- **CSS3**: Flexbox layout, CSS variables, modern animations
- **JavaScript (ES6+)**: Modules, async/await, modern syntax
- **JSON**: Content management system
- **Local Storage**: Cookie preferences and user settings

## 🎯 Key Features

### Home Page

- Hero section with call-to-action
- Embedded game iframe
- Feature showcase with icons
- How-to-play instructions
- Track information
- Player reviews

### News Page

- Game updates section
- Trail diaries section
- Expandable content with "Read More" buttons
- Dynamic content loading

### Contact Page

- Contact information cards
- Contact form with validation
- Google Maps integration
- Success modal

### Legal Pages

- Comprehensive privacy policy
- Cookie policy
- Off-road gaming disclaimer

## 🎨 Design System

### Colors

- Primary: #2563eb (Blue)
- Secondary: #64748b (Gray)
- Accent: #f59e0b (Orange)
- Success: #10b981 (Green)
- Error: #ef4444 (Red)

### Typography

- System fonts: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif

### Breakpoints

- Mobile: 360px
- Tablet: 768px
- Desktop: 1280px

## 🔧 Setup and Usage

1. **Clone or download** the project files
2. **Open index.html** in a web browser
3. **Serve locally** for full functionality (due to CORS restrictions for JSON loading)

### Local Development Server

You can use any local server. Here are some options:

**Python 3:**

```bash
python -m http.server 8000
```

**Node.js (with http-server):**

```bash
npx http-server
```

**PHP:**

```bash
php -S localhost:8000
```

## 📱 Responsive Features

- **Mobile-first design** with progressive enhancement
- **Touch-friendly** interface elements
- **Optimized performance** for mobile devices
- **Flexible layouts** that adapt to screen size

## 🎮 Game Integration

The website integrates the Traffic Trap game via iframe from GameMonetize:

```html
<iframe
  src="https://gamemonetize.com/traffic-trap-game"
  frameborder="0"
  allowfullscreen
  class="game-iframe"
>
</iframe>
```

## 📋 Content Management

All website content is managed through the `data/content.json` file, including:

- Hero section content
- Game features
- How-to-play instructions
- Player reviews
- News articles
- Contact information

## 🔒 Privacy & Legal

- **GDPR Compliant**: Cookie consent system with localStorage
- **Privacy Policy**: Comprehensive privacy information
- **Cookie Policy**: Detailed cookie usage information
- **Disclaimer**: Gaming-specific legal disclaimers

## 🛠️ Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is created for educational and demonstration purposes.

## 🤝 Contributing

This is a demonstration project showcasing modern web development techniques for gaming websites.

---

**Note**: This website is designed to showcase modern web development practices and is not affiliated with any actual game or company.
