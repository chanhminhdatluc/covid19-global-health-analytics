# Global COVID-19 Health Analytics

A business analytics portfolio project that uses **Microsoft Excel** and **Power BI** to examine global COVID-19 outcomes, healthcare readiness, testing capacity, vaccination coverage, mortality, and recovery performance across continents.

![Power BI dashboard](assets/images/powerbi-dashboard.png)

## Project overview

This project was developed for **BUS5PB - Principles of Business Analytics**. The analysis was designed to support World Health Organization decision-making by converting historical COVID-19 data into clear, actionable insights.

The Excel dashboard provides descriptive analysis of cases, deaths, vaccination rates, hospital capacity, healthcare access, and monthly trends. The Power BI dashboard adds interactive filtering, geographic analysis, time-series exploration, and regional comparisons.

## Business problem

COVID-19 outcomes varied substantially between countries and continents. Decision-makers need to understand not only where case numbers were highest, but also where weak testing, limited healthcare access, low vaccination coverage, and poor recovery capacity created greater vulnerability.

This project addresses five questions:

1. How did pandemic burden differ across continents?
2. How did healthcare readiness vary between countries and regions?
3. How did cases and deaths evolve over time?
4. Which regions demonstrated stronger recovery capacity?
5. Where did testing and mortality disparities indicate hidden vulnerability?

## Tools and skills

- **Microsoft Excel:** PivotTables, PivotCharts, slicers, KPI cards, maps, trend analysis
- **Power BI:** interactive dashboards, DAX measures, maps, filters, time-series visuals, drill-through analysis
- **Business analytics:** descriptive and diagnostic analysis, KPI design, regional benchmarking
- **Data storytelling:** translating analytical findings into recommendations for decision-makers

## Dashboard previews

### Power BI dashboard

![Power BI dashboard](assets/images/powerbi-dashboard.png)

### Excel dashboard

![Excel dashboard](assets/images/excel-dashboard.png)

## Key insights

- Europe and the Americas recorded some of the highest confirmed case rates, while South America experienced particularly severe mortality outcomes.
- Africa reported fewer detected cases, but limited testing and elevated mortality in several countries suggested potential under-detection and weaker healthcare capacity.
- Europe and North America generally showed stronger vaccination coverage, hospital capacity, and healthcare access.
- Many African and Pacific Island countries remained vulnerable because of lower vaccination coverage and weaker healthcare access.
- Europe achieved the strongest reported recovery performance, while North America and parts of Africa showed comparatively weaker outcomes.
- Testing was concentrated in Asia, Europe, and North America, while Africa and South America conducted a much smaller share of global tests.

## Selected visual analysis

### Global vulnerability heatmap

![COVID-19 vulnerability heatmap](assets/images/vulnerability-heatmap.png)

The geographic view highlights countries with high deaths per million and helps identify regions where mortality was disproportionately severe relative to population.

### Pandemic evolution over time

![COVID-19 cases and deaths timeline](assets/images/pandemic-timeline.png)

The time-series analysis shows major pandemic waves from 2020 to mid-2021 and illustrates how mortality declined after wider vaccine rollout in better-resourced regions.

### Testing and mortality disparity

![Testing and mortality comparison](assets/images/testing-vs-mortality.png)

The comparison shows that regions with lower testing capacity could still account for a large share of mortality, indicating possible under-detection and surveillance gaps.

## Recommendations

The analysis supports four priority actions:

1. Expand hospital, ICU, oxygen, and emergency-care capacity in vulnerable regions.
2. Improve vaccine procurement, distribution, regional manufacturing, and public confidence.
3. Scale up affordable testing, standardised reporting, and genomic surveillance.
4. Strengthen community resilience through local partnerships, workforce training, and access to essential medicines.

## Repository structure

```text
COVID19_Global_Health_Analytics_Portfolio/
├── README.md
├── assets/
│   └── images/
├── data/
│   └── README.md
├── excel/
│   └── README.md
├── powerbi/
│   └── README.md
└── report/
    └── BUS5PB_Assignment_1_Dat_Luc.pdf
```

## Limitations

The source report notes several limitations, including inconsistent reporting standards, under-testing, missing socioeconomic variables, and incomplete recovery data for some regions. These issues mean that reported case and recovery figures may not fully represent the true scale of the pandemic.

## Future improvements

- Add the original cleaned dataset and a formal data dictionary.
- Upload the Excel workbook and Power BI `.pbix` file.
- Document Power Query transformation steps and DAX measures.
- Add a reproducible Python or SQL data-cleaning workflow.
- Include socioeconomic indicators such as income, population density, age structure, and health expenditure.
- Publish an interactive Power BI report link where permitted.

## Full report

The complete analytical report is available in the [`report`](report/) folder.

## Author

**Chanh Minh Dat Luc**  
Master of Business Analytics - Data Science  
Skills demonstrated: Excel, Power BI, data visualisation, analytical reasoning, and business recommendations.
