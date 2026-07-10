# interactive-flow v2026 - web-based node editor 2026

> **Interactive-flow is a browser-based node editor and route simulator for designing decision trees, tracing branches, and exporting polished walkthroughs as one standalone HTML file.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/dylanscott1998/interactive-flow-node-editor?style=flat-square)](https://github.com/dylanscott1998/interactive-flow-node-editor)

---

<p align="center">
  <a href="https://dylanscott1998.github.io/interactive-flow-node-editor/">
    <img src="https://img.shields.io/badge/Download-interactive-flow%20Latest-brightgreen?style=for-the-badge" alt="Download interactive-flow">
  </a>
</p>

> **[Direct Download - interactive-flow v2026](https://dylanscott1998.github.io/interactive-flow-node-editor/)**

---

[Download Latest Build](https://dylanscott1998.github.io/interactive-flow-node-editor/)

---

## Overview

interactive-flow is meant for turning branching concepts into readable, interactive walkthroughs. It combines node-based editing, path simulation, and diagram planning inside a single web workspace, so you can map decisions, outcomes, and exceptions without jumping between tools.

It fits well for product demos, planning workshops, sales presentations, and other explanation-heavy use cases where a plain linear deck is not enough. Because it emphasizes structured layout and exportable output, you can review the content in a browser or package it as a standalone HTML file for sharing and offline presentation.

---

## Features

- Web-based all-in-one editor for building interactive flow diagrams
- Node editor workflow for organizing decision paths and branching logic
- Path simulator for exploring outcomes across different routes
- 3-column studio layout for clearer editing and navigation
- Structured lanes for handling edge cases and alternate branches
- Export to a single standalone HTML file
- Fullscreen pitch deck support for presentation-style walkthroughs
- HTML-based output that is easy to share and open without extra packaging

---

## Installation

Clone the repository, then open it in a browser-capable environment or serve the HTML files from your preferred web server.

- Clone the repo:
  - `git clone https://github.com/dylanscott1998/interactive-flow-node-editor.git
- Move into the project folder:
  - `cd interactive-flow`
- Open the main HTML entry point in a browser, or serve it locally with any static file server.

If you export a standalone HTML build, that file can be opened or shared directly in a browser.

---

## Usage

1. Open the editor in your browser.
2. Create nodes for each decision point, step, or branch.
3. Connect paths to show how users, customers, or scenarios move through the flow.
4. Use structured lanes to separate edge cases from the main route.
5. Preview the simulation to check how the walkthrough behaves.
6. Export the result as a single HTML file when you are ready to share or present.

For presentation use, open the exported file in fullscreen mode to turn the flow into a pitch-deck-style walkthrough.

---

## Configuration

Configuration lives either in the project source or in the exported HTML, depending on how you deploy it. When working from source, keep layout choices, node definitions, and presentation settings inside the repository files used by the editor.

Example project-level settings:

    {
      "layout": "3-column studio",
      "exportFormat": "standalone-html",
      "presentationMode": "fullscreen"
    }

---

## Requirements

- A modern web browser
- HTML support for running the editor and exported output
- Enough local storage or disk space to save exported HTML files and project assets
- A static hosting setup if you want to serve the project or exported builds from a web server

---

## FAQ

**How do I get updates?**  
Watch the repository for new builds and refresh your local copy when a newer version is published.

**Can I change the editor layout or flow structure?**  
Yes. The project is built around a structured studio layout, so you can arrange nodes, branches, and special-case lanes to suit your workflow.

**Where are settings stored?**  
That depends on how you use the project. Settings may live in source files, browser state, or the exported HTML, depending on your deployment approach.

**What if the exported file does not display correctly?**  
Open the standalone HTML in a modern browser and make sure the export finished successfully. If needed, generate the file again and confirm that every required asset was included.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
