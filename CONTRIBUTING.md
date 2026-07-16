# Contributing to PDFCraft

Thank you for showing interest in contributing to **PDFCraft**! By participating, you help build a faster, more secure, and accessible set of PDF tools that run entirely in the user's browser.

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing to keep our community safe and welcoming.

---

## 🚀 How Can I Contribute?

### 🐛 Reporting Bugs
* Use GitHub Issues to search for existing bugs before reporting.
* State the specific operating system, browser, and document characteristics that caused the issue.
* Provide clean console logs or error states, making sure to redact any personal information or confidential content from your test documents.

### 💡 Requesting Features
* Open a feature request issue describing the specific PDF action or document conversion tool you would like to see implemented.
* Ensure your suggestion aligns with our core **100% Client-Side Privacy Policy** (the feature must run entirely inside the user's browser sandbox without server dependencies).

### 🛠️ Submitting Pull Requests (PRs)
1. Fork the repository and create your branch from `main`:
   ```bash
   git checkout -b feature/cool-new-tool
   ```
2. Run `npm install` to ensure your dependencies are synchronized.
3. Make your modifications, adhering to our coding standards.
4. Run the linter to verify syntax correctness:
   ```bash
   npm run lint
   ```
5. Build the application locally to ensure there are no compilation or bundling issues:
   ```bash
   npm run build
   ```
6. Commit your changes with descriptive commit messages following the Conventional Commits specifications (e.g., `feat: add PDF resize tool`, `fix: correct split range validation`).
7. Open a Pull Request targeting the `main` branch.

---

## 🎨 Coding Guidelines

To maintain visual precision and technical performance:
* **TypeScript & Type Safety:** Write strongly-typed code. Avoid using `any` types; prefer strict interfaces and standard `enum` types.
* **Component Modularity:** Avoid monolithic files. Extract logical components, static constants, helper functions, and types into separate modular files under `/src/components/`, `/src/data/`, or `/src/utils/`.
* **Tailwind CSS Styling:** Use Tailwind classes exclusively. Adhere to fluid designs using spacing rhythm and desktop-first responsive design principles.
* **Privacy-First Operations:** Never send files to external API backends. File processing must rely exclusively on client-side WebAssembly, workers, or canvas engines.
