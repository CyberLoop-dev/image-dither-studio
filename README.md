<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:f472b6&height=180&section=header&text=image-dither-studio&fontSize=42&fontColor=ffffff&animation=fadeIn" alt="Image Dither Studio banner" width="100%"/>

<a href="https://github.com/CyberLoop-dev/image-dither-studio">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1100&color=f472b6&center=true&vCenter=true&width=720&lines=Image%20Dither%20Studio;Small+tools.+Clear+feedback.+Local+first." alt="Typing title"/>
</a>

<p><strong>Apply classic dithering algorithms to local images and export the result as a PNG.</strong></p>

[![License](https://img.shields.io/github/license/CyberLoop-dev/image-dither-studio)](LICENSE)
[![Language](https://img.shields.io/github/languages/top/CyberLoop-dev/image-dither-studio)](https://github.com/CyberLoop-dev/image-dither-studio)
[![Stars](https://img.shields.io/github/stars/CyberLoop-dev/image-dither-studio?style=flat)](https://github.com/CyberLoop-dev/image-dither-studio/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/CyberLoop-dev/image-dither-studio)](https://github.com/CyberLoop-dev/image-dither-studio/commits/main)

<img src="assets/overview.svg" alt="Image Dither Studio project illustration" width="100%"/>

</div>

## ✨ Overview

Apply classic dithering algorithms to local images and export the result as a PNG. **Image Dither Studio** is a small, focused Node.js and browser JavaScript project. It runs locally, keeps user data in the browser, and is designed to be easy to inspect and extend.

## 🚀 Features

- ✨ 🖼️ Load an image directly into the browser canvas.
- ✨ 🧮 Apply Floyd–Steinberg error diffusion or ordered Bayer 4×4 dithering.
- ✨ 🎚️ Adjust output color levels from 2 to 8.
- ✨ 📥 Export the processed image as PNG without uploading it.

## 🖥️ Demo

Run `npm start`, open `http://127.0.0.1:4173`, and use the controls in the page. Choose a local image, switch between the two algorithms, adjust the levels, and export the canvas.

## ⚡ Quick Start

```bash
npm start
```

No third-party npm packages are required.

## 🧰 Tech Stack

- **Runtime:** Node.js (built-in HTTP server)
- **Frontend:** HTML, CSS, browser JavaScript
- **Dependencies:** None

## 📁 Folder Structure

```text
image-dither-studio/
├── assets/overview.svg
├── public/index.html
├── server.js
├── package.json
├── .gitignore
├── LICENSE
└── README.md
```

## 🗺️ Roadmap

- [ ] Add selectable monochrome and custom palettes.
- [ ] Add image scale and preview comparison controls.

## 🤝 Contributing

Issues and pull requests are welcome. Keep changes focused, explain behavior changes, and include reproducible steps for reported bugs.

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f472b6,100:0f172a&height=110&section=footer" alt="Animated wave footer" width="100%"/>
</div>
