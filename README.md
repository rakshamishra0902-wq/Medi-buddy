🩺 Medi-Buddy

📌 Description

Medi-Buddy is a pharmacogenomics-based web application that analyzes a user's genetic data to provide personalized medication insights.

Users upload their genetic file (VCF format), and the system processes it using backend analysis to predict drug response, dosage, and safety.

---

🚀 Features

- 📁 Upload genetic files (VCF format)
- 🧬 Extract gene variants and pharmacogenomic data
- ⚠️ Drug risk detection (Toxic / Ineffective / Safe)
- 💊 Dosage recommendations
- 🤖 AI-based alternative medicine suggestions
- 📊 Result dashboard
- 📄 Clinical report generation (PDF)

---

🛠️ Tech Stack

Frontend

- React + Vite

Backend

- Handles genetic data processing and analysis
- File validation and parsing (VCF files)
- Pharmacogenomic analysis using CPIC guidelines
- Drug risk prediction engine
- Dosage recommendation system
- Integration with AI/LLM for alternative medicines
- PDF report generation

---

⚙️ How It Works

1. Upload genetic file (VCF)
2. Backend validates file format and data
3. Extract genetic variants and relevant genes
4. Analyze drug response using pharmacogenomic rules
5. Classify drugs:
   - Safe ✅
   - Toxic ❌
   - Ineffective ⚠️
6. Generate:
   - Dosage recommendations
   - Alternative medicines (AI)
7. Display results on dashboard
8. Generate clinical PDF report

---

🧩 System Flow

User → Upload File → Backend Processing → Analysis Engine → Results Dashboard → Report Generation

---

▶️ Installation

Frontend

git clone <your-repo-link>
cd medi-buddy
npm install
npm run dev

Backend (if applicable)

cd backend
npm install   # or pip install -r requirements.txt
npm start     # or python app.py

---

📊 Output

- Drug safety classification
- Personalized dosage suggestions
- AI-based alternative medications
- Clinical PDF report

---

⚠️ Disclaimer

This project is for educational and research purposes only and should not be used as a substitute for professional medical advice.

---

🤝 Contributing

Pull requests are welcome. Feel free to improve documentation, features, or UI.

---