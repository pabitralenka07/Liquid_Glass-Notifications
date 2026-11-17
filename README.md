# 🫧 Liquid Glass Notifications

A modern, ultra-sleek notification stack interface inspired by Apple iOS and futuristic liquid glassmorphism design. Built with pure HTML5, CSS3, and JavaScript featuring layered backdrop blur, specular edge lighting, interactive hover states, and ambient floating orbs.

---

## ✨ Features

- 💎 **Liquid Glass Aesthetics:** Multi-layered CSS `backdrop-filter` blur combined with specular gradient highlights and border reflections.
- 🔮 **Animated Floating Orbs:** Dynamic background ambient light orbs that smoothly float and rotate to accentuate translucent glass surfaces.
- 📬 **Status Variants:**
  - 🆕 **New Notification:** Features an attention-grabbing radial pulse animation (`.new`).
  - 🚨 **Urgent / Alert:** Subtle warm crimson glass tint for priority notifications (`.urgent`).
  - ✅ **Success:** Soft emerald glow for completed tasks and backups (`.success`).
  - 🎵 **Media & Standard:** Crisp frosted glass for regular app alerts and media feeds.
- 📱 **Fully Responsive:** Gracefully adapts across mobile phones, tablets, and desktop displays.
- ⚡ **Zero Dependencies:** Pure vanilla HTML, CSS, and JS — lightweight, fast, and drop-in ready for any web project or framework.

---

## 🚀 Live Demo & Preview

Open `index.html` in any modern web browser or serve it locally using your preferred development server.

```
+-----------------------------------------------------------+
|                      Liquid Glass                         |
|                                                           |
|   💬  New message from Sarah                 2 min ago    |
|       Hey! Are we still meeting for coffee tomorrow...    |
|                                                           |
|   🔔  Meeting starting soon                 15 min ago    |
|       Team standup meeting begins in 15 minutes...        |
|                                                           |
|   ✅  Backup completed                       1 hour ago   |
|       Your daily backup has been completed...             |
+-----------------------------------------------------------+
```

---

## 📁 Project Structure

```text
Liquid_Glass-Notifications/
├── index.html       # Clean semantic HTML markup
├── index.css        # Glassmorphism styling, animations & responsive media queries
├── index.js         # Interactive behavior & dynamic state handlers
└── README.md        # Documentation and guide
```

---

## 🛠️ Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/pabitralenka07/Liquid_Glass-Notifications.git
cd Liquid_Glass-Notifications
```

### 2. Run locally

You can open `index.html` directly in your browser:
```bash
open index.html
```

Or run with a local HTTP server:

**Using Python:**
```bash
python3 -m http.server 3000
```
Then navigate to `http://localhost:3000`.

**Using Node.js (npx serve):**
```bash
npx serve .
```

---

## 🎨 Customization

### Glass Blur & Transparency
Adjust the glass intensity and blur directly in `index.css`:
```css
.notification-card {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(20px) saturate(100%);
    -webkit-backdrop-filter: blur(40px) saturate(180%);
}
```

### Background Wallpaper
Change the background image in `index.css`:
```css
body {
    background-image: url("your-custom-wallpaper.jpg");
}
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/pabitralenka07/Liquid_Glass-Notifications/issues).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
