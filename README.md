# Cairn: Cybersecurity Research Assistant

**Cairn** is a lightweight, single-file browser application designed for cybersecurity researchers and practitioners. It provides an academic-focused environment to ingest, preview, and perform structured analysis on cybersecurity PDFs using Google’s Gemini API.

---

##  Key Features

* **Local-First Architecture:** Operates entirely within your browser using vanilla JavaScript and HTML. No backend, database, or build tools required.
* **Structured Analysis:** Quickly generate professional-grade outputs such as:
* Cyber Threat Models
* Attack Chains
* CVE Extraction
* Red vs. Blue Team perspectives
* Defender Takeaways / SOC Actions


* **Interactive Chat:** Use the "Ask Chatbot" mode to query specific details from research papers, with strict grounding requirements.
* **Privacy-Focused:** Files are processed in your browser memory. API keys are handled locally and only used for direct communication with the Gemini endpoint.
* **Clean Interface:** A distraction-free, three-column "research notebook" layout with dark-mode optimized aesthetics.

---

##  How to Use

1. **Initialize:** Save the `index.html` file to your computer and open it in any modern web browser.
2. **Upload:** Drag and drop your cybersecurity research PDFs into the **Paper Library** (left sidebar).
3. **Configure:**
* Enter your **Gemini API Key** in the **Workspace** (right panel).
* Click **Test** to ensure connectivity (the status pill will turn green).
* Select your preferred **Gemini model** (e.g., Gemini 1.5 Pro).


4. **Analyze:**
* Select a paper from the list to preview it.
* Choose an analysis type from the dropdown menu (e.g., "Threat Model" or "Cyber Summary").
* Click **Run Analysis**.


5. **Review:** Results appear in the scrollable **Analysis Output** panel, designed to preserve formatting and readability.

---

##  Requirements

* **Modern Browser:** Chrome, Firefox, Edge, or Brave (requires modern JavaScript support).
* **API Key:** A valid Google Gemini API key (obtainable via [Google AI Studio](https://aistudio.google.com/)).
* **Internet Connection:** Required for API requests to the Gemini service.

---

## Security & Privacy Notice

* **Cairn does not save your documents to a server.** All processing happens locally in your browser session.
* **API Key Storage:** Your API key is stored only in the browser's volatile memory for the duration of your current tab session.
* **Disclaimer:** This tool is intended for research purposes. Always verify AI-generated technical claims against the original source documentation.

---

*Built for cybersecurity researchers who value speed, privacy, and structured insights.*
