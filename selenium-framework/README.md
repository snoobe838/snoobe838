# SIS Automation

This project automates sanity and regression test cases for the SIS application using Python, Selenium, and Pytest.  
It includes HTML reporting, email notifications, and retry mechanisms for test stability.

## Project Structure
<img width="938" height="347" alt="image" src="https://github.com/user-attachments/assets/52d45f23-376a-4014-b1ee-c44c5e2d80e4" />

<img width="958" height="362" alt="image" src="https://github.com/user-attachments/assets/9c372479-327b-4cb5-9282-cdafd5ee9f24" />


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
