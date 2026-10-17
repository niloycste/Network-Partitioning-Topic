# Network Partitioning Teaching Notebooks

Two Jupyter notebooks used for a lab session on network partitioning during a Faculty Development Program at the Department of Computer Science and Engineering, South Asian University, New Delhi (May 24-29, 2026).

## Notebooks

- `Network_partitioning_karate_reordered_Karger_KL_FM.ipynb` — a guided walkthrough of Zachary's Karate Club graph, including Karger min-cut, Kernighan-Lin, Fiduccia-Mattheyses, multilevel/METIS, spectral partitioning, and Markov clustering.
- `Network_partitioning_Manual_Graph.ipynb` — a manual graph-partitioning walkthrough with implementation and visualizations of several partitioning methods.

## Requirements

The notebooks use Python 3 with the following packages:

```text
networkx
matplotlib
pandas
numpy
pymetis
markov_clustering
```

Open either notebook in Jupyter or Google Colab. Some sections require the optional `pymetis` or `markov_clustering` package.
