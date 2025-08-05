
# InjectionGuardX

**InjectionGuardX** is a user-friendly web injection detection tool built with Flask. It scans individual web pages or full websites for injection vulnerabilities using a dynamic heuristic engine. It provides detailed, interactive reports and supports CSV export.

##  Features

- Detects **SQL**, **LDAP**, **XPath**, and **HTML Injection**
- Dynamic crawling for full-site scans
- Severity-based vulnerability summaries
- Exportable CSV scan reports
- Interactive scan history dashboard
- Built-in educational section with prevention techniques
- Stylish and responsive UI
- Optimized for low false positives using advanced pattern detection

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/injectionguardx.git
cd injectionguardx
````

### 2. Install Dependencies

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install required packages:

```bash
pip install -r requirements.txt
```

> **Note:** Required packages include `Flask`, `requests`, `beautifulsoup4`.

### 3. Run the Application

```bash
python work1.py
```

Visit [http://localhost:5000](http://localhost:5000) in your browser to start scanning.

##  Example Use Case

1. Enter a URL like `https://example.com/login`
2. Choose to scan a single page or the full website
3. View results with severity levels, payloads, and descriptions
4. Export the report as CSV or explore previous scans in the history tab

## 📁 Project Structure

```
.
├── work1.py               # Main Flask app with detection logic
├── static/                # CSS/JS assets (if separated)
├── templates/             # HTML templates (if using Jinja2)
├── README.md              # Project documentation
└── requirements.txt       # Dependencies
```

## 📖 Learn More

Each injection type includes:

* Summary description
* Exploit scenario
* Prevention tips
* OWASP documentation links
* Demo video

