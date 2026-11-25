# I ♥ Music Creator

A beautiful browser-based generative music app. Create original melodies, basslines, and grooves based on mood, key, and tempo — all running 100% in your browser with the Web Audio API.

No install. No account. No server. Just open and play.

## Features

- **Mood-based generation**: Happy, Chill, Energetic, Romantic, Epic, Melancholy
- **Musical keys**: Major and minor keys
- **Adjustable tempo**: 70–160 BPM
- **Complexity levels**: Simple, Medium, Rich
- Generates **melody + bass + drums** that fit the chosen vibe
- Live visualizer while playing
- **On-screen piano** (click or use computer keyboard)
- Fully offline after loading

## Live Demo

Once you push this repo to GitHub, you can enable **GitHub Pages** and get a free live URL.

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/i-love-music-creator.git
   cd i-love-music-creator
   ```

2. Open `index.html` in any modern browser  
   (or use a simple local server):

   ```bash
   # Python
   python -m http.server 8000

   # or Node
   npx serve .
   ```

3. Open http://localhost:8000 in your browser.

## How to Deploy on GitHub Pages (Free)

1. Create a new repository on GitHub named `i-love-music-creator` (or any name you like).
2. Push this project to the repository.
3. Go to **Settings → Pages**.
4. Under **Source**, select the `main` branch and `/ (root)`.
5. Click **Save**.
6. After a minute, your app will be live at:
   `https://YOUR_USERNAME.github.io/i-love-music-creator/`

## Keyboard Controls (Piano)

| Key | Note |
|-----|------|
| A   | C4   |
| S   | D4   |
| D   | E4   |
| F   | F4   |
| G   | G4   |
| H   | A4   |
| J   | B4   |
| K   | C5   |
| L   | D5   |
| W   | C#4  |
| E   | D#4  |
| T   | F#4  |
| Y   | G#4  |
| U   | A#4  |

## Tech Stack

- Pure HTML + CSS + JavaScript
- Web Audio API (no external libraries)
- Responsive design

## License

MIT License — feel free to use, modify, and share.

---

Made with ♥ for people who love music.
