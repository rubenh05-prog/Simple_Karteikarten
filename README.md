📚 Simple Flashcards – PWA

A simple, fast Progressive Web App (PWA) for learning with flashcards – usable directly in the browser or installable as an app.

✨ Features

🧠 Learn with digital flashcards

⚡ Fast and works offline

📱 Installable as an app (PWA)

🌐 Runs on Windows, iOS, and Android

🔄 No registration required

🚀 Installation
🪟 Windows / macOS / Linux (Offline Desktop Installation)

This method works with the current PWA standards, with one important limitation explained below.

Steps

Extract the project folder

Open a terminal in the project directory

Start a local web server:

python -m http.server 8080


Open the app in a browser:

http://localhost:8080


Click “Install” in the browser (address bar or menu)

✅ What works

The app runs locally via localhost

PWA installation prompt appears in Chrome / Edge

Offline functionality works after installation

No internet connection required after install

⚠️ Important limitations (current state)

HTTPS is normally required for PWAs, but
👉 localhost is explicitly allowed by modern browsers

Firefox desktop does not support full PWA installation (runs as tab or shortcut)

Safari desktop does not support installable PWAs

Updates require restarting the local server and reloading the app

🍎 iOS (Safari – important)

Open the website in Safari

Tap the Share icon

Select “Add to Home Screen”

Confirm the app name → Add

The app appears on the Home Screen

⚠️ Other browsers on iOS do not fully support PWA installation.

🤖 Android (Chrome)

Open the website in Chrome

Tap “Install app”
or: Menu (⋮) → “Add to Home screen”

Confirm the installation

ℹ️ Notes

Updates are applied automatically when the app is reloaded

If issues occur: clear the browser cache or reinstall the app
