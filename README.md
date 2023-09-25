# Distributed Coordination of Quadcopters Swarms via Online Feedback Equilibrium Seeking

## Abstract
Integration of unmanned aerial vehicles (UAVs) as wireless relays in traditional telecommunication
infrastructures has proved to be effective in mitigating network congestion, enhancing
Internet services, and establishing ad-hoc networks in complicated environments. Efficient and
scalable coordination mechanisms are crucial for managing and maintaining optimal, stable UAV
formations, and adapting to the rapidly changing network demands.
In this thesis, two fully-distributed control architectures are proposed that are based on Feedback
Equilibrium Seeking, a unifying framework for designing algorithmic-based output feedback
controllers. In particular, algorithmic trajectory planners are proposed that dynamically steer
UAV swarms near efficient network configurations that give the best quality of service (QoS) to a
group of Internet subscribers. Robustness to changes in the Internet demand for the discrete-time
planner in closed-loop with a pre-stabilized UAV network is studied in a sampled-data setting.
We provide a formal robust stability analysis of the obtained sampled-data system to ensure
tracking of an optimal (time-varying, a-priori unknown) swarm configuration and experimentally
validate the theoretical findings using real-world quadcopters. Precise convergence of a fleet of
Bitcraze Crazyflies to the desired operating conditions is achieved in the presence of exogenous
disturbances affecting the users’ request for Internet services, thus showcasing effectiveness of
the adopted framework in modelling relevant objectives for mobile wireless networks

## Further Information
Feedback Equilibrium Seeking control: https://arxiv.org/abs/2210.12088<br />
C++ code: https://gitlab.ethz.ch/dfall/dfall-system
