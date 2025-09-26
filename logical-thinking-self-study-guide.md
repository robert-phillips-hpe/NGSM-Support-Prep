# Self-Study Plan: Logical Thinking & Problem Decomposition for Python in HPC

## 🎯 Goals
- Build strong logical reasoning and systematic problem-solving skills.  
- Learn to decompose complex problems into smaller steps.  
- Apply these skills in **Python** within a **Linux/HPC environment**.  
- Practice solving both algorithmic and HPC-oriented tasks.  

---

## Phase 1: Foundations of Logical Thinking
**Objective:** Build habits of structured, stepwise reasoning.

- [MIT OCW – How to Speak (Patrick Winston)](https://ocw.mit.edu/resources/res-tll-004-how-to-speak-january-iap-2018/)  
  *Frameworks for structured thinking and communication.*  

- [Brilliant – Logic Puzzles](https://brilliant.org/courses/logic/)  
  *Interactive reasoning exercises to practice logical problem solving.*  

**Exercise:**  
- Keep a notebook. For each puzzle, write *how* you broke the problem down into steps.  

---

## Phase 2: Problem Decomposition with Algorithms
**Objective:** Learn to express problems in pseudocode and structured steps.

- [CMU CS Academy – Problem Decomposition](https://academy.cs.cmu.edu/exercise_problems/problem-decomposition)  
  *Practice breaking problems into subproblems.*  

- [Khan Academy – Algorithms](https://www.khanacademy.org/computing/computer-science/algorithms)  
  *Introduces algorithmic thinking and step-by-step procedures.*  

**Exercise:**  
- For any problem, write pseudocode first. Example: simulate rolling dice until a target is reached. Break into input, process, and output.  

---

## Phase 3: Applying Problem Solving in Python
**Objective:** Implement decomposed solutions as clean Python code.

- [Exercism – Python Track](https://exercism.org/tracks/python)  
  *Hands-on coding practice with structured problems.*  

- [Real Python – Data Structures & Problem Solving](https://realpython.com/python-data-structures/)  
  *How to use lists, dicts, sets, etc. for building solutions.*  

**Exercise:**  
- Pick an Exercism problem. Write pseudocode → implement in Python → test with sample input.  
- Compare multiple solutions (e.g., iterative vs. recursive).  

---

## Phase 4: Linux Problem Solving Basics
**Objective:** Connect logical problem solving with the Linux environment used in HPC.

- [The Linux Command Line (Free Book)](https://linuxcommand.org/tlcl.php)  
  *Covers systematic approaches to problem solving on Linux.*  

**Exercises:**  
1. Write a Bash script that counts the number of `.py` files in a directory.  
   - Decompose: list files → filter by extension → count results.  
2. Write a Python script that reads log files and extracts lines matching a pattern.  
   - Decompose: open file → iterate → match regex → print/save results.  

---

## Phase 5: HPC-Specific Problem Solving
**Objective:** Apply decomposition to HPC workflows and parallel jobs.

- [LLNL HPC Tutorials – Parallel Computing](https://hpc-tutorials.llnl.gov/parallel_computing/)  
  *Introduces breaking work into parallel tasks.*  

- [NERSC New User Training](https://docs.nersc.gov/)  
  *Practical guide to HPC workflows and batch jobs.*  

**Exercises:**  
1. **Batch Job Script**  
   - Write a Slurm or PBS script that runs a Python program on multiple cores.  
   - Break into: load modules → request resources → run job → save output.  

2. **Parallel Work Decomposition**  
   - Write a Python script using `multiprocessing` to calculate word counts across many files in parallel.  
   - Decompose: split file list → assign tasks to workers → combine results.  

3. **Scaling Problem**  
   - Implement a Monte Carlo π approximation in serial Python.  
   - Extend to parallel execution with `mpi4py`.  
   - Compare runtime and reflect on decomposition: setup → distribution → collection.  

---

## Phase 6: Regular Practice & Reflection
**Objective:** Reinforce decomposition and reasoning as a habit.

- Weekly practice:
  - Solve one [Project Euler](https://projecteuler.net/) problem in Python.  
  - Submit one Exercism solution.  
  - Run one Python script on your HPC cluster.  

- Keep a **problem-solving journal**:
  - Problem statement  
  - Decomposition steps  
  - Pseudocode outline  
  - Final implementation notes  

---

## 📊 Progress Tracker

| Phase | Skills | Checkpoint |
|-------|--------|------------|
| 1 | Logical reasoning | Solved 10+ logic puzzles, documented reasoning |
| 2 | Decomposition & pseudocode | Writes pseudocode for each problem |
| 3 | Python implementation | Completed 5 Exercism problems with tests |
| 4 | Linux workflows | Built 2 shell/Python scripts for file/log tasks |
| 5 | HPC workflows | Ran a parallel Python job on HPC cluster |
| 6 | Reflection | Maintains weekly journal entries |

---
