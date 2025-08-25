# 🛒 E-commerce Website with Recommender System

📌 A full-stack mini e-commerce platform with an integrated **AI recommender system** suggesting products based on user activity and preferences.

---

## 🚀 Features
- User authentication (login/signup)  
- Browse products & add to cart  
- AI-based product recommendations  
- Admin dashboard for managing products  
- Responsive design  

---

## 🛠️ Tech Stack
- Backend: **Flask (Python)** or Django  
- Frontend: **React.js / HTML, CSS, JS**  
- Database: SQLite / MySQL  
- AI Recommender: **Scikit-learn**  

---

## 📂 Project Structure
📁 ecommerce-recommender
┣ 📂 backend/ # Flask or Django backend
┣ 📂 frontend/ # React.js frontend
┣ 📜 models.py # Database models
┣ 📜 requirements.txt # Python dependencies
┣ 📜 package.json # Frontend dependencies
┗ 📜 README.md

---

## ▶️ How to Run
```bash
### 1️⃣ Clone the Repository
git clone https://github.com/username/ecommerce-recommender.git
cd ecommerce-recommender

2️⃣ Backend Setup (FastAPI)
Go to the backend folder:
cd backend

python -m venv .venv
.venv\Scripts\activate   # Windows
source .venv/bin/activate  # Linux/Mac

pip install -r requirements.txt

uvicorn main:app --reload

📍 API will be available at:
http://127.0.0.1:8000

3️⃣ Frontend Setup (React + Vite)
Go to the frontend folder:
cd ../frontend

npm install

npm run dev

cd ../frontend

npm install

npm start

Open in browser
