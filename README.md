# cross-entropy-loss-function
Implementing cross-entropy loss function on random data

# problem statement
Write a program in C++ which calculates "Cross Entropy Loss". Use random data for calculation.

- The program is implemented to generate a random VALID data and calculate the Cross-Entropy loss for that.
- Implemented for Binary and Categorical Cross-Entropy loss calculations.
- Inputs:
  - argument 1: No. of samples (Default=100, Range > 1)
  - argument 2: No. of classes (Default=5, Range > 1)
  - argument 3: bias parameter (Default=1, Range > 1)
- Output:
  - The cross-entropy loss value.
- Verification:
  - The extra bias parameter generates the random data with a bias, so that increasing the parameter reduces the loss.

# To Compile:
        cd build/
        make loss_function
        
# To Execute:
        cd build/
        
Runs with a default of sample = 100 and class = 5
        ./loss_function

To modify the sample and class size
        ./loss_function 10000 10

To verify the calculation added a bias to the data
The loss reduces as bias is increased (Range >= 1)
        ./loss_function 100 10 3

# Development environment:
1. Ubuntu/Linux OS
2. Opencv for C++ --version=4.4


