<h1>rta_mmtvgp</h1>

This code repository contains preliminary experiments for the paper "Trajectory Tracking for Systems with Unknown Time-Varying Disturbances" by Michael E. Cao, Akash Harapanahalli, Evanns Morales-Cuadrado, and Samuel Coogan.

<h2>Notes on Repository</h2>

This repository assumes you have the `immrax` library which can be found [here](https://github.com/gtfactslab/immrax). The scripts contained within this repository can be used to demonstrate the runtime assurance mechanism in simulation. For the code that directly demonstrates the Software-In-The-Loop and Hardware experiments from the final paper, see the [linked repository](https://github.com/evannsmc/PX4_RTA_MM_GPR/).

For reference:

* The `rta_tvgp.ipynb` jupyter notebook demonstrates the runtime assurance mechanism on a planar multirotor system with time-varying wind disturbance behavior.
* The `iasif_tvgp.ipynb` and `iasif.ipynb` notebooks demonstrate a variant of the formulation used in an Implicit Active Set Invariance Filter (see "Safety from fast, in-the-loop reachability with application to UAVs" by C. Llanes, M. Abate, and S. Coogan for an overview).
