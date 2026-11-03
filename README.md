# ✈️ UAV Aerodynamic Analysis & Airfoil Simulation (NACA 2412)

[![XFLR5 Version](https://img.shields.io/badge/XFLR5-v6.62-blue.svg)](https://www.xflr5.com/)
[![Revenge Number](https://img.shields.io/badge/Re-200,000-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

> Professional aerodynamic research report evaluating the performance characteristics of the **NACA 2412** airfoil for Unmanned Aerial Vehicle (UAV) applications, simulated using XFLR5 at a Reynolds number of $Re = 200,000$.

---

## 📑 Overview
This repository contains computational fluid dynamics (CFD) / panel method simulation results, polar curves, and a comprehensive engineering report (`.pdf`) detailing the aerodynamic behavior of the NACA 2412 airfoil across an angle of attack ($\alpha$) range from **$-4^\circ$ to $+12^\circ$**.

### 📄 Download Full Report
You can view or download the complete formatted engineering document here:
👉 **[View PDF Report](./reports/xflr5_uav_aerodynamic_report.pdf)**

---

## ⚙️ Simulation Parameters & Setup
* **Airfoil:** NACA 2412
* **Reynolds Number ($Re$):** $200,000$
* **Mach Number:** $0.0$, $NCrit = 9.0$
* **Sweep Range ($\alpha$):** $-4^\circ$ to $+12^\circ$ with $\Delta = 1^\circ$ (17 calculated points)
* **Software:** XFLR5 v6.62 (Direct Foil Analysis, viscous/inviscid coupling with boundary layer initialization `Init BL` and `Store Opp`).

---

## 📊 Key Aerodynamic Polars
Here are preview highlights of the simulated performance curves:

| Lift Coefficient ($C_L$ vs $\alpha$) | Drag Polar ($C_L$ vs $C_D$) | Aerodynamic Efficiency ($C_L / C_D$) |
| :---: | :---: | :---: |
| <img src="assets/lift_alpha.png" width="220"> | <img src="assets/cl_cd_polar.png" width="220"> | <img src="assets/efficiency.png" width="220"> |

---

## 📈 Summary of Results (Sample Data Points)
* **Optimal Angle of Attack ($\alpha_{opt}$):** $\approx 6.0^\circ$ yielding a peak efficiency ratio ($C_L / C_D$) of **$67.31$**.
* **Zero-Lift Angle:** Evaluated accurately through boundary layer transition tracking.
* **Stall Behavior:** Monitored via upper-surface transition point shifting and pressure coefficient ($C_{pmin}$) extremes.

---
*Author: Ayan | Specialized Physics & Mathematics Track*
