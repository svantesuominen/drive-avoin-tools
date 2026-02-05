# Avoin.Tools - Google Docs Brand Styler

A Google Apps Script designed to automatically apply the **Avoin.Systems** brand identity to Google Documents.

## Features

- **Automated Branding**: Sets Titillium Web for headings and Assistant for body text.
- **Brand Colors**: Applies the official Burgundy (`#5A1537`) to text and Purple (`#B369F3`) to links.
- **Selection Support**: Choose to format the entire document or just highlighted text.
- **Professional Layout**: Optimized spacing for a modern, "clinging" heading-to-text hierarchy.
- **Color Palette Priming**: Automatically injects brand colors into the document's "Recent Colors" history for easy manual use.

## Installation

1. Open your Google Doc.
2. Go to **Extensions > Apps Script**.
3. Create a new file named `avoin-styles.gs`.
4. Copy the contents of `avoin-styles.gs` from this repository into the editor.
5. Save the project and refresh your Google Doc.
6. A new menu **"Avoin.Tools"** will appear!

## Usage

### 1. First-Time Setup
* When you run the script for the first time, Google will ask for **Authorization**.
* Click **Review Permissions**, select your account, and then click **Advanced > Go to [Your Project Name] (unsafe)**. This is a standard Google security warning for custom scripts.
* Click **Allow**.

### 2. Applying Styles
* **Entire Document**: Simply click **Avoin.Tools > Apply Avoin.Styles! ✨**. The script will automatically format every heading, paragraph, and list in the document.
* **Partial Selection**: Highlight a specific section of text first, then run the command. Only the selected area will be updated.

### 3. Using the Brand Palette
* Each time you run the script, it "primes" the document with your brand colors.
* Open the standard Google Docs **Text Color** or **Highlight Color** picker.
* Look at the **"Recent"** row—you will find the official Avoin burgundy, lavender, orange, coral, etc., ready for manual use!

---
*Created by Svante Suominen on Runeberg Day, February 5th, 2026.*
