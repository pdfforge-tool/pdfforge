# ⚡ PDFForge — Client-Side PDF & Office Toolkit

A 100% serverless, client-side web application designed to process PDFs, perform OCR, and convert office documents instantly. Everything runs locally inside the user's browser using their device's hardware—meaning no backend servers, zero hosting costs, and total data privacy.

## 🚀 Live Demo
[👉 Open PDFForge Live App](https://pdfforge-tool.github.io/pdfforge/)

---

## 👨‍💻 Project Origin & Honest Breakdown

I am a **1st-year AI & Data Science student**. Coming into this project, my programming foundation was limited to **basic Python logic**. I didn't know advanced frontend frameworks or deep asynchronous JavaScript, but I wanted to understand how browser-side data processing and "edge computing" worked in the real world.

Instead of hiding it, I am proud to showcase that **this application was built using a dual-AI collaborative workflow**. I acted as the systems architect, layout evaluator, and logical debugger, using the strengths of two different AI models to bridge my programming knowledge gaps and bypass typical software boundaries:

### 🤖 The AI Dual-Orchestration Strategy:
1. **DeepSeek (The System Builder):** I utilized DeepSeek to quickly generate the multi-step HTML5 layout framework, wire up the step-by-step sequential processing pipeline (Steps 1 to 5), and connect the massive array of online CDN library links.
2. **Claude Sonnet 5(The Code Mechanic):** DeepSeek was incredibly efficient at building the initial layout but failed heavily when tracking down complex runtime bugs. When the app hit a wall, I turned to Claude 5 Sonnet to parse my single-file architecture. Claude successfully hunted down fatal syntax issues, resolved duplicate variable declarations (`let`/`const` collisions), fixed asynchronous timing blocks, and implemented lazy-loading logic so heavy scripts load on-demand without freezing the user interface.

Through this project, I learned how to read complex event listeners, manage browser memory (like wiping canvas objects clear after processing), and handle network errors—directly mapping these structural behaviors back to the core programming fundamentals I am learning in Python.

---

## 🛠️ The Edge Tech Stack (Libraries Used via CDN)

Because this app uses zero server space, it leverages heavy-hitting client-side JavaScript engines pulled directly through network scripts:
* **`pdf-lib` & `PDF.js`** — Handles local binary PDF reading, rendering pages to a hidden canvas, and document generation.
* **`Tesseract.js`** — Runs Optical Character Recognition (OCR) locally using the computer's local processing loops.
* **`SheetJS` (`xlsx`) & `Mammoth`** — Decodes and parses spreadsheets and Word documents at a binary level inside the browser.
* **`JSZip`** — Automatically packages processed text or image outputs into clean, local downloadable `.zip` files.
