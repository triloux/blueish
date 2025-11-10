# 🟦 Blue Bayer Dither — Pure Blue CRT Render Tool

Transform images into a **pure-blue monochrome CRT / print-dither aesthetic** — right in the browser.

This tool applies:

- 🎨 Electric Blue Monochrome (#0077FF palette)
- ▦ 4×4 Ordered Bayer Dithering (retro CRT / print press)
- 🔆 Contrast & Brightness Boost
- 🎞 Subtle Film Grain Overlay
- ⚡ 100% Client-side — no uploads, privacy-safe

Upload → adjust → download. All in-browser.

---

## ✨ Demo

> https://triloux.github.io/blueish/ — hosted via GitHub Pages

---

## 🖼 Example Output

https://x.com/triloux/status/1987857711178961090

---

## 🚀 Features

| Feature | Description |
|---|---|
🎛 Real-time sliders | Contrast, brightness, grain, dot size  
🧠 Bayer dithering engine | Authentic 4×4 threshold matrix  
📂 Local-only processing | Zero data leaves the browser  
🎨 Blueprint / CRT vibes | Deep navy shadows + electric blue light  
📥 One-click download | High-quality PNG export  

---

## 🧩 Usage

1. **Upload an image**
2. **Adjust sliders**
   - Contrast
   - Brightness
   - Grain
   - Dot size
3. **Download processed image**

---

## 🛠 Tech Stack

- HTML5 Canvas
- Vanilla JavaScript
- CSS UI
- No dependencies
- No server

---

## 🧠 How It Works

1. Convert to grayscale  
2. Apply 4×4 Bayer ordered dithering  
3. Map tones → electric-blue palette  
4. Apply display-style contrast curve  
5. Overlay analytic grain to preserve color  

Inspired by:

- CRT scanline & pixel-mask textures  
- Risograph / screen printing  
- Cyanotype & blueprint photography  

---

## 📦 Run Locally

Clone the repo:

```
git clone https://github.com/<username>/blueprint
cd blueprint
```

Open the site:

```
open index.html       # macOS
```

or

```
xdg-open index.html   # Linux
```

> Or simply double-click `index.html`

No build, no install, no tooling required.

---

## 🌐 Deploy

Since it's static, you can host it anywhere:

- GitHub Pages
- Netlify Drop
- Vercel
- Cloudflare Pages
- Local file system

---

## 📄 License

**MIT License**  
Free to use, modify, share, remix.

---

## 🤝 Contributions

PRs welcome!  
Ideas:

- Additional color modes
- Scanline / pixel-mask shader
- Drag-and-drop UI
- Batch processing
- Mobile UI refinements

---

## ⭐ Support

If you like this tool, ⭐ star the repo and share it!
