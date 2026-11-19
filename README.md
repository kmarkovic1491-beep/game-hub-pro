# Windows 11 Pro Web Desktop + Website Maker

A self-contained browser desktop simulation built with plain HTML, CSS, and vanilla JavaScript. It runs on GitHub Pages without a package manager, framework, or build step.

## Files
- index.html — desktop shell and app entry point
- style.css — wallpaper, taskbar, windows, and app styling
- script.js — window manager, Website Maker, File Explorer, Notepad, Settings, Calculator, and Browser

## Features
- Windows-style desktop, Start menu, taskbar, clock, lock/restart controls
- Draggable, resizable, minimizable, and maximizable app windows
- Website Maker with draggable/clickable blocks, inline text editing, properties inspector, desktop/mobile preview, local project saving, and standalone HTML export
- File Explorer with Desktop, Documents, and Saved Websites views
- Notepad editor with file download and saved-site opening
- Settings with wallpaper choices and appearance toggle
- Calculator and a simple browser launcher

## Run locally
Open index.html in a modern browser. For GitHub Pages, upload all three files to the repository root.

## Publish with GitHub Pages
1. Sign in to GitHub and open your repository (or create a new public repository).
2. Choose Add file → Upload files.
3. Upload index.html, style.css, and script.js together into the repository root (not inside a subfolder).
4. Commit the upload to the main branch.
5. Open Settings → Pages.
6. Under Build and deployment, choose Deploy from a branch.
7. Set the branch to main and folder to /(root), then click Save.
8. Wait for the Pages deployment to finish. GitHub will display the published URL in the Pages settings panel.

## Important limitations
This is an interactive web desktop simulation, not a licensed copy of Windows and not a virtual machine. It cannot boot Windows, install Windows applications, access the host computer's filesystem, or run .exe programs. Projects are saved in browser local storage on the current device/browser. Exported websites are standalone HTML files; upload the exported index.html to a separate repository (or a separate Pages folder/repository) to publish that site.