## Repository Structure (Artifact Contents)

```text
AQ_KAN/
├── AQ_KAN_Evidence.ipynb
├── AQKAN_Unit_Tests.ipynb
├── AQKAN_Mathematical_Experiments.ipynb
├── AQKAN_Appendix_Reference.pdf   (optional)
├── CITATION.cff
├── LICENSE
└── README.md
```


License: Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0). Commercial use is not permitted without explicit authorization.

This artifact intentionally contains only the files listed below.
There is no figures/ directory in the submitted artifact.
All figures are generated at runtime inside the notebooks.

Adaptive Quantum-Inspired Kolmogorov–Arnold Networks (AQ-KAN)

🧠 Scope and Limitations

AQ-KAN is quantum-inspired, not a quantum algorithm.

No claims of quantum speedup are made.

No benchmark performance comparisons are provided.

The focus is on structural validity, stability, and adaptability.

This repository contains the complete experimental evidence, unit tests, and mathematical validation for the Adaptive Quantum-Inspired Kolmogorov–Arnold Network (AQ-KAN) framework.

AQ-KAN is proposed and evaluated as a computational artifact, not as a task-specific predictive model. The implementation emphasizes architectural invariants, adaptive dynamics, structured dependency modeling, and provable linear complexity, consistent with Design Science Research (DSR) methodology.

Important Note for Reviewers

The artifact is not a software library.

The notebooks themselves are the primary research artifact.

No pre-generated figures are included by design.

Running the notebooks top-to-bottom reproduces all figures and checks.

# AQ-KAN Reproducibility Artifact

This repository contains the official reproducibility artifact for the paper:

**Adaptive Quantum-Inspired Kolmogorov–Arnold Networks (AQ-KAN)**

The artifact consists of two Jupyter notebooks that together validate
the theoretical and methodological claims of the paper through
mathematical experiments and unit tests.

## Citation

If you use this repository or the accompanying notebooks, please cite:

**Siddarth Laxminarayanan**  
*Adaptive Quantum-Inspired Kolmogorov–Arnold Networks (AQ-KAN)*, 2026.  
Reproducibility Artifact.

Citation metadata is provided in `CITATION.cff`.

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
 
- `AGUA_Appendix_Reference.pdf`  

Appendix and reference material supporting:

- Formal definitions
- Lemmas and proofs
- Operator formulations
- Measurement stability arguments
- Complexity analysis references

---
🧪 Experimental Philosophy

All experiments adhere to the following principles:

Artifact-centric evaluation (DSR-compliant)

Deterministic execution (fixed seeds, no stochastic learning)

No task-specific loss optimization

Explicit invariant enforcement

Linear time and space complexity

Interpretability by construction

AQ-KAN is evaluated as a general adaptive computational substrate, not as a trained ML model.

## ▶️ How to Run

Requirements

Python ≥ 3.9

NumPy

Matplotlib

Jupyter Notebook / JupyterLab

Install dependencies:
### 1. Install dependencies
```bash
pip install -r requirements.txt
