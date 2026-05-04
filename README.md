IT23589322 - Damsith V S

Singlish to Sinhala Translator – Test Automation (Playwright)
Setup Instructions

1. Install Python
Python 3.11 or 3.12 is required.

2. Install dependencies
pip install -r requirements.txt

3. Install Playwright browsers
playwright install

4. Run the tests
cd /d D:\test_automation
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
