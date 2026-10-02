# CS 361 Homework 2 submission notes

## Part 1

The workbook `CS361_HW2_Part1_NAND.xlsx` changes the targets to the NAND truth table and runs 200 online gradient-descent updates for each requested learning rate. The final four squared errors are:

| Learning rate | (0,0), expected 1 | (0,1), expected 1 | (1,0), expected 1 | (1,1), expected 0 | Maximum |
|---:|---:|---:|---:|---:|---:|
| 1.0 | 0.000250 | 0.038890 | 0.039939 | 0.057801 | 0.057801 |
| 2.0 | 0.000012 | 0.016886 | 0.017400 | 0.024418 | 0.024418 |
| 0.5 | 0.003337 | 0.073390 | 0.074211 | 0.115942 | 0.115942 |

For this initialization and 200 updates, R=2 has the smallest maximum final error.

## Parts 2 and 3

Upload `CS361_HW2_Parts2_3_MNIST.ipynb` to Google Colab and run all cells. The notebook trains both networks under matching conditions, records elapsed time and test loss, plots validation loss by epoch, and prints a careful comparison. Actual timing depends on the selected Colab hardware, so use the values produced by your run in the submitted explanation.

The 256-128-64 model contains three hidden layers and therefore needs a separate 10-unit output layer. The notebook includes the output layer update as W4/b4 in addition to the assignment's requested W1/b1, W2/b2, and W3. If your instructor intended “three layers” to include the output layer, the architecture would instead be 784 to 256 to 128 to 10, with W3 as the output matrix.

For screenshots, capture the workbook Summary tab, the Colab comparison table and loss chart after training, and the drawing UI after predicting a hand-drawn digit.
