# Bayesian_Hierarchical_Model
MPhil Dissertation
This code implements a simulation study for a Bayesian hierarchical modeling (BHM) basket trial. The purpose of the study is to evaluate different prior specifications and their impact on the type 1 error rate and statistical power of the trial. The code consists of the following main components:

Simulation Study:

The scntb function generates sample data for the basket trial based on the given subtrial sizes and response rates.
The logit function calculates the logit of a given probability.
The sim_procedure function performs the Bayesian analysis for a specific procedure, including prior calibration, posterior sampling, and posterior inference.
The simulation process involves generating sample data for different scenarios, calibrating priors based on expert opinions, and performing Bayesian analysis for each procedure.
Calibration Problem Attempt:

This section of the code attempts to solve the calibration problem by generating sample data for a specific scenario and performing Bayesian analysis using different procedures.
Visualization:

The code includes visualizations to plot the prior and posterior distributions of the variance parameter, as well as the response rates for each subtrial.
Data Example:

This section provides an example of formulating data for the JAGS model and performing Bayesian analysis using the calibrated mixture prior.
To use the code, make sure to have the required packages (rjags, posterior, tidyverse, forestplot, dplyr) installed. Set the desired parameters for the simulation study, such as subtrial sizes and response rates, and run the code to obtain the type 1 error rate, statistical power, and visualizations for each procedure and scenario.

Note: The code is provided as a reference and may require modifications to suit specific use cases or adapt to changes in software dependencies.
