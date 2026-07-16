# Changelog

All notable changes to the **PDFCraft** project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.1.0] - 2026-07-16

### Added
- Integrated **Adsterra Ad Units** supporting optimal desktop (728x90) and mobile (320x50, 300x250) banners seamlessly placed after content sections.
- Embedded a customized local popunder advertising script to optimize monetization without breaking site navigation.
- Created `google7e2e2781208f53e0.html` validation file in `/public` for verified search engines indexation.
- Created comprehensive repository documentation files including `README.md`, `LICENSE`, `CHANGELOG.md`, `CONTRIBUTING.md`, `SECURITY.md`, and `CODE_OF_CONDUCT.md`.

### Changed
- Dynamically synchronized the visual sitemap with the complete `TOOLS` array to support indexation of all 20+ specialized browser-based PDF utilities.
- Cleaned up footer layouts by optimizing visual elements and text, replacing old brand logos with the high-resolution transparent vector format.

---

## [1.0.0] - 2026-07-14

### Added
- Initial deployment of **PDFCraft** client-side workspace.
- Full suite of 20+ browser-based offline-safe PDF manipulation tools including:
  - Merge, Split, Compress, Rotate, Sign, Flatten, Reorder, Delete Pages, Protect, and Unlock.
  - Formatted document engines (Word to PDF, Excel to PDF, Markdown to PDF, Images to PDF).
  - Tesseract.js client-side OCR engine.
- High-fidelity transparent application icon and dark/light responsive interface.
- Complete XML dynamic Sitemap implementation for search indexing.
- Deep-linking and sharing engine using window query strings (`?tool=`, `?page=`) mapping directly to specific tools.
