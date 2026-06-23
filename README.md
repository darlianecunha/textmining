# PDFWords — Co-occurrence network for VOSviewer

**A bibliometric and text-mining tool that turns PDFs into word co-occurrence networks compatible with VOSviewer.**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20708534.svg)](https://doi.org/10.5281/zenodo.20708534)

🔗 **Live demo:** [text-umber-delta.vercel.app](https://text-umber-delta.vercel.app)

---

## About the project

PDFWords lets you load one or more PDF files, extract the text locally (with nothing sent to a server), process the words and generate a JSON file in the format accepted by [VOSviewer Online](https://app.vosviewer.com). With that file you can visualise word co-occurrence maps in seconds.

It is especially useful for researchers carrying out bibliometric analyses, systematic literature reviews and text-mining studies.

For a directed, controlled-vocabulary approach (you define the terms and the app counts them), see the companion tool [PDFTerms](../keywordsprojeto2).

---

## Features

- Upload of multiple PDFs by drag & drop or selection
- 100% local text extraction (no data sent anywhere)
- Generation of a word co-occurrence network in the VOSviewer JSON format
- Configurable parameters:
  - Minimum occurrence frequency
  - Minimum co-occurrence between terms
  - Maximum number of words in the network
  - Minimum character length per word
- Automatic stopwords in Portuguese and English
- Custom stopwords via the interface
- Export of the VOSviewer JSON
- Export of frequencies as CSV
- Direct opening in VOSviewer Online
- Responsive and accessible interface

---

## How to use

1. Go to [text-umber-delta.vercel.app](https://text-umber-delta.vercel.app)
2. Drag your PDFs into the upload area (or click to select)
3. Adjust the network parameters as needed
4. Click **Generate co-occurrence network**
5. Download the generated JSON
6. Open [app.vosviewer.com](https://app.vosviewer.com), click **Open** → **VOSviewer JSON file** and load the file

> **Note:** scanned PDFs (image only) need OCR before processing.

---

## Technologies

| Technology | Use |
|---|---|
| HTML / CSS / JavaScript | Interface and application logic |
| [PDF.js](https://mozilla.github.io/pdf.js/) (v3.11) | Text extraction from PDFs |
| [VOSviewer](https://www.vosviewer.com/) | Co-occurrence network visualisation |
| [Vercel](https://vercel.com/) | Hosting and continuous deployment |

---

## Privacy

All processing happens in the user's browser. No file or data is sent to external servers.

---

## How to cite

> Cunha, D. R. (2026). PDFWords: bibliometric text-mining for VOSviewer co-occurrence networks (v0.1.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.20708534

---

## Author

**Darliane Ribeiro Cunha, PhD**
Researcher in sustainability governance, environmental analytics and the SDGs
[ORCID: 0000-0003-2548-1237](https://orcid.org/0000-0003-2548-1237)

---

## Licence

This project is free to use for academic and research purposes.
