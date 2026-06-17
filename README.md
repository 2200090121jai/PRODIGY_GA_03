# PRODIGY_GA_03: Text Generation using Markov Chains

This repository contains my official submission for **Task 3** of my Generative AI Internship at Prodigy InfoTech.

🚀 Project Overview
The goal of this task is to implement a foundational statistical text generation algorithm using a classic **Markov Chain**. This project highlights how natural language text can be synthesized structurally through probability states without relying on modern deep neural networks.

🧠 Theory Learned
- **The Markov Property:** Understanding how a stochastic process functions when the probability of future states depends strictly on the current state, maintaining a state of absolute memorylessness.
- **State Transition Probability Matrices:** Building dictionary lookups where each unique token acts as a key mapping to an array of observed following tokens, effectively representing transition distributions.
- **Random Walk Sampling:** Exploring how generative sampling works by choosing paths randomly out of weighted probability horizons.

🛠️ Technology Stack
- Python 3 (Standard Libraries: `random`)
- Google Colab (CPU Runtime Environment)
