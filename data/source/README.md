# Source Data Files

## Grower / Permit Records
- **fresno_growerlist_cm.xlsx** — Fresno County Ag Commissioner pesticide use permit grower list (2023). Created by Gibson Angel, Fresno County AG Commissioner office. Contains 19,446 rows, 2,309 unique farms, 174 crop types. Used for the CA Crop Pairs tab.
- **County_Ag_Commissioner_Report_2022_data_by_commodity.xlsx** — NASS compilation of 99 commodities × 56 CA counties (acreage + value, 2022). Not yet used in dashboard.

## USDA Census of Agriculture 2022 (CA County Acreage)
Tables from COA 2022 Vol 1, Ch 1 — used to build the California by County chart:
- **COA2022_Vol1_Ch1_Table71.csv** — Almonds
- **COA2022_Vol1_Ch1_Table72.csv** — Walnuts
- **COA2022_Vol1_Ch1_Table73.csv** — Pistachios
- **COA2022_Vol1_Ch1_Table74.csv** — Peaches / Nectarines
- **COA2022_Vol1_Ch1_Table75.csv** — Cherries
- **COA2022_Vol1_Ch1_Table76.csv** — Apples
- **COA2022_Vol1_Ch1_Table77.csv** — Grapes (bearing acres, county level)
- **sod_quickstats.csv** — Sod/turf acreage by CA county from USDA NASS QuickStats

## FAO World Data
- **world_orchards_2022.csv** — FAO 2022 orchard & fruit crop acreage by country. Used for the World view.

## Notes
- The full USDA QuickStats bulk download (`qs_census2022.txt.gz`, ~295MB) is not included due to size. Download from: https://quickstats.nass.usda.gov/
- **sanjoaquin_Permits-2024-.xlsx** — San Joaquin County Ag Commissioner pesticide use permit grower list (2024). 1,586 unique farms, 148 crop types.
- **stanislaus_Pesticide_Use_Reports_...xlsx** — Stanislaus County pesticide use reports (2021-2023). 629,192 application rows deduplicated to 2,026 farms, 71 crop types.
