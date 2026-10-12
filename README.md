# DataVisualisation-TP2025 — TP1

Simple solution of the [teacher's TP1](https://github.com/ahmed3991/DataVisualisation-TP2025/blob/main/TP1/TP1.md), covering the required tasks only.

- **TP1.ipynb**: executed notebook, with real outputs and the written answers.
- **tp1.py**: equivalent Python entry point.
- **EXPLICATION_AR.md**: Arabic explanation of each step and the results.
- **data/**: the actual source data used.
- **results/**: generated results and **REPORT.md** with the required answers.

## Run

Download `TP1.ipynb` from this private repository, upload it to [Google Colab](https://colab.research.google.com/), and choose **Runtime → Run all**. The first cell installs missing libraries. Private GitHub links can require authentication; uploading the downloaded notebook avoids that issue.

Alternatively, from this repository folder:

```sh
python -m pip install -r requirements.txt
python tp1.py
```

Verified: all notebook cells executed successfully; the daily differences and seven-day averages were checked against the source series. Three required charts and the critique are included.
