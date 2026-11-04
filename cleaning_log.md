# Cleaning Log
## Data provenance
- Source: NYC TLC Trip Record Data (nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- Downloaded: 4 Nov 2026
- Files: Yellow Taxi Parquet for Jan, Feb, Mar 2024; Taxi Zone Lookup (CSV)
- Scope: development on 3 months; full year to be added once the pipeline works

## Load and inspect (4 Nov 2026)
- Raw rows loaded: 9,554,778 (Jan-Mar 2024 yellow taxi), 19 columns
- Finding: pickup timestamps range from 2002-12-31 to 2024-04-01
- Planned rule: keep only pickups between 2024-01-01 and 2024-03-31 inclusive
- Rows affected: [fill in from Cell 5]
