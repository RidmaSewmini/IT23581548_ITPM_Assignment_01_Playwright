# Singlish to Sinhala Translator Testing Automation

## 📌 Project Overview
This project focuses on testing a Singlish-to-Sinhala translation system using both manual test cases and automated testing with Playwright.

## 📌 Git Hub Repo
https://github.com/RidmaSewmini/IT23581548_ITPM_Assignment_01_Playwright

## 🎯 Objectives
- Identify failures in Singlish to Sinhala conversion
- Cover 24 Singlish input types
- Automate testing using Playwright
- Record results in Excel

## 🧪 Test Case Design
- Total test cases: 50
- Negative test cases: 50 (focus on failures)
- Covers:
  - Questions
  - Names (Person/Place)
  - Currency, Time, Dates
  - Commands, Requests, Responses
  - Slang, Emojis, Abbreviations
  - English word mixing
  - Spacing, Case sensitivity

## ⚙️ Technologies Used
- Python
- Playwright
- OpenPyXL
- Excel

## 🚀 How to Run

### 1. Install dependencies

pip install playwright openpyxl


### 2. Install browser

python -m playwright install


### 3. Run automation

python IT23581548_test_automation.py --excel "IT23581548_Test_cases.xlsx" --url "https://www.pixelssuite.com/chat-translator
"


## 📊 Output
- Excel file updated automatically
- Includes:
  - Actual Output
  - Pass/Fail status

## ❗ Observations
- Some failures observed in:
  - Place name conversion
  - Currency formats
  - Abbreviations
  - Case sensitivity
  - Missing spaces
  - English word handling

## 📁 Project Structure

IT23581548/
│
├── IT23581548_Test_cases.xlsx
├── IT23581548_test_automation.py
├── README.md
└── instructions.txt


## ✅ Conclusion
The system performs well for basic inputs but struggles with complex, mixed, and non-standard Singlish inputs.

Automation helped efficiently validate large number of test cases.