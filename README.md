# UnHoneyed - A Transparent, Community-Driven Alternative to Honey

UnHoneyed is an open-source browser extension designed to democratize the process of applying discount codes and supporting content creators. Unlike traditional services, UnHoneyed focuses on transparency, community contributions, and empowering users to make informed choices about affiliate and promo code usage.

---

## Features

### **Browser Extension**
- **Code Application:** Automatically detects checkout pages and applies user-selected affiliate or promo codes.
- **Community Contribution:** Users can submit new codes directly from the extension.
- **Customizable Preferences:** Options to prioritize:
  - Supporting specific content creators.
  - Applying the highest available discount.
- **Transparency:** Displays all applied codes and their purposes (e.g., supporting creators, maximizing discounts).

---

## Feature Table

| Feature                          | Status     |
|----------------------------------|------------|
| Browser extension for applying codes | ❌ Pending |
| User submission of promo codes   | ❌ Pending |
| Customizable user preferences    | ❌ Pending |

---

## Architecture

### **Browser Extension**
- **Built With:** JavaScript, HTML, and CSS using the WebExtension API.
- **Key Components:**
  - **Content Script:** Injected into shopping sites to detect checkout pages and apply codes.
  - **Popup Interface:** User-facing settings and submission form.
  - **Background Worker:** Handles extension-specific logic and user preferences.
- **Compatibility:** Chrome, Firefox, Edge, and other WebExtension-compatible browsers.

---

## Installation

### **Browser Extension**
1. Clone the repository:
   ```bash
   git clone https://github.com/Dont-Copy-That-Floppy/UnHoneyed.git
   cd UnHoneyed/browser-extension
   ```
2. Build the extension (if required):
   ```bash
   npm install
   npm run build
   ```
3. Load the extension:
   - For Chrome:
     - Navigate to `chrome://extensions`.
     - Enable "Developer mode".
     - Click "Load unpacked" and select the `dist/` folder.
   - For Firefox:
     - Navigate to `about:debugging` > "This Firefox" > "Load Temporary Add-on".
     - Select any file within the `dist/` folder.

---

## Usage

1. Install the browser extension and configure your preferences.
2. Navigate to a shopping site.
3. At checkout, the extension will:
   - Automatically apply your selected creator's affiliate/promo code.
   - Fetch discount codes from the community database.
4. To contribute codes:
   - Open the extension popup.
   - Enter the code, associated website, and optional creator details.
   - Submit it for inclusion in the database.

---

## Contributing

We welcome contributions from the community! Here’s how you can help:

1. **Fork the repository** and create a new branch for your feature or bugfix.
2. **Ensure code quality** by running tests and adhering to our linting guidelines.
3. **Submit a pull request** with a detailed description of your changes.

---

## License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

---

## Roadmap

### Short-Term Goals:
- Finalize the browser extension functionality.
- Enable robust validation for submitted codes.

### Long-Term Goals:
- Integrate machine learning to predict the best-performing codes.
- Build optional features for advanced user preferences.

---

## Contact

For questions or suggestions, feel free to open an issue or reach out to @me.
