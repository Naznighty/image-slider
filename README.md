# 🎞️ Image Slider

A lightweight, dependency-free image slider built with vanilla HTML, CSS, and JavaScript. Features smooth sliding transitions, manual navigation, dot indicators, auto-play, and pause-on-hover.

## ✨ Features

- **Auto-play** — advances every 5 seconds
- **Manual navigation** — prev/next arrow buttons
- **Dot indicators** — jump to any slide directly
- **Pause on hover** — auto-play stops while the cursor is over the slider
- **State-driven** — a single `current` index drives rendering, no duplicated logic
- **No dependencies** — pure HTML/CSS/JS, easy to drop into any project


🔗 **[Live Demo](https://naznighty.github.io/image-slider/)**


## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox, transitions)
- Vanilla JavaScript (DOM manipulation, event listeners, `setInterval`)

## 📁 Project Structure

```
├── index.html
├── style.css
└── script.js
```

## 🚀 Usage

1. Clone or download the project
2. Replace the image URLs in `index.html` with your own
3. Open `index.html` in a browser — that's it, no build step required

## ⚙️ Customization

- Change autoplay speed: edit `AUTOPLAY_DELAY` in `script.js`
- Change transition speed: edit the `transition` value on `.slides` in `style.css`
- Add/remove slides: add or remove `.slide` divs in `index.html`
