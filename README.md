# 💌 Flip-Open Greeting Card

An interactive 3D greeting card built with pure HTML and CSS. The front cover is a handmade quilled-flower card. Hover over it (or tap on mobile) and the cover swings open to reveal a heartfelt thought inside.

> *"The Saddest part is trusting someone who never valued your loyalty."*

## ✨ Features

- 3D card-opening animation using CSS `perspective` and `rotateY`
- Realistic paper depth with edge shadows and folded-corner effects
- Handwritten fonts (Indie Flower and Amatic SC) from Google Fonts
- Tap-to-open support for touch devices (small JavaScript snippet)
- No frameworks or build tools, just open the file

## 📁 Project Structure

```
greeting-card/
├── index.html   # Card markup and tap-to-open script
├── styles.css   # 3D flip animation and styling
└── cover.jpg    # Front cover image
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   https://github.com/bhoomikaab88-gif/greeting.git
   ```
2. Open the folder and double-click `index.html` in any modern browser.

An internet connection is needed for the Google Fonts to load.

## 🎨 Customization

- **Change the message:** edit the text inside the `.quote` paragraph in `index.html`.
- **Change the cover:** replace `cover.jpg` with your own image (a square image works best).
- **Change card size:** adjust `width` and `height` in the `.card` rule in `styles.css`.
- **Change colors:** edit the background and `.color1` values in `styles.css`.

## 🛠️ Built With

- HTML5
- CSS3 (transforms, transitions, box-shadow)
- Vanilla JavaScript (for tap-to-open only)

## 🙏 Credits

The flip-card effect is inspired by the popular CSS open-book card technique.

## 📄 License

Free to use for personal projects. Add a license of your choice (for example, MIT) if you plan to share or reuse it more widely.
