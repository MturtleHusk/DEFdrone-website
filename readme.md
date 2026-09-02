# DEFdrone, LLC — Website

Single-page site for DEFdrone, LLC, a Florida-based advisory firm helping
defense-sector companies prepare pitch materials and connect with investors.

## 📁 Structure
- `index.html` — main page (all sections)
- `assets/css/style.css` — all styling
- `assets/js/script.js` — nav toggle + scroll animations
- `assets/fonts/` — self-hosted Space Grotesk & Inter font files
- `assets/images/` — logo + partner headshots

## 🛠️ Before Going Live
1. Add `logo.png` to `assets/images/`
2. Add partner headshots: `partner-danny.jpg`, `partner-alex.jpg`, `partner-mitchell.jpg`
3. Add font files to `assets/fonts/` (see below)
4. Replace `REPLACE-DANNY`, `REPLACE-ALEX`, `REPLACE-MITCHELL` in `index.html` with real LinkedIn usernames

## 🔤 Fonts Needed
Download from Google Fonts or [gwfh.mranftl.com](https://gwfh.mranftl.com/fonts), convert to `.woff2`, and place in `assets/fonts/`:
- `SpaceGrotesk-Bold.woff2`
- `SpaceGrotesk-Medium.woff2`
- `Inter-Regular.woff2`
- `Inter-Medium.woff2`

Site works fine with system fonts even if these aren't added yet.

## 🚀 Deployment
Hosted via GitHub → AWS EC2. See deployment notes in project docs.

## 📧 Contact
defdronellc@gmail.com