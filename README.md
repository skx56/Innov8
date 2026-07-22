# Predicting Troop Betrayal in the War

<p align="center">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge" />
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge" />
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge" />
  <img alt="Machine Learning" src="https://img.shields.io/badge/Machine%20Learning-102230?style=for-the-badge" />
  <img alt="Data Science" src="https://img.shields.io/badge/Data%20Science-1F77B4?style=for-the-badge" />
</p>

<p align="center">
  <strong>A data-science challenge solution for predicting strategic betrayal risk from structured wartime data.</strong>
</p>

Innov8 is a notebook-driven analytical project that models betrayal prediction as a structured machine learning problem. It includes data, solution notebooks, outputs, and a written report for communicating approach and results.

## Core Capabilities

- Explores and models structured challenge data.
- Builds prediction workflows across multiple solution notebooks.
- Produces result artifacts for submission or evaluation.
- Includes a report summarizing problem framing and solution strategy.

## Technical Architecture

The repository is organized around notebook experimentation and output artifacts. Data files feed the solution notebooks, which generate predictions and support the project report.

## Architecture Diagram

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 55, "rankSpacing": 70, "curve": "basis"}, "themeVariables": {"fontSize": "16px", "fontFamily": "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"}}}%%
flowchart TD
  Data["Challenge Dataset"] --> Notebook["Solution Notebooks"]
  Notebook --> EDA["Data Exploration"]
  EDA --> Features["Feature Engineering"]
  Features --> Model["Prediction Model"]
  Model --> Results["result.csv"]
  Results --> Report["Project Report"]

  classDef inputs fill:#FEF3C7,stroke:#D97706,color:#78350F,stroke-width:2.5px;
  classDef process fill:#DBEAFE,stroke:#2563EB,color:#1E3A8A,stroke-width:2.5px;
  classDef data fill:#DCFCE7,stroke:#16A34A,color:#14532D,stroke-width:2.5px;
  classDef agent fill:#F3E8FF,stroke:#9333EA,color:#581C87,stroke-width:2.5px;
  classDef output fill:#FFE4E6,stroke:#E11D48,color:#881337,stroke-width:2.5px;
  class Data inputs;
  class Notebook,EDA,Features process;
  class Results data;
  class Model agent;
  class Report output;
  linkStyle default stroke:#64748B,stroke-width:2.5px;
```

## Technology Stack

- Jupyter notebooks for experimentation and explanation.
- Python data-science workflow with tabular data handling.
- CSV artifacts for input and result output.
- PDF report for formal project communication.

## Repository Structure

- `solution.ipynb` - Primary solution notebook.
- `part2_solution.ipynb` - Secondary solution workflow.
- `part_2_data.csv` - Challenge data artifact.
- `result.csv` - Prediction output.
- `Predicting Troop Betrayal in the War.pdf` - Project report.

## Getting Started

```bash
python -m venv .venv
source .venv/bin/activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

```bash
jupyter notebook
```

## Professional Context

This project demonstrates applied predictive modeling, challenge communication, and reproducible notebook-based analysis.
