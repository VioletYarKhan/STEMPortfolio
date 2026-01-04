[Home](README.md) | [ORNL Internship 2](ORNL2.md) | [Tetris AI](TetrisAI.md) | [Robotics](Robotics.md)
# Oak Ridge National Laboratory Internship — Molecular Dynamics Validation

**Problem:** Validate molecular dynamics simulations of liquid water using high-performance computing to assess simulation accuracy and computational efficiency.

**Context:**  
- Oak Ridge National Laboratory  
- Summer 2025  
- Team: Two interns, supervised by research scientists  
- Role: Parallelization and statistical analysis

**Technical Challenge:**  
Simulations of water molecules require high computational power and precise analysis of oxygen–oxygen interactions. Serial methods were too slow for large-scale validation, necessitating parallel computation strategies.

**My Contributions:**  
- Partitioned the simulated water box and analyzed atomic interactions in parallel using MPI4Py  
- Developed scripts to compute local densities, pairwise distances, and distribution functions efficiently  
- Compared parallel results to serial runs to validate accuracy and quantify speedup  

**Tools & Methods:**  
- Python (NumPy, MPI4Py)  
- High-performance computing clusters  
- Statistical analysis of molecular dynamics data

**Results:**  
- Parallelization significantly reduced computation time compared to serial methods  
- Enabled large-scale validation of molecular simulations relevant to biomedical research  
- Approach can extend to water-protein interactions and experimental comparisons  

**Reflection:**  
This project emphasized the power of computational methods for real-world scientific problems. I learned to translate theoretical methods into scalable, efficient workflows and gained experience bridging coding, physics, and statistical analysis.

[Project Repository](https://github.com/VioletYarKhan/Internship-Work-2025)  
[Final Report PDF](https://drive.google.com/file/d/1o6u2bI8O1qgDeZs3PZByenMVqHwoArR3/view?usp=sharing)
