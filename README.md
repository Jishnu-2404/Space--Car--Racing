# Space Car Racing 🚀

A fast-paced space racing game where you pilot a ship, avoid obstacles, and survive as long as possible!

## 🎮 How to Play

1.  **Objective**: Survive as long as you can and achieve the highest score.
2.  **Controls**:
    *   **Arrow Keys** or **WASD**: Move your ship.
    *   **Escape**, **P**, or **Spacebar**: Pause the game.
    *   **Mobile**: Touch and drag to move.

## 🚀 Running Locally

To play the game on your local machine:

1.  Ensure you have the `index.html` file (and any assets if separated).
2.  Open `index.html` directly in your web browser.
    *   *Note*: For the best audio experience, some browsers may require user interaction (click anywhere) before sound starts.

Alternatively, running a local server is recommended for better performance and asset loading:

```bash
# Python 3
python3 -m http.server 8080
```

Then visit `http://localhost:8080` in your browser.

## 📦 Deployment

This game is a static web application, making it easy to deploy on various platforms.

### GitHub Pages (Recommended)
1.  Create a new repository on GitHub.
2.  Push `index.html` to the repository.
3.  Go to **Settings** > **Pages**.
4.  Select the branch (usually `main`) and root folder.
5.  Click **Save**. Your game will be live in a few minutes!

### Netlify / Vercel
1.  Drag and drop the folder containing `index.html` into the deployment dashboard.
2.  The platform will automatically build and deploy the site.

## 🛠 Tech Stack
*   **HTML5 Canvas**: For high-performance rendering.
*   **Vanilla JavaScript**: No frameworks, just pure code.
*   **Web Audio API**: For sound effects and generated music.
