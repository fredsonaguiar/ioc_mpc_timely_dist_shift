#  Inverse Optimal Control and Model Predictive Control for Autonomous Decision Making Under Timely Distributional Shift

This repository includes codes, images and files generated in the project entitled "Inverse Optimal Control and Model Predictive Control for Autonomous Decision Making Under Timely Distributional Shift", where we discuss why we need to make Learning Agents able to act in a robust manner even under continuously updating environments.

In this project we show how conjoint techniques from the field of Optimal Control Theory (namely, Inverse Optimal Control and Model Predictive Control) can be used to reach good generization and adaptability properties even under environmental timely  distributional shift.

## Inverse Optimal Control for Learning from Demonstrations

Loss Structure:

<p align="center">
<img src="img/loss_structure.png" alt="drawing" width="80%" alt="Observation Loss Structure"/>
</p>


Learning Logs:

<p align="center">
<img src="img/training_logs.png" alt="drawing" width="80%" alt="Training Logs"/>
</p>


## Model Predictive Control for Adaptive Autonomous Motion

Results using MPC

<p align="center">
<img src="img/dynamics_static_5s_mpc_05s.png" alt="drawing" width="20%" alt="MPC traces 0.5 second"/>
<img src="img/dynamics_static_5s_mpc_1s.png" alt="drawing" width="20%" alt="MPC traces 1 seconds"/>
<img src="img/dynamics_static_5s_mpc_2s.png" alt="drawing" width="20%" alt="MPC traces 2 seconds"/>
<img src="img/dynamics_static_5s_optimal.gif" alt="drawing" width="20%" alt="MPC traces optimal"/>
</p>