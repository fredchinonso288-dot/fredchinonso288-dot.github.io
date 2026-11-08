# The Apostle Cybersecurity Bible

A mobile-first, searchable cybersecurity reference website designed for Android Chrome and desktop browsers.

## What's included
- Linux and Bash
- Python for security
- Windows CMD and PowerShell
- Networking and protocols
- Cybersecurity practicals and tools
- Glossary and quick reference
- Search, dark/light theme, and responsive layout
- Progressive Web App (PWA) support with offline caching

## Publish it with GitHub Pages
GitHub Pages provides the HTTPS hosting needed for Chrome's installable/offline PWA features.

1. Extract this project folder on your computer.
2. Create a GitHub repository named `apostle-cybersecurity-bible`.
3. Upload the contents of this folder to the repository's root (so `index.html` is at the root).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait for GitHub Pages to publish the site. The Pages screen will show the website address.

## Open it on your Android phone
1. Open the published GitHub Pages address in Chrome.
2. Let the page load once while online.
3. Open Chrome's three-dot menu.
4. Tap **Add to Home screen** or **Install app** if Chrome offers it.
5. Open it from the new home-screen icon. After the first successful load, the cached pages can be available offline.

## Add more material
The learning content lives in `app.js` inside the `volumes` array. Each entry can include:
- `title`
- `cmd` (optional command or syntax)
- `what`
- `why`
- `example`
- `interpret`

Keep examples within systems and networks you own or are authorised to test. Do not put passwords, private keys, personal data or real client evidence in a public repository.

## Current edition
Version 1.0 is the first mobile reference edition. It is a foundation to expand as the study Bible is developed; it is not yet the complete expanded cybersecurity curriculum.
