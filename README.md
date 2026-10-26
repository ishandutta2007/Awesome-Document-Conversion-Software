<div align="center">
  <img src="assets/banner.svg" alt="Awesome Document Conversion Software Banner" width="100%" />
</div>

# 📄 Awesome Document Conversion Software

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-Conversion-Software/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Document-Conversion-Software?style=flat-square&logo=github&color=gold" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-Conversion-Software/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Document-Conversion-Software?style=flat-square&logo=github&color=blue" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-Conversion-Software/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-Conversion-Software/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🚀 **The definitive curated directory of SaaS platforms, self-hosted web utilities, CLI engines, and open-source developer libraries for document conversion, PDF manipulation, and format transformation.**

---

## 📑 Table of Contents

- [🔍 Overview & SEO Highlights](#-overview--seo-highlights)
- [🌐 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [💼 SaaS & Commercial Document Conversion Platforms](#-saas--commercial-document-conversion-platforms)
- [💻 Open-Source Document Conversion Engines & Libraries](#-open-source-document-conversion-engines--libraries)
- [🎯 Document Conversion Architecture & Decision Guide](#-document-conversion-architecture--decision-guide)
- [🤝 How to Contribute](#-how-to-contribute)
- [⭐ Star History](#-star-history)
- [💖 Support & Community](#-support--community)
- [📜 Disclaimer](#-disclaimer)

---

## 🔍 Overview & SEO Highlights

**Awesome Document Conversion Software** tracks the modern ecosystem of document transformation technology. Whether you need to convert proprietary Microsoft Office files (Word `.docx`, Excel `.xlsx`, PowerPoint `.pptx`), assemble or extract Portable Document Format (`.pdf`) files, render Markdown and HTML to print-ready PDF, or build autonomous AI document ingestion pipelines, this repository catalogs both enterprise cloud services and sovereign self-hosted open-source software.

### 🏷️ Key Topics & Format Search Matrix
- **Document Formats**: `PDF`, `DOCX`, `DOC`, `XLSX`, `CSV`, `PPTX`, `ODT`, `ODS`, `ODP`, `HTML`, `Markdown`, `LaTeX`, `EPUB`, `RTF`, `TXT`
- **Use Cases**: PDF to Word conversion, headless Office conversion, client-side WebAssembly document processing, OCR text extraction, batch document transformation, automated PDF generation, LLM document parsing and tokenization.
- **Developer Protocols**: REST API, CLI tools, Python libraries, Node.js packages, Docker microservices, MCP (Model Context Protocol) servers.

---

## 🌐 Sector Overview & Market Dynamics

The global document conversion and management software market is estimated at **$7.4 billion in 2026** (projected to reach **$13.2 billion by 2031** at a compound annual growth rate of **11.8%**), accelerated by enterprise digital transformation, AI/LLM unstructured data ingestion pipelines, and rigorous data residency mandates (GDPR, HIPAA).

The market exhibits a **barbell concentration pattern with moderate mid-tier fragmentation**:
- **Enterprise Core (Concentrated)**: High-end enterprise desktop installations and enterprise-wide licensing remain heavily consolidated around Adobe Systems, with secondary positions held by Nitro and Wondershare.
- **Self-Hosted & API Layer (Highly Fragmented & Open-Source Driven)**: The mid-market, SMB, and developer tiers are widely distributed among high-velocity web utilities (Smallpdf, iLovePDF, CloudConvert) and vibrant open-source self-hosted solutions (LibreOffice headless, Pandoc, Stirling-PDF, BentoPDF, Gotenberg) that allow privacy-conscious engineering teams to avoid recurring cloud subscription fees and data compliance risks.

---

## 💼 SaaS & Commercial Document Conversion Platforms

The table below provides a competitive analysis of category-leading SaaS document conversion solutions, ranked in **descending order by company size** (estimated annual revenue and market valuation).

| 🏢 Product / Service | 📈 Company Scale (Revenue / Valuation) | 💳 Starting Tier Pricing | 🎁 Free Tier / Trial Limits | 🛠️ Core Capabilities & Supported Formats |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Acrobat Export PDF / Pro](https://www.adobe.com/acrobat/online/pdf-to-word.html)** | **~$21.4B Annual Revenue**<br>(~$220B Market Cap · Adobe Inc.) | **$2.99/mo** (Export PDF annual)<br>or **$19.99/mo** (Acrobat Pro) | **7-day free trial** (unrestricted Pro features); web tools permit **2 free conversions per 30-day window** with Adobe ID | Industry-standard fidelity for converting complex PDFs to editable Word (DOCX), Excel (XLSX), PowerPoint (PPTX), and RTF with flawless font and table layout preservation. |
| **[Wondershare PDFelement](https://pdf.wondershare.com/pdf-converter/)** | **~$180M Annual Revenue**<br>(~$1.2B Market Cap · SZSE: 300624) | **$29.99/quarter**<br>or **$79.99/year** perpetual options | **14-day free trial** with watermark; free export mode restricted to **up to 3 pages per conversion** | Desktop and cloud document transformation suite converting PDF to Office, EPUB, and HTML with built-in OCR and batch processing. |
| **[Nitro Cloud](https://www.gonitro.com/)** | **~$65M Annual Revenue**<br>(~$350M Valuation · Potentia Capital) | **$14.99/user/month**<br>(Nitro Pro annual subscription) | **14-day free trial** with full capabilities (capped at **5 document conversions per day** during trial) | Enterprise PDF productivity platform with native Microsoft Office integration, electronic signatures, and batch PDF-to-DOCX/XLSX conversions. |
| **[Soda PDF](https://www.sodapdf.com/)** | **~$60M Division Revenue**<br>(~$120M Group Cap · Claranova SE) | **$6.67/mo**<br>($80/year billed annually) | **7-day free trial**; web utility allows **2 free document conversions per 24 hours** (ad-supported) | Dual desktop and browser suite converting PDF to Word, Excel, PowerPoint, HTML, and TXT with document merging and form editing. |
| **[Smallpdf](https://smallpdf.com/)** | **~$50M ARR**<br>(~$250M Valuation · ~50M MAUs) | **$9.00/mo**<br>($108/year billed annually) | **Free forever plan** with **2 document conversions per day**, standard processing queue, and **15MB file size limit** | Streamlined web and mobile document suite converting PDF to/from DOCX, XLSX, PPTX, and JPG with OCR and PDF compression. |
| **[iLovePDF](https://www.ilovepdf.com/)** | **~$30M ARR**<br>(~$150M Valuation · ~40M MAUs) | **$4.00/mo**<br>($48/year billed annually) | **Free forever plan** allowing **3 conversions per day**, 1 file per batch queue, and **15MB maximum file size** | High-speed browser tools and REST API for PDF to Word, Excel, PowerPoint, JPG, and HTML with optical character recognition. |
| **[CloudConvert](https://cloudconvert.com/)** | **~$15M ARR**<br>(~$70M Valuation · Lunaweb GmbH) | **$9.00 one-time** (500 credits)<br>or **$9.00/mo** (1,000 min) | **Free forever plan** granting **25 conversion minutes per day** and **up to 1GB file size limit** | Universal developer API and web interface supporting 200+ formats (PDF, DOCX, XLSX, EPUB, CAD, vector graphics) with webhooks and cloud storage sync. |
| **[Zamzar](https://www.zamzar.com/)** | **~$8M ARR**<br>(~$40M Valuation · Zamzar Ltd) | **$9.00/mo**<br>(Basic tier, 50 daily jobs, 200MB file cap) | **Free forever tier** with **2 conversions per 24 hours** and **50MB maximum file size limit** | Veteran online conversion platform supporting 1,100+ format pairs across documents, spreadsheets, presentations, ebooks, and archive formats. |
| **[PDF Candy](https://pdfcandy.com/)** | **~$5M ARR**<br>(~$20M Valuation · Icecream Apps) | **$6.00/mo**<br>or **$48/year** ($4/mo) or **$99 lifetime** | **Free forever tier** permitting **1 conversion task every 60 minutes** (cooldown period) and **50MB file size limit** | Comprehensive suite of 47+ web tools for PDF to DOCX, RTF, ODT, EPUB, and MOBI with offline Windows companion software. |
| **[FreePDFConvert](https://www.freepdfconvert.com/)** | **~$3M ARR**<br>(~$10M Valuation · Baltic Virtual) | **$6.00/mo**<br>($72/year billed annually) | **Free tier** limited to **1 document conversion every 30 minutes** with **15MB maximum file size limit** | Straightforward browser utility converting PDF to Microsoft Office formats (Word, Excel, PowerPoint) and extracting image assets. |

---

## 💻 Open-Source Document Conversion Engines & Libraries

The following projects represent the pinnacle of open-source document conversion technology. They are **sorted in descending order by GitHub star count**, equipped with live star badges linking to each project's stargazers community.

---

### 1. [MarkItDown](https://github.com/microsoft/markitdown)  
[![Stars](https://img.shields.io/github/stars/microsoft/markitdown?style=social&color=white)](https://github.com/microsoft/markitdown/stargazers)  
- **Description**: Microsoft's official Python utility and engine for converting heterogeneous files and office documents into clean, structured Markdown.
- **Supported Formats**: PDF, PowerPoint (`.pptx`), Word (`.docx`), Excel (`.xlsx`), HTML, CSV, JSON, XML, Audio (speech transcription), and Images (EXIF metadata & OCR).
- **Ideal For**: LLM text chunking, retrieval-augmented generation (RAG) pipelines, and AI document indexing.

---

### 2. [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)  
[![Stars](https://img.shields.io/github/stars/Stirling-Tools/Stirling-PDF?style=social&color=white)](https://github.com/Stirling-Tools/Stirling-PDF/stargazers)  
- **Description**: The #1 self-hosted, full-featured web application for complete PDF manipulation and multi-format document conversion.
- **Supported Formats**: PDF to Word, PowerPoint, Excel, Images, HTML, Markdown, XML, and vice versa via headless LibreOffice integration.
- **Features**: Docker one-click deployment, multi-user accounts with role-based access, comprehensive REST API, OCR (Tesseract), digital signatures, and redaction.

---

### 3. [Typst](https://github.com/typst/typst)  
[![Stars](https://img.shields.io/github/stars/typst/typst?style=social&color=white)](https://github.com/typst/typst/stargazers)  
- **Description**: A modern, markup-based typesetting system and compiler designed as a blazing-fast, accessible alternative to LaTeX.
- **Supported Formats**: Typst markup (`.typ`) to PDF, SVG, and PNG with sub-second incremental compilation.
- **Features**: Intuitive syntax, built-in layout engine, expressive scripting system, and instant visual preview.

---

### 4. [Pandoc](https://github.com/jgm/pandoc)  
[![Stars](https://img.shields.io/github/stars/jgm/pandoc?style=social&color=white)](https://github.com/jgm/pandoc/stargazers)  
- **Description**: The legendary Swiss Army knife of markup format transformation, written in Haskell.
- **Supported Formats**: Markdown, CommonMark, DOCX, ODT, HTML, LaTeX, EPUB, RTF, MediaWiki, Org-mode, Textile, OPML, DocBook, and PDF (via external LaTeX/Typst engines).
- **Features**: Scriptable AST filter pipelines (Lua filters), citation processing via `pandoc-citeproc`, and universal CLI scriptability.

---

### 5. [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)  
[![Stars](https://img.shields.io/github/stars/ocrmypdf/OCRmyPDF?style=social&color=white)](https://github.com/ocrmypdf/OCRmyPDF/stargazers)  
- **Description**: Production-grade tool that adds an optical character recognition (OCR) text layer to scanned PDF files and images.
- **Supported Formats**: Scanned PDFs, TIFF, PNG, JPEG to searchable, extractable, standards-compliant PDF/A files.
- **Features**: Unpaper preprocessing, deskewing, automatic orientation correction, lossless image compression, and multithreaded processing.

---

### 6. [Calibre](https://github.com/kovidgoyal/calibre)  
[![Stars](https://img.shields.io/github/stars/kovidgoyal/calibre?style=social&color=white)](https://github.com/kovidgoyal/calibre/stargazers)  
- **Description**: The premier cross-platform e-book and digital document conversion and management powerhouse.
- **Supported Formats**: EPUB, MOBI, AZW3, PDF, DOCX, RTF, HTML, TXT, LRF, PDB, FB2, and LIT.
- **Features**: Advanced command-line converter (`ebook-convert`), CSS stylesheet manipulation, cover preservation, and metadata enrichment.

---

### 7. [BentoPDF](https://github.com/alam00000/bentopdf)  
[![Stars](https://img.shields.io/github/stars/alam00000/bentopdf?style=social&color=white)](https://github.com/alam00000/bentopdf/stargazers)  
- **Description**: Privacy-first, browser-based PDF toolkit containing 130+ manipulation and conversion utilities.
- **Supported Formats**: PDF to DOCX, XLSX, PPTX, JPG, PNG, and text formats.
- **Features**: 100% client-side WebAssembly execution (LibreOffice WASM, PyMuPDF, Ghostscript); zero file uploads to external servers; easily deployable as a static site or Docker container.

---

### 8. [wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf)  
[![Stars](https://img.shields.io/github/stars/wkhtmltopdf/wkhtmltopdf?style=social&color=white)](https://github.com/wkhtmltopdf/wkhtmltopdf/stargazers)  
- **Description**: Open-source command-line tool suite to render HTML into PDF and various image formats using the Qt WebKit rendering engine.
- **Supported Formats**: HTML/CSS/JavaScript to PDF and raster images (PNG, JPEG).
- **Features**: Headless operation, header/footer templating, table of contents generation, and widespread legacy server support.

---

### 9. [Gotenberg](https://github.com/gotenberg/gotenberg)  
[![Stars](https://img.shields.io/github/stars/gotenberg/gotenberg?style=social&color=white)](https://github.com/gotenberg/gotenberg/stargazers)  
- **Description**: Docker-powered stateless HTTP API for converting HTML, Markdown, and Office documents into high-quality PDFs.
- **Supported Formats**: HTML, Markdown, Word (`.docx`), Excel (`.xlsx`), PowerPoint (`.pptx`), OpenDocument (`.odt`), and RTF to PDF and PDF/A.
- **Features**: Bundles Chromium, LibreOffice, PDFtk, and QPDF into a scalable microservice architecture with webhook support.

---

### 10. [pdfmake](https://github.com/bpampuch/pdfmake)  
[![Stars](https://img.shields.io/github/stars/bpampuch/pdfmake?style=social&color=white)](https://github.com/bpampuch/pdfmake/stargazers)  
- **Description**: Pure JavaScript document generation and conversion engine for both client-side browser and Node.js environments.
- **Supported Formats**: Declarative JSON document definitions to vector-accurate PDF files.
- **Features**: Automatic page wrapping, complex table styling, custom fonts, margins, headers, footers, and vector drawing.

---

### 11. [PyMuPDF](https://github.com/pymupdf/PyMuPDF)  
[![Stars](https://img.shields.io/github/stars/pymupdf/PyMuPDF?style=social&color=white)](https://github.com/pymupdf/PyMuPDF/stargazers)  
- **Description**: High-performance Python binding for MuPDF, delivering exceptionally fast rendering, text extraction, and document conversion.
- **Supported Formats**: PDF, XPS, OpenXPS, CBZ, CBR, EPUB, and FB2 to text, HTML, XML, JSON, and images.
- **Features**: Fast page rasterization, table detection, OCR integration with Tesseract, and metadata editing.

---

### 12. [PDFKit](https://github.com/foliojs/pdfkit)  
[![Stars](https://img.shields.io/github/stars/foliojs/pdfkit?style=social&color=white)](https://github.com/foliojs/pdfkit/stargazers)  
- **Description**: Declarative JavaScript PDF generation library designed for Node.js and browser applications.
- **Supported Formats**: Programmatic JavaScript drawing and layout primitives to PDF.
- **Features**: Vector graphics, embedded TrueType fonts, image embedding (JPEG, PNG), encryption, and streaming output.

---

### 13. [pypdf](https://github.com/py-pdf/pypdf)  
[![Stars](https://img.shields.io/github/stars/py-pdf/pypdf?style=social&color=white)](https://github.com/py-pdf/pypdf/stargazers)  
- **Description**: Pure-Python PDF library capable of splitting, merging, cropping, transforming, encrypting, and decrypting PDF files with zero C dependencies.
- **Supported Formats**: PDF to text, image extraction, and structural PDF generation.
- **Features**: Layout text extraction, form filling, lossless compression, watermark insertion, and PDF bookmark management.

---

### 14. [WeasyPrint](https://github.com/Kozea/WeasyPrint)  
[![Stars](https://img.shields.io/github/stars/Kozea/WeasyPrint?style=social&color=white)](https://github.com/Kozea/WeasyPrint/stargazers)  
- **Description**: Visual document factory that turns web standards (HTML and CSS) into print-ready PDF files.
- **Supported Formats**: HTML5 and CSS3 to PDF.
- **Features**: Full compliance with W3C CSS Paged Media standards, automatic page numbers, margin boxes, footnotes, and CMYK color space support.

---

### 15. [pdf-lib](https://github.com/Hopding/pdf-lib)  
[![Stars](https://img.shields.io/github/stars/Hopding/pdf-lib?style=social&color=white)](https://github.com/Hopding/pdf-lib/stargazers)  
- **Description**: Modern TypeScript/JavaScript library to create and modify PDF documents in any JS runtime (Node.js, Browser, Deno, React Native).
- **Supported Formats**: PDF manipulation and rendering from raw JavaScript primitives.
- **Features**: Pure JavaScript with zero native dependencies, page extraction, form creation and flattening, vector drawing, and font embedding.

---

### 16. [pdfminer.six](https://github.com/pdfminer/pdfminer.six)  
[![Stars](https://img.shields.io/github/stars/pdfminer/pdfminer.six?style=social&color=white)](https://github.com/pdfminer/pdfminer.six/stargazers)  
- **Description**: Community-maintained Python tool focused on exact layout analysis and structural text/image extraction from PDF documents.
- **Supported Formats**: PDF to plain text, HTML, XML, or `hOCR`.
- **Features**: Font and bounding box coordinate extraction, CJK language support, and programmatic layout tree traversal.

---

### 17. [pdfarranger](https://github.com/pdfarranger/pdfarranger)  
[![Stars](https://img.shields.io/github/stars/pdfarranger/pdfarranger?style=social&color=white)](https://github.com/pdfarranger/pdfarranger/stargazers)  
- **Description**: Small, intuitive Python-GTK desktop application for visual page-level PDF manipulation.
- **Supported Formats**: PDF merging, splitting, rotation, cropping, and rearranging.
- **Features**: Drag-and-drop visual canvas, zero document re-encoding artifacts, and fast desktop operation.

---

### 18. [QPDF](https://github.com/qpdf/qpdf)  
[![Stars](https://img.shields.io/github/stars/qpdf/qpdf?style=social&color=white)](https://github.com/qpdf/qpdf/stargazers)  
- **Description**: C++ command-line tool and library that performs content-preserving structural transformations on PDF files.
- **Supported Formats**: PDF linearization (Web optimization), encryption (up to 256-bit AES), decryption, and stream transformation.
- **Features**: Structural repair of damaged PDFs, object stream inspection, and lossless structural re-packaging.

---

### 19. [LibreOffice Core](https://github.com/LibreOffice/core)  
[![Stars](https://img.shields.io/github/stars/LibreOffice/core?style=social&color=white)](https://github.com/LibreOffice/core/stargazers)  
- **Description**: The foundational engine powering headless office document conversions across the software industry.
- **Supported Formats**: DOCX, DOC, XLSX, XLS, PPTX, PPT, ODT, ODS, ODP, RTF, HTML to PDF, EPUB, and images.
- **Command**: `soffice --headless --convert-to pdf document.docx`

---

### 20. [pdf2docx](https://github.com/ArtifexSoftware/pdf2docx)  
[![Stars](https://img.shields.io/github/stars/ArtifexSoftware/pdf2docx?style=social&color=white)](https://github.com/ArtifexSoftware/pdf2docx/stargazers)  
- **Description**: Python library and CLI specifically engineered for reconstructing editable Microsoft Word (`.docx`) files from PDF documents.
- **Supported Formats**: PDF to DOCX.
- **Features**: Parses layout blocks, paragraphs, text styles, tables, borders, and embedded images into native Word document XML elements.

---

### 21. [unoconv](https://github.com/unoconv/unoconv)  
[![Stars](https://img.shields.io/github/stars/unoconv/unoconv?style=social&color=white)](https://github.com/unoconv/unoconv/stargazers)  
- **Description**: Universal Office Converter command-line utility that converts between any format that LibreOffice or OpenOffice can import and export.
- **Supported Formats**: Any office document, spreadsheet, presentation, or vector graphic to PDF, HTML, DOCX, CSV, TXT.
- **Features**: Automates LibreOffice UNO daemon connections for batch command-line transformations.

---

### 22. [Ghostscript (ghostpdl)](https://github.com/ArtifexSoftware/ghostpdl)  
[![Stars](https://img.shields.io/github/stars/ArtifexSoftware/ghostpdl?style=social&color=white)](https://github.com/ArtifexSoftware/ghostpdl/stargazers)  
- **Description**: The industry-standard PostScript interpreter and PDF rasterization engine.
- **Supported Formats**: PostScript (`.ps`), EPS, PDF, XPS to raster image formats (TIFF, PNG, JPEG) and PDF/A.
- **Features**: Font embedding, color profile conversion (ICC/CMYK), raster image resolution scaling, and print spool processing.

---

### 23. [DocWen](https://github.com/ZHYX91/docwen)  
[![Stars](https://img.shields.io/github/stars/ZHYX91/docwen?style=social&color=white)](https://github.com/ZHYX91/docwen/stargazers)  
- **Description**: Local-first GUI and CLI application for document conversion, proofreading, and format standardization.
- **Supported Formats**: Word (`.docx`) ↔ Markdown, Excel/CSV ↔ Markdown.
- **Features**: Built-in template system, punctuation auto-normalization, and sensitive word scanning.

---

### 24. [anyconvert](https://github.com/word-sys/anyconvert)  
[![Stars](https://img.shields.io/github/stars/word-sys/anyconvert?style=social&color=white)](https://github.com/word-sys/anyconvert/stargazers)  
- **Description**: Zero-dependency, pure-Python PDF conversion engine designed to reconstruct office files without external C libraries.
- **Supported Formats**: PDF to DOCX, PPTX, ODT, ODP, and TXT.
- **Features**: Features both **Canvas Mode** (strict visual fidelity) and **Flow Mode** (semantic reflowable text), with native OPC packaging.

---

### 25. [Duckling](https://github.com/excelano/duckling)  
[![Stars](https://img.shields.io/github/stars/excelano/duckling?style=social&color=white)](https://github.com/excelano/duckling/stargazers)  
- **Description**: Offline desktop GUI for high-accuracy document transformation powered by `docling.rs` (Rust implementation of IBM Docling).
- **Supported Formats**: Word, PowerPoint, Excel, PDF, HTML, EPUB, RTF to Markdown, JSON, LaTeX, DOCX, and ODT.
- **Features**: Scanned document OCR parsing, equation detection, and local-first execution.

---

### 26. [ConvertAgent](https://github.com/vid-factory/convertagent)  
[![Stars](https://img.shields.io/github/stars/vid-factory/convertagent?style=social&color=white)](https://github.com/vid-factory/convertagent/stargazers)  
- **Description**: Developer-centric file conversion toolkit designed specifically for autonomous AI agents and automated workflows.
- **Supported Formats**: 20+ conversion pairs including PDF→DOCX, DOCX→PDF, HTML→PDF, and Markdown→DOCX.
- **Features**: Exposes unified CLI, REST API, and Model Context Protocol (MCP) server interfaces backed by FFmpeg, LibreOffice, and Pandoc.

---

### 27. [file-converter](https://github.com/ab0jwad/file-converter)  
[![Stars](https://img.shields.io/github/stars/ab0jwad/file-converter?style=social&color=white)](https://github.com/ab0jwad/file-converter/stargazers)  
- **Description**: Lightweight Python-based multi-format conversion utility featuring both CLI and GUI interfaces.
- **Supported Formats**: Document (PDF→DOCX, TXT→DOCX, Markdown→HTML), tabular data (CSV↔JSON, XML, XLSX), and image conversions.

---

## 🎯 Document Conversion Architecture & Decision Guide

Choosing the ideal document conversion tool depends on your deployment environment, throughput requirements, and document complexity:

```
                      ┌──────────────────────────────────────┐
                      │ What is your primary conversion need?│
                      └──────────────────┬───────────────────┘
                                         │
         ┌───────────────────────────────┼───────────────────────────────┐
         ▼                               ▼                               ▼
┌──────────────────┐           ┌──────────────────┐           ┌──────────────────┐
│  Office to PDF   │           │   PDF to Word    │           │ Markdown / HTML  │
│(DOCX, XLSX, PPTX)│           │  (Editable DOCX) │           │     to PDF       │
└────────┬─────────┘           └────────┬─────────┘           └────────┬─────────┘
         │                              │                              │
  Headless LibreOffice           pdf2docx (Python)             Pandoc + Typst
   or Gotenberg API             Stirling-PDF / CloudConvert     WeasyPrint / Chromium
```

### ⚡ Architectural Recommendations
1. **High-Throughput Dockerized Conversion Microservice**: Deploy **[Gotenberg](https://github.com/gotenberg/gotenberg)** or **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** behind an API gateway to handle high-concurrency Office-to-PDF and HTML-to-PDF conversions.
2. **AI & LLM Ingestion / RAG Pipelines**: Use **[MarkItDown](https://github.com/microsoft/markitdown)** to convert office documents, spreadsheets, and PDFs into semantically rich Markdown with clean table structures.
3. **Command-Line & Scriptable Publishing**: Use **[Pandoc](https://github.com/jgm/pandoc)** combined with **[Typst](https://github.com/typst/typst)** for lightning-fast, repeatable document compilation from plain text.
4. **Zero-Server / Client-Side Web Apps**: Use **[BentoPDF](https://github.com/alam00000/bentopdf)** or **[pdf-lib](https://github.com/Hopding/pdf-lib)** to process files directly inside the user's browser via WebAssembly without transferring sensitive files to the cloud.

---

## 🤝 How to Contribute

Contributions from the developer community and document software creators are warmly welcomed!

1. 🍴 **Fork this repository**.
2. 🌿 **Create a feature branch**: `git checkout -b add-new-converter`.
3. 📝 **Add or update entries in `README.md`**:
   - Ensure tools are categorized correctly under SaaS or Open-Source.
   - For SaaS products, provide exact starting pricing, company valuation/revenue metrics, and explicit free tier/trial limits.
   - For Open-Source repositories, include the official `style=social` GitHub stars badge linking to the stargazers page and ensure placement respects star count descending order.
4. 🚀 **Submit a Pull Request** with a concise description of the added software.

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Document-Conversion-Software&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Document-Conversion-Software&type=date&legend=top-left)

---

## 💖 Support & Community

Thank you for exploring **Awesome Document Conversion Software**! If this curated directory helps you discover tools, streamline document pipelines, or build sovereign file workflows, please consider supporting the project:

- ⭐ **Star this repository** to help other developers and teams discover it on GitHub.
- 🍴 **Fork and share** with colleagues and document workflow communities.
- 📢 **Join our community** on [Discord](https://discord.gg/jc4xtF58Ve) to discuss file transformation tools, document architectures, and automation tips.
- ☕ **Sponsor the maintainer**: Support continuous research and open-source curation via the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007). Every bit of support is deeply appreciated!

---

## 📜 Disclaimer

- This repository is a **community-curated index** published for informational, architectural, and educational purposes. Inclusion does not constitute an official endorsement.
- All trademarks, service marks, logos, and company names referenced herein are the property of their respective owners.
- When handling sensitive, medical, legal, or personal documents, always evaluate compliance regulations (such as GDPR, HIPAA, and SOC 2) and verify the data retention policies of third-party cloud conversion providers.
