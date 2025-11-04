🧮 Optimization of the Rastrigin Function with the PSO Algorithm
This project demonstrates the optimization of the Rastrigin mathematical function using the Particle Swarm Optimization (PSO) algorithm — one of the most well-known bio-inspired optimization techniques.

📘 Project Overview
This project was carried out as part of the Artificial Intelligence course at Arak University, under the supervision of Professor Majid Sepahvand.

Contributors:
🧑‍💻 Daniyal Iran Mehr
🧑‍💻 Mehrzad Zandevakili
🧑‍💻 Sepehr Abdollahi

📅 Completed in March 2024
🏫 Affiliation: Arak University

🎯 Objective
The goal of this project is to minimize the Rastrigin function, a common benchmark function in optimization problems known for its large search space and numerous local minima.
The PSO algorithm is implemented from scratch in Python to find the global minimum efficiently.

🧠 Theoretical Background

🔹 Rastrigin Function
The Rastrigin function is defined as $f(x) = A \cdot n + \sum_{i=1}^{n} [x_i^2 - A \cos(2 \pi x_i)]$.


where 
𝐴
=
10
A=10 and 
𝑛
n is the number of dimensions.
It is widely used to test optimization algorithms because of its non-convex, multi-modal landscape.

🔹 Particle Swarm Optimization (PSO)

PSO is a population-based stochastic optimization algorithm inspired by the social behavior of birds and fish.
Each particle adjusts its trajectory based on:
1. its own best-known position (cognitive component)
2. the best-known position of the swarm (social component)
