# Large-scale CMB EB null tests (Planck 2018)

This repository contains the analysis code and notebooks used in the paper:

> V. Simbolon, *Constraints on large-scale CMB EB correlations from Planck polarization*.

The analysis performs conservative, model-independent null tests of large-scale parity-odd
EB correlations using Planck 2018 polarization data.

---

## Repository contents

- `notebooks/EB_TEST.ipynb`
  Main analysis notebook. Running this notebook reproduces all numerical results and
  figures presented in the paper.
---

## Data

This analysis uses the publicly available Planck 2018 polarization maps,
available from the NASA/IPAC Infrared Science Archive:

https://irsa.ipac.caltech.edu

Due to size and licensing constraints, Planck data products are **not included**
in this repository. The notebooks download the required Planck 2018 FITS files at runtime using `wget`. By default, all data files are downloaded into and loaded from the notebook’s current working directory, which is explicitly defined within the notebook as `DATA_DIR`.

---

## Reproducibility

To reproduce the results:

1. Install the required Python packages.

   For interactive notebook environments (e.g. Google Colab or Jupyter),
   the required packages are installed automatically within the notebook.

   For a local Python environment, the dependencies can be installed using:

   ```bash
   pip install -r requirements.txt
2. Run `notebooks/EB_TEST.ipynb`

The notebook reproduces figures presented in the paper and the reported numerical
constraints.

---

## License

This code is released under the MIT License. See `LICENSE` for details.

## Preprint
Simbolon, V. (2026).
Constraints on large-scale CMB EB correlations from Planck polarization.
Zenodo. https://doi.org/10.5281/zenodo.18136369