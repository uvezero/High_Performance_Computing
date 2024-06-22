# High_Performance_Computing
High-Performance Computing (HPC) Course Assignments.

This repository contains my coursework for the High-Performance Computing (HPC) module in my Master's program at UCL. It includes several assignments focused on numerical methods, parallel computing, and performance optimization.

Assignment 1: Wave Problem with Sparse Matrices
In this assignment, I solved a one-dimensional wave problem using the finite differences method and implemented the solution with sparse matrices. The objective was to understand sparse matrix representations' computational efficiency and accuracy in solving partial differential equations (PDEs).

Assignment 2: Heat Equation with GPU Acceleration
This task involved solving the heat equation for a rod using both CPU and GPU implementations. The GPU acceleration was achieved using Numba's CUDA module, demonstrating significant performance improvements over traditional CPU methods.

Assignment 3: Sparse Matrix-Vector Multiplication (SpMV)
The third assignment focused on implementing and optimizing sparse matrix-vector multiplication (SpMV) operations. I implemented custom sparse matrix classes, such as CSR (Compressed Sparse Row) format, and compared their performance with standard dense matrix operations using NumPy.

Assignment 4: Comparative Analysis of Iterative Solvers
In this part, I performed a comparative performance analysis of iterative solvers, including Conjugate Gradient (CG) and Generalized Minimal Residual (GMRES) methods, for solving linear systems with symmetric positive definite matrices. The analysis included benchmarking the residuals and convergence rates of these solvers.

Extensions and Additional Work
Additionally, I explored implementing custom matrix structures, such as the Ellpack format, to further optimize sparse matrix operations. These extensions provided insights into the advantages and trade-offs of different sparse matrix formats in high-performance computing scenarios.

Technologies and Tools
- Python
- Numpy
- Scipy
- Matplotlib
- Numba (CUDA for GPU acceleration)
- Jupyter Notebooks

Any feedback and suggestions are welcome!
