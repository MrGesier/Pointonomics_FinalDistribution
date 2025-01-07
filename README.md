# Pointonomics_FinalDistribution
Calcules the final distribution based on tasks points systems

# Dynamic User Scoring and Token Distribution Simulation

This repository contains a Python script that simulates user scoring, group promotions/demotions, and token distribution based on Elo ranking principles. The script includes dynamic scoring, inactivity penalties, weekly promotions, and fair token allocation.

## Features

- **Dynamic Scoring:** Simulates task completion with truncated normal distributions for a realistic user scoring process.
- **Inactivity Penalty:** Applies penalties for users with prolonged inactivity periods.
- **Group Promotions and Demotions:** Dynamically adjusts user groups based on weekly scores.
- **Fair Token Distribution:** Allocates weekly tokens proportionally across user groups, ensuring fairness.
- **Gini Coefficient Calculation:** Evaluates fairness of the token distribution using the Gini coefficient.
- **Visualization:** Provides histograms and Lorenz curves to analyze token distribution.

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scipy`

Install the required dependencies:
```bash
pip install -r requirements.txt
