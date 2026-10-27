# 🚀 PROJECT QUANTUM-GRAV: Hypersonic Cockpit & Telemetry Backend

Welcome to the official backend repository for **PROJECT QUANTUM-GRAV**. This system bridges an advanced Streamlit-based hypersonic cockpit UI with a production-grade FastAPI server and a cloud-hosted Supabase PostgreSQL database.

---

## 🛠️ Tech Stack & Architecture

- **Frontend / UI:** Streamlit (CRT Military-Green Cockpit Interface)
- **Backend Server:** FastAPI (Python) running on Vercel Serverless Functions
- **Database:** Supabase PostgreSQL (`starship_telemetry` table for live telemetry data)
- **Physics Engine:** Custom Quantum-Gravitational & Relativistic Calculations (`core/physics_engine.py`)

---

## 📂 Project Structure

```text
PROJECT_QUANTUM_GRAV/
│
├── core/
│   └── physics_engine.py      # Relativistic & Warp physics calculation engine
├── app.py                     # FastAPI backend + Streamlit cockpit interface
│
├── requirements.txt           # Python dependencies for Vercel deployment
├── vercel.json                # Vercel serverless configuration file
└── README.md                  # Project documentation
