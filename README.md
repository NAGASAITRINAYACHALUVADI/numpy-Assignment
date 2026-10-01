# NumPy Assignment

**Name:** Naga Sai Trinaya Chaluvadi
**Notebook:** `NagaSaiTrinayaChaluvadi.ipynb`

## Overview
This notebook contains my work for the NumPy assignment for AI/ML. It covers NumPy fundamentals (array operations, vectorization, broadcasting, reshaping, aggregation along axes), handling missing values, feature scaling, reproducibility with random seeds, and working with image batches.

## Notebook Structure
| Section | Topic | Questions |
|---|---|---|
| A | Conceptual Understanding | A1–A10 |
| B | Predict the Output | B1–B8 |
| C | Coding / Implementation | C1–C8 |
| D | Applied / Scenario-Based Problems | D1–D3 |
| E | Bonus / Challenge | E1–E2 |

## Topics Covered
- **Section A:** NumPy vs Python lists, vectorization, `*` vs `@`, broadcasting, `flatten()` vs `ravel()`, `axis=0` / `axis=1`, normalization vs standardization, `np.nanmean()`, image batch shapes, reproducibility with `np.random.default_rng(seed)`.
- **Section B:** Predicting the output of short snippets on shapes, slicing, boolean masking, matrix products, NaN handling, `np.where()`, `ndim` / `size`, and reversed slicing.
- **Section C:** `np.where()` labelling, z-score standardization function, `np.vstack()`, column-wise standardization, linear prediction `X @ w + b` with MSE, seeded random data, min-max image normalization, average pixel value across a batch.
- **Section D:** NaN preprocessing pipeline (detect, impute, standardize), RGB image batch and average image, and debugging model code (shape mismatch and operator precedence).
- **Section E:** Per-column min-max normalization and a fully vectorized three-way score classification.

## Requirements
- Python 3.x
- `numpy`
- Jupyter Notebook or JupyterLab

Install the libraries with:

```bash
pip install numpy notebook
```

## How to Run
1. Open `NagaSaiTrinayaChaluvadi.ipynb` in Jupyter.
2. Choose **Kernel > Restart & Run All**.
3. Check that every cell runs without errors and all outputs are visible.

## Notes
- No external data files are needed. All arrays are created inside the notebook.
- Cells that use `np.random` without a fixed seed (C4, C8, D2) give different values on each run. Seeded cells (A10, C6) give identical results every time.
- Explicit loops over data are avoided in favour of vectorized NumPy operations.
