# Reemini Clone App (AI Photo Enhancer)

এটা একটি Reemini এর মতো ছবি রিস্টোর বা AI দিয়ে ফটো পরিষ্কার করার অ্যাপ। এই প্রজেক্টটি মূলত দুইটি অংশে তৈরি:
1. 🧠 Backend (FastAPI + GFPGAN)
2. 📱 Frontend (Kodular/MIT App Inventor)

---

## 📦 Features

- কম রেজোলিউশনের ছবি থেকে হাই-কোয়ালিটি ছবি তৈরি
- GFPGAN দিয়ে AI ফেস রিস্টোরেশন
- REST API (FastAPI) দিয়ে ছবি আপলোড ও প্রসেসিং
- মোবাইল অ্যাপ ইন্টিগ্রেশন (Kodular বা Android Studio)

---

## ⚙️ Technologies Used

- Python 3.10+
- FastAPI
- GFPGAN
- Uvicorn
- PIL (Pillow)
- Kodular/MIT App Inventor (Frontend)

---

## 🚀 Installation & Run (Backend)

```bash
git clone https://github.com/your-username/reemini-clone.git
cd reemini-clone
pip install -r requirements.txt
uvicorn main:app --reload
