# NorthStar Urban Mobility & Logistics — Coursework

Database Development & Data Analytics case study submission.

## Notebooks

| # | Notebook | Marks | Open |
|---|----------|-------|------|
| 01 | SQL in R | 15 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erucard/northstar-coursework/blob/main/notebooks/01_SQL_in_R.ipynb) |
| 02 | R Analytics | 15 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erucard/northstar-coursework/blob/main/notebooks/02_R_Analytics.ipynb) |
| 03 | Python Data Processing | 20 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erucard/northstar-coursework/blob/main/notebooks/03_Python_Data_Processing.ipynb) |
| 04 | MongoDB Development | 20 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erucard/northstar-coursework/blob/main/notebooks/04_MongoDB_Development.ipynb) |
| 05 | Query Optimisation | 10 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Erucard/northstar-coursework/blob/main/notebooks/05_Query_Optimisation.ipynb) |

## Repository Structure

```
├── notebooks/          ← 5 Colab notebooks (press play to run)
├── data/
│   ├── raw/            ← 9 original CSVs
│   ├── cleaned/        ← Zone-standardised, imputed CSVs
│   └── json/           ← MongoDB-ready JSON collections
├── NorthStar_Report.docx
└── README.md
```

## Data Files (4,030 total records)

| File | Rows | Description |
|------|------|-------------|
| customers.csv | 650 | Profiles, loyalty scores |
| orders.csv | 1,250 | Orders, zones, values |
| deliveries.csv | 950 | Status, costs, routes |
| drivers.csv | 170 | Ratings, training |
| vehicles.csv | 120 | Battery, maintenance |
| hubs.csv | 8 | Locations, capacity |
| incidents.csv | 280 | Delivery incidents |
| complaints.csv | 320 | Complaints, compensation |
| app_events.csv | 640 | Platform events |
