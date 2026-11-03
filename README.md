# Afterhours

Afterhours is a responsive event discovery and registration site for finding small local gatherings. It is built with semantic HTML, CSS, and vanilla JavaScript, with no build step or package dependencies.

## Run locally

Open `index.html` in a browser, or serve the project directory with any static web server. For example, if Python is installed:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Features

- Browse eight sample events, search by text, and filter by category
- Open an event for details and register with name, email, and phone validation
- Add, edit, and remove events in the on-page manager
- Save events, registrations, and the selected color theme in browser Local Storage
- Responsive layouts for mobile, tablet, and desktop
- Keyboard access for event cards and the `Ctrl`/`⌘` + `K` search shortcut

## Project files

- `index.html` — page structure, forms, and dialogs
- `styles.css` — visual styles, responsive layouts, and motion
- `script.js` — sample events, search, filtering, registration, and Local Storage

## Publish with GitHub Pages

This is a static site and can be hosted from the repository root:

1. Open the repository’s **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. GitHub Pages will show the published site URL in the Pages settings. Future pushes to `main` will publish updates.

Repository: [MahmudEkhlas/AfterHours](https://github.com/MahmudEkhlas/AfterHours)

## Data and external assets

The included event listings are sample content. Use **Manage gatherings** under the event cards to edit them. Changes and registration entries are stored only in the current browser’s Local Storage; they are not sent to a server or shared with other visitors and devices. A hosted database and server-side registration flow are needed for a shared, multi-user service.

Event photography is loaded from Unsplash and typography from Google Fonts, so those assets require an internet connection. The site itself can be served as static files.
