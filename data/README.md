# Dataset notes

The analysis uses two local datasets:

1. `accounting_data.csv` - accounting variables used to construct RNOA and related financial ratios.
2. `EPS.csv` - firm-level earnings-per-share observations used for random-walk and moving-average forecasts.

The report describes the accounting source as covering **21,735 firms from 2000 to 2020**, and the EPS source as covering **12,910 firms from 2009 to 2020**. The loaded accounting file contains 285,491 rows and 21 columns before filtering, while the loaded EPS file contains 84,794 observations before preprocessing.

These raw files are intentionally omitted from the public-ready repository because redistribution permission has not been established.

## To reproduce locally

Place the two files at:

```text
data/accounting_data.csv
data/EPS.csv
```

The cleaned notebook already uses these relative paths.
