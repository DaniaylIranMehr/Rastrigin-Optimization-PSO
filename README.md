🧮 Optimization of the Rastrigin Function with the PSO Algorithm

This project demonstrates the optimization of the Rastrigin mathematical function using the Particle Swarm Optimization (PSO) algorithm — one of the most well-known bio-inspired optimization techniques.

📘 Project Overview

This project was carried out as part of the Artificial Intelligence course at Arak University, under the supervision of Professor Majid Sepahvand.


Contributors:

🧑‍💻 Daniyal Iran Mehr

🧑‍💻 Mehrzad Zandevakili

🧑‍💻 Sepehr Abdollahi


🏫 Affiliation: Arak University


🎯 Objective

The goal of this project is to minimize the Rastrigin function, a common benchmark function in optimization problems known for its large search space and numerous local minima.
The PSO algorithm is implemented from scratch in Python to find the global minimum efficiently.

🧠 Theoretical Background

🔹 Rastrigin Function

The Rastrigin function is defined as $f(x) = A \cdot n + \sum_{i=1}^{n} [x_i^2 - A \cos(2 \pi x_i)]$.

Where A = 10 and n is the number of dimensions.

It is widely used to test optimization algorithms because of its non-convex, multi-modal landscape.

Particle Swarm Optimization (PSO)

PSO is a population-based stochastic optimization algorithm inspired by the social behavior of birds and fish.
Each particle adjusts its trajectory based on:

1. Its own best-known position (cognitive component)

2. The best-known position of the swarm (social component)


🧩 Implementation Details

Main Steps:

1. Initialize a swarm of random particles within defined bounds.

2. Evaluate each particle’s position using the Rastrigin function.

3. Update velocities and positions iteratively using PSO equations.

4. Track and plot the best solution found over iterations.

### 🔧 Key Parameters

| Parameter         | Description                      | Default     |
|-------------------|----------------------------------|-------------|
| `num_particles`   | Number of particles in the swarm | 30          |
| `num_iterations`  | Maximum number of iterations     | 100         |
| `bounds`          | Search space range               | (-5.12, 5.12) |
| `inertia_weight`  | Influence of previous velocity   | 0.5         |
| `cognitive_weight`| Particle’s own experience        | 1.5         |
| `social_weight`   | Swarm’s collective knowledge     | 1.5         |


📊 Results

✅ The PSO algorithm successfully minimized the Rastrigin function to 0.0, finding the global optimum near [0, 0].

The progress of the optimization can be visualized through a 2D contour plot and a log-scale score evolution chart over iterations.

Example output:

Iteration 95/100, Best Score: 0.0
Global Best Position: [-6.88e-10, 2.75e-09]
Global Best Score: 0.0


📈 Visualization

2D Contour Plot: Displays particle positions and the search trajectory across iterations.

Convergence Graph: Plots the global best score versus iteration number (log scale).

Both visualizations help understand how the swarm converges toward the optimal solution.


⚙️ Technologies Used

Python 3.x - NumPy - Matplotlib - IPython.display (for dynamic visualization in notebooks)
