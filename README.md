# Mattia's Workshop

Minimalist developer portfolio with HTML, TailwindCSS, and AlpineJS. Clean, interactive, no fluff.

## Features

- **Typewriter animation** for hero text
- **Terminal simulation** with animated output
- **Expandable project cards**
- **Copy-to-clipboard** email functionality
- **Responsive design** with mobile menu

## Tech Stack

- HTML5 + TailwindCSS + AlpineJS
- Google Fonts (Inter + JetBrains Mono)
- No build process required

## Setup

1. Download `index.html`
2. Open in browser
3. Customize content

## Key AlpineJS Features

### Typewriter Effect
```javascript
x-data="{ currentText: '', texts: [...], isDeleting: false }"
```

### Terminal Animation
```javascript
x-data="{ commands: [...], displayedLines: [], currentIndex: 0 }"
```

### Project Toggles
```javascript
@click="selectedProject = selectedProject === 1 ? null : 1"
```

## Customization

- Update personal info in HTML
- Change `stone-*` colors to your preference
- Adjust animation timings (100ms typewriter, 300ms terminal)
- Replace project details

## Deployment

Works anywhere that serves static files:
- GitHub Pages, Netlify, Vercel
- Any web server

Just upload the HTML file!

---

**Made with ☕ and AlpineJS**
