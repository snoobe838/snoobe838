# MCP No-Code Automation Framework

This project demonstrates a no-code automation framework where test cases are written in plain English using Markdown files and executed through a lightweight test runner. The framework is designed to simulate real-world QA workflows while making automation accessible to non-programmers.

It showcases how structured documentation-driven testing can be converted into executable automation, enabling rapid validation of business scenarios and simplified test maintenance.

---

## 🎯 Project Objectives

✔ Enable test creation using plain English Markdown files
✔ Execute structured test cases without traditional coding
✔ Generate readable Markdown-based execution reports
✔ Support scalable documentation-driven automation
✔ Bridge the gap between manual and automated testing

---

## 📂 Project Structure

```
├── test-cases/                     # Markdown files containing English test cases
│   ├── login-tests.md
│   ├── checkout-tests.md
│
├── test-reports/                   # Markdown execution reports
│   ├── execution-report.md
│
├── runner/                         # Test runner logic
│   └── test-runner.py
│
├── workflows/                      # Automation workflow definitions
├── config/                         # Execution configuration
└── README.md                       # Project documentation
```

---

## 🛠️ Framework Concept

The framework uses Markdown as a structured format for writing test scenarios. Each test case file contains:

* Test steps written in natural language
* Expected outcomes
* Execution status tracking
* Automated result logging

The test runner parses these files, executes the defined workflows, and generates Markdown reports summarizing results.

---

## ⚙️ Features Implemented

✔ English-based test case authoring
✔ Markdown-driven execution workflow
✔ Automated test result reporting
✔ Simple and maintainable structure
✔ Reusable test runner architecture
✔ Scalable documentation-first testing approach
✔ Suitable for non-technical QA contributors

---

## ▶️ Running Tests

Execute the test runner:

```bash
python runner/test-runner.py
```

This will:

* Parse Markdown test cases
* Execute defined workflows
* Generate Markdown execution reports

---

## 🧾 Reports

Execution reports are generated in:

```
test-reports/
```

Each report contains:

* Test summary
* Step-by-step execution status
* Pass/Fail results
* Observations and notes

---

## 🧩 Framework Customization

To extend the framework:

* Add new Markdown test files in `test-cases/`
* Modify execution logic in `runner/`
* Customize workflows in `workflows/`
* Update configuration in `config/`

---

## 🚀 Use Cases

This framework is ideal for:

* No-code automation demonstrations
* Documentation-driven testing
* Rapid prototyping of QA workflows
* Collaboration with non-technical stakeholders

---

## 👤 Author

Shubham Pareek
QA Automation Engineer | No-Code Automation | Modern QA Workflows

