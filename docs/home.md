<title>Graph Neural Netwoks</title>

# **Graph Neural Netwoks**


**Maede Mohammadi, Spring 2025**

Computer Science Dept, Ferdowsi University of Mashhad



```{note}
These lectures were built using the new Sphinx-based [Jupyter Book
2.0](https://beta.jupyterbook.org/intro.html) tool set, as part of the
[ExecutableBookProject](https://ebp.jupyterbook.org/en/latest/).  They are
intended mainly as a demonstration of these tools.
Instructions for how to build them from source can be found in the Jupyter
Book documentation.
```

Certainly! Here's an educational overview about **Graph Neural Networks (GNNs)** in a similar style and format:

---

# About Graph Neural Networks (GNNs)

In this educational collection, you will learn about Graph Neural Networks and their applications. GNNs are a class of neural networks designed to operate on graph-structured data, capturing relationships, dependencies, and patterns directly from the graph topology. They are widely used in social network analysis, recommender systems, molecular biology, and more.

## Why Graph Neural Networks?
- **Representation Learning**: Effectively embed nodes, edges, and entire graphs into meaningful vector spaces.
- **Relational Modeling**: Capture complex dependencies that structured data exhibits.
- **Versatility**: Applicable to various tasks—node classification, link prediction, graph classification.
- **Scalability**: Capable of handling large, complex graphs efficiently with modern architectures.

## Categories of Graph Neural Network Methods
### 1. Spectral-Based Methods
Operate in the graph frequency domain using graph Fourier transforms.
- Examples: Spectral Graph Convolution, Chebyshev Networks

### 2. Spatial-Based Methods
Aggregate features from neighboring nodes directly in the graph domain.
- Examples:
  - Graph Convolutional Networks (GCNs)
  - GraphSAGE
  - GIN (Graph Isomorphism Network)
  - GAT (Graph Attention Network)

### 3. Hierarchical and Pooling Methods
Capture graph-level representations by pooling node features.
- Examples:
  - DiffPool
  - SAGPool

## Applications of Graph Neural Networks
- **Social Networks**: Friend recommendation, community detection.
- **Recommender Systems**: Personalized product suggestions.
- **Chemistry & Biology**: Molecular property prediction, protein interaction networks.
- **Finance**: Fraud detection, risk modeling.
- **Natural Language Processing**: Text classification, knowledge graphs.

## Prerequisites

- **Programming Skills**: Familiarity with Python and machine learning frameworks like PyTorch or TensorFlow.
- **Mathematics**: Understanding of linear algebra, graph theory basics, and deep learning fundamentals.
- **Data Handling**: Working with graph datasets such as node features, edge attributes, adjacency matrices.

## Example Applications
Healthcare: Drug discovery and molecular property prediction.
Book: "Graph Representation Learning" (Zhou et al.).
Social Media: Influence maximization and community detection.
Recommender Systems: Product suggestions based on user-item graphs.
Tool: PyTorch Geometric, DGL (Deep Graph Library).

## Courses and Tutorials
- **Graph Neural Networks Course** (Stanford)
- **Graph Machine Learning** (DeepMind)
- PyTorch Geometric Tutorials
- DGL Tutorials and Documentation

## References
[1] An Introduction to Propensity Score Methods for Reducing the Effects of Confounding in Observational Studies by Peter C. Austin

[2] Counterfactuals and Causal Inference: Methods and Principles for Social Research by Stephen L. Morgan & Christopher Winship

[3] An Introduction to Causal Inference by Judea Pearl


