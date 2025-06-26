 THINGS TO INSTALL
Python
You need Python 3.8 or newer (Python 3.10+ recommended).
Download: https://www.python.org/downloads/

 Pip
Pip is included with modern Python.
To check:
python --version
pip --version

Required Python Packages
Open a terminal (cmd, PowerShell, or terminal) and run:

pip install undetected-chromedriver selenium requests

If you get errors, try:

python -m pip install --upgrade pip
python -m pip install undetected-chromedriver selenium requests

Google Chrome
You must have Google Chrome installed (the script uses Chrome).
Download: https://www.google.com/chrome/

5. ChromeDriver
Download the ChromeDriver that matches your Chrome version:
https://chromedriver.chromium.org/downloads
Place the chromedriver.exe in G:\chromedriver-win64\ as you specified.

6. (Optional) AdGuard Extension
If you want to use AdGuard, download the .crx file and set the path in the script.
Not required for basic operation.

7. Discord Webhook
You must have a valid Discord webhook URL (which you already have).

8. (Optional) Virtual Environment
For best practice, use a virtual environment:
python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On Linux/Mac
pip install undetected-chromedriver selenium requests

9. Run the Script
Save the script as sms_scraper.py
Run:
python sms_scraper.py

Summary Table
Dependency	Install Command / Link
Python 3.8+	python.org/downloads
pip	Included with Python
undetected-chromedriver	pip install undetected-chromedriver
selenium	pip install selenium
requests	pip install requests
Google Chrome	google.com/chrome
ChromeDriver	chromedriver.chromium.org
