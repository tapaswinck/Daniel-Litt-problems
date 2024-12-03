# Coin Flipping Challenge: Probabilistic Simulations with Alice and Bob

## Overview

This repository contains two fascinating probabilistic simulations exploring coin-flipping scenarios involving two players, Alice and Bob. Each notebook presents a unique challenge that demonstrates the intriguing world of probability and randomness.

## Simulation 1: Two Consecutive Heads/Tails Challenge

### Problem Statement
- 100 coins are flipped and numbered from 1 to 100
- Alice checks coins in numerical order: 1, 2, 3, ...
- Bob checks odd-numbered coins first (1, 3, 5, ..., 99), then even-numbered coins (2, 4, 6, ...)
- **Goal**: Who will first find two consecutive heads (HH) or two consecutive tails (TT)?

### Key Findings
- Alice wins approximately 37% of the time
- Bob wins approximately 25% of the time
- Ties occur in about 37% of simulations

### Insights
- A straightforward, linear strategy can sometimes be more effective than a complex approach
- Probability can yield unexpected and counterintuitive results

## Simulation 2: 26 Heads Challenge

### Problem Statement
- 100 coins are flipped and numbered from 1 to 100
- Alice checks coins in numerical order: 1, 2, 3, ...
- Bob checks odd-numbered coins first (1, 3, 5, ..., 99), then even-numbered coins (2, 4, 6, ...)
- **Goal**: Who will first see a total of 26 heads?

### Key Findings
- Alice wins approximately 20% of the time
- Bob wins approximately 14% of the time
- Ties occur in about 64% of simulations

### Insights
- The high percentage of ties challenges assumptions about competitive scenarios
- Randomness plays a crucial role in determining outcomes
- Different checking strategies can lead to remarkably similar results

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib

## Running the Simulations
1. Ensure you have Jupyter Notebook or Google Colab installed
2. Install required libraries: `numpy`, `pandas`, `matplotlib`
3. Open the respective `.ipynb` files
4. Run the cells sequentially

## Lessons Learned
- Simple strategies can be surprisingly effective
- Probability is complex and often defies intuition
- Randomness can lead to unexpected patterns and results

## Future Explorations
- Modify the number of coins
- Experiment with different coin-checking strategies
- Investigate other probabilistic challenges

## Contributions
Contributions, questions, and suggestions are welcome! Feel free to open an issue or submit a pull request.
