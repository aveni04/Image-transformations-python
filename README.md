# Image-transformations-python
Python codes for basic image processing transformations like down sampling, up sampling, Euclidean, Affine, Projective, and Similarity transformations.

This repository contains beginner-friendly Python implementations of fundamental image processing transformations.  
Each example uses **NumPy** and **Matplotlib/OpenCV** to demonstrate how images (or shapes) change under different transformations.  

## Contents
1. **Downsampling & Upsampling**  
   - Reduce or increase image resolution.  
   - Shows how pixels are dropped or replicated.  

2. **Euclidean Transformation**  
   - Rotation + Translation.  
   - Preserves distances and angles.  

3. **Similarity Transformation**  
   - Rotation + Translation + Scaling.  
   - Keeps shape similarity while resizing.  

4. **Affine Transformation**  
   - Rotation, Scaling, Shearing, Translation.  
   - Maps square → parallelogram, keeps parallelism.  

5. **Projective Transformation (Homography)**  
   - General 3×3 matrix.  
   - Adds perspective effect (square → trapezoid).  
