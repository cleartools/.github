<img src="assets/cleartools-title.svg" alt="cleartools" width="420">

`cleartools` develops sparse normalization, PCA, and annotated-matrix tools for
compositional count data in single-cell and other genomics workflows.

## Repositories

| Repository | Description |
| --- | --- |
| [`scclrR`](https://github.com/cleartools/scclrR) | R/Seurat package for sparse PFlogPF normalization and PCA, including a rendered Angelidis pseudobulk vignette. |
| [`scclr`](https://github.com/cleartools/scclr) | Python package for sparse PFlogPF normalization and sparse PCA on AnnData and MuData objects. |
| [`runorm`](https://github.com/cleartools/runorm) | Rust normalization routines for shifted centered log-ratio / PFlogPF transformations. |
| [`rupca`](https://github.com/cleartools/rupca) | Rust sparse PCA routines for shifted-CLR matrices represented as a sparse matrix plus a centering vector. |
| [`ruanndata`](https://github.com/cleartools/ruanndata) | Rust-first annotated matrix container modeled after Python `anndata`. |

## Documentation

- `scclrR` documentation: <https://cleartools.github.io/scclrR/>
- `scclrR` Angelidis pseudobulk vignette:
  <https://cleartools.github.io/scclrR/articles/seurat-pflogpf.html>
