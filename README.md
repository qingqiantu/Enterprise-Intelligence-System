# 🏢 Enterprise Intelligence System  
*A full-stack enterprise management platform integrating ERP, Knowledge Base, and AI Intelligence modules.*

---

## 📘 1. Project Overview
**Enterprise Intelligence System** is an integrated enterprise management solution combining three key components:
- **ERP System** — Handles procurement, inventory, and approval workflows.
- **Knowledge Base** — Supports document upload, version control, and intelligent retrieval.
- **AI Intelligence Layer** — Provides OCR invoice recognition, RAG-based document Q&A, and predictive analytics.

> 🎯 Goal: To create a unified digital platform that automates enterprise workflows, improves collaboration efficiency, and enhances data-driven decision making.

---

## 🧩 2. System Architecture

```text
┌──────────────────────────┐
│       Frontend UI        │
│ (Vue + Element Plus / React) │
└────────────┬─────────────┘
             │
┌────────────▼────────────┐
│     Backend Services     │
│  (Flask + RESTful APIs)  │
├────────────┬─────────────┤
│ ERP Module │ Knowledge Base │
├────────────┴─────────────┤
│  AI Intelligence Layer   │
│ (OCR / RAG / Prediction) │
└────────────┬─────────────┘
             │
┌────────────▼────────────┐
│     Database Layer       │
│ (MySQL / PostgreSQL / ES)│
└──────────────────────────┘
