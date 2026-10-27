# VarunOS Web Edition 1.1 🚀

A desktop-inspired web environment made with plain HTML, CSS, and JavaScript. It runs in a modern browser and can be hosted free with GitHub Pages.

## Features
- Desktop-style workspace, taskbar, Start menu, draggable app windows
- Start menu app search
- Quick Notes stored in browser localStorage, with JSON backup export
- Calculator with a restricted arithmetic parser
- Simulated Terminal with safe demo commands only
- Web Launcher for opening websites in a new tab
- Mission Control rocket launch animation (educational simulation)
- Wallpaper and dark/light appearance settings
- Keyboard shortcuts: `Ctrl + Space` opens/closes Start, `Esc` closes Start, `Ctrl + Alt + N` opens Notes
- Responsive styling and visible keyboard focus indicators

## Windows setup (free)
1. Download or clone this repository to your Windows laptop.
2. Extract the ZIP if you downloaded it.
3. Open the project folder in Visual Studio Code, or open `index.html` directly in Chrome or Edge.
4. For the best editing workflow, install the free **Live Server** extension in VS Code, right-click `index.html`, and choose **Open with Live Server**. Live Server is optional.
5. Edit `index.html`, `style.css`, and `script.js`. Save and refresh the browser.

No Node.js, paid API, or build step is required.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `varunos-web`.
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and `LICENSE` to the repository root.
3. Open **Settings → Pages**.
4. Under build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site; the URL usually looks like `https://YOUR-USERNAME.github.io/varunos-web/`.

## Data and safety notes
- Notes and appearance settings are stored in the current browser profile on this device. They do not automatically sync between devices. Use **Export backup** in Notes to download your notes as JSON.
- The Terminal is a simulator; it does not execute Windows commands.
- The File Explorer/Projects area is a demonstration and does not browse your actual computer files.
- The Mission Control animation is not a real flight or orbital simulation.
- The Web Launcher opens external sites in a new tab.
- This is a browser UI project, not a real operating system and not a Windows replacement.

## Project structure
```text
VarunOS-Web-Upgrade/
├── index.html   # Page structure and app shell
├── style.css    # Desktop layout, themes, and responsive styles
├── script.js    # Window manager and app behavior
├── README.md    # Setup and publishing instructions
└── LICENSE      # MIT License
```

## Next planned upgrades
1. Add import-from-backup for Notes with validation.
2. Add a dedicated app launcher and window snap/restore controls.
3. Add tests for calculator, storage failures, and keyboard navigation.
4. Consider an optional local desktop wrapper only after the web version is stable.

Created as a student learning project. Keep it safe, accessible, and free.
