# Google Cloud Platform (GCP) Icons for Draw.io / Diagrams.net (2025 Update)

**Stop resizing 512px icons manually.** 

This repository contains a ready-to-use, optimized custom library of the **official Google Cloud icons (Sept 2025 update)** for Draw.io (Diagrams.net). 

While Google provides the raw SVG files, importing them directly results in massive images (512x512px) with messy filenames. This set fixes that.

## 🚀 Features

*   **Perfect Size:** All icons are pre-resized to **64x64px**, the standard size for architectural diagrams. No more dragging a VM icon and covering your entire canvas.
*   **Searchable Names:** Filenames have been cleaned (`Compute_Engine.svg` instead of `Compute_Compute_Engine-512-color.svg`) so the Draw.io search bar actually works.
*   **Vector Format:** High-quality SVGs that scale without pixelation.
*   **Up to Date:** Based on the official [Google Cloud Architecture Icons](https://cloud.google.com/icons) release (Sept 2025).

## 📦 How to Use

1.  Download the `*.xml` file from this repository. *(Note: You need to save your library from Draw.io as an XML file first to upload it here, or just upload the folder of SVGs)*.
2.  Open [Draw.io](https://app.diagrams.net/).
3.  Go to **File** -> **Open Library...**
4.  Select the downloaded file.
5.  Enjoy your new panel of fresh and shiny Google Cloud icons!

## 🛠️ How it was built

The raw icons from Google come in a complex nested folder structure with redundant naming. 
I used a Python script (included in this repo as `fix_icons.py`) to:
1.  Flatten the directory structure.
2.  Clean up the filenames (removing `_512`, `_color`, and category duplication).
3.  Inject `width="48px"` and `height="48px"` attributes directly into the XML of every SVG.

## ⚖️ License & Attribution

The icon designs are the property of Google. 
According to the [official page](https://cloud.google.com/icons): *"Google Cloud allows the use of these icons in architectural diagrams, training materials, and documentation."*

This repository is just a repackaging tool to make them usable in Draw.io.

---
*If this saved you time, give the repo a ⭐!*
