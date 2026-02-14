# Privacy Policy for PowerInput

**Effective Date:** February 2026

Welcome to PowerInput! We built this browser extension with a strict "Privacy-First" philosophy. This Privacy Policy explains how we handle your data when you use the PowerInput extension. 

The short version is: **We do not collect, store, or sell your personal data. Your API keys and text content never touch our servers.**

---

## 1. Information We Access and How We Use It

To provide its core functionality (inline translation, rewriting, and styling), PowerInput needs to interact with the text in your browser. Here is exactly what the extension accesses and why:

### A. Website Content & Personal Communications
* **What it is:** The text you select or type in input fields, textareas, and rich-text editors (such as emails, social media posts, or chat messages) across the web.
* **How we use it:** The extension reads this content **only** when you actively trigger a PowerInput keyboard shortcut or context menu action. The text is then processed either entirely locally (for basic styling) or sent directly to the third-party AI provider you configured (e.g., OpenAI, DeepL) to perform the requested transformation (translation, rewrite, etc.).
* **Data Storage:** We **do not** store, log, or transmit this content to any developer-owned servers. 

### B. Authentication Information (API Keys)
* **What it is:** The third-party API keys (e.g., OpenAI API key) you provide in the extension's settings to power the AI features.
* **How we use it:** Your API keys are stored 100% locally on your machine using the browser's native, secure local storage (`chrome.storage.local`). They are used exclusively to authenticate your requests directly with your chosen AI provider.
* **Data Storage:** We have **zero access** to your API keys. They are never transmitted to our servers or any unauthorized third parties.

### C. User Activity (Keystrokes)
* **What it is:** The extension listens for specific keyboard events.
* **How we use it:** This is strictly used to detect when you press your custom shortcut combinations (e.g., `Ctrl+Alt+1`). The extension does not perform general "keylogging" and does not record your typing history.

## 2. Third-Party Services

PowerInput acts as a secure bridge between your browser and the AI providers you choose to connect. 

When you use AI-powered presets (like Translation or AI Rewriting), your selected text is sent directly from your browser to the API endpoint you configured (e.g., OpenAI API). 

Please note that the data you process through these third-party providers is subject to their own respective privacy policies:
* [OpenAI Privacy Policy](https://openai.com/policies/privacy-policy)
* [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy)
* *(Refer to the privacy policy of any other custom provider you configure).*

## 3. Data Retention

Because PowerInput does not use centralized servers to process your inputs or store your settings, we do not retain any of your data. All configurations, custom presets, and API keys remain on your device and can be deleted entirely at any time by uninstalling the extension or clearing the extension's local data.

## 4. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our extension or for other operational, legal, or regulatory reasons. We will notify users of any significant changes by updating the "Effective Date" at the top of this policy.

## 5. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or how PowerInput handles your data, please contact us at:
**contact@subtiltee.com**
