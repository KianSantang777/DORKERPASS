# DORKERPASS – Advanced Dork Parser in Python 3.11

![Tool Screenshot](https://raw.githubusercontent.com/KianSantang777/DORKERPASS/refs/heads/main/main.png)

DORKERPASS is a fast and efficient dork parser developed with Python 3.11. It automates the process of collecting search engine results based on custom dorks. The tool includes proxy support, user-agent rotation, and multi-threading for high performance.

---

## Features

- Auto switch between multiple search engines (Google, Bing, Yahoo, DuckDuckGo)  
- User-Agent rotation from custom text file  
- Proxy rotation with support for authenticated proxies  
- Multi-threaded scraping (up to 250 threads)  
- Maximum page scraping per query: 100 pages  
- Automatic retries on failed requests (up to 25 attempts)  
- Cache/session cleanup for fresh results  
- SSL certificate verification using `certifi`  

---

## Requirements

- Python 3.11 or higher  

Install the required dependencies:

```
pip install -r requirements.txt
```

---

## Installation & Usage

### On Windows

1. Download and extract the project.
2. Open Command Prompt in the project directory.
3. Install the requirements:
   ```
   pip install -r requirements.txt
   ```
4. Run the script:
   ```
   python dorkparser.py
   ```

### On Linux

1. Clone the repository:
   ```
   git clone https://github.com/KianSantang777/DORKERPASS.git
   cd DORKERPASS
   ```
2. Make sure Python 3.11+ is installed.
3. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the script:
   ```
   python3 dorkparser.py
   ```

Make sure the following files are present:

- `dorks.txt` – List of search queries (dorks)  
- `useragents.txt` – List of user-agent strings  
- `proxies.txt` *(optional)* – Proxy list in either `ip:port` or `ip:port:username:password` format  

---

## Project Structure

```
DORKERPASS/
├── dorkparser.py
├── dorks.txt
├── useragents.txt
├── proxies.txt (optional)
├── requirements.txt
└── README.md
```

---

## Disclaimer

This project is intended for educational and authorized security testing purposes only.  
The author is not responsible for any misuse or illegal activity performed using this tool.

---

© 2025 [KianSantang777](https://github.com/KianSantang777) – All rights reserved.
