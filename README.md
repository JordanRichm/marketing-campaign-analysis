# Marketing Campaign Performance Analysis

## Overview
An exploratory data analysis of a synthetically generated marketing campaign dataset comprising 200,000 records across multiple companies, campaign types, channels, customer segments, and durations. The analysis examines four core business questions relevant to marketing strategy, surfaces the methodological limitations of cross-company aggregate analysis, identifies the ecological fallacy as a key constraint on the commercial applicability of the findings, and proposes a more rigorous analytical approach as a result.

## Business Questions
1. Which campaign type drives the highest average ROI?
2. Which channel yields the highest average conversion rate?
3. Which customer segment can be acquired most cost-efficiently?
4. Does campaign duration have a meaningful relationship with ROI?

## Key Findings
- No commercially significant variation in ROI was observed across campaign types, channels, customer segments, or duration at the aggregate level.
- This convergence is attributable to the ecological fallacy arising from cross-company aggregate analysis, whereby firm-level variance is obscured when data is collected across organisations.
- The dataset is synthetically generated, which compounds the absence of meaningful variance and constrains the commercial applicability of the findings.
- These limitations point towards a more rigorous analytical approach: firm-level segmentation, longitudinal trend analysis, and multivariate modelling.

## Recommendations
1. **Avoid aggregate-level budget allocation decisions** - performance differentials at the aggregate level are insufficient to justify strategic budget reallocation.
2. **Shift toward multivariate modelling** - interaction effects between campaign type, channel, audience, and duration are invisible to univariate analysis and require regression or decision tree methods to surface.
3. **Incorporate longitudinal analysis** - the dataset spans two years and includes a date column that presents an opportunity for temporal trend analysis at the firm level.

## Tools and Technologies
- Python 3
- pandas
- matplotlib
- Jupyter Notebook

## Dataset
- **Source:** [Marketing Campaign Performance Dataset - Kaggle](https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset)
- **Size:** 200,000 rows, 16 columns
- **Nature:** Synthetically generated

## Project Structure
Marketing Campaign Performance Analysis/
│
├── data/
│   └── marketing_campaign_dataset.csv
├── outputs/
│   ├── acquisition_by_segment.png
│   ├── conversion_rate_by_channel.png
│   ├── roi_by_campaign_type.png
│   └── duration_vs_roi.png
└── marketing_analysis.ipynb

*Note: `.conda/` and other environment files are excluded via `.gitignore`.*

## Author
Jordan Richmond
[LinkedIn](www.linkedin.com/in/jordan-richmond-ab0227213)
