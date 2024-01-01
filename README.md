# Economic Order Quantity (EOQ) Calculator

This repository contains a Python implementation of an Economic Order Quantity (EOQ) calculator, a fundamental concept in inventory management. The EOQ model helps businesses determine the optimal order quantity to minimize total inventory costs, balancing ordering costs and holding costs.

## Features

- **EOQ Calculation:** Compute the Economic Order Quantity based on ordering costs, annual demand, and holding costs.
- **Backordering and Stockouts:** Extend the EOQ model to consider backordering costs and stockout costs, providing a more comprehensive analysis.
- **Sensitivity Analysis:** Explore the sensitivity of EOQ to different parameters such as demand, holding costs, and more.
- **Interactive Visualization:** Utilize interactive widgets for visualizing EOQ results and conducting sensitivity analyses.

## How to Use

1. Install the required libraries: `numpy`, `matplotlib`, `seaborn`, `ipywidgets`.
2. Run the provided Python script or Jupyter Notebook.
3. Input relevant parameters such as ordering costs, annual demand, and holding costs when prompted.
4. Explore EOQ results, sensitivity analyses, and visualizations.

## Examples

```python
# Example Usage
S = 150  # Ordering cost
D = 1000  # Annual demand
H = 5  # Holding cost per unit
Cb = 0.2  # Backordering cost per unit per period
Cs = 0.5  # Stockout cost per unit per period

result = EOQ(S, D, H, Cb, Cs)
