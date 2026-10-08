# Custom Kernels

An incremental learning project exploring GPU programming with CUDA
and Triton, from basic operations to efficient Transformer training.
Concepts are implemented and explored step by step through small
notebooks.

## Notebooks

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shoaibphysics/custom-kernels/blob/main/notebooks/01_performance_basics.ipynb) [01_performance_basics.ipynb](notebooks/01_performance_basics.ipynb) — Arithmetic operations, memory traffic, arithmetic intensity, and performance estimates.

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shoaibphysics/custom-kernels/blob/main/notebooks/02_cpu_performance_basics.ipynb) [02_cpu_performance_basics.ipynb](notebooks/02_cpu_performance_basics.ipynb) — CPU benchmarking, Python versus NumPy, memory layout, dependencies, and threading.

## Getting started

Open a notebook using its **Open in Colab** button, or install the
project dependencies locally with `uv`:

```bash
uv sync
```

For local work, open a notebook in `notebooks/` and select the project's
`.venv` Python environment. Run the cells from top to bottom.

CUDA and Triton experiments require a compatible GPU environment.
Dependencies will be added as the project develops.

Work in progress.