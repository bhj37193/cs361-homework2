# CS 361 Homework 2

This repository contains the three parts of CS 361 Homework 2.

## Contents

- `01_Part1_NAND_Spreadsheet.xlsx`: formula-driven NAND neuron training for learning rates 1, 2, and 0.5
- `NAND_results_preview.png`: summary of the final NAND errors after 200 updates
- `08_Parts2_3_MNIST_Code.ipynb`: MNIST model comparison, backpropagation equations, and drawing interface
- `submission_notes.md`: result summary and submission guidance
- `02_Part1_NAND_Results.png`: final NAND error summary
- `03_Part2_Equations.png`: loss and backpropagation equations
- `04_Part2_Network_Architecture.png`: 256-128-64 model summary
- `05_Part2_Training_Results.png`: measured MNIST comparison and validation-loss graph
- `06_Part3_Drawn_Digit.png`: hand-drawn digit used by the interface
- `07_Part3_Prediction_Results.png`: expected digit, prediction, error, confidence, and probability graph

## Results

For the NAND neuron, the maximum final squared errors were:

| Learning rate | Maximum error |
| ---: | ---: |
| 1.0 | 0.057801 |
| 2.0 | 0.024418 |
| 0.5 | 0.115942 |

In the recorded MNIST run, the 256-128 baseline trained for 6 epochs with test loss 0.0827 and accuracy 97.59%. The 256-128-64 model trained for 4 epochs with test loss 0.0971 and accuracy 96.98%. The added hidden layer used fewer epochs and less execution time, but produced slightly worse test loss in that run.

Open the notebook in Google Colab and run all cells to reproduce the results and use the drawing interface.
