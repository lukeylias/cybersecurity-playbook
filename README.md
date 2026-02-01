# Cybersecurity Fundamentals - Interactive Visualizers

An interactive educational website that explains cybersecurity and networking concepts through step-by-step visualizations. Learn how the internet works, from DNS lookups to HTTP protocols, Linux commands, and VPN encryption.

## 🎯 Project Overview

This project provides visual, interactive explanations of fundamental cybersecurity and networking concepts. Each page walks you through complex topics with animations, step-by-step guides, and clear explanations.

## 📚 Topics Covered

### Networking
- **OSI Model** - The 7-layer framework for network communication
- **DNS Lookup** - How domain names resolve to IP addresses
- **VPN** - Encrypted tunnels and online privacy

### Web Technologies
- **HTTP Protocol** - Methods, status codes, and headers
- **Cookies** - Maintaining state on the stateless web

### Systems
- **Linux Fundamentals** - Essential command line skills
- **Packages & Logs** - Software management and system monitoring

## 🚀 Viewing Locally

Simply open `index.html` in your web browser. All pages are self-contained with inline CSS and JavaScript, so no build process or server is required.

### Option 1: Direct File Opening
1. Navigate to the project directory
2. Double-click `index.html` or open it with your preferred browser

### Option 2: Local Server (Recommended)
For the best experience, use a local web server:

**Python 3:**
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`

**Node.js (with http-server):**
```bash
npx http-server -p 8000
```

**PHP:**
```bash
php -S localhost:8000
```

## 🌐 GitHub Pages Deployment

This repository is ready for GitHub Pages deployment:

1. Push your code to a GitHub repository
2. Go to **Settings** → **Pages**
3. Under **Source**, select your main branch (usually `main` or `master`)
4. Click **Save**
5. Your site will be available at `https://[username].github.io/[repository-name]/`

### Notes
- All internal links use relative paths and will work on GitHub Pages
- External resources (Google Fonts) are loaded via CDN
- No build process required - just push the HTML files

## 📁 Project Structure

```
cybersecurity-playbook/
├── index.html              # Homepage with topic overview
├── osi-model.html          # OSI Model visualization
├── dns.html                # DNS Lookup walkthrough
├── vpn.html                # VPN encryption explanation
├── http.html               # HTTP Protocol reference
├── cookies.html            # Cookie lifecycle visualization
├── linux.html              # Linux command reference
├── linux-admin.html        # Package management & logs
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **Vanilla JavaScript** - No frameworks, pure JS for interactivity
- **Google Fonts** - DM Mono and DM Sans typography

## 📝 Features

- **Interactive Visualizations** - Step-by-step animations showing how concepts work
- **Keyboard Navigation** - Use arrow keys or spacebar to navigate through steps
- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Dark Theme** - Easy on the eyes with a modern dark color scheme
- **Self-Contained** - All styles and scripts are inline, no external dependencies

## 🎨 Design Philosophy

Inspired by [makingsoftware.com](https://makingsoftware.com), this project focuses on:
- **Clarity** - Breaking down complex topics into digestible steps
- **Visual Learning** - Using animations and diagrams to illustrate concepts
- **Practical Examples** - Real-world scenarios and code examples
- **Progressive Disclosure** - Revealing information step-by-step

## 📄 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

---

**Built for learning · Inspired by makingsoftware.com**

