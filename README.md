# Parallel Task Graph Analyzer

A Python-based tool for analyzing task dependency graphs and understanding how computational workloads can be executed in parallel. It evaluates task dependencies, identifies critical paths, estimates parallelism, and simulates processor scheduling to explore execution time and speedup.

## Overview

Many computational problems can be represented as directed acyclic graphs (DAGs), where each node represents a task and each directed edge represents a dependency between tasks.

The Parallel Task Graph Analyzer examines these graphs to help understand task execution order, available concurrency, and the impact of processor availability on overall performance.

## Features

- **Task Dependency Analysis:** Represents computational workloads as directed task graphs.
- **Critical Path Analysis:** Identifies the longest dependency path and its execution cost.
- **Work Analysis:** Calculates total computational work across all tasks.
- **Parallelism Estimation:** Estimates average and maximum available concurrency.
- **ASAP Scheduling:** Determines the earliest possible start and finish times of tasks.
- **Processor Scheduling Simulation:** Simulates task execution with a configurable number of processors.
- **Performance Analysis:** Compares execution times and calculates speedup for different processor counts.
- **Multiple Graph Examples:** Demonstrates analysis using different task dependency structures.

## Concepts Covered

- Parallel and distributed computing
- Directed acyclic graphs (DAGs)
- Task dependencies and precedence constraints
- Critical path and total work
- Concurrency and parallelism
- Static task scheduling
- Processor utilization and execution time
- Speedup analysis

## Technologies

- Python 3
- Standard Python library

No external Python packages are required.

## Getting Started

### Prerequisites

Install Python 3.10 or later.

Check your Python installation:

```bash
python --version
```

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/parallel-task-graph-analyzer.git
```

Navigate to the project directory:

```bash
cd parallel-task-graph-analyzer
```

### Run the Project

```bash
python q9_task_graph_analyser.py
```

If your system uses the Python launcher on Windows, you can also run:

```bash
py q9_task_graph_analyser.py
```

## Output

The program analyzes the included task graphs and reports results such as:

- Total computational work
- Critical path and its length
- Task execution order and timing
- Available parallelism
- Processor scheduling results
- Execution time and speedup comparisons

The exact output depends on the graph definitions and scheduling configuration in the source code.

## Project Structure

```text
parallel-task-graph-analyzer/
├── q9_task_graph_analyser.py
├── README.md
└── .gitignore
```

## Learning Objectives

This project demonstrates how dependency graphs can be used to model parallel workloads, identify execution bottlenecks, and estimate the performance benefits of running tasks on multiple processors.

## Future Improvements

- Visualize task graphs using graphical diagrams.
- Add more scheduling strategies.
- Compare processor utilization across scheduling algorithms.
- Support user-defined task graphs.
- Export analysis results to CSV or JSON.

## License

This project is intended for educational and research purposes. Add a license such as MIT if you want others to reuse and modify the code under those terms.
