# FLOWCAST AI

FLOWCAST AI is a cutting-edge, local-first transportation intelligence platform. It features real-time route prediction, weather forecasting, toll & road closure simulations, and interactive MapLibre visualizations.

## Prerequisites

Before running the application, ensure you have the following installed on your system:
- **Node.js** (v18 or higher)
- **Python** (v3.8 or higher)

---

## 1. Running the Backend (Python / FastAPI)

The backend handles the AI prediction models, route heuristic calculations, and real-time Overpass/Weather API fetching.

1. **Open a new terminal window.**
2. **Navigate to the backend directory:**
   ```bash
   cd "d:/College Projects/FlowCastAi/backend"
   ```
3. **Activate the virtual environment:**
   ```bash
   # On Windows (PowerShell/CMD):
   ..\venv\Scripts\activate
   ```
4. **Start the Uvicorn server:**
   ```bash
   uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload
   ```
   *The backend will now be running at `http://localhost:8000`.*

---

## 2. Running the Frontend (React / Vite / TailwindCSS)

The frontend is a stunning, highly responsive React application with interactive MapLibre routing.

1. **Open a second, separate terminal window.**
2. **Navigate to the frontend directory:**
   ```bash
   cd "d:/College Projects/FlowCastAi/frontend"
   ```
3. **Install dependencies (if this is your first time):**
   ```bash
   npm install
   ```
4. **Start the Vite development server:**
   ```bash
   npm run dev
   ```
   *The frontend will now be running at `http://localhost:5173`.*

---

## Usage Instructions

1. Open your web browser and navigate to `http://localhost:5173`.
2. Select your preferred transport mode (Walk, Car, Bus, Flight).
3. Use the Target icons 🎯 to visually select your Origin and Destination on the interactive map.
4. Click **Predict Exact Route** to calculate distance, simulate delays, view weather conditions, and identify nearby amenities.

Enjoy FLOWCAST AI!
