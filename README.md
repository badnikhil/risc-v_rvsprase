# RISC-V LFX Mentorship: Sparse Matrix Multiplication Challenge

## Project Description
This repository contains a C implementation of Sparse Matrix-Vector Multiplication (SpMV) using the **Compressed Sparse Row (CSR)** format. This optimization is essential for high-performance computing on RISC-V architectures, where reducing memory footprint and computational overhead is critical.

## Key Features
- **Efficient CSR Storage**: Minimizes memory usage by storing only non-zero elements.
- **CSR Multiplication Logic**: Implements optimized indexing to perform matrix-vector multiplication.
- **Validation Suite**: includes a comprehensive test harness that validates the implementation against a reference dense matrix multiplication across varied dimensions and densities.

## How to Build and Run

### Compilation
Use any standard C compiler (GCC recommended):
```bash
gcc -o spmv challenge.c -lm
```

### Execution
Run the generated binary to execute the automated tests:
```bash
./spmv
```

## Results
The implementation correctly handles matrices of varying sparsity, consistently passing all 100 test iterations with high numerical precision. 
