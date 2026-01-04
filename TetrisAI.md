# Tetris AI: Neuroevolution and Parallel Training

[Home](README.md) | [Robotics](Robotics.md) | [ORNL Internship 1](ORNL1.md) | [ORNL Internship 2](ORNL2.md) | [Tetris AI](TetrisAI.md)

**Problem:** Can an AI learn to play Tetris optimally using evolutionary algorithms and parallel computation?

**Context:**  
- Personal project / school outreach  
- Timeline: 2024–2025  
- Role: Lead designer and implementer

**Technical Challenge:**  
Training AI agents to play Tetris requires exploring a large solution space and evaluating thousands of possible strategies. Serial training methods were too slow, so parallelization was necessary.

**My Contributions:**  
- Implemented Neuroevolution of Augmenting Topologies (NEAT) to evolve neural networks for gameplay  
- Used multiprocessing to parallelize evaluation of agents and accelerate training  
- Developed a 1v1 Tetris game with similar mechanics to modern Tetris for outreach events to let students play against the AI

**Tools & Methods:**  
- Python, NEAT-Python library  
- Multiprocessing module for parallel evaluation  
- Custom evaluation functions to test multiple gameplay strategies as the project evolved

**Results:**  
- AI learned to achieve a variety of gameplay objectives based on the evaluation function  
- Created a tool that made AI development interesting and interactive for younger students  
- Demonstrated the potential of combining evolutionary algorithms with parallel computation for learning applications

**Reflection:**  
This project taught me how to use software engineering to solve complex problems. I also learned how to communicate technical ideas to a non-technical audience during outreach events to middle and elementary schools.

[AI Training Repository](https://github.com/VioletYarKhan/TetrisAI)  
[1v1 Outreach Game Repository](https://github.com/VioletYarKhan/Tetris_1v1_Remake)
