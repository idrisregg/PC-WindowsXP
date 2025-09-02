Windows XP Desktop (HTML/CSS)

A lightweight, purely front-end recreation of a Windows XP-style desktop built with HTML and CSS. a example for layout techniques (flexbox/grid).

Demo![Capture](https://github.com/user-attachments/assets/053ac320-6167-4877-9e71-fcea2f7b7952)


Open index.html in a browser (or serve with a local web server) to view the desktop.

Features

Pixel-style Windows XP visual — taskbar, Start button, desktop icons, wallpaper area.

Responsive layout: scales reasonably for typical desktop and laptop screen sizes.

Pure CSS styling for shadows and simple animations.

Project structure / (PC) ├─ home.html # main demo page ├─ style/ # CSS files │ └─ style.css ├─ img/ # images and icons │ ├─ folder.png │ ├─ right.png ├─ start.png ├─ window.jpg ├─ time.jpg

Clone or download the repository.

Open index.html directly in your browser

Edit files in style/ and img/ to customize.

Usage & Customization

Change the wallpaper: replace img/window.jpg and adjust background-size in style/style.css if needed.

Windows & dialogs: duplicate the window markup and modify content. CSS variables at the top of style.css make it easy to change colors and sizes.

Accessibility & Browser support

Designed for modern evergreen browsers (Chrome, Firefox, Edge, Safari). Works best with recent versions.

Use semantic HTML for non-decorative elements if you plan to extend the project. Add aria-* attributes and keyboard handlers for improved accessibility.

Tips for improvement

Convert icons to SVG for crisp scaling.

Concept inspired by Microsoft Windows XP UI.

Icons and wallpaper should be either your own assets or appropriately licensed
