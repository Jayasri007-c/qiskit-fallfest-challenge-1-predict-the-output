# Challenge 1: Predict the Output

**Event:** Qiskit Fall Fest 2026 (IBM Quantum)
**Venue:** Vishnu Institute of Technology, Bhimavaram
**Participant:** [Your Name] · [Roll Number]

## Problem
Predict the measurement outcome of three single-qubit circuits, run each for 100 shots, and compare the results with the predictions.

## Circuits
| Circuit | Gates | Prediction | Reason |
|---|---|---|---|
| A | X | always `1` | X flips \|0⟩ to \|1⟩ |
| B | X, X | always `0` | the two X gates cancel out |
| C | H | about 50% `0` / 50% `1` | H creates an equal superposition |

## Result summary
Circuits A and B were deterministic, giving `1` and `0` on every shot. Circuit C gave a roughly even split between `0` and `1`, and the counts change from run to run because measurement is probabilistic.

## Files
- `Challenge_1_Predict_the_Output.ipynb`: the notebook with circuits, predictions, results, histograms and comparison

## How to run
```bash
pip install qiskit qiskit-aer matplotlib pylatexenc jupyter
jupyter notebook Challenge_1_Predict_the_Output.ipynb
```

## Tools
Python, Qiskit, Qiskit Aer simulator, Matplotlib
