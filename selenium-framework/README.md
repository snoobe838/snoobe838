# SIS Automation

This project automates sanity and regression test cases for the SIS application using Python, Selenium, and Pytest.  
It includes HTML reporting, email notifications, and retry mechanisms for test stability.

## Project Structure

├── .vscode/                            # VS Code settings and launch configurations
├── config/                             # Environment configurations, secrets, and constants
├── data/                               # Input data files (Excel, CSV, JSON, etc.)
├── downloads/                          # Auto-downloaded files from browser sessions
├── fixtures/                           # Pytest fixtures (driver, HTML reports, setup/teardown)
├── logs/                               # Log files from test executions
├── pages/                              # Page Object Model (POM) files for each module
├── reports/                            # HTML reports, screenshots, and summary files
├── tests/                              # Test cases organized by module or functionality
├── utils/                              # Helper utilities (email, file ops, waits, etc.)
├── conftest.py                         # Global pytest configuration and hooks
├── pytest.ini                          # Pytest configuration (markers, ordering, etc.)
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation

## Prerequisites
Before running the project, ensure you have the following installed:

- Python **3.14+**
- Google Chrome and **ChromeDriver** (for Selenium-based browser automation)
- Git (for cloning the repository)
- Optional: VS Code for convenient development

## 🧩 Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd sis-automation

2. Install dependencies
    pip install -r requirements.txt

## Email Notifications
After test execution, an email is automatically sent with the HTML report attached.  
You can configure SMTP settings in `config/secrets_reader.py`.


## 🧾 Reports and Logs
Type	         Location	                                Description
HTML Reports	reports/html_report/	      Contains detailed HTML reports for each test run
Screenshots	    reports/screenshots/	      Captured automatically on test failures
Logs	        logs/	                      Log files generated during each run
Downloads	    downloads/	                  Files downloaded during test execution

## 🧩 Project Customization

- To extend or modify:
- Add new pages under pages/
- Create corresponding test files in tests/
- Reuse or create new fixtures in fixtures/
- Add helper functions in utils/
- Update configuration under config/
