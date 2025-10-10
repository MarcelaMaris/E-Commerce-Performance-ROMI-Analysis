#📂 Data Folder

This folder contains the datasets used in the Y.Afisha Marketing & Product Analytics project.

samples/ → Contains sample CSV datasets used in the analysis:

visits_log_us.csv — user sessions and traffic sources

orders_log_us.csv — purchase timestamps and revenue

costs_us.csv — daily marketing spend by acquisition source

🧭 Notes

The datasets are provided as CSV snapshots for reproducibility.
In the notebook, data are loaded directly from the data/samples/ folder using relative or local paths.

If you want to reproduce the analysis:

Place the three CSV files (visits_log_us.csv, orders_log_us.csv, costs_us.csv) inside data/samples/.

Run the notebook Project-8-Tripleten.ipynb.

⚙️ The original raw datasets are not included in the repository due to size and privacy restrictions.
Use only the sample versions provided in this folder.