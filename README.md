# MOPSO Multi-Objective Optimizer

This project uses a simple implementation of the MOPSO algorithm to solve multi-objective problems and visualize the Pareto front in a Streamlit interface.

## 📦 Components
- `mopso.py`: Optimization algorithm logic
- `problems.py`: Contains objective functions (e.g., ZDT1)
- `main.py`: Streamlit interface to run and visualize results

## ▶️ How to Run
```bash
pip install -r requirements.txt
streamlit run main.py
```

## 📌 Notes
- The default problem is ZDT1 (2 objectives)
- Easily extendable with other benchmark functions

## 📜 License
MIT
