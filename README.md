# saosith.github.io

This repository hosts my professional website (GitHub Pages) and a curated portfolio of analog IC designs, technical notes, and measurement results.

## About
I am an analog/mixed-signal IC design engineer focused on low-noise front-ends, power-efficient biasing, and robust measurement methodology. This site presents reproducible project writeups, schematics, simulation and measured results, and reference material for collaboration and review.

## Highlights
- Specialty: low-noise amplifiers, bandgap/reference circuits, ADC front-ends
- Typical deliverables: block diagrams, Cadence schematic snapshots, BOM, testbenches, measurement setups, and final plots
- Emphasis on repeatable measurements, units, tolerances, and test conditions

## Repository structure
- / (root) — website source (HTML, Markdown, CSS)
- assets/ — images, schematic PDFs, measurement plots
- projects/ — one folder per project with docs, BOM, results
- notes/ — concise technical notes, derivations, scripts
- resume.pdf — up-to-date CV
- README.md — this file

## How I document projects (use this template)
- Title — one line
- Summary — 1–2 sentences: purpose and application
- Key specs — bullets with units (e.g., input‑referred noise: 3.5 nV/√Hz)
- Block diagram / schematic — embedded image or PDF
- Method — test setup, instruments, fixture, and conditions (temperature, supply, lot)
- Results — figures/tables with captions, brief analysis, and pass/fail vs spec
- Limitations and next steps
- License / attribution

Example (short)
- Project: Low-Noise OTA
- Specs: gain 110 dB, GBW 25 MHz, input noise 3.5 nV/√Hz, VDD 1.2 V
- Results: see /projects/ota/results/*.png

## Updating & publishing
- Edit Markdown/HTML and push to this repo. GitHub Pages will publish per repo Pages settings.
- For local preview, serve the site root (e.g., python -m http.server) or use your static site generator workflow if applicable.

## Licensing & IP
- Only publish non‑proprietary work. Respect NDAs and foundry PDK restrictions.
- Choose and include a license (recommended: CC BY 4.0 for content; MIT for code). Add LICENSE file.

## Contact
- GitHub: https://github.com/saosith
- Email: saosithisak@gmail.com
- LinkedIn: https://www.linkedin.com/in/saoaphisithsithisack/
