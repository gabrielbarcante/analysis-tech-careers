# Tech Careers in 2025: What the Stack Overflow Survey Tells Us

- [Tech Careers in 2025: What the Stack Overflow Survey Tells Us](#tech-careers-in-2025-what-the-stack-overflow-survey-tells-us)
  - [Installation](#installation)
  - [Project Motivation](#project-motivation)
  - [File Descriptions](#file-descriptions)
  - [Results](#results)
  - [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)


## Installation<a name="installation"></a>
- Prerequisites: Python >= 3.11, Git
- Clone:
  - git clone <repo-url>
  - cd analysis-tech-careers
- Environment (choose one):
  - Create:
    - Windows (PowerShell): python -m venv .venv
    - macOS/Linux: python -m venv .venv
  - Activate:
    - Windows: .\.venv\Scripts\Activate.ps1
    - macOS/Linux: source .venv/bin/activate
- Install:
  - pip install -r requirements.txt
- Optional:
  - Copy .env.example to .env and set variables as needed

## Project Motivation<a name="motivation"></a>
The tech landscape is always changing, but what does it really look like to be a developer in 2025? We dove into the massive [2025 Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co), which collected responses from over 49,000 developers, to answer a few key questions about salaries, technologies, and the global developer community.

The core objective of this machine learning project is to transform the descriptive statistics of the survey into actionable predictive intelligence. Specifically, we will focus on solving the critical business problem of predicting a developer’s current annual compensation based on their stated technologies, experience level, location, and educational background. The key question we aim to answer is: 
> What is the optimal machine learning model and feature set for accurately predicting a developer's annual compensation in the 2025 technology market?


## File Descriptions<a name="files"></a>
- data/
  - stack-overflow-developer-survey-2025.zip: original datasets
  - 20251027 23.00.00 Exchange Rates.xlsx: Excel file containing currency exchange rates as of 27/10/2025 at 23:00:00
- tech-careers-analysis.ipynb: exploratory analysis, reports and machine learning modeling
- requirements.txt: Python dependencies
- .env.example: environment variable template
- LICENSE: project license
- README.md: this document


## Results<a name="results"></a>
The main findings of the exploratory analysis can be found at the post available [here](https://medium.com/@gabriel.barcante/tech-careers-in-2025-what-the-stack-overflow-survey-tells-us-b6b919da3495).


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
- License: MIT (see LICENSE)
- Authors: Gabriel Barros
- Acknowledgements:
  - [2025 Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co)
  - Open-source libraries used in this project (pandas, numpy, matplotlib, etc.)

