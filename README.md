# PhD Research Analysis

**Researcher:** Hassan Abdelhamid Hassan Soliman  
**Doctoral thesis:** *The Efficacy of a Cognitive Strategy-Based Pedagogical Intervention on Academic Learning Gain: A Randomized Controlled Trial and Predictive Modeling Approach*

## Overview

This repository contains the Python/Jupyter analytical code supporting the doctoral thesis named above. It is provided to support computational transparency and reproducibility of the analytical workflow.

The notebook covers:

- integration and preprocessing of the study datasets;
- quality-control and missing-data screening;
- construction of the Working Memory Capacity (WMC) composite;
- calculation of learning gain;
- statistical assumption testing;
- two-way analysis of variance (ANOVA);
- robustness analyses;
- moderated regression and regression diagnostics; and
- supplementary machine-learning classification.

## Repository contents

- `analysis.ipynb` — cleaned Jupyter Notebook containing the analytical workflow.
- `requirements.txt` — Python package dependencies.
- `CITATION.cff` — citation metadata for the repository.
- `.gitignore` — prevents participant-level datasets and generated results from being committed accidentally.
- `LICENSE` — repository-use notice.

## Data availability and participant privacy

The original participant-level datasets are **not included in this public repository**.

The study datasets contain information relating to student participants and include variables that may permit direct or indirect identification when combined. Consequently, the original CSV/XLSX datasets and participant-level analytical dataset are excluded from this repository to protect participant confidentiality and to comply with applicable ethical and data-governance requirements.

The public notebook has been cleaned of stored cell outputs and direct personal identifiers. The analytical code is provided so that the computational procedures used in the thesis can be inspected independently.

Researchers seeking access to underlying data should follow the data-access conditions specified in the doctoral thesis and any applicable institutional or ethical requirements.

## Running the analysis

The notebook expects the authorised study datasets to be available locally. These files are intentionally excluded from version control.

Create a Python environment and install the required packages:

```bash
pip install -r requirements.txt
```

Then place the authorised datasets in the local location expected by the notebook and run:

```bash
jupyter notebook analysis.ipynb
```

Do **not** commit participant-level datasets to this repository.

## Citation

If citing the analytical code, use the citation information provided in `CITATION.cff`.

Before creating the final GitHub release, replace the `repository-code` placeholder in `CITATION.cff` with the final GitHub repository URL.

## Version

Initial thesis-analysis release: **v1.0.0**
