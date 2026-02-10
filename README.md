# 💖 Be My Valentine - Interactive Web Card

A fun, interactive, and mobile-responsive Valentine's Day card featuring a "No" button that dodges the user's touch and a celebratory surprise when "Yes" is clicked.

## 🚀 Live Demo
Check it out here: [INSERT YOUR GITHUB PAGES LINK HERE]

## 📱 Mobile Fixes Applied
If you were having trouble with the "No" button not working on phones, the following fixes have been implemented:
* **Touch Action Fix:** Added `touch-action: none` to the "No" button to prevent the screen from scrolling or zooming while trying to tap it.
* **Viewport Constraints:** Updated the JavaScript logic to use `window.innerWidth` and `window.innerHeight` so the button never flies off the edge of the phone screen.
* **Absolute Positioning:** Switched from `fixed` to `absolute` positioning to handle mobile browser address bars better.
* **Audio Interaction:** Programmed the music to start on the "Yes" click, satisfying mobile browser security requirements.

## 🛠️ Built With
* **HTML5**
* **CSS3** (Animations & Gradients)
* **JavaScript** (DOM Manipulation)

## 👤 Created By
**Bernard**
