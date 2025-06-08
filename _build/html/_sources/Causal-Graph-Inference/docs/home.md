<title>Causal Graph Learning</title>

# Causal Graph Learning


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

# About Causal Graph Inference

In this educational collection, you will learn about Causal Graph Learning and its applications. Causal graph learning is a subfield of machine learning and causal inference that focuses on discovering and analyzing cause-effect relationships from data, represented as directed graphs (e.g., Bayesian networks or structural causal models). These graphs help uncover underlying data-generating processes and enable robust predictions and interventions.

Example:
Causal Discovery Toolbox

## Why Causal Graph Learning?
Interpretability: Causal graphs provide transparent representations of cause-effect relationships.
Robustness: Unlike correlation-based models, causal models generalize better under distribution shifts.
Interventional Insights: Enables "what-if" analysis (e.g., predicting effects of policy changes).
Broad Applications: Used in healthcare, economics, genomics, and AI fairness.

Categories of Causal Graph Learning Methods
## Causal Discovery Algorithms
Methods to infer causal structures from observational or experimental data:

Constraint-Based:
PC Algorithm (Tests conditional independence).
FCI Algorithm (Handles unobserved confounders).

Score-Based:

GES (Greedy Equivalence Search) (Optimizes a score metric like BIC).
Functional Causal Models:
LiNGAM (Linear non-Gaussian models).
ANM (Additive Noise Models).

## Causal Inference Methods
Techniques to estimate causal effects from learned graphs:
Do-Calculus: Pearl’s Framework.
Propensity Scores: Inverse probability weighting.
Double Machine Learning: EconML.

## Prerequisites

- **Programming Skills**: Familiarity with Python programming. A great starting point is [Think Python](https://allendowney.github.io/ThinkPython/), which offers a deep dive into the language's essentials.
- **Mathematics**: Basic understanding of calculus and statistics at the undergraduate level.
- Current students of **MDS** at **FUM University** are already familiar with the concepts covered in the [**FDS**](https://fum-cs.github.io/fds/) and [**MFDS**](https://fum-cs.github.io/mfds/) courses.


## Example Applications
Healthcare: Predicting treatment effects from electronic health records.
Paper: "Causal Inference in Medicine".
Economics: Policy evaluation using synthetic controls.
Book: "Mostly Harmless Econometrics".
AI Fairness: Detecting discrimination in ML models.
Tool: IBM’s AIF360.

## Courses and Tutorials
Causal ML Course (Stanford).
Elements of Causal Inference (MIT).
PyWhy Tutorials.

## References
[1] An Introduction to Propensity Score Methods for Reducing the Effects of Confounding in Observational Studies by Peter C. Austin

[2] Counterfactuals and Causal Inference: Methods and Principles for Social Research by Stephen L. Morgan & Christopher Winship

[3] An Introduction to Causal Inference by Judea Pearl


