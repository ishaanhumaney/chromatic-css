# Chromatic CSS

A lightweight, high-performance UI layout designed to explore structured color harmonies and instantly test dark and light text contrast profiles. This entire application operates completely independent of JavaScript frameworks, runtimes, or client-side scripting engines.

## Overview & Value Proposition

Modern web development leans heavily on JavaScript processing pipelines for trivial interface mutations, often introducing unnecessary performance degradation and asset bundle bloating. Chromatic CSS addresses that problem by implementing advanced UI state toggling architectures exclusively using semantic HTML5 markup and the declarative power of modern CSS.

By utilizing hidden radio button controls tied directly to layout element siblings via the general sibling combinator (`~`), the application provides instantaneous theme switching, live hexadecimal/RGB composition inspections, and functional contrast accessibility verification checks at zero execution runtime cost.

## Key Features

* **Zero JavaScript Architecture:** Zero dependencies, zero compilation frameworks, and zero bundle sizes. State persistence and layout logic are fully compiled by the browser layout engine.
* **Dual-Contrast Preview Fields:** Simultaneously exposes light text readability targets alongside dark slate variants to guarantee high-contrast structural designs.
* **Component Metadata Cards:** Dynamic display fields sync up the hex value and RGB composition mappings for active hex swatches instantly upon selection.
* **Responsively Adaptive:** Grid layouts dynamically scale configurations from desktop layouts down to single-column mobile viewports without design breakdown.
* **Zero-Overlap Fixed Signatures:** Employs explicit margin architectures to prevent layout elements from obscuring footer badge links on short viewports.

## Tech Stack Breakdown

* **HTML5 Markup:** Leverages semantic elements (`<header>`, `<main>`, `<footer>`), radio buttons for input storage tracking, and explicit structural label relationships.
* **Modern CSS3 Layouts:** Built using CSS Grid for auto-fitting swatch alignment, smooth transform scale matrices, and sophisticated viewport breakpoint processing.
* **CSS General Sibling Combinators:** Powers the functional component engines by binding elements like `#color-nordic:checked ~ .preview-zone` to handle state transitions dynamically.

## Prerequisites & Web-Based Quick Start

Because this system runs entirely on vanilla client-side browser files, you don't need compilation tools, runtimes, or package downloads.

### Launching in Your Browser
1. Click the **`.`** (dot) key on your keyboard while viewing this repository to launch the web-based GitHub editor workspace.
2. Select `index.html`. Right-click and choose to view it with your preferred local browser extension previewer, or use **GitHub Codespaces** to launch a live-reload web server instance automatically.

### Simple Local Execution
If you prefer running a copy locally on your machine, clone or download the file artifacts and spin up a lightweight, zero-configuration local server setup:
```bash
# Serve the current directory layout directly using Python's built-in platform
python3 -m http.server 8000

Open your internet browser and navigate directly to http://localhost:8000.
```
## Project Structure
```bash
├── .gitignore            # Excludes local IDE caches and system junk
├── LICENSE               # Open-source MIT terms coverage
├── README.md             # Documentation asset
├── index.html            # Semantic elements and input state elements
└── style.css             # Grid systems, layouts, and combinator states
```

## Roadmap
[ ] WCAG Contrast Validation Badges: Integrate native calculated luminosity alerts using CSS color contrast evaluation standards directly inside validation cards.

[ ] Clipboard Copy Triggers: Implement simple, non-obtrusive fallback actions to capture hex text strings smoothly upon clicking.

[ ] Custom CSS Variable Injection: Re-engineer theme layers to parse real-time global target overrides via native root element tokens.
