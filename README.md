# 06-Morphological

## Overview
This notebook demonstrates basic morphological image processing operations using OpenCV on binary images.

The lab includes:
- Creating a synthetic binary image with shapes and noise
- Defining square and circular structuring elements
- Applying erosion, dilation, opening, and closing
- Comparing the effect of square and circular kernels

## Tasks Covered

### Task 1
Created a binary image containing:
- Filled circle
- Filled rectangle
- Hollow circle
- Hollow rectangle
- Random salt noise

### Task 2
Defined a 5×5 square structuring element and a circular structuring element.

### Assessment Task 1
Applied:
- Erosion
- Dilation
- Opening
- Closing

using the square kernel.

### Assessment Task 2
Repeated the same operations using a circular kernel.

### Assessment Task 3
Compared the effect of square and circular kernels on image shapes and noise removal.

## Main Concepts Learned
- Erosion shrinks objects and removes small noise.
- Dilation expands objects and fills gaps.
- Opening removes noise while preserving object size.
- Closing fills small holes inside objects.
- Kernel shape affects the final morphology result.

## Tools and Libraries
- Python
- OpenCV
- NumPy
- Matplotlib

## Conclusion
Morphological operations are useful for image cleaning, shape processing, noise removal, and object enhancement. Choosing the correct kernel shape and size is important for achieving the desired result.