# 🚀 Progress Tracking & Analytics Tool

[![Python](https://img.shields.io/badge/python-3.7%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/selenium-webdriver-green)](https://www.selenium.dev/)


A powerful **Python** application that automates web data extraction, logs progress over time into Excel files, and displays a real-time overlay with detailed stats — all designed to help you analyze your growth efficiently.

---

## ✨ Features

- **Automated Web Data Extraction**  
  Seamlessly logs into web dashboards using Selenium with saved session cookies to scrape progress data headlessly.

- **Robust Data Logging & Analytics**  
  Stores timestamped gains into Excel spreadsheets via `openpyxl`, calculating rates over multiple intervals (2.5, 5, 12 minutes).

- **Real-Time Overlay GUI**  
  Always-on-top, borderless Tkinter window updates every second with current stats, recent gains, expected progress rates, and averages.

- **Multi-Monitor Awareness**  
  Detects and positions the overlay intelligently when multiple monitors are connected.

- **Session Persistence with Cookies**  
  Enables manual login and cookie saving to avoid repeated authentications.

---

## 🛠 Technologies Used

| Technology         | Purpose                          |
|--------------------|---------------------------------|
| Python 3           | Core programming language        |
| Selenium WebDriver | Web automation and scraping      |
| WebDriver Manager  | Automatic ChromeDriver handling  |
| Tkinter            | GUI overlay                      |
| OpenPyXL           | Excel file creation & updates    |
| Threading          | Concurrent background tasks      |
| ScreenInfo         | Multi-monitor detection          |
| Pickle             | Cookie serialization             |

---

## 🚀 Installation & Setup

1. Make sure you have Python 3 and selenium webdriver-manager with chrome driver installed.

2. Run the script `Scraper.py`
3. On first run, a Chrome window will open for manual login.
4. After logging in, press Enter in the terminal to save cookies.
5. Provide a filename (without extension) for the Excel log file.
6. The script will begin fetching progress data and display a live overlay 
window with detailed stats (by default right bottom screen of ur second left monitor).



## ⚠️ Disclaimer

Feel free to use or modify this code, in whole or in part — it was created for educational purposes and to demonstrate automation, GUI, and data logging techniques in Python.

The program is designed to periodically extract and display statistics from a user-accessible web dashboard while minimizing the frequency of requests. However, it still performs automated site visits at intervals. Use it responsibly and at your own discretion.

The author is not responsible for any consequences resulting from misuse or violation of third-party site policies.



