# Matrioshka Brain

The Matrioshka Brain is a concept inspired by the idea of nested Russian Matryoshka dolls. It represents a hierarchical structure of agents working together to solve complex problems. This repository contains a simplified PHP implementation of the Matrioshka Brain concept.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Agents](#agents)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Matrioshka Brain implementation in PHP consists of a `MatrioshkaBrain` class that manages a list of agents, each with its unique responsibilities. The agents collaborate to solve a given problem, and the Matrioshka Brain coordinates the process.

## Usage
To use this implementation, follow these steps:

1. Create a list of agents, each implementing the `solveProblem` method.

2. Initialize the `MatrioshkaBrain` with the list of agents.

3. Call the `solveProblem` method on the Matrioshka Brain, providing the problem as input.

4. The Matrioshka Brain will coordinate the agents to solve the problem and return a final solution.

## Agents
Agents represent different entities or subsystems within the problem-solving process. In this implementation, we've provided example agents for a supply chain optimization problem. You can create your own agents by extending the `Agent` class and implementing the `solveProblem` method.

## Installation
To use this implementation, simply copy the PHP classes (`MatrioshkaBrain.php` and the agent classes) into your project. Make sure to include or require these files in your PHP script.

## Contributing
Contributions to this project are welcome! If you have improvements or additional features to add, please fork this repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. 
