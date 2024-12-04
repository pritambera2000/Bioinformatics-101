# Superinformation Calculation for Biological Sequences

This repository contains a Python implementation of a function to calculate **superinformation** for biological sequences, as described in the paper:

**"Alternate Measure of Information Useful for DNA Sequences"** by Ranjan Bose and Sonali Chouhan, published in *Physical Review E* (2011).

Superinformation provides a measure of the "randomness of randomness" in DNA sequences and can effectively distinguish between coding and noncoding regions.

---

## Features

- **Flexible Inputs**: Handles sequences of varying lengths and block configurations.
- **Entropy Analysis**: Uses Shannon entropy to calculate the randomness in blocks.
- **Histogram-based Superinformation**: Generates a histogram of entropies and computes superinformation as entropy of the probability distribution.
- **Customizable Parameters**:
  - **Symbols per Block**: Number of symbols in each block.
  - **Number of Blocks**: Maximum number of blocks to consider.

---

## Installation

Ensure you have Python 3.x installed along with the following required libraries:

- `numpy`
- `math` (Python standard library)

Install dependencies using `pip`:

```bash
pip install numpy
```
## Usage

### Function: `calculate_superinformation`

This function calculates the superinformation value for a given biological sequence.

**Inputs**:
- `sequence`: The DNA sequence (string).
- `symbols_per_block`: Number of symbols per block (integer).
- `number_of_blocks`: Maximum number of blocks to consider (integer).

**Output**:
- A floating-point value representing the superinformation.

## Running the Test Script
The `main()` function in `superinfo.ipynb` demonstrates usage with example sequences and parameters.