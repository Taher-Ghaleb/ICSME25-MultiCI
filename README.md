# Multi-CI Replication Package


**Authors:** Nitika Chopra and Taher A. Ghaleb

This repository contains the replication package for the paper "_From First Use to Final Commit: Studying the Evolution of Multi-CI Service Adoption_," accepted at the 41st IEEE International Conference on Software Maintenance and Evolution 2025 (ICSME'25). The package provides all resources needed to reproduce the analyses and results presented in the paper.

## Package Structure

```
project-root/
├── data/                         # Data used in the study
│   ├── java_ci_services_existence_check.csv
│   ├── java_ci_services_yml_stats.csv
│   ├── java_commits_per_ci_files.csv
│   ├── java_contributors.csv
│   ├── java_repo_commit_counts.csv
│   └── java_repo_details.csv
├── scripts/                      # Analysis scripts
│   └── script.ipynb
├── results/                      # Generated visualizations
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

## Installation

This package was developed and tested with **Python 3.x**.

Clone the repository and install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. **Run Analysis:**
   Open the Jupyter notebook and execute the analysis:
   ```bash
   jupyter notebook scripts/script.ipynb
   ```
   The notebook analyzes CI service adoption and evolution, including:
   - Percentage of projects using 1–6 CI services together.
   - Top CI service pairs used together.
   - Data visualizations and summary statistics.

2. **Save Results:**
   Generated results and figures will be displayed in the notebook or can be saved to the `results/` folder.

## Data

The `data/` folder contains all data used in the study. See the paper and script comments for details on each file.

## Results

The `results/` folder contains:
- Analysis visualizations as reported in the paper (and more).

## License

Code in this repository is licensed under the MIT License. See the LICENSE file.

Data files in this repository are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license unless otherwise noted. You are free to share and adapt the data with appropriate credit.

## How to Cite

If you use this package, please cite our paper:

> Nitika Chopra and Taher A. Ghaleb. "From First Use to Final Commit: Studying the Evolution of Multi-CI Service Adoption." In Proceedings of the 41st IEEE International Conference on Software Maintenance and Evolution (ICSME), 2025.

```bibtex
@inproceedings{chopra2025multici,
  title={From First Use to Final Commit: Studying the Evolution of Multi-CI Service Adoption},
  author={Chopra, Nitika and Ghaleb, Taher A.},
  booktitle={Proceedings of the 41st IEEE International Conference on Software Maintenance and Evolution (ICSME)},
  year={2025},
  organization={IEEE}
}
```
