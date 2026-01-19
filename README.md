# heat-risk-maricopa

Heat risk analysis for Maricopa County — a starter repository for organizing data, notebooks, and code used to analyze and visualize heat-related risks (extreme heat, vulnerabilities, exposures) across Maricopa County.

## Contents

- `data/` — raw and processed datasets (not checked into Git; use a data pipeline)
- `notebooks/` — exploratory and analysis Jupyter notebooks
- `src/` — reusable Python package or scripts
- `tests/` — unit and integration tests
- `docs/` — documentation, reports, and figures

## Quick start

1. Clone the repository:
   git clone git@github.com:Christian-Dusenge/heat-risk-maricopa.git
   cd heat-risk-maricopa

2. (Optional) Create and activate a Python virtual environment:
   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .venv\Scripts\activate      # Windows PowerShell

3. Install dependencies (example):
   pip install -r requirements.txt

4. Add data to `data/` (or configure remote data source), then run analyses in `notebooks/` or `src/`.

## Contributing

- Use feature branches and open PRs against `main`.
- Add unit tests to `tests/` and keep notebooks reproducible where possible.
- Document code in `docs/`.

## License

This project is licensed under the MIT License — see the `LICENSE` file for details.