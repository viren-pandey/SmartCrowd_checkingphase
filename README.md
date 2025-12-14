
# 🚦 SmartCrowd – AI-Powered Crowd Intelligence Platform

SmartCrowd is an **AI-powered real-time crowd monitoring system** that detects people from live camera feeds, estimates crowd density, and visualizes risk levels to improve **public safety in crowded spaces**.

Built for **smart cities, campuses, events, stations, and malls**.

---

<marquee>Working url https://smartcrowd.netlify.com Click Here </marquee>

## ✨ Key Features

* 🎥 **Live Camera Detection**
  Real-time people detection using YOLO (Ultralytics)

* 📊 **Crowd Density Analysis**
  Automatically classifies density as **Low / Medium / High / Danger**

* 📈 **Live Density Trend Graph**
  Visualizes crowd changes over time

* 🚨 **Risk Awareness**
  Helps prevent stampedes, congestion, and unsafe overcrowding

* 🌐 **Modern Web Interface**
  Clean landing page + live detection page (React + Vite)

* ☁️ **Cloud-Deployed Backend**
  Hosted on Hugging Face Spaces (FastAPI)

---

## 🏗️ Tech Stack

### Frontend

* React + TypeScript
* Vite
* Tailwind CSS
* React Router
* Recharts (graphs)
* Axios

### Backend

* FastAPI
* YOLOv8 (Ultralytics)
* OpenCV (headless)
* NumPy
* Python

### Deployment

* Frontend: Netlify / Vercel
* Backend: Hugging Face Spaces

---

## 📁 Project Structure

```text
SmartCrowd/
├── backend/
│   ├── app.py
│   ├── detection.py
│   ├── models.py
│   ├── database.py
│   ├── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/
│   │   │   └── pages/
│   │   ├── api.js
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── index.css
│   ├── index.html
│   └── package.json
│
└── README.md
```

---

## 🚀 How It Works

1. User opens **Live Detection** from frontend
2. Browser requests **camera access**
3. Video frames are sent to backend
4. Backend:

   * Detects people
   * Counts crowd
   * Computes density level
   * Returns annotated frame
5. Frontend:

   * Displays live feed
   * Shows density bar + trend graph

---

## 🧪 Run Locally

### Backend

```bash
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
uvicorn app:app --reload
```

Backend runs at:

```
http://127.0.0.1:8000
```

---

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🌍 Live Demo

* **Frontend:**
  👉 [https://smartcrowd.netlify.app](https://smartcrowd.netlify.app) 

* **Backend API:**
  👉 [https://virenn77-smartcrowd-backend.hf.space](https://virenn77-smartcrowd-backend.hf.space)

---

## 📌 Use Cases

* 🚉 Railway stations & metros
* 🎶 Concerts & festivals
* 🏫 Campuses & hostels
* 🏟️ Stadiums
* 🏙️ Smart city surveillance

---

## 🛠️ Future Improvements

* Multi-camera support
* Heatmap-based density visualization
* Alert notifications (SMS / dashboard)
* Edge deployment (Jetson / Raspberry Pi)
* Authentication & role-based access

---

## 👤 Author

**Viren Pandey**
Computer Science (AI/ML)
🔗 GitHub: [https://github.com/viren-pandey](https://github.com/viren-pandey)

---

## ⭐ Why This Project Matters

Crowd disasters are preventable.
SmartCrowd focuses on **early detection instead of damage control**.

> *“Better awareness today prevents tragedy tomorrow.”*

Just say the word.

