# 3D-Mesh-Preprocessing


# 3D Mesh Normalization and Quantization Analysis

# Project Overview
This project analyzes 3D mesh data to understand the effects of normalization and quantization on reconstruction quality.  
I used two normalization methods — **Min–Max scaling** and **Unit-Sphere normalization** — and measure reconstruction error after quantization and dequantization.  
Each `.obj` mesh is processed automatically, and results are stored in separate folders with error plots and reconstructed meshes.

Running the Code

Place all your .obj mesh files in the same directory as the .ipynb notebook or Python script.

Run the notebook (or script) — it will:

Load each mesh automatically.

Apply normalization, quantization, and reconstruction.

Save:

Normalized and reconstructed meshes in respective folders.

Per-axis error plots (meshname_axis_error_plot.png).

Create two global comparison plots:

comparison_MSE_all_meshes.png

comparison_MAE_all_meshes.png

You can open the reconstructed meshes in Blender or MeshLab for visualization.
