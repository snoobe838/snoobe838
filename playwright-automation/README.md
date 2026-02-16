# Playwright Automation Framework (TypeScript)

This project is a modern end-to-end UI automation framework built using **TypeScript** and Playwright. It automates sanity, regression, and functional test scenarios with a scalable architecture designed for maintainability, speed, and reliability.

The framework demonstrates enterprise-level automation practices including parallel execution, cross-browser testing, structured reporting, and reusable Page Object Model design.

---

## 🎯 Project Objectives

✔ Automate real-world end-to-end UI workflows
✔ Validate cross-browser behavior and responsiveness
✔ Support scalable regression testing
✔ Provide clean reporting and debugging insights
✔ Enable maintainable and reusable test architecture

---

## 📂 Project Structure

```
├── config/                         # Environment configs and test settings
├── fixtures/                       # Custom Playwright fixtures & setup hooks
├── pages/                          # Page Object Model (POM) classes
├── tests/                          # Organized test suites
├── test-data/                      # JSON/CSV test input data
├── utils/                          # Helper utilities and custom commands
├── reports/                        # Playwright HTML & trace reports
├── screenshots/                    # Failure screenshots
├── videos/                         # Execution recordings
├── playwright.config.ts            # Playwright configuration
├── package.json                    # Node dependencies
├── tsconfig.json                   # TypeScript configuration
└── README.md                       # Project documentation
```

---

## 🛠️ Tech Stack

| Category        | Tools                     |
| --------------- | ------------------------- |
| Language        | TypeScript                |
| Framework       | Playwright                |
| Test Runner     | Playwright Test           |
| Design Pattern  | Page Object Model (POM)   |
| Reporting       | HTML Report, Trace Viewer |
| Package Manager | npm                       |
| CI/CD Ready     | GitHub Actions            |

---

## ⚙️ Features Implemented

✔ Cross-browser testing (Chromium, Firefox, WebKit)
✔ Parallel and headless execution
✔ Page Object Model architecture
✔ Data-driven testing support
✔ Environment configuration handling
✔ Automatic screenshots on failure
✔ Video recording of test runs
✔ Trace viewer for debugging
✔ Custom fixtures and hooks
✔ Structured logging and reporting
✔ Retry and timeout mechanisms
✔ Tag-based test execution
✔ CI/CD integration readiness

---

## ✅ Prerequisites

Before running the project, install:

* Node.js **18+**
* npm or yarn
* Git
* Supported browsers (installed automatically by Playwright)

---

## 🧩 Setup Instructions

1. Clone the repository

```bash
git clone <repo-url>
cd playwright-automation
```

2. Install dependencies

```bash
npm install
```

3. Install Playwright browsers

```bash
npx playwright install
```

---

## ▶️ Running Tests

Run all tests:

```bash
npx playwright test
```

Run specific browser:

```bash
npx playwright test --project=chromium
```

Run headed mode:

```bash
npx playwright test --headed
```

Run tagged tests:

```bash
npx playwright test --grep @smoke
```

---

## 🧾 Reports & Debugging

| Type        | Location       | Description                       |
| ----------- | -------------- | --------------------------------- |
| HTML Report | `reports/`     | Interactive test execution report |
| Screenshots | `screenshots/` | Captured on failures              |
| Videos      | `videos/`      | Execution recordings              |
| Traces      | `trace/`       | Step-by-step debugging traces     |

View report:

```bash
npx playwright show-report
```

---

## 🧩 Framework Customization

To extend the framework:

* Add new pages inside `pages/`
* Create new test suites in `tests/`
* Reuse fixtures from `fixtures/`
* Add utilities in `utils/`
* Update environment settings in `config/`

---

## 🚀 CI/CD Integration

The framework supports automated execution in CI pipelines and can be integrated with GitHub Actions for continuous testing.

---

## 👤 Author

Shubham Pareek
QA Automation Engineer | TypeScript | Playwright | Modern UI Automation
