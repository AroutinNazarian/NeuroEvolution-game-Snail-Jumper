# Snail jumper
**Neuroevolution game assignment.**  
**Fall 2021 - Computer Intelligence.**  

This game has been developed as an assignment for students at Amirkabir University of Technology to apply neuroevolution using a simple game.  
![Snail Jumber](SnailJumper.png)

# Snail Jumper - Neuroevolution Game

AI agents learn to jump and survive through **genetic algorithms** and **neural network evolution**.

---

## Overview

Snail Jumper demonstrates neuroevolution in action: AI agents evolve jumping behavior over generations using neural networks optimized by a genetic algorithm. Real-time visualization tracks fitness improvement and population dynamics.

---

## Technologies & Concepts

**Machine Learning:** Neural networks, genetic algorithms, evolutionary computation, fitness-based selection  
**Game Development:** Physics simulation, collision detection, real-time rendering  
**Visualization:** Learning curves, performance metrics, generation analysis  
**Algorithm Design:** Crossover, mutation, population dynamics, convergence optimization

---

## Project Structure

```
├── nn.py              # Neural network (forward pass, weights)
├── evolution.py       # Genetic algorithm (selection, mutation, crossover)
├── game.py           # Game physics & environment
├── player.py         # Agent class & decision logic
├── learning_curve.py # Performance visualization
└── variables.py      # Configuration & hyperparameters
```

---

## Key Features

✓ Adaptive learning through evolutionary pressure  
✓ Configurable mutation rates and network architecture  
✓ Real-time performance tracking and visualization  
✓ Modular design separating NN, evolution, and game logic  

---

## Algorithm

**Genetic Algorithm Pipeline:**
1. Initialize random population of agents
2. Evaluate fitness in game environment
3. Select top performers (elite selection)
4. Reproduce via crossover and mutation
5. Repeat for multiple generations

**Neural Network:** Agents use feedforward networks to map game state (position, velocity, obstacles) → actions (jump/stay)

---

## Installation

See `requirements.txt` for dependencies.

```bash
pip install -r requirements.txt
python game.py
```

---

## Author

**Aroutin Nazarian** | Computer Intelligence | Amirkabir University of Technology (2021)