<h1 align="center">NixWrk</h1>

<p align="center">
  <strong>Document engineering | OCR pipelines | Zotero automation | local AI tooling</strong>
</p>

<p align="center">
  <a href="https://github.com/NixWrk?tab=repositories&type=source">
    <img alt="Public repositories" src="https://img.shields.io/badge/GitHub-public%20repos-0f172a?style=flat-square&logo=github">
  </a>
  <img alt="Python" src="https://img.shields.io/badge/Python-tooling-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="OCR" src="https://img.shields.io/badge/OCR-searchable%20PDFs-0f766e?style=flat-square">
  <img alt="Zotero" src="https://img.shields.io/badge/Zotero-academic%20workflows-CC2936?style=flat-square">
  <img alt="Local AI" src="https://img.shields.io/badge/local--first-AI%20tooling-2563eb?style=flat-square">
</p>

> I build local-first tools for converting scanned documents, PDFs, and academic collections into searchable, structured, reproducible knowledge assets.

## Core Domains

| Domain | Engineering output |
|---|---|
| OCR and searchable PDFs | Local OCR pipelines, hOCR bridges, OCRmyPDF plugins, searchable PDF assembly. |
| PDF processing | Page cleanup, geometry correction, crop benchmarking, image-to-PDF workflows. |
| Zotero workflows | Local Zotero storage processing, PDF-to-Markdown conversion, WebDAV mirroring, traceability artifacts. |
| Local AI | LM Studio workflows, local model routing, document translation experiments, self-hosted tooling. |
| Automation | Windows-first GUI/CLI tools, repeatable setup scripts, workflow orchestration. |
| Information extraction | RAG-ready document preparation and structured document conversion. |

## Featured Engineering Projects

<table>
  <thead>
    <tr>
      <th>Project</th>
      <th>Problem domain</th>
      <th>Role in the ecosystem</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/NixWrk/Surya_Chandra_PDF_OCR"><strong>Surya_Chandra_PDF_OCR</strong></a></td>
      <td>OCR, searchable PDFs, document AI</td>
      <td>Core local OCR pipeline for turning scanned PDFs into searchable PDF assets.</td>
      <td>Core project</td>
    </tr>
    <tr>
      <td><a href="https://github.com/NixWrk/ZoteroPDF_2_MD"><strong>ZoteroPDF_2_MD</strong></a></td>
      <td>Zotero, Marker, academic workflows</td>
      <td>Processes local Zotero PDF collections into Markdown and HTML workflows with traceability.</td>
      <td>Active workflow tool</td>
    </tr>
    <tr>
      <td><a href="https://github.com/NixWrk/img_2_pdf"><strong>img_2_pdf</strong></a></td>
      <td>PDF preprocessing, document geometry</td>
      <td>Pre-OCR layer for page capture, cleanup, crop, perspective correction, and PDF export.</td>
      <td>Foundation layer</td>
    </tr>
    <tr>
      <td><a href="https://github.com/NixWrk/Claude_Code_Local_LLM_Switcher_LM_Studio"><strong>Claude Code Local LLM Switcher</strong></a></td>
      <td>Local AI, LM Studio, developer tooling</td>
      <td>Windows GUI/CLI for mapping Claude Code aliases to local LM Studio models and isolated VS Code sessions.</td>
      <td>Local AI utility</td>
    </tr>
  </tbody>
</table>

## OCR and Searchable PDF Ecosystem

| Layer | Repository | Purpose |
|---|---|---|
| OCR pipeline | [`Surya_Chandra_PDF_OCR`](https://github.com/NixWrk/Surya_Chandra_PDF_OCR) | Local scanned-PDF to searchable-PDF workflow. |
| Geometry bridge | [`surya_hOCR_bridge`](https://github.com/NixWrk/surya_hOCR_bridge) | Converts Surya sidecars and OCR artifacts into hOCR/searchable-PDF workflows. |
| OCRmyPDF plugin | [`Surya_OCRmyPDF_Plugin`](https://github.com/NixWrk/Surya_OCRmyPDF_Plugin) | Surya OCR integration for OCRmyPDF. |
| OCRmyPDF plugin | [`Chandra_OCRmyPDF_Plugin`](https://github.com/NixWrk/Chandra_OCRmyPDF_Plugin) | Chandra layout OCR to hOCR/OCRmyPDF bridge. |
| Plugin hub | [`OCRmyPDF_Plugins_HUB`](https://github.com/NixWrk/OCRmyPDF_Plugins_HUB) | Working snapshots and integration references for OCRmyPDF plugin experiments. |

## PDF Processing and Document Preprocessing

[`img_2_pdf`](https://github.com/NixWrk/img_2_pdf) is the pre-OCR document pipeline layer:

- page import and capture;
- deskew, crop, perspective correction, and enhancement;
- image export and merged PDF generation;
- crop benchmark tooling;
- clean separation from OCR benchmarking and plugin repositories.

Related repositories:

- [`Surya_Chandra_PDF_OCR`](https://github.com/NixWrk/Surya_Chandra_PDF_OCR) - searchable PDF assembly;
- [`surya_hOCR_bridge`](https://github.com/NixWrk/surya_hOCR_bridge) - OCR geometry and hOCR bridge;
- [`OCRmyPDF_Plugins_HUB`](https://github.com/NixWrk/OCRmyPDF_Plugins_HUB) - OCRmyPDF plugin integration workspace;
- [`mrf.museumart.ru-pdf_book_saver`](https://github.com/NixWrk/mrf.museumart.ru-pdf_book_saver) - book/PDF saving automation.

## Zotero and Academic Workflows

[`ZoteroPDF_2_MD`](https://github.com/NixWrk/ZoteroPDF_2_MD) connects local academic collections with document conversion workflows:

- local Zotero PDF collection processing;
- Markdown and HTML conversion paths;
- deterministic staging and traceability artifacts;
- WebDAV-oriented file mirroring;
- local model experiments for document translation and review.

[`Zotero_Integration_Metadata_Mapping`](https://github.com/NixWrk/Zotero_Integration_Metadata_Mapping) and [`Zotero_SciHub_module`](https://github.com/NixWrk/Zotero_SciHub_module) are adjacent experiments around metadata and academic-source automation.

## Local AI and Self-Hosted Tooling

| Repository | Focus | Notes |
|---|---|---|
| [`Claude_Code_Local_LLM_Switcher_LM_Studio`](https://github.com/NixWrk/Claude_Code_Local_LLM_Switcher_LM_Studio) | Claude Code and LM Studio | Alias binding, local endpoint checks, context control, isolated VS Code launcher. |
| [`ZoteroPDF_2_MD`](https://github.com/NixWrk/ZoteroPDF_2_MD) | Marker and local model experiments | Academic PDF conversion, HTML workflows, local translation experiments. |
| [`LLM_Task_Orchestration`](https://github.com/NixWrk/LLM_Task_Orchestration) | Task orchestration | Experimental workspace for future local AI workflow coordination. |
| [`LLM_translator_test`](https://github.com/NixWrk/LLM_translator_test) | Translation experiments | Early local translation and workflow testing. |

## Automation and Research Utilities

Secondary work includes GUI wrappers, local workflow launchers, book/PDF savers, OCR plugin experiments, document conversion utilities, and workflow orchestration prototypes.

| Repository | Area |
|---|---|
| [`ISO_Sensitometer_GUI`](https://github.com/NixWrk/ISO_Sensitometer_GUI) | Imaging and measurement GUI tooling. |
| [`Obsidian_Doctor`](https://github.com/NixWrk/Obsidian_Doctor) | Local knowledge-base maintenance. |
| [`marker_GUI`](https://github.com/NixWrk/marker_GUI) | GUI experimentation around document conversion. |

## Technical Stack

**Languages and runtime:** Python, PowerShell, Bash, Docker  
**Document tooling:** OCRmyPDF, hOCR, pypdf, pypdfium2, ReportLab, Marker  
**AI/OCR:** Surya, Chandra, LM Studio, local model workflows  
**Data and workflow:** SQLite, Zotero storage, WebDAV, CSV/JSON traceability artifacts  
**Interfaces:** CLI, Tkinter GUI, local HTTP services, Windows automation

## Engineering Activity

<p>
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=NixWrk&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" />
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NixWrk&layout=compact&theme=transparent&hide_border=true&hide=html,css" />
</p>

## Contact

- GitHub: [@NixWrk](https://github.com/NixWrk)
- Best project contact path: open an issue in the relevant repository.
- Collaboration focus: OCR/PDF automation, Zotero workflows, local AI tooling, information extraction, and RAG-ready document pipelines.

## Contribution Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NixWrk/NixWrk/refs/heads/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NixWrk/NixWrk/refs/heads/output/github-contribution-grid-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/NixWrk/NixWrk/refs/heads/output/github-contribution-grid-snake.svg" />
  </picture>
</p>
