# Analysis Code for SSRN Paper

This repository contains the **analysis code and notebooks** supporting the paper available on **SSRN**:

**Paper:**  
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5376300 
(SSRN abstract ID: 5376300)

---

## Repository Overview

This repository contains code for the empirical analysis in the paper. It includes:

- Data processing and analysis notebooks
- Scripts used to generate figures and summary statistics
- Output visualizations (PDFs)

**Large raw datasets are intentionally excluded from this repository** and are not tracked in Git. 

---

## Data Access

The analysis relies on several CSV datasets that are **not included here** due to size constraints.

If you would like access to the data used in the analysis, please request it via the following link:

**Data request folder:**  
https://drive.google.com/drive/folders/1It7M_jijPuCWUs5EjZjkZoMLcKoT2hY7

(Data is hosted on **Google Drive**.)

Once downloaded, place the CSV files in the /tprc2025 directory as expected by the notebook.

---

## Running the Analysis

The primary analysis notebook is in tprc.ipynb:

To run the notebook successfully:

1. Download the required CSV files from the data link above
2. Ensure the files are placed in the /tprc2025 directory
3. Open and run `tprc.ipynb` in Jupyter

Without the data files, the notebook will load but **will not execute fully**.

---

## Notes

- This repository contains **analysis code only**
- Large datasets are excluded via `.gitignore`
- Generated outputs (e.g., figures) are located in the /tprc2025/results folder
- Note, since the county+zipcode level analysis rely on the Nominatim API, numbers may vary slightly between runs

---

## Contact

For questions about the analysis or data access, please email isabel AT cmu dot edu.
