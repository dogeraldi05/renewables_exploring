# Exploring renewables sources 
```
Starting from data visualization, and moving forward to clustering 
```


# Renewable Energy Share Analysis (2000–2025)

Exploratory data analysis of global renewable energy adoption using country-level data from 2000 to 2025.

## Dataset

`renewable_energy_share_2000_2025.csv` — 7,636 rows, 33 columns covering 309 countries and regions.

Key columns: `renewables_share_elec`, `solar_share_elec`, `wind_share_elec`, `hydro_share_elec`, `fossil_share_elec`, `gdp`, `energy_per_capita`.

## Approach

1. **Data overview** — understand shape, data types, and descriptive statistics.
2. **Missing values** — identify which columns have gaps and how severe they are.
3. **Trend analysis** — track the global average renewables share over time.
4. **Country ranking** — find the top 10 countries by renewables share in the latest year.
5. **Correlation** — measure relationships between energy sources and economic indicators.

## Next Steps

- World map visualization of renewables share by country.
- Country-level deep dives and regional comparisons.
- Clustering countries by energy mix profile.
- Regression between GDP per capita and renewables adoption.

## Requirements

```
pandas
numpy
matplotlib
seaborn
```
