# project

# Data Science Toolbox Assignment 6

## Introduction

The **Project** repository is a educational repo created as part of the Data-Science-Toolbox course. The repository is focused on understanding best practices for file naming, project organization, and managing virtual environments.

## Project Structure

```
project/
|
|- data/
|   |- dataset.csv  # project data set
|
|- docs/
|   |- Documents/
|   |   |- report_01.docx
|   |   |- report_02.docx
|   |   |- report_03.docx
|   |   |- report_04.docx
|   |   |- report_05.docx
|   |
|   |- weekly-meetings/
|   |   |- 2023-03-15T1300_meeting-minutes.md
|   |   |- 2023-03-21T1400_meeting-minutes.md
|   |   |- 2023-04-03T1300_meeting-minutes.md
|   |   |- 2023-04-11T1400_meeting-minutes.md
|   |   |- 2023-04-20T1200_meeting-minutes.md
|   |
|   |- report.pdf
|
|- images/  # analysis images
|   |- dataset_image.png
|   |- predictions.png
|
|- reports/  # analysis using Jupyter notebook
|   |- Report.ipynb
|
|- src/  # source code directory
|   |- 01_generate-data.py
|   |- 02_visualize-data.py
|   |- 03_plot-predictions.py
|
|- environment.yaml  # conda environment configuration
|- LICENSE
|- README.md  # project documentation
```

## Dependencies

The environment includes the following key dependencies:
- `ipykernel`
- `jupyterlab`
- `matplotlib`
- `pandas`
- `python>=3.10`
- `scikit-learn=1.3.0`

## Workflow