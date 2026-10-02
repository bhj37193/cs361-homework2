# CS 361 Homework 2

This repository contains the three parts of CS 361 Homework 2.

## Contents

- `CS361_HW2_Part1_NAND.xlsx`: formula-driven NAND neuron training for learning rates 1, 2, and 0.5
- `NAND_results_preview.png`: summary of the final NAND errors after 200 updates
- `CS361_HW2_Parts2_3_MNIST.ipynb`: MNIST model comparison, backpropagation equations, and drawing interface
- `submission_notes.md`: result summary and submission guidance
- `Part1_NAND_Summary.png`: final NAND error summary
- `Part2_Equations.png`: loss and backpropagation equations
- `Part2_Architecture.png`: 256-128-64 model summary
- `Part2_Results.png`: measured MNIST comparison and validation-loss graph

## Results

For the NAND neuron, the maximum final squared errors were:

| Learning rate | Maximum error |
| ---: | ---: |
| 1.0 | 0.057801 |
| 2.0 | 0.024418 |
| 0.5 | 0.115942 |

In the recorded MNIST run, the 256-128 baseline trained for 6 epochs with test loss 0.0827 and accuracy 97.59%. The 256-128-64 model trained for 4 epochs with test loss 0.0971 and accuracy 96.98%. The added hidden layer used fewer epochs and less execution time, but produced slightly worse test loss in that run.

Open the notebook in Google Colab and run all cells to reproduce the results and use the drawing interface.
