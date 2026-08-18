# End-to-End Supply Chain Network & Logistics Optimization

## Overview
This repository contains a mathematical optimization model for a multi-echelon supply chain network. The project formulates a Mixed-Integer Linear Programming (MILP) model to manage capacitated network flows and dynamic facility allocation, aiming to minimize overall distribution and transportation costs while strictly meeting demand requirements.

## Key Features
* **MILP Formulation:** Utilizes Pyomo to mathematically model the supply chain network.
* **Cost Minimization:** Optimizes flow quantities across different supply links to minimize total operational costs.
* **Capacitated Flow Management:** Incorporates strict constraints on node handling capacities and pipeline disruptions.
* **Solver Integration:** Employs the CBC solver to efficiently compute the optimal network flow.

## Repository Structure
* `Supply_Chain_Opt.ipynb`: The Jupyter/Colab notebook containing the model formulation, constraints, and solver execution.
* `Supply_Chain_Opt_Report.pdf`: A detailed technical report outlining the mathematical formulation, objective function, constraints, and scenario results.
