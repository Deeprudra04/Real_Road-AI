# BharatKrishi AI - Revolutionizing Indian Agriculture

A modern, beautiful static website that showcases three AI-powered agricultural services to help Indian farmers make better decisions.

## 🌱 Features

### AI Services
1. **Krishi BOT** - Intelligent agricultural chatbot providing real-time guidance
2. **Predict Crop** - AI-powered crop recommendation system
3. **Rice Disease Detection** - Advanced computer vision for rice disease identification

### Website Features
- 🎨 Modern, responsive design with beautiful animations
- 👥 Team section with leader and member cards
- 📱 Mobile-friendly interface
- 🔗 Social media integration
- 📧 Contact form
- 🚀 Fast and optimized performance
- 🔗 Direct links to AI services

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **UI Framework**: Bootstrap 5
- **Icons**: Font Awesome 6
- **Fonts**: Google Fonts (Poppins)

## 📋 Prerequisites

- Any modern web browser
- No server setup required - it's a static website!

## 🚀 Installation & Setup

1. **Download the files**
   - Download all files to your local machine
   - Or clone the repository if available

2. **Configure the AI services**
   - Open `index.html` in a text editor
   - Find the service links in the Services section
   - Replace the placeholder IP addresses:
     ```html
     <!-- Krishi BOT -->
     <a href="http://YOUR_KRISHI_BOT_IP:5000" target="_blank" class="btn btn-primary">
     
     <!-- Predict Crop -->
     <a href="http://YOUR_PREDICT_CROP_IP:5000" target="_blank" class="btn btn-primary">
     
     <!-- Rice Disease Detection -->
     <a href="http://YOUR_RICE_DISEASE_IP:5000" target="_blank" class="btn btn-primary">
     ```

3. **Open the website**
   - Double-click on `index.html` to open in your browser
   - Or open it through any web server

## 📁 Project Structure

```
bharatkrishi-ai/
├── index.html              # Main HTML file
├── README.md               # Project documentation
├── static/
│   ├── css/
│   │   └── style.css      # Custom CSS styles
│   ├── js/
│   │   └── script.js      # JavaScript functionality
│   └── images/
│       └── placeholder.txt # Image requirements
```

## 🎨 Customization

### Updating Team Information
Edit the team section in `index.html`:

```html
<div class="team-card-content">
    <h4>Your Name</h4>
    <p class="team-role">Your Role</p>
    <p class="team-description">Your description</p>
</div>
```

### Changing Colors
Update the CSS variables in `static/css/style.css`:

```css
:root {
    --primary-color: #2e7d32;    /* Main green color */
    --secondary-color: #4caf50;  /* Secondary green */
    --accent-color: #8bc34a;     /* Accent green */
    /* ... other colors */
}
```

### Adding New Services
1. Add a new service card in the Services section of `index.html`
2. Update the corresponding CSS styles in `static/css/style.css`
3. Add any new JavaScript functionality in `static/js/script.js`

## 🔗 Service Configuration

To connect your AI services, update these links in `index.html`:

### Krishi BOT
```html
<a href="http://YOUR_KRISHI_BOT_IP:5000" target="_blank" class="btn btn-primary">
    <i class="fas fa-comments me-2"></i>Start Chat
</a>
```

### Predict Crop
```html
<a href="http://YOUR_PREDICT_CROP_IP:5000" target="_blank" class="btn btn-primary">
    <i class="fas fa-calculator me-2"></i>Get Prediction
</a>
```

### Rice Disease Detection
```html
<a href="http://YOUR_RICE_DISEASE_IP:5000" target="_blank" class="btn btn-primary">
    <i class="fas fa-camera me-2"></i>Upload Image
</a>
```

## 🖼️ Images

The website currently uses placeholder images from Picsum Photos. You can replace them with your own images:

- Hero image: `https://picsum.photos/800/600?random=1`
- Team photos: `https://picsum.photos/400/400?random=2` through `random=7`

To use your own images:
1. Add your images to the `static/images/` directory
2. Update the image sources in `index.html`
3. Recommended sizes:
   - Hero image: 800x600px
   - Team photos: 400x400px (square format)

## 🌐 Deployment

### Local Development
Simply open `index.html` in your web browser!

### Web Server Deployment
1. Upload all files to your web server
2. Ensure the file structure is maintained
3. Access via your domain name

### GitHub Pages
1. Push the code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://username.github.io/repository-name`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Commit your changes: `git commit -m 'Add feature'`
5. Push to the branch: `git push origin feature-name`
6. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For support and questions:
- Email: info@bharatkrishi.ai
- Phone: +91 98765 43210
- Location: Bangalore, Karnataka, India

## 🙏 Acknowledgments

- Bootstrap for the responsive framework
- Font Awesome for the beautiful icons
- Google Fonts for the typography
- Picsum Photos for placeholder images
- The agricultural community for inspiration

---

**BharatKrishi AI** - Empowering Indian farmers with cutting-edge AI technology. 