Repository Structure (Artifact Contents)

This artifact intentionally contains only the files listed below.
There is no figures/ directory in the submitted artifact.
All figures are generated at runtime inside the notebooks.

Contents:
- README.md
- LICENSE
- ARTIFACT_EVALUATION.md
- notebooks/AQKAN_Mathematical_Experiments.ipynb
- notebooks/AQKAN_Unit_Tests.ipynb
- requirements.txt


Important Note for Reviewers

The artifact is not a software library.

The notebooks themselves are the primary research artifact.

No pre-generated figures are included by design.

Running the notebooks top-to-bottom reproduces all figures and checks.

How to Run

Install dependencies:

pip install -r requirements.txt


Open the notebooks:

jupyter notebook notebooks/


Restart the kernel and run all cells sequentially.

# AQ-KAN Reproducibility Artifact

This repository contains the official reproducibility artifact for the paper:

**Adaptive Quantum-Inspired Kolmogorov–Arnold Networks (AQ-KAN)**

The artifact consists of two Jupyter notebooks that together validate
the theoretical and methodological claims of the paper through
mathematical experiments and unit tests.

---

## 📂 Contents

- `AQKAN_Mathematical_Experiments.ipynb`  
  Reproduces all experiments from Sections 4 and 5, including:
  - boundedness and stability,
  - robustness under distributional drift,
  - dependency recovery,
  - performance trade-offs,
  - computational scaling.

- `AQKAN_Unit_Tests.ipynb`  
  Verifies key mathematical properties via unit-test-style checks:
  - Lemma 1.1 (state boundedness),
  - Proposition 4 (determinism),
  - Corollary 2.1 (measurement stability),
  - Lemma 2.1 (bounded dependency weights),
  - Theorem 4 (scaling behavior).

---

## ▶️ How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
