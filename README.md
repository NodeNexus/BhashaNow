# BhashaNow 🌐🔤

**BhashaNow** is an AI-powered Multilingual Optical Character Recognition (OCR) and Text Transliteration web application designed to bridge language barriers across Indic languages. Built using Python, Flask, and EasyOCR, it allows users to upload images, extract text in real-time, and transliterate script between supported Indian languages seamlessly.

---

## ✨ Key Features

- **Multi-Language OCR**: Extract text from images and documents across multiple Indic scripts including Hindi, Marathi, Nepali, Urdu, Telugu, Kannada, Bengali, and Assamese.
- **Real-Time Camera Integration**: Capture live images directly from your device camera for instant text detection.
- **Script Transliteration**: Convert text between different Indic writing systems with high fidelity.
- **Secure Authentication**: Supports traditional password login as well as web-based passkey registration and authentication.
- **Credit / Token System**: Integrated token management for user query limits and usage tracking.

---

## 🌐 Supported Languages

| Language | Language Code | Engine |
| :--- | :---: | :---: |
| **Hindi** | `hi` | EasyOCR |
| **Marathi** | `hi` | EasyOCR |
| **Nepali** | `hi` | EasyOCR |
| **Urdu** | `ur` | EasyOCR |
| **Telugu** | `te` | EasyOCR |
| **Kannada** | `kn` | EasyOCR |
| **Bengali** | `bn` | EasyOCR |
| **Assamese** | `bn` | EasyOCR |

---

## 🛠️ Tech Stack

- **Backend**: Python 3.x, Flask Web Framework
- **OCR Engine**: EasyOCR (PyTorch-backed deep learning model)
- **Database**: SQLite (`database.db`)
- **Frontend**: HTML5, CSS3, JavaScript, Jinja2 Templates

---

## 🚀 Installation & Setup

### Prerequisites
- Python 3.9+ installed on your system.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NodeNexus/BhashaNow.git
   cd BhashaNow
   ```

2. **Create a Virtual Environment** (Optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize Database & Run Application**:
   ```bash
   python initialise.py
   python app_Transliterate.py
   ```

5. **Open Application**:
   Navigate to `http://127.0.0.1:5000` in your web browser.

---

## 📄 Project Structure

```
BhashaNow/
├── app_Transliterate.py      # Main Flask application & routes
├── initialise.py             # Database initialization & EasyOCR setup
├── database.db               # SQLite database store
├── requirements.txt          # Python dependencies
├── static/                   # Static assets (images, QR codes, icons)
└── templates/                # Jinja2 HTML templates
    ├── landing.html          # Homepage
    ├── text-transliteration.html # OCR & transliteration dashboard
    ├── camera.html           # Live camera OCR scanner
    ├── signup.html           # User registration
    └── passkey_login.html    # Passkey authentication page
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).