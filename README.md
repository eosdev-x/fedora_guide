# 🚀 Fedora 44 Post-Installation Guide

<div align="center">

![Fedora](https://img.shields.io/badge/Fedora-44-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A visually stunning, interactive guide for optimizing your fresh Fedora 44 installation**

[View Demo](#-preview) • [Features](#-features) • [Installation](#-installation) • [Usage](#-usage)

</div>

---

## 📖 About

This landing page transforms essential Fedora 44 post-installation knowledge into a beautiful, interactive web experience. Fedora 44's package manager is DNF5 (`dnf` → `dnf5`). The guide covers the two speed tweaks that still matter, and explains which old DNF4 settings are already default — or gone.

### Why This Guide?

- **⚡ Faster installs** by raising DNF5 parallel downloads from 3 to 10
- **🧹 Automatic system cleanup** preventing bloat and disk space waste
- **🔒 Enhanced security** with proper GPG verification
- **📚 Educational** - explains *why* each setting matters, not just *what* to do

---

## ✨ Features

### 🎨 Design & UX

- **Cyberpunk Dark Theme** - Eye-catching gradient animations and glowing accents
- **Smooth Animations** - Scroll-triggered reveals and hover interactions
- **Interactive Elements** - Animated scroll progress indicator and dynamic section highlighting
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Custom Typography** - JetBrains Mono + Syne fonts for a distinctive technical aesthetic

### 📋 Content

- **5 Comprehensive Sections**:
  1. DNF Performance Optimization
  2. Security Settings Explained
  3. Automatic System Maintenance
  4. System Update Best Practices
  5. Next Steps & Recommendations

- **Detailed Explanations** - Every configuration option is thoroughly documented
- **Code Snippets** - Ready-to-use terminal commands with syntax highlighting
- **Visual Hierarchy** - Color-coded information boxes for quick scanning

### 🛠️ Technical Features

- **Pure Vanilla JavaScript** - No frameworks, no dependencies
- **CSS Custom Properties** - Easy theming and customization
- **Intersection Observer API** - Performant scroll animations
- **Semantic HTML5** - Accessible and SEO-friendly structure

---

## 🖼️ Preview

The landing page features:

- **Animated gradient backgrounds** that pulse and shift
- **Color-coded sections** (cyan for tips, blue for commands, purple for settings)
- **Interactive hover effects** that respond to user interaction
- **Smooth scroll progress indicator** at the top of the page
- **Professional code blocks** with proper formatting and labels

---

## 🚀 Installation

### Quick Start

1. **Download the file:**
   ```bash
   wget https://your-domain.com/index.html
   ```

2. **Open in your browser:**
   ```bash
   firefox index.html
   # or
   google-chrome index.html
   ```

### Hosting Options

#### Local Web Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

Then visit `http://localhost:8000/`

#### Deploy to GitHub Pages

1. Create a new repository
2. Upload `index.html`
3. Rename to `index.html`
4. Enable GitHub Pages in repository settings

#### Deploy to Netlify

Simply drag and drop the HTML file into [Netlify Drop](https://app.netlify.com/drop)

---

## 💻 Usage

### For End Users

Simply open the HTML file in any modern web browser. The guide is:
- **Self-contained** - No external dependencies required
- **Offline-ready** - Works without an internet connection (fonts load from Google Fonts CDN but degrade gracefully)
- **Copy-paste friendly** - All commands are ready to use

### For Developers

#### Customization

The design uses CSS custom properties for easy theming:

```css
:root {
    --bg-primary: #0a0e27;      /* Main background */
    --accent-blue: #51a8ff;      /* Primary accent */
    --accent-purple: #a855f7;    /* Secondary accent */
    --accent-cyan: #06b6d4;      /* Tertiary accent */
    /* ... more variables */
}
```

#### Adding New Sections

Sections follow a consistent structure:

```html
<section class="section">
    <h2><span class="section-number">N</span> Section Title</h2>
    <p>Content here...</p>
    
    <div class="code-block">
        <div class="code-header">
            <span class="code-label">Label</span>
        </div>
        <pre><code>command here</code></pre>
    </div>
</section>
```

---

## 🎯 What This Guide Covers

### 1. DNF5 Configuration (Fedora 44)
- Parallel downloads (10 vs DNF5 default of 3)
- Fastest mirror selection
- What Fedora already sets (`pkg_gpgcheck`, `best=False`, `skip_if_unavailable=True`)
- `deltarpm` removed — DNF5 does not support it

### 2. Security Best Practices
- GPG signature verification explained
- Why security settings should never be disabled
- Protection against compromised packages

### 3. System Maintenance
- Automatic removal of orphaned packages
- Kernel version management
- Disk space optimization strategies

### 4. Update Procedures
- Proper update commands
- Repository refresh best practices
- Update frequency recommendations

### 5. Next Steps
- RPM Fusion repository setup
- Flatpak configuration
- Essential tools installation
- GNOME 50 / KDE Plasma 6.6 customization

---

## 🎨 Design Philosophy

This guide follows several key design principles:

- **Bold over bland** - Distinctive aesthetic choices that stand out
- **Function meets form** - Beautiful design that enhances understanding
- **Context-specific** - Tailored specifically for Fedora users
- **Education-first** - Teaching *why*, not just *what*
- **Performance-conscious** - Fast loading, smooth animations

---

## 📊 Performance Impact

Following this guide's recommendations typically results in:

| Metric | Stock Fedora 44 | After this guide | Notes |
|--------|-----------------|------------------|-------|
| Package downloads | 3 parallel | 10 parallel | DNF5 max is 20 |
| Mirror pick | Metalink order | Latency-based `fastestmirror` | Optional |
| Cache / orphans | Already cleaned | Unchanged | DNF5 defaults |
| `deltarpm` | Not a DNF5 option | Not used | Don't add it |

---

## 🤝 Contributing

Contributions are welcome! Here are ways you can help:

- **Report Issues** - Found a typo or technical error? Open an issue
- **Suggest Improvements** - Have ideas for additional sections? Let me know
- **Design Enhancements** - CSS/animation improvements always appreciated
- **Translations** - Help make this guide accessible in other languages

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- **Fedora Project** - For creating an amazing Linux distribution
- **DNF Team** - For building a powerful package manager
- **Community** - For continuous feedback and improvements

---

## 📮 Contact

Created by **Dan** - A systems enthusiast at Panasonic Energy working with enterprise Linux environments.

- **Experience**: Oracle Linux, Fedora, Rocky Linux
- **Interests**: System optimization, hardware tuning, Linux administration

---

## 🔗 Related Resources

- [Official Fedora Documentation](https://docs.fedoraproject.org/)
- [DNF Command Reference](https://dnf.readthedocs.io/)
- [RPM Fusion Setup Guide](https://rpmfusion.org/Configuration)
- [Fedora Magazine](https://fedoramagazine.org/)

---

<div align="center">

**⭐ Star this project if you found it helpful!**

Made with ❤️ for the Fedora community

</div>
