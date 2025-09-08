# Islamic Adhkar & Ruqyah Web App - Version 0.1

A clean, web-only version of the Islamic Adhkar and Ruqyah application, optimized for modern web deployment.

## Features

- **Morning & Evening Adhkar**: Complete collection with Arabic text, transliteration, and translations
- **Short Ruqyah Verses**: Essential verses for protection and healing
- **Manzil Verses**: Complete Manzil collection
- **Progressive Web App (PWA)**: Installable on mobile and desktop
- **Dark/Light Mode**: Toggle between themes
- **Multilingual Support**: Arabic with English translations and transliterations
- **Responsive Design**: Works on all devices

## Pages

- `index.html` - Main landing page
- `EveningMornindAdhkarv5.html` - Morning and Evening Adhkar
- `shortRuqyah.html` - Short Ruqyah verses
- `manzilVerses.html` - Complete Manzil verses
- `debug.html` - Debug and testing page

## Deployment

### Vercel Deployment

1. Create a new repository on GitHub
2. Push this code to the repository
3. Connect the repository to Vercel
4. Deploy automatically

The `vercel.json` configuration is optimized for static file serving with proper caching headers.

### Local Development

Simply open `index.html` in a web browser or serve with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

## Project Structure

```
├── index.html              # Main page
├── EveningMornindAdhkarv5.html
├── shortRuqyah.html
├── manzilVerses.html
├── debug.html
├── css/
│   └── index.css          # Main stylesheet
├── js/
│   └── index.js           # Main JavaScript
├── img/
│   └── logo.png           # App logo
├── manifest.json          # PWA manifest
├── vercel.json           # Vercel configuration
└── README.md             # This file
```

## Version History

- **Version 0.1**: Initial clean web-only release
  - Separated from Cordova mobile app
  - Optimized for web deployment
  - Added version numbers to all pages
  - Clean Vercel configuration

## License

This project is created for Islamic educational purposes.
