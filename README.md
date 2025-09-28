# BhashaNow – Transliterations Tool for Street Signs  

### 📌 Overview  
**BhashaNow** is a smart transliteration app designed to make navigation across India’s diverse linguistic landscape easier. India recognizes **22 official languages with multiple scripts**, and street signs often display a mix of local languages, Hindi, and English. This creates difficulties for travelers, migrants, and even locals.  

Unlike translation (which conveys meaning), **transliteration preserves sound**. For example, “Simon & George Cleaners” becomes **सायमन अँड जॉर्ज क्लीनर्स** in Marathi – same pronunciation, different script. This ensures that names and places are not lost in translation.  

---

### 🚀 Features  
- **Source & Target Language Selection** – Choose the scripts you want to convert between.  
- **Camera / Image Upload** – Point your smartphone camera at a street sign or upload an image.  
- **OCR Integration** – Detects and extracts text from signboards using Indic OCR models.  
- **Smart Transliteration Engine** – Converts the recognized text phonetically into the chosen script.  
- **Overlay / In-app Display** – View transliterated text over the original image or as plain text.  
- **Offline/Online Support** – Runs on-device with lightweight models, with optional cloud fallback.  

---

### 🛠️ Technical Approach  
- **Image Capture & Preprocessing** – OpenCV for brightness/contrast adjustments.  
- **Text Detection** – Scene-text recognition for signboards.  
- **OCR (Recognition)** – Tesseract/Indic-OCR for Unicode text extraction.  
- **Script Identification** – Detects which script is present (Devanagari, Tamil, Telugu, etc.).  
- **Transliteration Engine** – Uses libraries like `indic-transliteration` or Unicode mappings.  
- **Frontend/Backend** – Web demo with HTML/CSS/JS + Flask/Node.js backend. Future scope: Android/iOS app.  

---

### 🌍 Impact & Benefits  
- **Cultural Bridge** – Helps citizens and travelers “read” local signboards in their own script.  
- **Inclusivity** – Supports migrants, students, and others who struggle with unfamiliar scripts.  
- **Heritage Preservation** – Promotes appreciation of India’s script diversity.  
- **Practical Utility** – Improves navigation, tourism, emergency response, and civic accessibility.  

---

### 📊 Feasibility  
- Smartphones + 5G/4G penetration ensure accessibility.  
- OCR models are lightweight (<100MB), enabling offline use.  
- Aligned with government initiatives like **Bhashini** for digital inclusivity.  

---

### 📚 References & Inspirations  
- [Indic OCR Project](https://github.com/tesseract-ocr/langdata)  
- Google Lens / JioTranslate (text translation tools)  
- Research: Gunna et al. (2022) on deep-learning for Indian script recognition  
- Indian Railways signage language policy (Indian Express)  

---

### 👥 Team  
Developed by **Team EPYC** for **Smart India Hackathon 2025**.  

---

🔮 *Future Scope*: Expand to full mobile app, integrate speech-to-text, and add real-time AR overlays.  
