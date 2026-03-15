# IITM BDM Capstone Project: Enhancing Product Uptake for Kayal Wellness Center

This repository contains the analysis and code for a capstone project from IIT Madras Online BS Degree Program in Business Data Management (BDM). The project investigates barriers to product adoption and sales optimization for Kayal Wellness Center, a Herbalife distributor in Bodinayakanur, India.

## Project Overview
Kayal Wellness Center sells Herbalife nutrition products since May 2025 but faces challenges in customer uptake and sales growth. This analysis uses survey data from 53 respondents (July-August 2025) and four months of sales data (May-August 2025) to identify key insights like non-price barriers (awareness, trust), target demographics (21-40 age group), and top products (Formula-1, Shake Mate, Afresh).

## Key Findings
- Price is not the primary barrier (Z-test: z=-3.98, p=0.000068); trust and awareness dominate.
- No significant urban-rural difference in willingness to spend (Z-test: p=0.79).
- ABC analysis: Category A products (Formula-1, Shake Mate, Afresh) contribute 81% of sales.
- Top motivators: free trials, testimonials, smaller packs.

## Methodology
- **Survey Analysis**: Google Forms data cleaned in Google Sheets; pivot tables, stacked bar charts, Z-tests for hypothesis testing.
- **Sales Analysis**: Excel-digitized diary data; Pareto/ABC classification for product prioritization.
- **Tools**: Google Sheets for stats/visuals; potential Python (Pandas, Matplotlib) for replication.

## Recommendations
- Build awareness/trust via workshops, free trials, testimonials (projected 20-25% conversion lift).
- Promote hero products and bundles (12-15% revenue boost).
- Shift to digital sales tracking (Excel/POS).
- Target 21-40 age group with referrals/discounts.

| Focus Area | Action | Projected Impact |
|------------|--------|------------------|
| Awareness & Trust | Workshops, trials, testimonials | 20-25% conversion in 3-6 months |
| Hero Products | Promotions, bundles | 12-15% revenue increase |
| Data Recording | Digital POS/Excel | Better inventory, repeat sales |
| Engagement | 21-40 targeting | 5-10% retention boost |

## Repository Structure
```
.
├── data/
│   ├── survey_responses.xlsx     # Anonymized survey data
│   └── sales_data_may-aug.xlsx   # Product sales records
├── notebooks/
│   ├── 01_survey_analysis.ipynb  # Demographics, Z-tests, visuals
│   └── 02_sales_abc_analysis.ipynb # Pareto charts, ABC classification
├── src/
│   ├── hypothesis_tests.py       # Z-test functions
│   └── abc_classifier.py         # Sales categorization
├── report/
│   └── IITM_BDM_PROJECT_Final.pdf # Full capstone report
├── requirements.txt              # Python deps: pandas, scipy, matplotlib
└── README.md                    # This file
```

## Limitations
- Survey sample: 53 responses; sales data: 4 months only.
- Assumes stable market conditions.

## Author
Jeevaharini K B 
