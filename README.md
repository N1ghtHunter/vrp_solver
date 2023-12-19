# VRP Solver

This project is a Vehicle Routing Problem (VRP) solver that uses Genetic and Differential Evolution algorithms.

## Sample Generator

The sample generator is implemented in the [`vrp_sample_gen.py`](vrp_sample_gen.py) file. It is used to generate random data for the Vehicle Routing Problem (VRP). The generated data includes the number of nodes, maximum capacity, and the minimum and maximum values for X and Y coordinates.

The `generate` function in this file is used in the GUI to generate data when the user clicks the "Generate" button. The generated data is saved in a file called `input.txt`.

## Algorithms

The algorithms used in this project are implemented in the `algorithm` directory.

- [Genetic Algorithm](algorithm/genetic_algorithm.py): Implemented in the `genetic_algorithm.py` file. It includes functions like `vrp`, `run_algorithm`, and `generate_population`.
- [Differential Evolution](algorithm/differential_evolution.py): Implemented in the `differential_evolution.py` file. It also includes functions like `vrp` and `run_algorithm`.

## GUI

The Graphical User Interface (GUI) for this project is implemented in the `gui` directory.

- [Both Algorithms](gui/both_algo.py): This file runs both Genetic and Differential Evolution algorithms.
- [Differential Evolution](gui/diff_evo.py): This file runs the Differential Evolution algorithm.
- [Genetic Algorithm](gui/genetic_algo.py): This file runs the Genetic Algorithm.

## Running the Project

To run the project, execute the `main.py` file.

```sh
python main.py
```

## Authors

- [Mazin Islam](https://github.com/N1ghtHunter)
- [Kerolus Soliman](https://github.com/kerolus77)
- [Philo Ezzat](https://github.com/Philo-Ezzat)
- [Fam Fayez](https://github.com/FamFayez)
- [Kerolos Samy]()
- [Marina Ayman](https://github.com/MarinaAymanHanna)
- [Marina Ghattas](https://github.com/Marinaghatas)
