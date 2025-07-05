# 🚀 Automation Portfolio

This repository showcases end-to-end automation test frameworks and projects that simulate my experience in QA automation. It's built using modern tools and industry practices.

---

## 🔧 Tools & Frameworks Used

- **Selenium** – Web UI automation
- **Playwright (Python)** – Modern browser automation
- **Pytest** – Test execution and reporting
- **Requests** – API automation
- **Robot Framework** – Keyword-driven testing
- **BDD with Behave** – Behavior-driven development

---

## 📁 Folder Structure

automation-portfolio/
├── web-automation/
│ ├── selenium/
│ └── playwright/
├── api-automation/
├── bdd/
├── robot/
├── tests/
└── README.md


---

## ✅ Projects Covered

| Area       | Project Description                                       |
|------------|------------------------------------------------------------|
| Selenium   | Scrape quotes, login tests, e-commerce navigation         |
| Playwright | Login automation, async test handling, UI validation      |
| API        | CRUD tests using `requests` with Pytest                   |
| BDD        | Login scenario using Behave                               |
| Robot      | UI and API testing with reusable keywords                 |

---

## 🧪 Example Test Case

```python
def test_login_valid_user():
    page.goto("https://example.com/login")
    page.fill("input[name='username']", "admin")
    page.fill("input[name='password']", "password")
    page.click("text=Login")
    assert page.text_content("h1") == "Dashboard"
