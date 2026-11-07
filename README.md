# Student ID Card Maker | طلبہ کارڈ ساز

A free, single-page web app that makes printable Urdu student ID cards (front and back) in the browser.
No login, no server. Everything is saved in the user's own browser.

تیار کنندہ: حمزہ مشتاق حسین بکالی

## Features
- Student photo from live camera, phone camera or gallery
- Automatic registration number, saved records with search, backup and restore file
- Card customization: institute names, address, phone, logo (with framing), colors, photo side, signature line
- Urdu institute name in a Thuluth-style Arabic font (Katibeh, with Amiri as fallback); a real Thuluth font file can be added in the design menu
- Long institute names shrink automatically; the logo stays at the top center and the photo stays in place
- Print (CR80 card size on A4) and direct PDF download
- Light and dark theme, works offline after the first visit

## Put it on GitHub Pages (free)
1. Create a new **public** repository on GitHub (free accounts need a public repository for Pages).
2. Click **Add file > Upload files** and drag in all the files from this folder (not the zip itself): `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`. Click **Commit changes**.
3. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and Save.
4. After a minute your app is at `https://<your-username>.github.io/<repository-name>/`.
5. Open that link in Chrome or Safari. On a phone use **Add to Home Screen** to install it.

## Notes
- The Urdu fonts are loaded from Google Fonts, so open the page online at least once.
- GitHub Pages is meant for projects, not for running a paid service. If you later sell access to the app, host it somewhere whose terms allow that.
- Add a license file of your choice if you want others to reuse the code.
