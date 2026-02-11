# Büyük Kitap Değişimi

A simple static web app for the "Great Book Exchange" chain game. Built for GitHub Pages.

## How It Works

1. Share the story text on your Instagram/social media story
2. When someone responds "Varım!", send them your personalized link
3. They open the link, see the address to send a book to, and enter their own address
4. They get their own link to continue the chain

The app encodes addresses in URL-safe Base64, so no backend is needed. Everything runs client-side.

## Deploy

Push to GitHub and enable GitHub Pages from Settings → Pages → Deploy from branch (main).

The app is a single `index.html` file with no dependencies.

## Tech

- Pure HTML, CSS, JavaScript
- No frameworks, no build step
- Mobile-first responsive design
- URL-safe Base64 encoding for Turkish character support
