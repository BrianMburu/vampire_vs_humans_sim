# Human Vs Vampires Simulation

## Overview
This project is a simple probability simulation that models interactions between humans and vampires in a confined space. The simulation also includes resources such as food, water, and garlic that the humans can interact with.

## Features
- **Entities**: The simulation includes entities like humans, vampires, food, water, and garlic. Each entity has its own characteristics and behaviors.
- **Interactions**: Entities can interact with each other. For example, humans can interact with other humans, vampires, food, water, and garlic. Vampires can interact with humans and other vampires.
- **Movement**: Entities can move around the map. The movement is random and within the map bounds.
- **Simulation**: The simulation runs for a specified number of timesteps. In each timestep, entities move and interact with each other. The state of the simulation is plotted after each timestep.


## Entity Possible Interactions
**1. Human-Human Interactions:**
- When two humans interact, there are two possible outcomes:
    - **Selfish interaction**: One human gains 20 health, and the other loses 20 health. This happens with a 40% probability.
    - **Helpful interaction**: Both humans gain 10 health. This happens with a 60% probability.

**2. Human-Vampire Interactions:**
- When a human interacts with a vampire, there are two possible outcomes:
    - **Bitten by vampire**: The human is bitten by the vampire and becomes a vampire. This happens with a 70% probability.
    - **Kills the vampire**: The human kills the vampire. This happens with a 30% probability.

**3. Vampire-Vampire Interactions:**
- When two vampires interact, they bite each other, and both lose 20 health.

**4. Human-Item Interactions:**
- When a human interacts with an item, the outcome depends on the type of the item:
    - **Food**: The human gains 30 health.
    - **Water**: The human gains 50 health.
    - **Garlic**: The human gains 100 health.

**5. Vampire-Item Interactions:**
- When a vampire interact with **Garlic**, it loses 10 health.


## Getting Started
### Prerequisites
- Python 3.x
- Matplotlib
- OpenCV-Python

### Installation
1. Clone the repository
- `git clone https://github.com/BrianMburu/vampire_vs_humans_sim.git`

### Usage
Run the simulation by running the notebook cells:


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
MIT
