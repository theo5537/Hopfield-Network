# Hopfield-Network
This project implements a classic Hopfield associative-memory network entirely in NumPy. Ten 16 × 16 binary images are embedded, corrupted with controllable noise, and then recovered using both synchronous and asynchronous update rules. A visualization routine shows the original, noisy, and recovered patterns plus convergence-step counts, making the network’s stability and noise tolerance easy to see.

# 🧠 Hopfield Neural Network – Associative Memory Demo

This repo contains a runnable Jupyter/Colab notebook that stores 10 custom 16×16
bitmaps in a Hopfield network, corrupts them with configurable noise, and
recovers them using synchronous *and* asynchronous updates.

## Key Features
- **Pure NumPy implementation** – no deep-learning frameworks required.
- **Interactive training size** – choose 1‒10 patterns at runtime to explore
  capacity limits.
- **Noise experimentation** – flip-probability is a single variable.
- **Side-by-side visualizer** – original ▸ corrupted ▸ sync-recovered ▸
  async-recovered + convergence steps.

## Quick Start
```bash
git clone https://github.com/yourname/hopfield-demo.git
cd hopfield-demo
jupyter notebook runnable_network.ipynb   # or open in Colab
