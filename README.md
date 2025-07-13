# 🐾 $TONK Meme Coin Website

<p align="center">
  <img src="assets/bonk-feral.gif" alt="$TONK Banner" width="300" />
</p>

This repository contains the source code for the **$TONK** meme coin landing page — a vibrant, fun, and responsive website designed to hype the feral Bonk-inspired crypto token.

---

## 📂 Project Structure

tonk-memecoin-website/
├── index.html # Main landing page with HTML, CSS & JS
├── assets/ # Images, GIFs, logos, icons
│ ├── bonk-feral.gif
│ └── logo.png
├── css/ # Stylesheets
│ └── styles.css
├── js/ # JavaScript files
│ └── walletConnect.js # Wallet connect logic & Web3 integration
├── README.md # This file
└── CNAME # (Optional) Custom domain for GitHub Pages

yaml
Copy
Edit

---

## 🧱 Key Components

- **index.html**  
  The core HTML page presenting the landing content — includes hero section, token lore, CTAs (buy, chart), and wallet connection button.

- **assets/**  
  Folder for all static media: GIFs of Bonk, logos, icons, backgrounds.

- **css/styles.css**  
  Styling rules that bring vibrant colors, responsive layouts, and the overall theme to life.

- **js/walletConnect.js**  
  Handles connecting users’ wallets using Web3Modal and ethers.js to enable seamless interaction with the blockchain.

- **CNAME**  
  Optional file to configure a custom domain when deploying to GitHub Pages.

---

## 🚀 How to Run Locally

Open `index.html` directly in any modern browser (Chrome, Firefox, Edge).  
For full Web3 wallet features, serve via a local server like:

```bash
# Using Python 3
python3 -m http.server 8000
