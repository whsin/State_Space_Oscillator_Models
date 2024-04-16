# State_Space_Oscillator_Models

Code repository for all of the methods described and the simulation studies performed in the paper Switching Models of Oscillatory Networks Greatly Improve Inference of Dynamic Functional Connectivity.

The detailed explantion of the code is at the top of each Matlab script file. Below is a brief description of all scripts in this repo.

* core_functions
  * skf.m -- switching Kalman filter
  * smoother.m -- switching RTS smoother
  * em_B.m -- EM on B matrices (for the Common Oscillator Model)
  * em_projA.m -- EM on A matrices (for the Correlated Noise Model)
  * em_projQ.m -- EM on Q (Sigma) matrices (for the Directed Influence Model)
 
* toy_examples
  * sim_COM_toy.m -- simulation file for the toy example of the Common Oscillator Model (COM)
  * sim_CNM_toy.m -- simulation file for the toy example of the Correlated Noise Model (CNM)
  * sim_DIM_toy.m -- simulation file for the toy example of the Directed Influence Model (DIM)
    
* helper_functions
  * funcs2.m -- including a combination of helper functions for simulation settings and visualizations