# Rubik’s Cube Solver – AeroHack’25 Submission

Hi, I’m Garlapati Hema, and this is my project for AeroHack’25 hosted by Collins Aerospace.

---

## About the Project

This is a Python-based Rubik’s Cube Solver for a 3x3 cube. It accepts a custom scramble and uses the IDA* (Iterative Deepening A*) algorithm to find a solution. The cube is animated using Matplotlib so that each solving step can be visualized clearly. The total execution time is also displayed.

---

## Motivation

"Solving problems with code gives me joy."

I’ve always found the Rubik’s Cube fascinating — a problem that’s as much about logic as it is about patience. Through this project, I wanted to create not just a solver, but an educational tool that shows how each step works.

---

## What It Does

- Accepts a user-defined scramble sequence (example: `F R U R' U' F'`)
- Models a 3x3 cube with 6 color-coded faces
- Solves the cube using the IDA* algorithm with a simple yet effective heuristic
- Animates every move using Matplotlib
- Measures and displays the time taken to solve the cube
- Follows clean, modular, object-oriented code structure

---

## Technologies Used

| Component     | Technology     |
|---------------|----------------|
| Programming Language | Python 3 |
| Development Platform | Google Colab |
| Algorithm     | IDA* Search    |
| Visualization | Matplotlib     |
| Output Formats | `.ipynb` and `.py` |

---

## Algorithm Overview

- **IDA*** is used instead of BFS to reduce memory usage and improve depth efficiency
- The heuristic counts the number of misplaced tiles per face
- The algorithm avoids unnecessary reverse moves for optimization
- Time complexity is approximately O(b^d), but performs better in practice for a 3x3 cube

---

## Performance Summary

- Scramble used: `F R U R' U' F'`
- Moves in solution: 11
- Execution time: ~24.32 seconds
- Status: Solved and animated successfully

---

## Sample Output

Screenshots were taken at each key step:
1. Scrambled state
2. Solving step-by-step animation
3. Final solved cube

(Refer to the attached presentation for visuals.)

---

## Future Improvements

While this is a complete functional solver, there are several enhancements planned:

- Add support for 4x4 and larger cubes
- Use Kociemba’s Algorithm for faster, optimal solutions
- Build a Streamlit-based web interface for live interaction
- Export solving steps to a GIF or video
- Add metrics on move optimality and scramble difficulty

---

## About Me

I’m Garlapati Hema, currently pursuing B.Tech at KL University.  
University ID: 2200031072  
Email: 2200031072cseh@gmail.com

I enjoy building intelligent systems and solving logical challenges through code. This project reflects my interest in algorithms, AI, and visual feedback.

---

## Included Files

| File Name                            | Description                                 |
|-------------------------------------|---------------------------------------------|
| `RubiksCubeSolver.ipynb`            | Google Colab notebook (full code and output)|
| `hemarubikscubesolver.py`           | Script version for standalone execution     |
| `Garlapati_Hema_RubiksCube_AeroHack25_Final.pptx` | Presentation slides with screenshots and explanation |
| `README.md`                         | Project documentation (this file)           |

---

## Contact

If you'd like to learn more or try out the project, feel free to reach out:

Email: 2200031072cseh@gmail.com  
University: KL University  
ID: 2200031072
