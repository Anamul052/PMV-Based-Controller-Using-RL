# PMV-Based Controller Using RL

This repository implements a **thermal comfort controller** based on **Fanger’s PMV index** and explores **reinforcement learning (RL)** concepts for HVAC optimization. The controller adjusts air temperature setpoints to maintain comfort while providing opportunities for energy-efficient operation.

## Features
- **PMV Implementation**: Calculates comfort level using ISO/ASHRAE equations.  
- **Model-Based Policy**: Grid-search strategy to select optimal air temperature setpoints.  
- **Reinforcement Learning Flavor**: Uses generated data to train a lightweight ML policy (behavioral cloning).  
- **3D Visualizations**: Comfort landscape plots for better understanding of system behavior.  
- **Customizable Parameters**: Easily change radiant temperature, humidity, and air velocity ranges.

## File
- `Fanger_model_based_controller.ipynb` – Jupyter Notebook with full implementation, training, and plots.

## Quick Start
1. Clone the repo or download the notebook:
   ```bash
   git clone https://github.com/<your-username>/PMV-Based-Controller-Using-RL.git
2. Install dependencies:
   ```bash
   pip install numpy matplotlib scikit-learn
3. Open the notebook:
   ```bash
   jupyter notebook Fanger_model_based_controller.ipynb
4. Run all cells to reproduce the results.

## License

MIT License – feel free to use, modify, and share.

