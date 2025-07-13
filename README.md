# HVAC-RL-Controllers

A comparative implementation of two Deep Reinforcement Learning (DRL) controllers — Double Deep Q-Network (Double DQN) and Policy Gradient with Baseline (PG-B) — for energy-efficient and comfort-aware HVAC control.

## 🧠 Algorithms Implemented
- **Double DQN**: Value-based method for discrete supply-air temperature control.
- **Policy Gradient with Baseline**: Actor-critic method for continuous damper modulation using advantage estimates.

## 🏢 Custom HVAC Environment
A Gym-compatible environment simulating a two-zone office building, including:
- Outdoor temperature and humidity
- Indoor temperatures
- Occupancy signals
- Mixed action space (discrete + continuous)
- Multi-objective reward (energy + thermal comfort)

## 📊 Evaluation Metrics
- Energy Consumption (kWh)
- Thermal Comfort Violations (PMV-based)
- Convergence Speed
- Learning Stability

## 📁 Structure
- `Naeem-20054701-CA.ipynb`: Full implementation, training, and evaluation.
- `results/`: Plots and metrics (to be updated after training).
- `report/`: Final PDF report (generated from results).

## 🚀 Setup & Run
### Requirements
- Python 3.9+
- PyTorch 2.x
- Gymnasium 0.29+
- Matplotlib, NumPy
