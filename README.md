# UK Renewable Electricity Generation (2010–2024)

This project presents an exploratory data analysis of renewable electricity generation in the UK from Q1 2010 to Q4 2024, based on government-published statistics. It includes a detailed LaTeX report with visualisations, statistical tests, and actionable insights.

##  Contents

- `uk_renewables_analysis.tex` – LaTeX source code for the report
- `uk_renewables_analysis.pdf` – Final compiled report
- `figures/` – Plots used in the report (time trends, comparison charts, etc.)

##  Project Overview

The goal of this project is to extract meaningful insights from UK renewable energy data, assess trends, and test relevant hypotheses. It focuses on wind, solar, biomass, and other key technologies, highlighting seasonal effects and long-term growth patterns.

### Key Sections

- Time series analysis of renewable generation
- Seasonal trends in solar production
- Wind vs. solar capacity and output
- Growth analysis: 2010–2014 vs. 2020–2024
- Hypothesis testing using Welch's t-tests
- Policy and infrastructure recommendations

##  Key Findings

- Wind power accounts for 58% of renewable output as of 2024.
- Solar generation peaks significantly in Q2 and dips in Q4.
- Total renewable electricity output increased 5.5x between 2010 and 2024.
- Generation in 2020–2024 was 126% higher than in 2010–2014.

##  Hypothesis Tests

1. **Solar Q2 vs. Q4** – Solar output is significantly higher in Q2 (p = 0.0011).
2. **Wind vs. Solar** – Wind generation is significantly greater than solar (p < 0.001).
3. **Growth Over Time** – Renewable output has significantly increased over time (p < 0.0001).

## Requirements

To compile the LaTeX report:
- A LaTeX distribution (TeX Live, MiKTeX, or Overleaf)
- Required packages: `graphicx`, `booktabs`, `geometry`, `hyperref`, `xcolor`, `parskip`, etc.


