# MPC Resources
General resources for MPC (Model Predictive Control) and general Optimal Control

## Dimitri P. Bertsekas
Prof. MIT
Not an MPC but general optimal control resource. Bridges the gap between MPC and RL. Has a free book [REINFORCEMENT LEARNING AND OPTIMAL CONTROL](http://web.mit.edu/dimitrib/www/RLbook.html), lecture notes and videos. He [claims](https://www.youtube.com/watch?v=UeVs0Op-Ui4) that the MPC and RL are not different essentially. His 2025 course includes MPC topic as well and he had started uploading [videos](https://www.youtube.com/watch?v=AdxhPj0PDHM).

## Matthew P. Kelly
Boston Dynamics & Cornell

Trajectory optimization and control
He has a [website](http://www.matthewpeterkelly.com/) with really good [tutorials](http://www.matthewpeterkelly.com/tutorials/index.html). Especially [his trajectory optimization tutorials](http://www.matthewpeterkelly.com/tutorials/trajectoryOptimization/index.html) are really rich in context.

[Summary video](https://www.youtube.com/watch?v=wlkRYMVUZTs) on YouTube.

* Trajectory optimization
* Optimal control : closed-loop solution
* Transcription
* Numerical integration
* Nonlinear-programming
* Which software to use with details

## Jesus Tordesillas
A nice [YouTube video](https://www.youtube.com/watch?v=j82Ia436DYY)

* Convexity
* Solver interfaces
* LQR
* Path planning & Trajectory Optimization
* Obstacle avoidance
* A swarm example

## Waren Powell
Phd. Princeton Emeritus, Operations Research, Finance & Economics

Operations Research (OR) field uses same system dynamics and control approaches with Optimal Control field. OR people are much more focused on hidden dynamics and stochastic process noise and optimal control under those. They call these types of problems **Sequential Decision Problems**. 

Waren has an [introduction video](https://www.youtube.com/watch?v=LEYLRn3ci7E&t=366s) on this field. He bridges the gap between Reinforcement Learning and Optimal Control and is the author of the book [Reinforcement Learning and Stochastic Optimization: A unified framework for stochastic optimization](https://castle.princeton.edu/RLSO/), in which he claims to unify all the possible control methods under 4 classes of policies.

He offers an interesting perspective on Optimal Control and frequently mentions that the methods are from Control's area.

## CMU - Optimal Control and Reinforcement Learning Lecture Videos
Really good lecture series. They upload a playlist each year on Youtube. 2025 has just started but [2024 videos](https://www.youtube.com/watch?v=Kj88Nory8ec&list=PLZnJoM76RM6Jv4f7E7RnzW4rijTUTPI4u) are complete. Lecture notes will be [here](https://github.com/Optimal-Control-16-745/lecture-notebooks/tree/main).

It includes:
* Dynamics
* Discretization, Stability
* Optimization (Deterministic/Stochastic)
* LQR, MPC, LQG
* Nonlinear Trajectory Optimization
* 3D rotations
* Iterative Learning Control
* Quadrotors, legged-robots, autonomous driving, rocket vertical landing etc.

## Mohamed W. Mehrez
Has [videos on YouTube](https://www.youtube.com/@MohamedWMehrez) using CasADi. Direct implementation. 

# Tools

## CasAdi
[CasADi](https://web.casadi.org/) is the interface between OCP and Optimizer. Very useful, free software. Can be used with Matlab, Python and, Cpp. Their [example pack](https://github.com/casadi/casadi/tree/main/docs/examples) has really nice introductory-examples.