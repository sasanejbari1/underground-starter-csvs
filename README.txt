Delve Underground-style tunnel monitoring starter dataset
IMPORTANT: These files are SYNTHETIC example data created for learning and portfolio practice.
They are not real Delve Underground data, not a real project record, and not suitable for engineering decisions.

Files:
1. settlement_monitoring.csv — daily settlement readings at five synthetic monitoring stations.
2. groundwater.csv — daily water-level and pore-pressure readings at the same stations.
3. inclinometer.csv — lateral displacement by station, date, and depth.
4. TBM_data.csv — synthetic daily TBM progress and operating parameters.

Suggested first steps:
- Load each file with pandas.read_csv(...)
- Convert date columns with pandas.to_datetime(...)
- Plot settlement_mm against date for one point_id.
- Group by station and calculate maximum settlement.
- Join settlement and groundwater on date + station for exploratory analysis.
- Treat risk thresholds as project-specific; do not label synthetic values as real engineering limits.
