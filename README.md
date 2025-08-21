# QRGuardian
QR Guardian scans and detects malicious QR codes, protecting users from phishing, malware, and suspicious links. A simple, fast tool for safer QR code use.

qr-risk-analyzer/
│
├── app/                           # Core application logic
│   ├── __init__.py
│   ├── main.py                    # Streamlit or Flask entry point
│   ├── qr_decoder.py              # QR decoding logic
│   ├── classifier.py              # Type classification (URL, text)
│   ├── risk_engine.py             # Rule-based risk scoring
│   ├── ai_explainer.py            # Gemini AI risk explainer (optional)
│   └── utils.py                   # Shared helper functions
│
├── static/                        # Static files (optional for Flask)
│   └── ...
│
├── templates/                     # HTML templates (for Flask, if needed)
│   └── ...
│
├── test_qrs/                      # Sample test QR images
│   └── ...
│
├── tests/                         # Unit tests (if writing any)
│   └── test_qr_decoder.py
│
├── .env                           # API keys, secrets (add to .gitignore)
├── .gitignore
├── README.md
├── requirements.txt
└── run.py                         # Entrypoint to launch the app
