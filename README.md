# GAWM: Global-Aware World Model for Multi-Agent Reinforcement Learning

**GAWM** is a novel **model-based multi-agent reinforcement learning (MARL)** framework designed to enhance sample efficiency and convergence stability in complex multi-robot coordination tasks. By integrating a **Transformer-based cross-agent observation fusion mechanism** and a **trend-aware reward modeling strategy**, GAWM addresses key challenges in real-world robotic applications, such as partial observability, dynamic distribution mismatch, and global state inconsistency. The framework adheres to the **Centralized Training with Decentralized Execution (CTDE)** paradigm, enabling scalable deployment for heterogeneous robot teams.

## Key Features 🌟
- **Global-Consistent State Representation**: Leverages Transformer-based observation fusion to align agents' local perceptions and reconstruct globally coherent latent states.
- **Trend-Aware Team Reward Modeling**: Simplifies reward prediction in high-complexity environments through temporal smoothing while preserving policy optimality.
- **Decoupled Architecture**: Separates world model training from policy optimization to ensure CTDE compliance and scalability.
- **Superior Sample Efficiency**: Outperforms state-of-the-art model-free (e.g., MAPPO, QMIX) and model-based (e.g., MAMBA, MAG) baselines on benchmarks like **StarCraft Multi-Agent Challenge (SMAC)** and **Multi-Agent MuJoCo (MAMuJoCo)**.

## Applications 🚀
- **Swarm Tactics**: Tested on challenging SMAC maps (e.g., `3s_vs_5z`, `corridor`) for collaborative combat scenarios.
- **Articulated Robot Control**: Validated on MAMuJoCo tasks like multi-agent HalfCheetah and Swimmer for locomotion and manipulation.
