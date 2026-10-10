# CLTX4 Web Flasher Landing Page

A standalone, responsive landing page for the existing CLTX4 Web Flasher.

## Deploy to GitHub Pages
1. Upload `index.html` to the repository where you want the landing page.
2. In repository Settings → Pages, enable GitHub Pages for your chosen branch/folder.
3. The **Launch Web Flasher** buttons link to the existing tool:
   https://clintxproduction.github.io/web-flasherbruce/

## Included
- Responsive dark cyber / red CLTX4 style
- Live local clock and date
- Browser name and Web Serial API availability indicator
- Firmware safety notes and quick-start steps
- No build step, dependencies, or backend required

## Important
The system information is read locally in the visitor's browser. Web Serial support does not guarantee a device is connected or that a firmware file is compatible. Keep your existing flasher files unchanged when deploying this as a separate landing page.


## Branding assets
- `assets/images/cltx4-logo.jpg` — supplied CLTX4 logo
- `assets/images/cltx4-web-flasher-banner.png` — generated cyberpunk banner
Keep the `assets` folder alongside `index.html` when uploading to GitHub Pages.
