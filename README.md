# Nussinov-Implementation

This repository contains an implementation of the **Nussinov algorithm** for RNA secondary structure prediction. The algorithm uses a dynamic programming approach to compute the optimal pairing of RNA bases, maximizing the number of valid base pairs.

## Contents

1. **README.md**: This file provides an overview of the project.
2. **Nussinov_Algorithm.ipynb**: A Jupyter Notebook containing the full implementation of the Nussinov algorithm, along with explanations, code, and example use cases.

## Features

- **Dynamic Programming**: Efficient computation of the RNA secondary structure using the Nussinov algorithm.
- **Visualization**: Example cases and intermediate results (e.g., dynamic programming tables) are visualized in the notebook.
- **Educational Use**: Designed to provide insights into RNA secondary structure prediction and dynamic programming.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/nussinov-algorithm.git

2. Open the Jupyter Notebook:

   ```
   cd nussinov-algorithm
   jupyter notebook Nussinov_Algorithm.ipynb
   ```

3. Follow the step-by-step implementation in the notebook.

## Requirements

- Python 3.7 or higher
- Jupyter Notebook
- Required libraries:
  - NumPy
  - Matplotlib (optional, for visualization)

## Example

The notebook demonstrates the Nussinov algorithm on sample RNA sequences, showcasing:

- Input RNA sequence: `GGGAAAUCC`
- Predicted secondary structure: `.((..()))`
- Dynamic programming table construction.
