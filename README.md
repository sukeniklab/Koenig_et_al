# Infection Tunes the Dynamics of Adenoviral E1A Disordered Regions

**Authors:** Patrick Koenig¹²³, Alexander Truong⁴, Hadrien Lehman⁴, Bailey-J C. Sanchez², Juris A. Grasis²³⁵ ✉, and Shahar Sukenik⁶⁷ ✉

\---

## Overview

This repository contains all data processing scripts, cleaned datasets, and figure-generation code associated with the manuscript **"Infection Tunes the Dynamics of Adenoviral E1A Disordered Regions"**. The code supports reproduction of all main and supplemental figures from raw imaging and spectroscopy data through final publication-quality plots.

\---

## Repository Structure

```
.
├── main\_figures/
├── supplemental\_figures/
└── raw\_data\_cleanup/
```

### `main\_figures/`

Scripts and CSV files used to generate all figures in the main manuscript. Each subdirectory or script is named according to the figure it produces. CSV files contain the processed, analysis-ready datasets used directly by the plotting scripts.

### `supplemental\_figures/`

Scripts and CSV files for all supplemental figures. Organized in parallel with the main figures directory. Supplemental figure scripts follow the same conventions as main figure scripts.

### `raw\_data\_cleanup/`

Scripts for processing raw experimental data into the cleaned CSV files used by the figure scripts. This includes image segmentation outputs, FRET efficiency calculations, osmotic stress delta computations, and quality control filtering steps.

\---

## Requirements

```
python <= 3.10
pandas
numpy
matplotlib
scipy
```

Install dependencies with:

```bash
pip install pandas numpy matplotlib scipy 
```

\---

> \*\*Note:\*\* Raw imaging data is not included in this repository due to file size. Cleaned CSV files in `main\_figures/` and `supplemental\_figures/` are sufficient to reproduce all figures without re-running the cleanup pipeline.

\---

## Data Description

|Directory|Contents|
|-|-|
|`main\_figures/`|Processed CSVs + plotting scripts for main text figures|
|`supplemental\_figures/`|Processed CSVs + plotting scripts for supplemental figures|
|`raw\_data\_cleanup/`|Pipeline scripts for converting raw data to cleaned CSVs|

\---

## Contact

Correspondence regarding this manuscript should be directed to:

* **Juris A. Grasis** — University of California, Merced
* **Shahar Sukenik** — University of Syracuse

\---

## Citation

If you use this code or data in your work, please cite:

> Koenig P, Truong A, Lehman H, Sanchez BJC, Grasis JA, Sukenik S.
> \*Infection Tunes the Dynamics of Adenoviral E1A Disordered Regions.\*
> (2026)

\---

## License

This repository is made available for academic use. Please contact the corresponding authors for permissions outside of academic research.

