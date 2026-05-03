# vIscosity-Vs-Temperature-
# Molten Salt Viscosity Analysis

This project investigates the thermophysical properties of **AgBr-AgCl** binary solutions. Specifically, it focuses on modeling the relationship between temperature (K) and viscosity (mPa·s).

## Objective
The goal is to verify if the viscosity of these molten salts follows the **Arrhenius behavior** and to visualize the transition from non-linear to linear data through mathematical transformation.

## Mathematical Model
The viscosity ($\eta$) is modeled using the Arrhenius equation:
$$\eta = A \cdot e^{\frac{B}{T}}$$

To perform a linear regression, the equation is linearized by taking the natural logarithm:
$$\ln(\eta) = \ln(A) + \frac{B}{T}$$

## Visualizations Included
1. **Viscosity vs. Temperature:** Shows the non-linear decay of viscosity as temperature increases.
2. **Arrhenius Plot (Linearized):** A plot of $\ln(\text{viscosity})$ vs. $1/T$, which yields a straight line for validation of the model constants.

## How to Run
1. Ensure you have `pandas`, `numpy`, and `matplotlib` installed.
2. Keep the `viscosity-csv.txt` file in the same directory as the notebook.
3. Open `viscosity_vs_temp.ipynb` in Jupyter Lab or VS Code and run all cells.

## Data Source
The data utilized in this study includes composition ranges from 0.0 to 100.0% AgCl across a temperature range of 720K to 970K.
