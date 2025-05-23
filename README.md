# 🎉 Eid Greeting Card Generator

A simple Flutter app to create personalized Eid greeting cards with a beautiful predefined background, custom "To" and "From" text fields, and the ability to save the final card as an image to your device.

---

## ✨ Features

- 📷 **Greeting Card Generator** – Add your name and your recipient’s name.
- 🎨 **Predefined Eid Background** – Beautiful, festive design for your card.
- 📝 **Custom Message Fields** – Simple text fields: `From` and `To`.
- 💾 **Save as Image** – Converts your card widget to an image and saves it to your device using `RenderRepaintBoundary`.

---

## 🧱 Tech Stack

- **Flutter** (StatefulWidget for state management)
- `RenderRepaintBoundary` for widget-to-image conversion
- `dart:io` for saving files locally

---

## 🖼️ UI Overview

- 🏠 **Home Screen**
  - App logo at the top
  - Two text fields:
    - `To`: recipient's name
    - `From`: your name
  - A preview of the greeting card
  - A save button to export the card as an image

---

## 🚀 How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/eid-greeting-generator.git
   cd eid-greeting-generator
