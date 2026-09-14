# 🌐 SnapClass — Official Landing Page & REST API

![SnapClass Logo](https://i.ibb.co/YTYGn5qV/logo.png)

A modern, responsive **FastAPI** landing page and REST API gateway for **SnapClass** — AI-Powered Classroom Attendance Recognition.

🔗 **Live Portal**: [https://snappyclass.streamlit.app/](https://snappyclass.streamlit.app/)

---

## ✨ Features

- **📱 100% Mobile & Desktop Responsive**: Fluid typography, responsive grids, and touch-optimized navigation buttons.
- **🎨 SnapClass Palette Styling**: Custom CSS with Google Fonts (*Outfit* & *Climate Crisis*), periwinkle blue (`#E0E3FF`), dark pink (`#EB459E`), and dark purple (`#2E1065`).
- **🎓 Quick App Launchers**: Direct 1-click links to launch the **Student & Teacher Portals** at `https://snappyclass.streamlit.app/`.
- **⚡ Interactive OpenAPI Swagger**: Built-in REST API documentation accessible via `/docs` and ReDoc via `/redoc`.
- **🩺 Health Monitoring Endpoint**: Lightweight REST endpoint at `/api/v1/health` for uptime ping checks.

---

## 🛠️ Tech Stack

- **Framework**: [FastAPI](https://fastapi.tiangolo.com/)
- **ASGI Server**: [Uvicorn](https://www.uvicorn.org/)
- **Templating**: Jinja2 / HTML5 / CSS3 (Fluid Flex & Grid)
- **Deployment Ready**: Render Blueprint (`render.yaml`) & Docker (`Dockerfile`)

---

## 🚀 Quick Start

### 1. Prerequisites
Ensure Python 3.9+ is installed on your machine.

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Landing Page Server
```bash
python main.py
# Or using uvicorn CLI:
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```
Open **`http://localhost:8000`** in your browser.

---

## ☁️ Deployment Guides

### A. Render.com (Recommended)
1. Sign in to [Render Dashboard](https://dashboard.render.com/).
2. Click **New +** $\rightarrow$ **Blueprint** and connect your `SnapClass-LandingPage` repository.
3. Render will automatically read `render.yaml` and deploy your service!

### B. Docker Container
```bash
docker build -t snapclass-landing .
docker run -d -p 8000:8000 snapclass-landing
```

---

## 📂 Project Structure

```
SnapClass-LandingPage/
├── main.py             # FastAPI application and responsive HTML templates
├── requirements.txt     # Python package dependencies
├── Dockerfile           # Docker container configuration
├── render.yaml          # Render.com deployment blueprint
├── .gitignore           # Git ignore file
└── README.md            # Repository documentation
```

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
