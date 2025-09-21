# StratoHack-Space-Debris-Collision-Risk-Prediction

## Problem Statement

Predict the probability of collision between satellites and space debris using orbital trajectory data.

## Datasets

- **Active satellites (baseline catalog for operational assets):**  
  [https://celestrak.org/NORAD/elements/gp.php?GROUP=active&FORMAT=tle](https://celestrak.org/NORAD/elements/gp.php?GROUP=active&FORMAT=tle)
- **FENGYUN‑1C ASAT debris (major LEO debris cloud):**  
  [https://celestrak.org/NORAD/elements/gp.php?GROUP=fengyun-1c-debris&FORMAT=tle](https://celestrak.org/NORAD/elements/gp.php?GROUP=fengyun-1c-debris&FORMAT=tle)
- **COSMOS‑2251 collision debris (Iridium‑33/COSMOS‑2251 fragments):**  
  [https://celestrak.org/NORAD/elements/gp.php?GROUP=cosmos-2251-debris&FORMAT=tle](https://celestrak.org/NORAD/elements/gp.php?GROUP=cosmos-2251-debris&FORMAT=tle)
- **COSMOS‑1408 ASAT debris (recent large debris event):**  
  [https://celestrak.org/NORAD/elements/gp.php?GROUP=cosmos-1408-debris&FORMAT=tle](https://celestrak.org/NORAD/elements/gp.php?GROUP=cosmos-1408-debris&FORMAT=tle)

## Approach

- **Baseline:** Rule-based proximity analysis with TLE data.
- **Advanced:** Graph Neural Networks or Reinforcement Learning for dynamic collision avoidance.

## Quick Start

1. Clone the repository.
2. Download datasets from the above sources.
3. Run the notebook or scripts for analysis and prediction.

## Colab Notebook

For a quick demonstration, you can use the Colab notebook:  
[Open in Colab](https://colab.research.google.com/drive/12O6sQuBlGP6GGdG0veJGse7Z_M3Ww7jf?usp=sharing)

---
> **Note:** This project is a prototype for research and educational purposes.
