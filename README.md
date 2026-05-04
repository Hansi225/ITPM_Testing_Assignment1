# IT3040 Assignment 1 - Singlish Transliteration Testing

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome browser

## Installation Steps
Run these commands one by one in Command Prompt:

pip install -U pip
pip install playwright openpyxl
playwright install

## How to Run Tests
Run this command in Command Prompt from inside the test_automation folder:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## What the Script Does
- Opens the chat translator website automatically
- Types each Singlish input from the Excel file
- Records the actual Sinhala output from the app
- Compares it with the expected output
- Marks each test case as Pass or Fail
