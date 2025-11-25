# MCRP 8-10B.11 Antenna Handbook (English)

This folder contains a Markdown reconstruction of the USMC **MCRP 8-10B.11 Antenna Handbook**. The source material comes from `MCRP-8-10B.11.pdf` in the repository root. Each Markdown file mirrors a section of the printed handbook to make the content easier to search, translate, and reflow.

## Available sections
- `foreword.md` — context and key themes for the handbook introduction.
- `chapter-1.md` — antenna fundamentals: electromagnetic waves, polarization, patterns, feed lines, and safety.

## Images
The PDF is a scanned source. To extract figures for Markdown, run an OCR-capable tool such as `ocrmypdf` or `pdftoppm` on a machine with those utilities available. Save exported images to an `images/` subdirectory and embed them with standard Markdown syntax (e.g., `![Figure 1-1](images/figure-1-1.png)`).

## Contributing
When adding new sections, keep headings aligned with the printed handbook numbering and cite the PDF page or figure being transcribed. If you extract images, prefer lossless PNGs sized for easy reading in both PDF and HTML outputs.
