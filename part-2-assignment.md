# Git Assignment Part II

## 1. README

# Country Capital API

This API is built using Python and Flask. It returns the country name when we provide a capital city.

## Requirements
- Python
- Flask
- Uvicorn

## Setup

1. Clone the repository and open the folder.
2. Create a virtual environment.

   ```bash
   python -m venv venv
   ```

3. Activate it.

   ```bash
   venv\Scripts\activate
   ```

4. Install the required packages.

   ```bash
   pip install flask uvicorn
   ```

## API URL

The API can also be used by other projects through this endpoint:

`https://example.com/country-capital/<query-params>`

For example, providing Tokyo should return Japan.

---

## 2. .gitignore

```gitignore
/build/*
*.env
/test-runs/logs/*
*.csv
```

These patterns ignore files inside the root build folder, `.env` files, files inside `test-runs/logs`, and CSV files anywhere in the repository.

---

## 3. Pull Request Description

**Title:** feat/FEAPP-420: Add WhatsApp notifications

**Source branch:** feature/FEAPP-420

**Destination branch:** develop

**WHAT:**

Added an option for customers to receive product updates through WhatsApp along with email notifications.

**WHY:**

Some customers want to receive product updates on WhatsApp as well as email.

**Notes:**

WhatsApp notifications are optional. If a customer provides their WhatsApp number, they should receive notifications on both WhatsApp and email. Existing email notifications should continue to work.

**Reviewers:** Team lead and team members