# BabyAGI Technical History

## Overview
A static single-page website documenting the technical history of BabyAGI — nine versions of an autonomous agent project traced through source code analysis.

## Project Architecture
- **Type**: Static HTML site (no build system, no backend)
- **Entry point**: `index.html` — single self-contained HTML file with inline CSS
- **Server**: `serve.js` — minimal Node.js static file server for development (port 5000)
- **Deployment**: Static deployment serving the root directory

## How to Run
The project runs via the "Start application" workflow which starts `node serve.js` on port 5000.
