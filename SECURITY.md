# Security Policy

At **PDFCraft**, security and privacy are not just features; they are the architectural foundation of our application. All document manipulations, file encodings, signatures, and OCR processes occur **entirely inside the client's local browser environment**. No user documents are ever uploaded, processed, or cached on remote cloud environments.

---

## 🛡️ Supported Versions

We actively maintain and apply security patches to the following release branches:

| Version | Supported          |
| ------- | ------------------ |
| v1.x    | :white_check_mark: |
| < v1.0  | :x:                |

---

## 🔬 Local Runtime Architecture

* **No Server Uploads:** PDFCraft is compiled as a static client-side single page application (SPA). There are no cloud-hosted backend APIs handling documents.
* **Wasm & Sandboxing:** Heavy processes like OCR (Tesseract.js) or compilation are executed inside browser WebAssembly execution layers, heavily sandboxed by standard browser memory safety barriers.
* **State Persistence:** Document contents exist only in the volatile runtime memory (`RAM`) of your current tab and are immediately cleared when the browser window or tab is closed.

---

## 🔓 Reporting a Vulnerability

If you discover a security vulnerability in this project (such as potential script injection via malformed PDF attachments, localized buffer overflow risks in parsing engines, or analytics leakages), please report it to us immediately.

### How to Report
* Do not disclose the vulnerability in public GitHub Issues.
* Email a detailed description of the vulnerability to the project administrator at **elqosby@gmail.com**.
* Include clear proof-of-concept scripts, steps, or sample files to reproduce the behavior.
* We will verify the issue and respond with an action plan within **48 hours**.

We appreciate your assistance in keeping PDFCraft a secure, private, and trusted workspace for everyone!
