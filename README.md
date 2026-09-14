# 🌐 SnapClass Landing Page & REST API Service

![SnapClass Logo](https://i.ibb.co/YTYGn5qV/logo.png)

A high-performance, responsive **FastAPI** landing page and REST API service for **SnapClass** — AI-Powered Classroom Attendance Recognition.

---

## ✨ Features

- **📱 100% Responsive Design**: Optimized across mobile phones, tablets, and desktop displays.
- **🎨 Custom Styling**: Styled with Outfit & Climate Crisis fonts, periwinkle blue (`#E0E3FF`), dark pink (`#EB459E`), and dark purple (`#2E1065`).
- **🎓 Quick App Launchers**: Direct 1-click shortcuts to launch Student & Teacher Portals.
- **⚡ OpenAPI Swagger Docs**: Built-in interactive API documentation at `/docs` and ReDoc at `/redoc`.
- **🩺 Health Check API**: REST endpoint at `/api/v1/health` for monitoring.

---

## 🚀 Quick Start

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run the Application
```bash
python main.py
# or using uvicorn:
uvicorn main:app --reload --port 8000
```
Open **`http://localhost:8000`** in your browser.

---

## ☁️ Deployment

### Render.com
Connect this GitHub repository to Render as a **Web Service** or **Blueprint**:
- **Build Command**: `pip install -r requirements.txt`
- **Start Command**: `uvicorn main:app --host 0.0.0.0 --port $PORT`

---

## 📄 License
Distributed under the MIT License.
