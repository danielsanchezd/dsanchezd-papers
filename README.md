# Dynamic-Angle Problem-Solving: A Control Policy for LLMs Under Missing Context

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17073701.svg)](https://doi.org/10.5281/zenodo.17073701)

**Author:** Daniel Sanchez Diaz  
**PDF:** [`dynamic-angle.pdf`](./dynamic-angle.pdf)  
**Version:** 1.0.1  
**Released:** 2025-09-07  
**Repository:** https://github.com/danielsanchezd/dynamic-angle-dsanchezd  
**License:** See [`LICENSE.md`](./LICENSE.md) (CC BY-NC-ND 4.0)

---

## Overview

This work presents **Dynamic-Angle**, a stake-aware control policy for LLMs operating under missing or uncertain context. The policy:
- maintains an internal confidence \(C_t\) with **stake-based thresholds** (e.g., 0.60/0.80/0.95),
- selects actions via a **myopic utility** (expected confidence gain ÷ cost, weighted by evidence independence),
- uses a **Two-Speed Context Gate** (Micro → Full) to minimize user burden,
- includes **reframing triggers** and **optimal stopping** to avoid loops and reduce hallucinations.

The paper situates Dynamic-Angle relative to ReAct, Reflexion, Self-RAG, DSPy, and recent UQ and search methods, and outlines limitations and future work (e.g., calibration, learned utilities, tree-search integration).

## How to cite

If you use this work, please cite it (DOI: **10.5281/zenodo.17073701**).

**BibTeX**
```bibtex
@misc{SanchezDiaz_DynamicAngle_2025,
  author  = {Sanchez Diaz, Daniel},
  title   = {Dynamic-Angle Problem-Solving: A Control Policy for LLMs Under Missing Context},
  year    = {2025},
  version = {1.0.1},
  doi     = {10.5281/zenodo.17073701},
  url     = {https://github.com/danielsanchezd/dynamic-angle-dsanchezd}
}

