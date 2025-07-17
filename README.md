# Track-Specific-Aerodynamic-Optimization-Using-RBDO-for-Formula-1-Vehicle
Developed a Reliability-Based Design Optimization (RBDO) algorithm in MATLAB integrating aerodynamic simulation data with structural constraints to identify the optimal lift and drag coefficients minimizing lap time across three race tracks 


Used a Monte Carlo approach to sample aerodynamic design space (−10 ≤ CL ≤ −2.5, −1.6 ≤ CD ≤ −0.7), and modeled lap times using exponential and quadratic regression fits for L/D vs lap time and CL vs lap time respectively


Implemented the Hasofer–Lind method to evaluate structural reliability of the rear wing under aerodynamic loading, ensuring that the design meets the industry safety requirement of β ≥ 4 under combined lift and drag-induced stresses


Formulated a constrained optimization problem using the Exterior Penalty Method, and solved it via Steepest Gradient Descent, balancing aerodynamic performance with structural yield constraints under von Mises stress criteria  


Showcased how aerodynamic tuning must be track-specific, with higher CL favored for turn-dense circuits (e.g., Paul Ricard) and lower CD for straight-heavy layouts (e.g., Monza), enabling data-driven aero configurations for real-world F1 applications


