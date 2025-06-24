# Reinforcement Learning in GridWorld 

This repository contains the implementation and analysis for the coursework of the module **24COP528 - Artificial Intelligence** at **Loughborough University**.

## 📌 Project Overview

The project demonstrates how an agent can learn optimal navigation policies in a GridWorld environment using two Reinforcement Learning (RL) methods:

- **Value Iteration** (model-based)
- **Q-Learning** (model-free)

The environment includes obstacles (`o`), walls (`w`), and a goal state (`g`). The agent starts from the top-left corner and must find the most efficient path to the goal while minimizing penalties.

---

## 🧠 Learning Objectives

- Implement classical RL algorithms from scratch.
- Analyze the effect of **discount factor (γ)** and **exploration rate (ε)** on agent performance.
- Compare **Value Iteration** and **Q-Learning** in terms of convergence, policy optimality, and adaptability.
- Visualize learned policies within a custom GridWorld environment.

---

## 📁 File Structure

| File Name                  | Description                                                              |
|---------------------------|--------------------------------------------------------------------------|
| `24COP528 Task a.ipynb`    | Jupyter Notebook implementing Value Iteration and Q-Learning algorithms. |
| `24COP528(TASK A).docx`    | Supporting documentation/report for Task A.                             |
| `24COP528_Task_b.ipynb`    | Jupyter Notebook for Task B – experimentation and result analysis.       |

---

## 🛠️ Dependencies

- Python 3.8+
- NumPy
- Matplotlib
- Jupyter Notebook
- A custom `gridworld` module (assumed to be provided with the coursework)

Install requirements:
```bash
pip install numpy matplotlib
# Image-Classification

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/GridWorld-RL.git
cd GridWorld-RL
Open Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Run:

24COP528 Task a.ipynb to train using both algorithms.

24COP528_Task_b.ipynb to view analysis and experiments on hyperparameters.

📊## Results & Analysis
The agent successfully learns optimal navigation policies using both methods. The report in 24COP528(TASK A).docx discusses:

The learning process for each method.

Policy heatmaps and Q-table outputs.

The effect of tuning γ and ε.

Comparative analysis between Value Iteration and Q-Learning.

