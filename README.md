🛡️ CYBER // Elite Cybersecurity Portfolio

[ Defending the Digital Frontier ]

An interactive 3D cybersecurity portfolio website with terminal aesthetics, glitch effects, and immersive animations.

Version
License
Build
Security
PRs Welcome
Made with

🚀 Live Demo • 📦 Installation • 🎨 Features • 🛠️ Tech Stack • 📖 Documentation • 🤝 Contributing

📋 Table of Contents

About
Live Demo
Features
Screenshots
Tech Stack
Installation
Usage
Project Structure
Configuration
Browser Support
Performance
Security
Roadmap
Contributing
License
Acknowledgments
Contact

🎯 About

GREATE is a high-end, interactive cybersecurity portfolio designed for security researchers, penetration testers, red teamers, and ethical hackers who want to showcase their work with style and sophistication.

Built with a terminal-inspired aesthetic, the portfolio features:

🌐 3D interactive backgrounds powered by Three.js
💚 Matrix-style rain effects for that authentic hacker vibe
⚡ Glitch text animations with RGB split effects
🖥️ Simulated terminal interfaces with live command execution
🎨 Custom cursor with hover states
📱 Fully responsive design for all devices

"Breaking systems. Building trust."

🚀 Live Demo

Check out the live version: greate-portfolio.demo

⚠️ Note: The demo uses placeholder content. Fork the repo and customize it with your own information.

🎨 Features

✨ Visual Effects
3D Particle Network — Animated node graph with mouse parallax
Wireframe Icosahedron — Rotating geometric shapes
Matrix Rain — Classic falling characters background
Scanline Overlay — CRT monitor simulation
Glitch Typography — RGB-split text animations
Hexagonal Grid — Interactive hover effects

🧩 Interactive Components
Terminal Emulator — Simulated command-line interface
Animated Skill Bars — Scroll-triggered progress indicators
Counting Statistics — Numbers animate on viewport entry
Hover Transitions — Smooth micro-interactions
Custom Cursor — Green ring cursor with blend mode
Reveal Animations — Intersection Observer-based fade-ins

📄 Content Sections
| Section | Description |
|---------|-------------|
| 🏠 Hero | Glitch title with CTA buttons |
| 👤 About | Terminal-style profile + stats |
| 💪 Skills | Animated progress bars |
| 🛡️ Services | 6 service cards with icons |
| 📁 Projects | 6 case study cards with code snippets |
| 📧 Contact | Encrypted form with PGP info |

🎛️ Technical Features
✅ Zero dependencies (except CDN libs)
✅ Single-file deployment
✅ SEO-friendly semantic HTML
✅ Accessible (ARIA-ready)
✅ Performance-optimized animations
✅ Mobile-responsive breakpoints

📸 Screenshots

| Hero Section | Terminal Profile |
|:---:|:---:|
| Hero | Terminal |

| Skills Grid | Projects Showcase |
|:---:|:---:|
| Skills | Projects |

🛠️ Tech Stack

Core
HTML5 — Semantic markup
CSS3 — Custom properties, Grid, Flexbox, Animations
Vanilla JavaScript — ES6+ modules

Libraries (via CDN)
| Library | Version | Purpose |
|---------|---------|---------|
| Three.js | r128 | 3D rendering |
| Orbitron | Latest | Headings font |
| Share Tech Mono | Latest | Terminal font |
| Rajdhani | Latest | Body font |

Tools Used
🎨 Custom CSS animations
📐 Intersection Observer API
🖱️ Mouse tracking events
📊 Canvas 2D API (matrix rain)
🌐 WebGL (Three.js)

📦 Installation

Option 1: Quick Start (No Build)
bash
Clone the repository
git clone https://github.com/yourusername/greate-portfolio.git

Navigate to the project
cd greate-portfolio

Open in your browser
open index.html

That's it! No build step required. 🎉

Option 2: With Local Server
bash
Using Python
python -m http.server 8000

Using Node.js (npx)
npx serve

Using PHP
php -S localhost:8000

Then visit: http://localhost:8000

Option 3: Deploy to GitHub Pages
bash
Initialize git repo
git init
git add .
git commit -m "Initial commit: GREATE portfolio"
git branch -M main
git remote add origin https://github.com/yourusername/greate-portfolio.git
git push -u origin main

Enable GitHub Pages in repo settings
Settings → Pages → Source: main branch → / (root)

📖 Usage

Customizing Content

Update Personal Information

Open index.html and search for these sections:
html

GREATE
&gt; Defending the Digital Frontier_

  

contact@greate-sec.io

Modify Skills
html

  
    Your Skill Name
    95%
  
  
    
  

Add Projects

Duplicate a .project block and update:
Title ()
Description ()
Tech tags (.tech-tag)
Code preview (.project-code)
Links (.project-links)

Change Color Theme

Edit CSS variables at the top:
css
:root{
  --green:#00ff41;    / Primary accent /
  --cyan:#00ffff;     / Secondary accent /
  --red:#ff0040;      / Glitch effect /
  --purple:#b026ff;   / Tertiary accent /
  --bg:#05070a;       / Background /
}

📂 Project Structure

greate-portfolio/
├── index.html              # Main portfolio file (all-in-one)
├── README.md               # This file
├── LICENSE                 # MIT License
├── .gitignore              # Git ignore rules
├── assets/                 # (Optional) Static assets
│   ├── images/
│   └── fonts/
└── docs/                   # (Optional) Documentation
    └── screenshots/

💡 Note: This is a single-file application. All CSS and JavaScript are embedded in index.html for easy deployment.

⚙️ Configuration

Performance Tuning

Adjust these values in the JavaScript section:
javascript
// Matrix rain density
const fontSize = 14;           // Smaller = more characters

// 3D particle count
const particleCount = 150;     // Reduce for better mobile performance

// Animation frame rate
setInterval(drawMatrix, 50);   // Lower = faster (more CPU)

Disable Effects
javascript
// Disable 3D background
renderer.setSize(0, 0);

// Disable matrix rain
clearInterval(matrixInterval);
document.getElementById('matrix').style.display = 'none';

// Disable custom cursor
document.getElementById('cursor').style.display = 'none';
document.getElementById('cursor-dot').style.display = 'none';

🌐 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ 90+ | Full support |
| Firefox | ✅ 88+ | Full support |
| Safari | ✅ 14+ | Full support |
| Edge | ✅ 90+ | Full support |
| Opera | ✅ 76+ | Full support |
| IE 11 | ❌ | Not supported |

⚠️ WebGL Required: The 3D background requires WebGL support. Falls back gracefully on unsupported browsers.

📊 Performance

| Metric | Score |
|--------|-------|
| Lighthouse Performance | 95+ |
| First Contentful Paint | 
  

🗺️ Roadmap

v2.1.0 (Planned)
[ ] Dark/Light theme toggle
[ ] Blog section integration
[ ] Multi-language support (i18n)
[ ] Achievement badges system
[ ] Interactive CVE database viewer

v2.2.0 (Planned)
[ ] WebAssembly particle system
[ ] Advanced terminal emulator
[ ] Real-time threat map
[ ] Certificate viewer
[ ] Resume/CV download

v3.0.0 (Future)
[ ] React/Next.js migration
[ ] Headless CMS integration
[ ] Admin dashboard
[ ] Analytics dashboard
[ ] AI-powered chatbot

Have a feature request? Open an issue!

🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are greatly appreciated.

How to Contribute

Fork the Project
Create your Feature Branch
   bash
   git checkout -b feature/AmazingFeature
   3. Commit your Changes
   bash
   git commit -m 'feat: Add some AmazingFeature'
   4. Push to the Branch
   bash
   git push origin feature/AmazingFeature
   5. Open a Pull Request

Contribution Guidelines

✅ Follow existing code style
✅ Write clear commit messages (Conventional Commits)
✅ Update documentation as needed
✅ Test across multiple browsers
✅ Ensure mobile responsiveness
✅ Add comments for complex logic

Code of Conduct

Please read our Code of Conduct before contributing.

📜 License

Distributed under the MIT License. See LICENSE for more information.

MIT License

Copyright (c) 2026 GREATE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...

🙏 Acknowledgments

Three.js — For the amazing 3D library
Fontsource — For self-hosted fonts
The Hacker Community — For inspiration
Cybersecurity Professionals — For setting the standard
Open Source Contributors — For making this possible

Inspired By
🎬 The Matrix (1999)
🖥️ Mr. Robot
🎮 Hacknet
🔐 DEF CON Aesthetics

📬 Contact

Project Link: https://github.com/yourusername/greate-portfolio

Author: GREATE Security Team  
Email: contact@greate-sec.io  
PGP Key: 0xA1B2 C3D4 E5F6 7890  
Twitter: @greate_sec  
LinkedIn: in/greate-security

🔐 Stay paranoid. Stay secure.

📈 Project Stats

GitHub stars
GitHub forks
GitHub watchers
GitHub followers

GitHub issues
GitHub pull requests
GitHub last commit
GitHub repo size

⭐ If this project helped you, consider giving it a star! ⭐

⬆ Back to Top

Built with 💚 and paranoia by the GREATE team

██████╗ ██████╗ ███████╗████████╗███████╗███████╗████████╗
██╔════╝ ██╔══██╗██╔════╝╚══██╔══╝██╔════╝██╔════╝╚══██╔══╝
██║  ███╗██████╔╝█████╗     ██║   █████╗  ███████╗   ██║   
██║   ██║██╔══██╗██╔══╝     ██║   ██╔══╝  ╚════██║   ██║   
╚██████╔╝██║  ██║███████╗   ██║   ███████╗███████║   ██║   
 ╚═════╝ ╚═╝  ╚═╝╚══════╝   ╚═╝   ╚══════╝╚══════╝   ╚═╝
