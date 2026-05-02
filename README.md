# The Pulse of the City
## An Investigation into the Changing State of the NYC Taxi Ecosystem

**Roll Number (last 4 digits):** 0458  
**Analysis Window:** July – September 2023 (derived from R=8)

---

## Structure

| File | Description |
|------|-------------|
| `notebook/ACT_1.ipynb` | Mathematical time window derivation |
| `notebook/ACT_2.ipynb` | Data acquisition and cleaning |
| `notebook/ACT_3.ipynb` | Behavioural hypothesis testing |
| `notebook/ACT_4.ipynb` | Temporal pattern analysis |
| `notebook/ACT_5.ipynb` | Policy simulation (8% fare increase) |
| `notebook/ACT_6.pbix` | Power BI dashboard |
| `notebook/ACT_7.ipynb` | Closing frame — defensible choices and limits |
| `notebook/figures/` | All saved charts |
| `notebook/powerbi_data/` | CSVs used in Power BI |

---

## Data Setup

Data files are not included in this repo due to size limits.  
Download from the [NYC TLC Trip Record Data portal](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page):

- `yellow_tripdata_2023-07.parquet`
- `yellow_tripdata_2023-08.parquet`
- `yellow_tripdata_2023-09.parquet`
- `green_tripdata_2023-07.parquet`
- `green_tripdata_2023-08.parquet`
- `green_tripdata_2023-09.parquet`
- `fhvhv_tripdata_2023-07.parquet`
- `fhvhv_tripdata_2023-08.parquet`
- `fhvhv_tripdata_2023-09.parquet`
- `taxi_zone_lookup.csv`

Place all files in `notebook/data/` before running the notebooks.

---

## Requirements

```
pip install jupyter numpy pandas matplotlib seaborn scipy pyarrow requests sympy
```
