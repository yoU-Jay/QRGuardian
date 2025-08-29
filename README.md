# QRGuardian

QRGuardian scans and detects malicious QR codes, protecting users from phishing, malware, and suspicious links. It’s a simple, fast tool for safer QR code use.

---

## Features
- Decode QR codes from images
- Detect if the QR contains text, a URL, or something else
- Run rule-based risk scoring for suspicious links
- (Optional) AI-powered risk explanations
- Easy to extend and customize

---

## Project Structure
qr-risk-analyzer/
├── app/
│ ├── init.py
│ ├── main.py # Entry point (Streamlit or Flask)
│ ├── qr_decoder.py # QR decoding logic
│ ├── classifier.py # Classify QR content
│ ├── risk_engine.py # Rule-based risk scoring
│ ├── ai_explainer.py # AI explanation (optional)
│ └── utils.py # Helper functions
│
├── static/ # Static files (for Flask, optional)
├── templates/ # HTML templates (for Flask, optional)
│
├── test_qrs/ # Sample test QR images
├── tests/ # Unit tests (e.g., test_qr_decoder.py)
│
├── .env # API keys, secrets (ignored by git)
├── .gitignore
├── requirements.txt # Dependencies
├── run.py # Launcher script
└── README.md


---

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/yoU-Jay/QRGuardian.git
   cd QRGuardian

2. Create a virtual environment:
   python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

4. Run the application:
   python run.py


