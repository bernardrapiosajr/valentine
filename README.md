# 💖 Interactive Valentine Card (Mobile Optimized)

A fun, interactive Valentine's card for mobile and web. It features a "No" button that stays perfectly in line with the "Yes" button until the user attempts to tap it—at which point it begins dodging!

## 🚀 Live Link
[👉 Click here to view my Valentine Card](https://bernardrapiosajr.github.io/valentine/)

## ✨ Key Features
* **Perfect Inline Alignment:** Buttons are aligned horizontally on all screen sizes using Flexbox.
* **Instant Mobile Dodge:** Added `ontouchstart` support so the button escapes the moment a finger touches it on a phone.
* **Smooth Transitions:** Uses CSS transitions to make the "No" button glide away rather than teleporting.
* **Sweet Message:** Displays "Happy valentines!" with a heart explosion when "Yes" is clicked.

## 🛠️ How it was fixed for Phone
1. **Touch-First Events:** Replaced standard `onclick` logic with `ontouchstart` to ensure mobile devices respond instantly before the tap is even finished.
2. **Fixed Positioning Switch:** The button starts as `relative` (staying in line) and instantly switches to `fixed` the moment it needs to dodge.
3. **Safe-Area Math:** Used `Math.max` and updated padding to ensure the button never dodges off the top or left of the phone screen.

## 👤 Credits
Created with ❤️ by **Bernard**
