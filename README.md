# Personal Website — Abdi D. Nugraha

A simple, clean personal website built with static HTML, Vanilla JS, and a touch of Glassmorphism, showcasing projects and professional identity.

## 🚀 Live Demo

> [https://abdidnugraha.github.io/](https://abdidnugraha.github.io/)

## ✨ Features

- **Single Page Design**: Smooth scrolling and unified user experience.
- **Glassmorphism UI**: Modern, clean aesthetic with frosted glass effects.
- **Dynamic Content Loading**: Projects are loaded dynamically from `projects.json` using Vanilla JavaScript.
- **Fade-up Animations**: Subtle animations on page load and scroll.
- **Responsive Layout**: Optimized for both desktop and mobile devices.
- **Modal Previews**: Click-to-zoom functionality for project images.
- **Semantic HTML**: SEO-friendly structure with proper heading hierarchy and ARIA roles.
- **Lightweight & Fast**: No heavy frameworks or build tools.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure.
- **Vanilla JavaScript**: DOM manipulation, event handling, and dynamic content loading.
- **CSS3**: Custom Properties (Variables), Flexbox, Grid, and Glassmorphism effects.
- **Lucide Icons**: Open-source icon library.
- **Font Awesome**: Social media icons.

## 📁 Project Structure

```
abdidnugraha.github.io/
├── assets/
│   ├── css/
│   │   └── style.css     # Styles & Animations
│   └── js/
│       ├── projects.js   # Data layer for projects
│       └── scripts.js  # Main application logic (unused in final version, logic moved to index.html)
├── index.html          # Main entry point & application shell
├── projects.json       # Project data (JSON format)
└── README.md           # Project documentation
```

## 🔧 Setup & Installation

No complex setup is required. This is a static website.

1.  **Clone the repository** (or download the source code).
2.  **Open `index.html`** in your web browser.
3.  (Optional) Edit `projects.json` to update or add new projects.

## 🔄 Updating Projects

To add or modify projects, simply edit the `projects.json` file. The website will automatically reflect the changes on reload.

**File Structure:**

```json
[
  {
    "title": "Project Title",
    "description": "Short description.",
    "link": "https://example.com",
    "preview_image": "assets/img/project.jpg",
    "category": "Category",
    "tags": ["Tag1", "Tag2"],
    "delay": "0.1s" 
  }
]
```

## 🎨 Design Notes

The design uses CSS Variables for a consistent color palette:

-   **Background**: Dark blue/grey (`--bg`)
-   **Accents**: Electric blue (`--accent`)
-   **Glassmorphism**: `backdrop-filter: blur()` and semi-transparent backgrounds.

## 📝 Credits

-   **Icons**: [Lucide](https://lucide.dev/), [Font Awesome](https://fontawesome.com/)
-   **Fonts**: [Inter](https://fonts.google.com/specimen/Inter), [Lora](https://fonts.google.com/specimen/Lora)