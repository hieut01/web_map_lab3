# COVID-19 County Maps (2020)

## Introduction
Two interactive county-level web maps of COVID-19 in the United States (2020): a choropleth of case **rates per 1,000 residents** and a proportional symbol map of total **case counts**.

## Maps
- Map 1 (Rates choropleth): `map1.html`
- Map 2 (Cases proportional symbols): `map2.html`

## Screenshots
- Map 1: *(add screenshot in `/img` and link here)*
- Map 2: *(add screenshot in `/img` and link here)*

## Primary Functions
**Map 1 (Rates)**
- Choropleth styling using `rates`
- Hover popup showing `county`, `state`, `rates`, `cases`, `deaths`, `pop18`
- Hover outline highlight
- Albers projection

**Map 2 (Counts)**
- Proportional symbols sized by `cases`
- Hover popup showing `county`, `state`, `cases`, `deaths`, `fips`
- Click-to-zoom interaction
- Albers projection

## Libraries
- Mapbox GL JS v2.8.1

## Data Sources
- COVID-19 cases/deaths: The New York Times (county totals for 2020)
- Population for rates: 2018 ACS 5-year estimates
- County boundaries: U.S. Census Bureau

## Credits / Acknowledgment
- Lab template and instructions: GEOG 458 (Bo Zhao)
- Data processed for lab use (per handout): Steven Bao
