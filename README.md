# 3D Mesh Normalization and Quantization Analysis

## Project Overview

This project analyzes **3D mesh data** to understand the impact of different **normalization** and **quantization** methods on mesh reconstruction quality.

Two normalization approaches are implemented:

- **Min–Max Scaling**
- **Unit-Sphere Normalization**

Each `.obj` mesh file is processed automatically, and the pipeline measures reconstruction errors after quantization and dequantization.  
All results are saved into organized folders containing normalized meshes, reconstructed meshes, and error plots.

---

## Features

- Automatic loading of all `.obj` meshes in the directory  
- Mesh normalization  
- Quantization and dequantization  
- Reconstruction error computation  
- Per-axis error visualization  
- Global MSE/MAE comparison plots  
- Clean folder structure for results  

---

## Running the Code

1. Place all your `.obj` files in the **same directory** as the Python script or Jupyter notebook.
2. Run the script/notebook.
3. The pipeline will automatically:

   - Load each mesh  
   - Apply normalization  
   - Quantize and dequantize  
   - Reconstruct the mesh  
   - Compute all error metrics  
   - Save output plots and meshes  

---
