# Solar Challenge Week 1

This repository contains the setup for the 10 Academy AIM Week 0 challenge.

## Environment Setup

### Prerequisites
- Python 3.8 or higher
- Git

### Steps to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/Ays27/solar-challenge-week1.git
   cd solar-challenge-week1
```
2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Verify setup:
```bash
python --version
```
### Folder Structure
solar-challenge-week1/
├── .github/workflows/ci.yml  # GitHub Actions workflow
├── .gitignore               # Git ignore file
├── requirements.txt         # Python dependencies
├── README.md                # This file
├── data/                    # (Ignored) For cleaned datasets

