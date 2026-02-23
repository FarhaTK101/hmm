# hmm
# Hidden Markov Model – Baum-Welch Visualizer
NAME : FARHA T K
REGISTER NUMBER : TCR24CS027

An interactive web-based visualization tool for understanding Hidden Markov Models (HMM) and the Baum-Welch training algorithm.

This application allows users to generate observation sequences, train an HMM model, and visualize:

Log-likelihood convergence

Transition matrix (heatmap)

Emission matrix (heatmap)

State posterior probabilities over time

Built using HTML, CSS, JavaScript, and Plotly.js — all in a single file with no backend required.


# Features

🔢 Customizable number of states (N)

👁 Customizable number of observation symbols (M)

📏 Adjustable sequence length (T)

🔁 Configurable training iterations

📈 Log-likelihood convergence graph

🔥 Transition & emission heatmaps

📉 State probability over time plot

🎨 Clean modern UI with responsive layout

🧠 Concepts Used

# Hidden Markov Model (HMM)

Forward Algorithm

Baum-Welch Training (Expectation-Maximization concept)

Probability normalization

Matrix operations

Data visualization using Plotly.js


# Technologies Used

HTML5

CSS3

Vanilla JavaScript

Plotly.js (CDN)

# Project Structure
HMM-BaumWelch-Visualizer/
│
└── hmmmm.html   (Contains HTML, CSS, and JS in one file)

No installation required.

# How to Run

Save the file as index.html

Open it in any modern browser (Chrome, Edge, Firefox)

Set:

Number of States (N)

Number of Observations (M)

Sequence Length (T)

Iterations

Click Generate Sequence

Click Train Model

All graphs will be generated dynamically.

📊 Visualizations Explained
1️⃣ Log Likelihood Convergence

Shows how the model likelihood changes across iterations.

2️⃣ Transition Matrix

Heatmap showing probabilities of moving from one state to another.

3️⃣ Emission Matrix

Heatmap showing probability of each observation given a state.

4️⃣ State Probability Over Time

Displays state-wise probabilities for each time step.

