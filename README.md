# 🌌 Ram Charan AI Universe OS Portfolio

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-AI%20Universe%20OS-00f3ff?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-bd00ff?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

**A futuristic portfolio experience designed like a custom Operating System** 🚀

[Live Demo](#) | [Report Bug](mailto:ck528824@gmail.com) | [Request Feature](mailto:ck528824@gmail.com)

</div>

---

## 📖 About The Project

Welcome to **Ram Charan AI Universe OS** - a next-generation portfolio website that reimagines the traditional portfolio as a fully interactive Operating System experience. This isn't just a website; it's a digital universe showcasing my journey as a Full Stack Developer and AI Generalist.

### ✨ What Makes This Unique?

- **🖥️ OS-Style Interface**: Experience a portfolio like never before with draggable windows, boot animations, and system-style navigation
- **🎨 Neon-Glass Aesthetic**: Stunning glassmorphism design with vibrant neon accents (cyan & magenta)
- **🤖 AI-Powered Features**: Integrated AI chatbot powered by Google Gemini for interactive conversations
- **📱 Fully Responsive**: Seamless experience across all devices - desktop, tablet, and mobile
- **⚡ Performance Optimized**: Smooth animations and fast loading times

---

## 🎯 Features

### Core Features
- ✅ **Boot Animation Screen** - Authentic OS-style loading experience on page load
- ✅ **Animated Neon-Glass UI** - Modern glassmorphism with gradient borders and glow effects
- ✅ **Project Showcase** - 40+ projects displayed across 5 categories
- ✅ **Skills Dashboard** - System performance monitor-style skill display
- ✅ **AI Chatbot** - Interactive AI assistant for visitor engagement
- ✅ **Contact Terminal** - Terminal-style contact form for a unique UX
- ✅ **Scroll Reveal Animations** - Smooth fade-in effects as you scroll
- ✅ **Floating Elements** - Dynamic floating cards with parallax effects

### Project Categories
1. **Web Development** - Custom portfolios, e-commerce, landing pages
2. **App Development** - Mobile applications and utilities
3. **AI Automation** - 23+ AI agents and automation workflows
4. **AI RAG Agents** - Document Q&A, knowledge bases
5. **Chatbots** - Customer support, lead generation bots

---

## 🛠️ Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

</div>

### Technologies Used
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Fonts**: Google Fonts (Outfit)
- **Icons**: Font Awesome 6.4.0
- **AI Integration**: Google Gemini API (gemini-2.0-flash)
- **Design**: Glassmorphism, Neon aesthetics, Gradient animations

---

## 📁 Project Structure

```
my-portfiloramcharan/
│
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # Interactive functionality & AI chatbot
├── profile.jpg         # Profile image
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for modifications)

### Installation & Local Setup

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open the Project**
   - Simply open `index.html` in your web browser
   - Or use a local server for better experience:
   
   **Using VS Code Live Server:**
   ```bash
   # Install Live Server extension in VS Code
   # Right-click on index.html → "Open with Live Server"
   ```

   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

   **Using Node.js:**
   ```bash
   npx http-server
   # Visit http://localhost:8080
   ```

3. **Customize Your Content**
   - Update personal information in `index.html`
   - Modify colors and styles in `style.css`
   - Adjust animations and functionality in `script.js`
   - Replace `profile.jpg` with your own image

---

## 🌐 Deployment

### Deploy to Netlify (Recommended)

1. **Drag & Drop Method:**
   - Go to [app.netlify.com/drop](https://app.netlify.com/drop)
   - Drag your project folder
   - Your site is live! 🎉

2. **GitHub Integration:**
   ```bash
   # Push to GitHub
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   
   # Connect to Netlify
   # Go to netlify.com → New site from Git → Select your repo
   ```

### Deploy to Vercel

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Deploy:**
   ```bash
   cd my-portfiloramcharan
   vercel
   ```

3. **Or use Vercel Dashboard:**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Deploy automatically

### Deploy to GitHub Pages

1. **Create Repository:**
   - Create a new repo named `yourusername.github.io`

2. **Push Your Code:**
   ```bash
   git init
   git add .
   git commit -m "Deploy portfolio"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Source: Deploy from main branch
   - Your site will be live at `https://yourusername.github.io`

---

## 📸 Screenshots

### Hero Section
![Hero Section](./screenshots/hero.png)
*Animated profile with floating skill cards*

### Projects Showcase
![Projects](./screenshots/projects.png)
*40+ projects across 5 categories*

### AI Chatbot
![Chatbot](./screenshots/chatbot.png)
*Interactive AI assistant powered by Google Gemini*

### Contact Section
![Contact](./screenshots/contact.png)
*Modern glassmorphism contact form*

> **Note:** Add screenshots to a `screenshots/` folder for better documentation

---

## ⚙️ Configuration

### API Key Setup (Important!)

The chatbot uses Google Gemini API. To use your own API key:

1. Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Open `script.js`
3. Replace the API key:
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';
   ```

⚠️ **Security Note:** For production, move the API key to a backend service to keep it secure.

---

## 🎨 Customization Guide

### Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary-color: #00f3ff;    /* Cyan */
    --secondary-color: #bd00ff;  /* Magenta */
    --bg-color: #0a0a0f;         /* Dark background */
}
```

### Animations
Adjust animation speeds in `style.css`:
```css
.floating-card {
    animation: float 3s ease-in-out infinite;
}
```

### Content
Update your information in `index.html`:
- Personal details (name, email, location)
- Projects and descriptions
- Skills and expertise
- Social media links

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📧 Contact

**Ram Charan Toom**

- 📧 Email: [ck528824@gmail.com](mailto:ck528824@gmail.com)
- 💼 LinkedIn: [ramcharan-toom](https://www.linkedin.com/in/ramcharan-toom-b2a2a7258/)
- 🎥 YouTube: [@ramcharantoom](https://youtube.com/@ramcharantoom)
- 📝 Blog: [ramcharantoom.blogspot.com](https://ramcharantoom.blogspot.com/)

**Project Link:** [https://github.com/yourusername/portfolio](https://github.com/yourusername/portfolio)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Ram Charan Toom

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- [Google Fonts](https://fonts.google.com/) - Outfit font family
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Gemini](https://deepmind.google/technologies/gemini/) - AI chatbot integration
- Inspiration from modern OS designs and glassmorphism trends

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

**Built by Ram Charan with ❤️**

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)
![Powered by AI](https://img.shields.io/badge/Powered%20by-AI-00f3ff?style=for-the-badge)

</div>
