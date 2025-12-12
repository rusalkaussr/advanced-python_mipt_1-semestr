# advanced-python_mipt_1-semestr


Overview

This repository accompanies a presentation and a small practical project exploring how graph databases interact with Python applications, and where high-performance computing (HPC) techniques become necessary for graph analytics.


Contents

Slides

The slides cover three main themes:
	•	Graph DBMS fundamentals
Storage models, execution models, and how graph databases represent and process connected data.
	•	Object–Graph Mapping (OGM)
How Python objects map to graph structures (nodes, relationships, properties), and how this differs from traditional ORM approaches in relational databases.
	•	HPC considerations for graph problems
Why many graph algorithms are computationally expensive, where Python struggles, and which techniques are used to push performance further.

Practical Project

The practical part demonstrates a graph-theoretic problem implemented purely on the CPU:
	•	Triangle counting in random graphs G(n, p)
	•	The graph is treated as numeric data using NumPy
	•	Performance is improved using Numba JIT compilation
