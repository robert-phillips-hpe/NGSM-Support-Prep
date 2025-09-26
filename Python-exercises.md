# HPC Mini-Projects: Python Problem Decomposition

These projects are designed for junior programmers to practice **logical thinking** and **problem decomposition** directly in a High-Performance Computing (HPC) context.  

Each project includes:
- **Goal** – what you’ll build.  
- **Decomposition Hints** – how to break the problem into smaller parts.  
- **Extensions** – optional challenges for growth.  

---

## Project 1: File Processing at Scale
**Goal:** Write a Python script to scan thousands of text files and count the number of times a given keyword appears.  

**Decomposition Hints:**
1. Accept keyword + directory as inputs.  
2. Recursively list files in directory.  
3. For each file: open → read → count matches.  
4. Print total count.  

**Extensions:**
- Add command-line arguments with `argparse`.  
- Parallelize with `multiprocessing` so each core processes a subset of files.  

---

## Project 2: Batch Job Automation
**Goal:** Run a Python script on your cluster using a job scheduler (Slurm or PBS).  

**Decomposition Hints:**
1. Write a simple Python script that prints system info (hostname, CPU count, time).  
2. Create a batch script that requests 2 nodes, 4 tasks each.  
3. Submit with `sbatch` or `qsub`.  
4. Capture output logs.  

**Extensions:**
- Write a wrapper that submits multiple jobs with varying parameters (e.g., different random seeds).  

---

## Project 3: Monte Carlo Simulation (Serial → Parallel)
**Goal:** Approximate π using random sampling, first serially, then in parallel.  

**Decomposition Hints:**
1. Generate random (x, y) points inside unit square.  
2. Check if inside circle.  
3. Estimate π = 4 × (points inside / total points).  
4. Extend with `multiprocessing` or `mpi4py` to split work across processes.  
5. Gather results and compute average.  

**Extensions:**
- Compare runtime for 1 core vs. multiple cores.  
- Add timing and scaling plots.  

---

## Project 4: Log Analysis on HPC Nodes
**Goal:** Write a Python script to parse scheduler logs and report average job runtime.  

**Decomposition Hints:**
1. Read log file line-by-line.  
2. Extract job ID, start time, end time.  
3. Compute runtime = end – start.  
4. Aggregate statistics (mean, median, max).  

**Extensions:**
- Visualize results using `matplotlib`.  
- Run analysis in parallel when logs are split across multiple files.  

---

## Project 5: Parallel Word Count
**Goal:** Implement a parallelized "word count" program (classic HPC exercise).  

**Decomposition Hints:**
1. Split text file into chunks.  
2. Assign chunks to workers with `multiprocessing.Pool`.  
3. Each worker computes a word frequency dictionary.  
4. Merge dictionaries into final result.  

**Extensions:**
- Scale to gigabyte-size input.  
- Try with `mpi4py` for distributed processing.  

---

## Project 6: Workflow Pipeline
**Goal:** Build a mini data pipeline that chains together multiple steps on an HPC cluster.  

**Decomposition Hints:**
1. Step 1: Generate synthetic data (Python).  
2. Step 2: Process data (filter, transform).  
3. Step 3: Analyze (compute stats, visualize).  
4. Write a batch script that runs all three steps in sequence.  

**Extensions:**
- Submit each step as a dependent job in Slurm (`--dependency`).  
- Add logging and error handling.  

---

## 📊 Tracking Progress

| Project | Key Skill | Completed? |
|---------|-----------|------------|
| File Processing | Breaking down large I/O tasks | ☐ |
| Batch Job Automation | Linux + scheduler workflows | ☐ |
| Monte Carlo Simulation | Parallelization basics | ☐ |
| Log Analysis | Text parsing & aggregation | ☐ |
| Parallel Word Count | MapReduce thinking | ☐ |
| Workflow Pipeline | Multi-step HPC workflows | ☐ |

---
