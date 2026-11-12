# Jan Gabriel Chavez

**Database Management & Workflow Automation Specialist**  
*Makati / Parañaque City, Metro Manila, Philippines*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jgmchavez/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jangabrielchavez1@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/jgmchavez-22)

---

### 💡 About Me

I am an IT and data professional specializing in **Python workflow automation**, **Business Intelligence reporting**, and **database management**. Currently serving as a **Database Management and Reports Specialist** at G9Outsourcing Corp., I engineer data tools and automated scripts that eliminate manual operational bottlenecks, protect CRM data integrity, and accelerate reporting speed.

My background bridges technical problem-solving with rigorous compliance and systems administration—having managed strict multi-agency regulatory filing calendars as a Paralegal and administered hybrid Windows/macOS network environments as an IT Specialist.

---

### ⚡ Core Capabilities

- **Workflow Automation & Scripting:** Developing Python scripts, web scrapers, and AI/LLM integrations that automate high-touch manual workflows (saving 4–6 operational hours weekly).
- **Business Intelligence & Analytics:** Designing unified dashboards in Power BI and Looker Studio to consolidate multi-source operational data, cutting manual reporting time by an estimated 30%.
- **Data Quality & CRM Validation:** Running software QA checks and structured schema audits on live CRM databases to guarantee clean, reliable records.
- **Systems & Infrastructure Support:** Administering dual-OS (Windows/macOS) workstations, commercial Wi-Fi, and structured cabling for zero-downtime office operations.
- **Compliance & Operations:** Tracking and coordinating 15–20 simultaneous statutory filings across government bodies (SEC, DOJ, BI, DOLE).

---

### 🛠️ Technical Toolkit

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages & Scripting** | Python (3.9–3.13), SQL, HTML5, CSS3, JavaScript (ES6+), Bash |
| **Data & BI Tools** | Power BI, Looker Studio, Power Query, SheetJS, ExcelJS, CRM Systems |
| **Software Engineering & CI/CD** | GitHub Actions Matrix CI, Docker, Pytest, Mypy, Ruff, PEP 621 / Hatchling Packaging |
| **Automation & AI** | Web Scraping (`BeautifulSoup`, `requests`), LLM Integration, Custom HTTP/CORS Proxies |
| **IT & Systems** | Windows Administration, macOS Support, Network Cabling, Commercial Wi-Fi, Hardware Diagnostics |
| **Certifications & Compliance** | Certified in Cybersecurity (ISC2 CC), Certified Paralegal (CePL), Python for Data & AI (Uplift Code Camp) |

---

### 🚀 Featured Work

#### [normcorp // Deterministic Legal Entity Normalizer & Blocking Engine](https://github.com/jgmchavez-22/normcorp)
*High-Throughput Open-Source CLI & Library*  
[![CI](https://github.com/jgmchavez-22/normcorp/actions/workflows/ci.yml/badge.svg)](https://github.com/jgmchavez-22/normcorp/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12%20%7C%203.13-blue)](https://www.python.org/)

- **The Problem:** Probabilistic fuzzy matching (Levenshtein, Splink, Dedupe) across enterprise company lists explodes in $O(N^2)$ quadratic complexity and triggers false-positive entity merges.
- **The Solution:** Engineered a zero-dependency, streaming Python library and CLI operating in constant $O(1)$ memory. Normalizes multi-jurisdictional legal suffixes across US, UK, Singapore (ACRA), DACH, France, Spain, Italy, Malaysia, and Philippines corporate structures, generates 4-character phonetic Soundex blocking keys, and injects dynamic Excel lookup formula helpers (`=LEFT(B2, 25)`).
- **Tech Stack:** Python 3.10–3.13, Hatchling, OpenPyXL, Pytest, Ruff, Mypy, GitHub Actions Matrix.

#### [tabula-guard // Tabular Schema Drift & PII Auditor for Pre-Commit](https://github.com/jgmchavez-22/tabula-guard)
*Pre-Commit Hook & Security/Data Governance CLI*  
[![CI](https://github.com/jgmchavez-22/tabula-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/jgmchavez-22/tabula-guard/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Coverage: 90%](https://img.shields.io/badge/coverage-90%25-brightgreen)](https://github.com/jgmchavez-22/tabula-guard)

- **The Problem:** Accidental commits of raw customer datasets or CRM exports with unmasked PII (emails, phone numbers, credit cards, tax IDs) trigger immediate compliance violations (GDPR, CCPA, Philippine Data Privacy Act), while silent schema drift breaks downstream analytics.
- **The Solution:** Engineered a zero-dependency pre-commit hook and CLI auditor that inspects staged CSV/TSV files, validates credit cards via the Luhn algorithm (zero false positives), validates schema contracts, enforces maximum null rates, and blocks contaminated commits.
- **Tech Stack:** Python 3.10–3.13, Pre-Commit, Hatchling, Pytest, Ruff, Mypy, GitHub Actions.

#### [Match Link // Company Name Templater](https://github.com/jgmchavez-22/Match-Link)
*Automated Legal Entity Normalization & Excel Lookup Helper Generator*  
[![CI](https://github.com/jgmchavez-22/Match-Link/actions/workflows/ci.yml/badge.svg)](https://github.com/jgmchavez-22/Match-Link/actions)
[![Coverage: 94%](https://img.shields.io/badge/coverage-94%25-brightgreen)](https://github.com/jgmchavez-22/Match-Link)
[![Docker](https://img.shields.io/badge/Docker-ready-2496ED?logo=docker&logoColor=white)](https://github.com/jgmchavez-22/Match-Link)

- **The Problem:** Reconciling customer, vendor, or lead lists across CRM databases and accounting platforms frequently fails exact matching (VLOOKUP/XLOOKUP) due to inconsistent corporate suffixes (PTE LTD, LLC, Corp, Private Limited) and non-alphanumeric noise.
- **The Solution:** Built a production-hardened FastAPI and Pandas web application featuring bounded in-memory LRU/TTL caching (eliminating memory exhaustion), parameterized Pytest test suite (94% coverage), Docker containerization, and native Excel formula helpers.
- **Tech Stack:** Python 3.10–3.13, FastAPI, Uvicorn, Pandas, OpenPyXL, Docker, Pytest, GitHub Actions.

#### [ShelfIQ // Perishable Spoilage Prediction & Restock Engine](https://github.com/jgmchavez-22/ShelfIQ)
*Machine Learning Decision Support System (Uplift Code Camp Capstone)*  
[![Streamlit](https://img.shields.io/badge/Streamlit-1.35+-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://github.com/jgmchavez-22/ShelfIQ)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Random%20Forest-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://github.com/jgmchavez-22/ShelfIQ)
[![Python: 3.9+](https://img.shields.io/badge/Python-3.9+-blue)](https://www.python.org/)

- **The Problem:** Mid-size grocers and chilled-goods distributors in the Philippines face heavy inventory shrinkage during heat spikes and cold-chain transit breakdowns, with revenue dropping to zero when goods spoil unpredicted.
- **The Solution:** Developed a collaborative Streamlit decision support application. Engineered the core Spoilage Prediction Engine (pages/rul_model.py) using a Random Forest classifier to calculate batch Remaining Useful Life (RUL), segment inventory into four urgency action tiers, and trigger automated markdown pricing and upcycling rules.
- **Tech Stack:** Python, Scikit-learn, Random Forest, Streamlit, Pandas, NumPy.
- **Attribution:** Collaborative capstone with [Ruth](https://github.com/mrebbuan-8), [Euie David](https://github.com/euiedavid), and [ejrevecho](https://github.com/ejrevecho); original upstream at [mrebbuan-8/ShelfIQ](https://github.com/mrebbuan-8/ShelfIQ).

#### [EOC Buff // End of Campaign Report Generator](https://github.com/jgmchavez-22/EOC-Break-FRVNT)
*Full-Stack Operational Reporting Utility — G9 Outsourcing Corp.*  
[![Python: 3.8+](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://github.com/jgmchavez-22/EOC-Break-FRVNT)
[![Engine: SheetJS & ExcelJS](https://img.shields.io/badge/Engine-SheetJS%20%7C%20ExcelJS-green)](https://github.com/jgmchavez-22/EOC-Break-FRVNT)
[![Proxy: Native HTTP](https://img.shields.io/badge/Proxy-Native%20Python%20HTTP-orange)](https://github.com/jgmchavez-22/EOC-Break-FRVNT)
- **The Problem:** Operations teams spent hours manually extracting and recalculating campaign metrics from live Google Sheets into client Excel spreadsheets.
- **The Solution:** Engineered a local Python HTTP proxy (`server.py`) with domain-filtering security to bypass browser CORS constraints, paired with an interactive frontend (`EOC_Report_Generator.html`) that parses SheetJS/ExcelJS data into formatted, production-ready workbooks.
- **Tech Stack:** Python, HTML5, SheetJS, ExcelJS, Google Docs/Sheets API.

---

### 📜 Professional Timeline

- **Database Management and Reports Specialist** — *G9Outsourcing Corp.* (Feb 2026 – Present)
- **Paralegal** — *Duran & Duran-Schulze Law* (July 2025 – Nov 2025)
- **IT Specialist** — *TMC Travel and Tours* (July 2023 – July 2024)
- **Sales and Marketing Associate** — *TMC Travel and Tours* (Jan 2022 – July 2023)
- **BSBA in Marketing Management** — *University of Santo Tomas* (2020 – 2024)

---

### 📬 Connect With Me

- **Email:** [jangabrielchavez1@gmail.com](mailto:jangabrielchavez1@gmail.com)
- **LinkedIn:** [linkedin.com/in/jgmchavez](https://www.linkedin.com/in/jgmchavez/)
- **GitHub:** [github.com/jgmchavez-22](https://github.com/jgmchavez-22)
