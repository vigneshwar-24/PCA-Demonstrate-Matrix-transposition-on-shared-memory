# PCA-Demonstrate-Matrix-transposition-on-shared-memory
Comparing the Performance of the Rectangular Shared Memory Kernels with  grid (1,1) block (16,16)

## Aim:
To compare the performance of Rectangular Shared Memory Kernels with a grid (1,1) and a block (16,16) for Matrix Transposition.

## Procedure:
Step 1:
Define constants for block dimensions, padding, and shared memory configurations.

Step 2:
Implement a function to print data.

Step 3:
Implement multiple kernel functions for performing matrix transposition using shared memory.

Step 4:
Set up CUDA device, configure grid and block dimensions, allocate device memory, perform matrix transposition using each kernel function, copy results to host, optionally print the data, and free the allocated memory.

Step 5:
Reset the CUDA device.

Step 6:
Terminate the program.

## Output:
![image](https://github.com/sherwin-roger0/PCA-Demonstrate-Matrix-transposition-on-shared-memory/assets/50732268/a96d412e-7f72-4e90-9cae-ae5dae8a23f5)

## Result:
Thus,the program to compare the performance of Rectangular Shared Memory Kernels with a grid (1,1) and a block (16,16) for Matrix Transposition has been successfully executed.
