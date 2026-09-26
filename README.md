# ⚡ PDFForge — Client-Side PDF & Office Toolkit

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A 100% serverless, client-side web application designed to process PDFs, perform OCR, and convert office documents instantly. 

Everything runs locally inside the user's browser using their device's hardware—meaning **no backend servers, zero hosting costs, and total data privacy.**

## 🚀 Live Demo
[👉 **Open PDFForge Live App**](https://pdfforge-tool.github.io/pdfforge/)

<!-- Add your screenshot here! Replace the link below with the actual image from your repo -->
![Uploading image.png…]()
---

## ✨ Features

- **PDF Processing:** Read, render, and generate PDFs entirely in the browser.
- **Optical Character Recognition (OCR):** Extract text from images and scanned PDFs locally using Tesseract.js.
- **Office Document Conversion:** Parse and convert Excel (`.xlsx`) and Word (`.docx`) files without uploading them to a server.
- **Bulk Packaging:** Automatically package processed text or image outputs into clean, downloadable `.zip` files.

## 🛠️ The Edge Tech Stack

Because this app uses zero server space, it leverages heavy-hitting client-side JavaScript engines pulled directly through CDN network scripts:

*   **`pdf-lib` & `PDF.js`** — Handles local binary PDF reading, rendering pages to a hidden canvas, and document generation.
*   **`Tesseract.js`** — Runs Optical Character Recognition (OCR) locally using the computer's processing loops.
*   **`SheetJS` (`xlsx`) & `Mammoth`** — Decodes and parses spreadsheets and Word documents at a binary level inside the browser.
*   **`JSZip`** — Packages processed outputs into clean, local downloadable `.zip` files.

---

## 👨‍💻 Project Origin & Learning Journey

I am a **1st-year AI & Data Science student**. Coming into this project, my programming foundation was limited to **basic Python logic**. I had no experience with advanced frontend frameworks or asynchronous JavaScript, but I wanted to understand how browser-side data processing and "edge computing" worked in the real world.

To bridge my knowledge gaps and learn rapidly, I treated AI models as **pair-programming partners**. I used **DeepSeek** for rapid structural scaffolding, and **Claude Sonnet 5 Max** for deep runtime debugging. 

**My role as the developer:**
I designed the architecture, evaluated the UI/UX, wired the step-by-step processing pipeline, and made the technical decisions on which CDN libraries to use. When the app hit critical walls, I debugged fatal syntax issues, resolved duplicate variable declarations (`let`/`const` collisions), fixed asynchronous timing blocks, and implemented lazy-loading logic so heavy scripts load on-demand without freezing the user interface.

Through this project, I learned how to read complex event listeners, manage browser memory (like wiping canvas objects clear after processing), and handle network errors—directly mapping these structural behaviors back to the core programming fundamentals I am learning in Python.

## 🧠 What I Learned

- **Asynchronous JavaScript:** Managing timing blocks and lazy-loading heavy external scripts.
- **Memory Management:** Preventing browser crashes by clearing canvas objects after processing.
- **Edge Computing:** Understanding how to handle binary data and complex file parsing without a backend.
- **Debugging:** Reading and fixing complex runtime errors in a single-file architecture.

## 🔮 Future Improvements

- [ ] **Refactor Architecture:** Split the single-file architecture into modular ES6 modules for better maintainability.
- [ ] **Web Workers:** Move heavy OCR and PDF processing to Web Workers to keep the main UI thread perfectly smooth.
- [ ] **UI/UX:** Add drag-and-drop file uploads and a dark/light mode toggle.
- [ ] **Testing:** Implement unit tests for the document parsing logic.

## 💻 How to Run Locally

Since this is a fully client-side app, running it locally is incredibly simple:

1. Clone the repository:
   ```bash
   git clone https://github.com/faherazam/pdfforge.git
