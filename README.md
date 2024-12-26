# Dental Clinic Website

A modern, responsive website for a dental clinic built with HTML, Tailwind CSS, and JavaScript. The website features a clean design with sections for services, testimonials, appointment booking, and contact information.

## 📋 Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features
- Online appointment booking system
- Service showcase with hover effects
- Testimonials section
- Blog section
- Contact form
- SEO-friendly structure

## 🛠 Technologies Used
- HTML5
- Tailwind CSS
- JavaScript
- Font Awesome Icons
- Google Fonts (Manrope)

## 🚀 Getting Started

### Prerequisites
- Node.js (for Tailwind CSS)
- A modern web browser

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/dental-clinic-website.git
cd dental-clinic-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the Tailwind CSS build process:
```bash
npm run watch
```

4. Open `index.html` in your browser or use a local development server.

## 📁 Project Structure
```
dental-clinic-website/
├── index.html
├── src/
│   ├── all.min.css       # Font Awesome styles
│   └── output.css        # Compiled Tailwind CSS
├── images/              # Image assets
├── README.md
└── package.json
```

## 🎨 Customization

### Colors
The website uses a custom color palette defined in the Tailwind configuration:
- Primary Color (Gamboge): Custom orange shade
- Secondary colors: Various grays and whites
- Accent colors: Custom blues and other supporting colors

To modify colors, update the `tailwind.config.js` file:
```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        gamboge: {
          DEFAULT: '#E49B0F',
          400: '#EBA532',
          600: '#D18A0F',
          800: '#B67A0E',
          900: '#9A690D'
        }
      }
    }
  }
}
```

### Images
Replace the images in the `images/` directory with your own:
- Logo.png
- Old-Logo.png
- doctor_*.jpg (various doctor images)
- service images for different dental procedures

## 📦 Dependencies
- Tailwind CSS v3.x
- Font Awesome v6.x
- Google Fonts (Manrope)

## 🌐 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Credits
- Design and Development: Yousef Elbilkasy
- Icons: Font Awesome
- Images: pexels

## 📞 Support
For support, please email yousef2004bilkasy@gmail.com] or open an issue in the GitHub repository.
