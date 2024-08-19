# 🎯 Random Emoji Hover Effect

## 📖 Description

A simple feature that changes an emoji randomly and scales it up when you hover over it. This adds a fun and interactive touch to any webpage.

## 🛠️ Tech Stack

- 🖼️ **HTML**: Structure
- 🎨 **CSS**: Styling & Scaling
- ✨ **JavaScript**: Random Emoji Logic

## 🚀 How It Works

On mouse hover, JavaScript selects a random emoji from an array and updates the displayed emoji. CSS handles the scaling effect for a dynamic visual experience.

### Core Code

```javascript
emoji.addEventListener("mouseover", () => {
  emoji.innerText = emojis[Math.floor(Math.random() * emojis.length)];
});
```

## 📂 Usage

1. **Clone the repo**: `git clone https://github.com/your-username/random-emoji-hover-effect.git`
2. **Open** `index.html` in your browser.

