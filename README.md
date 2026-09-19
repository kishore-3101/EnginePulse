# EnginePulse - Digital twin and Live health monitoring system for aerospace vehicle engines

An digital twin and live health monitoring system of aerospace vehicle engines which predicts live health of engines using raw sensor inputs using ML model.

---

## Quick Start

### 1. Frontend Setup
```bash
npm install
npm run dev      # Starts local dev server at http://localhost:5173
npm run build    # Builds production bundle
```

### 2. Backend Setup
```bash
pip install fastapi uvicorn scikit-learn pandas numpy scipy
python backend/main.py   # Starts FastAPI server at http://localhost:8000
```

### 3. Model Evaluation
```bash
python evaluate_ps2.py   # Runs PS2 model evaluation runner
```
