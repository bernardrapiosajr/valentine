# 💖 Interactive Valentine Card (Mobile Optimized)

A fun, interactive Valentine's card for mobile and web. It features a "No" button that perfectly aligns with the "Yes" button initially, but "breaks free" and dodges the user as soon as they try to click it.

## 🚀 Live Link
[👉 Click here to view my Valentine Card](https://bernardrapiosajr.github.io/valentine/)

## ✨ Key Features
* **Perfect Alignment:** The "No" and "Yes" buttons stay on the same line until the prank begins.
* **The Dodge Trap:** The "No" button uses a smooth `cubic-bezier` transition to slide away when clicked or hovered, making it impossible to catch.
* **Romantic Atmosphere:** Includes floating heart animations and background music that triggers upon saying "Yes."
* **Mobile Ready:** Optimized touch-action settings to ensure the button doesn't fly off-screen or cause zooming issues on mobile devices.

## 🛠️ How it was fixed for Phone
If you are building this, here are the core fixes used for this version:
1. **Dynamic Positioning:** The "No" button starts in the normal document flow (relative) to stay next to "Yes," and only switches to `absolute` positioning the moment the `dodge()` function is triggered.
2. **Bounds Detection:** Uses `window.innerWidth` and `window.innerHeight` with padding to ensure the button stays within the visible screen.
3. **Cubic-Bezier Timing:** Added a bouncy slide effect (`cubic-bezier(0.175, 0.885, 0.32, 1.275)`) to make the movement feel organic.

## 👤 Credits
Created with ❤️ by **Bernard**
