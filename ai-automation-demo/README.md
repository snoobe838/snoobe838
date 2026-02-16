# AICM Generation Automation

### 🧪 AI Content Module (AICM) Generation - Automation Framework

This project automates and validates an AI-based content generation application that creates **course pages, learning modules, and question banks** based on a user's prompt.  
The automation not only checks UI flow and content generation but also verifies the **accuracy and semantic relevance** of AI responses using **SBERT and TFT similarity scoring**, ensuring quality and meaningful output.

---

## 🎯 Purpose

The goal of this project is to:
✔ Automate end-to-end flow of an AI-driven course generator application  
✔ Trigger prompt-based content generation for modules and question banks  
✔ Validate generated content using **semantic similarity (SBERT + TFT)**  
✔ Measure relevance, accuracy, and alignment with user prompt  
✔ Built for **regression testing and functional validation**

---

## 👤 Role & Ownership

**Role:** QA Automation Engineer (Designed & Developed Entire Framework)  
**Ownership:** Architected and implemented the full automation framework including:  
✔ Test design & strategy  
✔ Framework setup (Pytest + POM architecture)  
✔ AI content validation using SBERT  
✔ Threshold-based accuracy evaluation  
✔ Reporting & structured logging

---

## 🛠️ Tech Stack & Tools

| Category | Tools / Libraries |
|----------|-------------------|
| Programming | Python |
| Testing Framework | Pytest |
| UI Automation | Selenium |
| Design Pattern | Page Object Model (POM) |
| AI Content Validation | SBERT (Sentence-BERT), TFT |
| Report Generation | Pytest HTML / JSON logging |
| Others | Requests, JSON, Logging, PyCharm |

---

## ⚙️ Features Implemented

✔ Automated end-to-end AI-powered course content generation  
✔ SBERT-based response validation (semantic similarity scoring)  
✔ Threshold-based pass/fail accuracy verification  
✔ Module-wise analysis (Content, Pages, MCQ, Question Bank)  
✔ Parametrized test execution using Pytest  
✔ Custom logging + HTML report output  
✔ Modular POM framework structure  
✔ Support for multiple prompts and curriculum types  
✔ Reusable API and UI automation support

---

## 🧠 AI Validation Logic (SBERT + TFT Integration)

The system validates AI-generated content using semantic similarity models.

**Validation Criteria:**
| Metric | Purpose |
|--------|---------|
| SBERT Similarity | Checks semantic closeness of content to prompt |
| TFT Score | Measures topical relevance & term frequency |
| Threshold | 0.75 (Content is accepted only if score >= threshold) |

✔ If both SBERT and TFT pass → AI response is considered **valid**  
✔ If below threshold → Flagged for improvement/regression failure

---


