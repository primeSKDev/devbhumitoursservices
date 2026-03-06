# Devbhumi Tours Services - Official Website

Your Gateway to Unforgettable Journeys in India.

![Devbhumi Tours](https://images.unsplash.com/photo-1506929562872-bb421503ef21?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

## 🌟 About

Discover India's most enchanting destinations through **Devbhumi Tours Services**, your trusted online travel companion. We specialize in:

- **Char Dham Yatra** - Sacred pilgrimage in Uttarakhand
- **Himalayan Adventures** - Trekking and mountain expeditions
- **Cultural Expeditions** - Explore India's rich heritage
- **Customized Itineraries** - Tailored to your preferences

## 🚀 Features

- ✅ Fully Responsive Design (Mobile, Tablet, Desktop)
- ✅ Modern UI with Tailwind CSS
- ✅ Interactive Tour Packages Gallery
- ✅ Customer Testimonials
- ✅ Easy Booking & Contact Forms
- ✅ 24/7 Support Information
- ✅ Smooth Scrolling Navigation
- ✅ SEO Optimized Structure

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript** - Interactive elements (mobile menu, smooth scroll)
- **Font Awesome** - Icons

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/devbhumi-tours.git
   cd devbhumi-tours
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build CSS for GitHub Pages**
   ```bash
   npm run build:css
   mkdir -p css
   cp dist/output.css css/style.css
   ```

4. **Watch for changes (Development)**
   ```bash
   npm run watch:css
   ```

5. **Open in browser**
   Simply open `index.html` in your favorite browser.

### ⚠️ Important for GitHub Pages

The CSS file is now located in the `css/` folder for proper GitHub Pages deployment. Make sure to:
1. Build the CSS using step 3 above
2. Commit and push the `css/style.css` file to your repository
3. The `index.html` references `./css/style.css` which works correctly on GitHub Pages

## 📱 Preview on GitHub Pages

To view this website live on GitHub:

1. Push your code to a GitHub repository
2. Go to **Settings** > **Pages**
3. Select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at: `https://your-username.github.io/repository-name`

**Quick Preview Alternative:**
Visit: `https://htmlpreview.github.io/?https://github.com/your-username/repository-name/blob/main/index.html`

## 📂 Project Structure

```
devbhumi-tours/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Compiled CSS (for GitHub Pages)
├── src/
│   └── css/
│       └── input.css   # Tailwind source file
├── dist/
│   └── output.css      # Compiled CSS (development)
├── tailwind.config.js  # Tailwind configuration
├── package.json        # Dependencies & scripts
└── README.md           # This file
```

## 🎨 Customization

### Change Colors
Edit `tailwind.config.js`:
```javascript
theme: {
  extend: {
    colors: {
      primary: '#ea580c', // Change to your brand color
      secondary: '#c2410c',
    }
  }
}
```

### Add New Destinations
Add new cards in the Destinations section of `index.html`:
```html
<div class="bg-white rounded-lg shadow-lg overflow-hidden">
  <img src="your-image.jpg" alt="Destination Name">
  <div class="p-6">
    <h3 class="text-xl font-bold">Destination Name</h3>
    <p>Description...</p>
  </div>
</div>
```

## 📞 Contact

For inquiries or support:
- **Email**: info@devbhemitours.com
- **Phone**: +91-XXX-XXXX-XXX
- **Address**: Dehradun, Uttarakhand, India

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Images from Unsplash
- Icons from Font Awesome
- Built with Tailwind CSS

---

**Made with ❤️ for Devbhumi Tours Services**

*Explore India's Hidden Gems with Us!*
