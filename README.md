# CH381M-simulations

Interactive HTML/CSS/JavaScript simulations for **CH 381M Advanced Analytical Chemistry**.

## Purpose

This repository hosts standalone, browser-based simulations used to support
CH 381M coursework. Each simulation is a self-contained static web page with
no build step or external dependencies.

## Running locally

Clone the repository and open the HTML files directly in a browser, or serve
the directory with any static file server:

```bash
git clone https://github.com/ren-hang/CH381M-simulations.git
cd CH381M-simulations
python3 -m http.server 8000
```

Then visit `http://localhost:8000/` in your browser.

## Deployment

This site is served via **GitHub Pages** directly from the `main` branch
(repository root). No build system (npm, Jekyll, React, etc.) is used -
it is plain static HTML/CSS/JS.

## Simulations

- **Lock-in Detection Simulator** - [`lockin/index.html`](lockin/index.html),
  linked from the landing page at [`index.html`](index.html).
