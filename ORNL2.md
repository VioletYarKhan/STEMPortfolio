# Oak Ridge National Laboratory Internship: Molecular Dynamics Validation

[Home](README.md) | [Robotics](Robotics.md) | [ORNL Internship 1](ORNL1.md) | [ORNL Internship 2](ORNL2.md) | [Tetris AI](TetrisAI.md)

## Problem:
Validate molecular dynamics simulations of liquid water using high-performance computing to assess simulation accuracy and computational efficiency.

<!--
Source - https://stackoverflow.com/a
Posted by Viper
Retrieved 2026-01-04, License - CC BY-SA 3.0
-->

<img id="ORNL2Poster" src="Violet_Sullivan_NGP_FINAL_page-0001.jpg">

<style>
#ORNL2Poster {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 800px;
    height: auto;
}
</style>

## Context
- Oak Ridge National Laboratory  
- 5 Weeks in Summer 2025  
- Team: Two interns, supervised by research scientists  
- Role: Parallelization and statistical analysis

## Technical Challenges:
- Simulations of water molecules require high computational power and precise analysis of molecule interactions.
- Serial methods were too slow for large-scale validation, necessitating parallel computation strategies, which had not yet been created.

## My Contributions:  
- Partitioned the simulated water box and analyzed atomic interactions in parallel using MPI4Py  
- Developed scripts to compute local densities, pairwise distances, and distribution functions efficiently  
- Compared parallel results to serial runs to validate accuracy and quantify speed increase  

## Tools & Methods:  
- Python, MPI4Py library, complex use of numpy and MDAnalysis
- Use of high-performance computing clusters running on Slurm Workload Manager  
- Statistical analysis of molecular dynamics data

## Results:  
- Research results presented at Oak Ridge Leadership Computing Facility User Meeting 2025, where it was awarded 3rd place in the Best Intern Poster competition
- Research results presented at Smoky Mountains Computational Sciences and Engineering Conference 2025
- Parallelization significantly reduced computation time compared to serial methods  
- Enabled large-scale validation of molecular simulations relevant to biomedical research  
- Approach can extend to interactions with proteins in the fluid and experimental comparisons  

## Reflection:  
This project allowed me to harness the power of parallelization for real scientific problems. I learned to translate theoretical methods into scalable workflows and gained experience in combining programming and physical systems.

[Project Repository](https://github.com/VioletYarKhan/Internship-Work-2025)  
[Project Poster PDF](https://drive.google.com/file/d/1o6u2bI8O1qgDeZs3PZByenMVqHwoArR3/view?usp=sharing)
