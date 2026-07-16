# PDFCraft

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Security: 100% Client-Side](https://img.shields.io/badge/Security-100%25%20Client--Side-green.svg)](SECURITY.md)

**PDFCraft** is a comprehensive, ultra-secure, and lightning-fast web application offering a suite of professional-grade PDF manipulation tools. Built entirely with React, TypeScript, and modern browser APIs, PDFCraft executes all file processing directly inside the user's browser. Your files never leave your computer, ensuring complete data privacy and 100% secure offline-first operations.

---

## 🌟 Key Features

### 🔧 PDF Modification & Assembly
* **Merge PDF:** Combine multiple PDF documents into a single file in seconds.
* **Split PDF:** Extract specific pages or split a PDF into separate files.
* **Reorder & Organize:** Drag and drop pages to visually rearrange or delete pages from any PDF document.
* **Rotate PDF:** Rotate individual or all pages of your documents.
* **Crop & Adjust:** Set custom crop margins on pages dynamically.

### 🔒 Security & Optimization
* **Protect PDF:** Add military-grade AES encryption and set password permissions.
* **Unlock PDF:** Remove password protections from authorized files.
* **Flatten PDF:** Merge form fields, annotations, and visual layers into a flat, non-editable document.
* **Redact PDF:** Mask sensitive details permanently in documents.
* **Add Watermark:** Add custom text or image stamps across PDF pages with custom opacity and angles.
* **Sign PDF:** Create, draw, or upload electronic signatures to place on documents.

### 🔄 Conversions
* **JPG / Images to PDF:** Convert multiple images into a clean PDF document.
* **PDF to JPG:** Export high-quality raster image pages from any PDF.
* **Word / Excel / Markdown to PDF:** Seamless client-side converters that convert formatted documents into PDFs.
* **OCR PDF:** Apply optical character recognition directly in the browser using Tesseract.js.

---

## 🔒 Security & Privacy by Design

Unlike traditional online PDF converters, **PDFCraft does not use server-side file processors**. 
* **Zero Uploads:** No databases or file storage APIs are integrated for document operations.
* **Private Runtime:** File parsers (e.g., `pdf-lib`, `pdfjs-dist`) execute entirely inside the browser's sandbox/Web Worker context.
* **Sensitive Data Safe:** Safe for corporate, financial, and highly confidential medical documents.

For more details, see our [Security Policy](SECURITY.md).

---

## 🚀 Tech Stack

* **Framework:** React 18+ & Vite
* **Language:** TypeScript
* **Styling:** Tailwind CSS (Modern `@import` layout structure)
* **Core PDF Libraries:** `pdf-lib`, `pdfjs-dist` (Mozilla PDF.js)
* **OCR Engine:** `tesseract.js` (WebAssembly-powered local OCR)
* **Animations:** `motion/react`

---

## 🛠️ Getting Started

### Prerequisites
* **Node.js** (v18 or higher)
* **npm** or **bun** / **yarn**

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pdfcraft.git
   cd pdfcraft
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your web browser.

### Building for Production
To bundle the frontend application with optimized static assets:
```bash
npm run build
```
This produces optimized static outputs in the `dist/` directory, ready to be served by any static file hosting service.

---

## 🤝 Contributing

We welcome community contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) and adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
