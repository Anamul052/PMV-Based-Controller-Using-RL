# PMV-Based-Controller-Using-RL
A PMV-based HVAC controller using Fanger’s thermal comfort model and reinforcement learning concepts. Includes PMV equations, grid search for optimal setpoints, 3D visualizations, and an ML surrogate policy for efficient comfort-driven control.
Perfect ✅ Here’s a ready-to-use **`README.md`** written in Markdown syntax that you can copy and paste directly into your repo:

````markdown
# PMV-Based Controller Using RL

This repository implements a **thermal comfort controller** based on **Fanger’s PMV index** and explores **reinforcement learning (RL)** concepts for HVAC optimization. The controller adjusts air temperature setpoints to maintain comfort while providing opportunities for energy-efficient operation.

---

## ✨ Features
- **PMV Implementation**: Calculates comfort level using ISO/ASHRAE equations.  
- **Model-Based Policy**: Grid-search strategy to select optimal air temperature setpoints.  
- **Reinforcement Learning Flavor**: Uses generated data to train a lightweight ML policy (behavioral cloning).  
- **3D Visualizations**: Comfort landscape plots for better understanding of system behavior.  
- **Customizable Parameters**: Easily change radiant temperature, humidity, and air velocity ranges.  

---

## 📂 File
- `Fanger_model_based_controller.ipynb` – Jupyter Notebook with full implementation, training, and plots.

---

## 🚀 Quick Start
1. Clone the repo or download the notebook:
   ```bash
   git clone https://github.com/<your-username>/PMV-Based-Controller-Using-RL.git
````

2. Install dependencies:

   ```bash
   pip install numpy matplotlib scikit-learn
   ```
3. Open the notebook:

   ```bash
   jupyter notebook Fanger_model_based_controller.ipynb
   ```
4. Run all cells to reproduce the results.

---

## 🖥 Example

```python
tr, rh, av = 25.0, 50.0, 0.6
ta = policy[(tr, rh, av)]
pmv = pmv_iso(ta, tr, av, rh)
print(f"Setpoint = {ta:.1f} °C, PMV ≈ {pmv:+.2f}")
```

---

## 🔮 Future Work

* Integrate advanced RL algorithms for online control.
* Extend to adaptive comfort models (ASHRAE 55).
* Add cost–comfort trade-off optimization.

---

## 📜 License

MIT License – feel free to use, modify, and share.

```

---

👉 You can paste this directly into the **README.md** file when editing on GitHub.  

Would you like me to also add a **“Run on Google Colab” badge** so others can try your notebook online without installing anything?
```
