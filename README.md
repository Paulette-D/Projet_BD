# Big Data Spark NLP Project

This directory contains the rewritten Quarto deliverable for the Spark/NLP/stylometry homework.

## Render

Install the project dependencies in a Python environment using Spark 3.5.x:

```powershell
python -m pip install -r requirements.txt
```

Then render:

```powershell
quarto render our_report.qmd
```

The report downloads public-domain texts into `DATA/raw_texts/`, then writes derived tables to `DATA/silver/`, `DATA/gold/`, and `DATA/benchmarks/`.

The raw novels are intentionally not committed.
