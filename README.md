# MAT-350 Project Two: Applied Linear Algebra

This repository contains solutions for Project Two in MAT-350: Applied Linear Algebra. The project explores concepts such as Singular Value Decomposition (SVD), rank approximations, image compression, and error calculation through various MATLAB problems.

## Project Details

- **Course**: MAT-350: Applied Linear Algebra
- **Date**: October 25th, 2024
- **Author**: Kane Miller

## Problems Overview

1. **Rank-1 Approximation and RMSE**  
   Compute the rank-1 approximation of a matrix using SVD, and calculate the root-mean square error (RMSE) between the original matrix and its rank-1 approximation.

2. **Rank-2 Approximation and Comparison**  
   Construct a rank-2 approximation and compare it with the rank-1 approximation by analyzing the RMSE.

3. **Orthogonality Checks with Dot and Cross Products**  
   Perform calculations on the SVD-generated vectors, including dot and cross products, to verify orthogonality.

4. **Span of Matrix Columns**  
   Determine if selected columns of the SVD matrix span \( R^3 \) by evaluating their rank.

5. **Image Compression Using SVD**  
   Load an image, determine the value of \( k \) for a target compression ratio, and construct a rank-\( k \) approximation of the image.

6. **Image Approximation and RMSE Calculation**  
   Display the image approximation and calculate the RMSE between the original and approximated images.

7. **Compression Ratio Analysis**  
   Analyze image approximations for various compression ratios, observing trends in image quality and recommending the optimal ratio.

## Requirements

- MATLAB (for executing `.mlx` files and running SVD-based computations)
- `image.mat` file (from the Project Two Supported Materials)

## Usage

1. Open MATLAB.
2. Run each problem sequentially in the `Project_Two.mlx` file to reproduce the results and images as specified.

## Explanation and Observations

Each problem includes an explanation of the approach and observations from the computed results. The trends in image quality with varying compression ratios are especially discussed in Problems 5-7.
