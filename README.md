# AI-Powered B2B Prospect Acquisition & Qualification Platform

## Overview

This project is an AI-powered prospect acquisition platform developed during my internship at **Dexprovider**.

Its objective is to automate the discovery, qualification, enrichment and prioritization of French companies that are likely to need HR outsourcing and recruitment services.

Instead of manually searching for prospects, the platform continuously collects signals from public data sources, enriches company information, scores each prospect according to business rules, and prepares qualified leads for sales outreach.

---

## Features

* Automated prospect acquisition
* France Travail API integration
* Pappers company enrichment
* Intelligent pre-qualification engine
* Prospect scoring engine
* Google Sheets CRM synchronization
* AI-assisted company qualification using Ollama
* Duplicate detection using SIREN
* Modular n8n workflows

---

## Architecture

```text
France Travail API
        │
        ▼
Pre-Qualification
        │
        ▼
Prospect Intelligence
        │
        ▼
Pappers API
        │
        ▼
Google Sheets
        │
        ▼
AI Qualification (Ollama)
```

---

## Technology Stack

### Automation

* n8n

### APIs

* France Travail API
* Pappers API

### Artificial Intelligence

* Ollama
* Local LLM

### Data

* Google Sheets

### Language

* JavaScript

### Version Control

* Git
* GitHub

---

## Repository Structure

```
workflows/
    V4/
    V5/

docs/

examples/

images/
```

---

## Current Status

* ✔ Prospect acquisition workflow
* ✔ France Travail integration
* ✔ Company enrichment
* ✔ Google Sheets integration
* ✔ AI qualification workflow
* 🚧 Continuous improvements

---

## Roadmap

* Multi-source acquisition (BODACC, INPI, LinkedIn)
* CRM integration
* Dashboard
* Automated outreach
* Machine learning-based scoring

---

## Security

All credentials, API keys, OAuth tokens and confidential company information have been removed from this repository.

Environment variables are documented in `.env.example`.

---

## License

MIT License
