# MindForge AI - Academic Concept & Mind Map Synthesizer

**MindForge AI** is a lightweight, client-side web application designed to synthesize complex academic texts, articles, and lecture notes into interactive Mind Maps and Concept Maps. Powered by Google's Gemini API (with a seamless local NLP fallback), MindForge AI helps users visualize connections, review key takeaways, and practice active recall through generated study flashcards.

---

## ✨ Features

- **Dual Visualization Modes:**
  - **Mind Map:** Radial tree layout focusing on central topics, subtopics, and details.
  - **Concept Map:** Directed network layout displaying semantic relationships between nodes.
- **AI-Powered Synthesis:** Connects to the **Gemini 3 Flash** API (`gemini-3-flash-preview`) to extract structured concepts, descriptions, and takeaways.
- **Offline / Local Fallback:** Includes a built-in heuristic NLP parser to generate structured maps instantly without requiring an API key.
- **Interactive Force-Directed Canvas:**
  - Dynamic physics engine for smooth node layout.
  - Full pan, zoom, drag-and-drop, and node selection capabilities.
  - Live keyword search for fast navigation across large diagrams.
- **Node Inspector Drawer:** Click any node to open a side panel displaying detailed summaries, bullet points, and connected topics.
- **Study Hub (Active Recall):** Automatically transforms generated maps into flip-card flashcards for self-testing.
- **Multiple Export Options:**
  - High-resolution **PNG** image.
  - Scalable Vector Graphics (**SVG**).
  - Print / **PDF** summary notes.
- **Presets & Customization:**
  - Built-in academic presets (Photosynthesis, Quantum Physics, WWI History, Deep Learning).
  - Adjustable depth/granularity slider (Summary, Balanced, Detailed).
  - Dark and Light mode support.

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript (ES6+):** Zero external framework dependencies for fast loading.
- **Tailwind CSS:** Modern utility-first styling with dark mode support.
- **Lucide Icons:** Clean vector icons for UI elements.
- **SVG Engine:** Custom vector renderer for node graphs, edge arrows, and physics calculations.

---

## 🚀 Getting Started

### Prerequisites

No local build environment or package manager (Node.js/npm) is required! MindForge AI runs directly in any modern web browser.

### Running Locally

1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-username/mindforge-ai.git
   ```
2. Open the file directly in your preferred web browser:
   ```bash
   # Example for macOS
   open ai_mind_map_concept_map_generator.html

   # Or simply double-click the HTML file in your browser/file explorer.
   ```

---

## 🔑 Gemini API Setup (Optional)

1. Obtain a Gemini API key from [Google AI Studio](https://aistudio.google.com/).
2. Open MindForge AI in your browser.
3. Click the **Settings (⚙️)** icon in the top header bar.
4. Paste your Gemini API key into the input field and click **Save Key**.
5. Your key is stored securely in your browser's `localStorage`.

> **Note:** If no key is provided, MindForge AI automatically falls back to its local rule-based extractor so you can still generate maps offline!

---

## 📁 File Structure

```text
├── ai_mind_map_concept_map_generator.html   # Main single-file application containing HTML, CSS, and JS
└── README.md                                # Project documentation
```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.