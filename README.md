🎲 Talent vs. Luck — A Simulation-Based Graduation Thesis

Author: Kento Morita
Supervisor: Takafumi Koshinaka
Department: Data Science
Year: 2023 (Reiwa 5)

📘 Overview

This research explores a timeless question: Is success driven more by talent, effort, or sheer luck?

Using multi-agent simulation and reinforcement learning (Q-learning), this project builds upon the Talent vs. Luck (TvL) model proposed by Pluchino et al., extending it with agents capable of learning from their environment to test whether effort can consistently overcome randomness.

🔬 Methodology
	•	Multi-Agent Simulation: Agents move through a grid-based environment encountering lucky and unlucky events.
	•	Reinforcement Learning: Agents are trained using Q-learning to maximize rewards, simulating learning and “effort”.
	•	Metrics: Success is quantified via virtual wealth accumulation.
	•	Parameters: Agents are initialized with varying levels of talent and learning rates (effort).

💡 Key Findings
	•	Even when agents learn from experience, luck still dominates success in most simulations.
	•	High talent and high learning rate do not guarantee success.
	•	Effort can act as a “booster”, but not a replacement for good fortune.
	•	Wealth distributions follow power laws, replicating real-world inequality patterns.

🧠 Implications

This study challenges the meritocratic notion that effort and talent alone determine outcomes. It emphasizes the hidden yet overwhelming role of randomness in shaping individual success, and encourages further inquiry into the intersection of fairness, opportunity, and chance.

📁 Files
	•	translated_thesis.pdf: English version of the original thesis
	•	simulation_code/: Python code for the TvL model with reinforcement learning (coming soon)
	•	figures/: Charts and heatmaps from simulations

🛠️ Technologies
	•	Python (OOP)
	•	Numpy, Matplotlib
	•	Multi-agent systems
	•	Reinforcement Learning (Q-Learning)

📈 Future Work
	•	Modeling interactions between agents (multi-agent RL)
	•	Introducing network structures or real-world constraints
	•	Deeper exploration of the causality between effort and opportunity
