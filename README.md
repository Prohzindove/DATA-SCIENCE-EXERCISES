# DATA SCIENCE EXERCISES

This repository contains data science exercises and small projects for learning and practice. 
## Repository structure

- notebooks/ - Jupyter notebooks with exercises and worked examples
- data/ - sample datasets used by the notebooks (not always committed; see below)
- scripts/ - utility scripts for preprocessing, evaluation, or reproducible runs
- solutions/ - reference solutions for exercises (optional)
- README.md - this file

> If a directory is missing in this repository yet, create it when you add related files.

## Getting started

1. Clone the repository:

   git clone https://github.com/Prohzindove/DATA-SCIENCE-EXERCISES.git
   cd DATA-SCIENCE-EXERCISES

2. Create a Python environment (recommended):

   - Using conda:
     conda create -n ds-exercises python=3.11
     conda activate ds-exercises

   - Or using venv:
     python -m venv .venv
     source .venv/bin/activate  # macOS / Linux
     .\.venv\Scripts\activate   # Windows (PowerShell)

3. Install dependencies (if a requirements file is added):

   pip install -r requirements.txt

   If there is no requirements.txt yet, typical packages used in these exercises are:

   pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab notebook

4. Start JupyterLab or notebook:

   jupyter lab
   # or
   jupyter notebook

## Data

- Small sample datasets may be placed in the `data/` directory.
- For large datasets, do not commit them to the repo. Instead, add a script under `scripts/` to download and prepare the data, and update the notebooks to read from a local `data/` path.

## Exercise format

- Each exercise notebook should include a short description, objectives, and clearly marked tasks.
- Prefer notebooks named with a leading number to indicate ordering, e.g. `01_exploratory_analysis.ipynb`.
- When adding solutions, place them under `solutions/` or in a separate branch to avoid spoilers.

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository.
2. Create a branch for your feature or exercise: `git checkout -b add-new-exercise`.
3. Add notebooks, scripts, and tests (if any).
4. Commit and open a pull request describing your changes.

Please follow these guidelines:
- Keep notebooks runnable top-to-bottom.
- Clear any large output cells before committing to reduce repo size.
- Add a brief README or header to describe each new exercise.

## License

If you want to add a license, create a `LICENSE` file at the repo root. A common choice is the MIT license.

## Contact

Repository maintained by Prohzindove. For questions or suggestions, open an issue or a pull request on GitHub.
