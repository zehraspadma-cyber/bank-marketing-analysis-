# Bank Marketing Campaign Analysis

## Project Overview
This project explores a Portuguese bank's direct marketing campaign data to identify patterns associated with term deposit subscriptions and potential opportunities for campaign targeting.

## Dataset
- **Source:** [UCI Machine Learning Repository — Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- **Records:** 45,211
- **Original columns:** 17
- **Target variable:** `y` — whether a client subscribed to a term deposit

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed
1. Data exploration and quality checks
2. Overall subscription rate analysis
3. Subscription rates by job and age group
4. Age and job segmentation using heatmaps
5. Campaign contact frequency analysis
6. Previous campaign outcome analysis

## Key Findings
- **Overall conversion:** Approximately 11.7% of records resulted in a term deposit subscription.
- **Job segments:** Students and retired clients had comparatively high subscription rates.
- **Age groups:** Clients aged 65+ and 18–24 showed higher subscription rates than many middle-aged groups.
- **Contact frequency:** Records with fewer campaign contacts generally showed higher conversion rates. This is an association, not evidence that additional calls cause lower conversion.
- **Previous campaign outcome:** Clients with a previously successful campaign outcome had a conversion rate of approximately 65%, compared with approximately 9% among records with an unknown previous outcome.

## Data Quality and Limitations
- The dataset has no fully duplicated rows based on the checked columns.
- The `poutcome` variable contains approximately 81.75% `unknown` values, which were retained for analysis.
- Some demographic subgroups have small sample sizes; segment comparisons should consider record counts.
- Findings are descriptive and should not be interpreted as causal effects.

## Business Recommendations
- Further investigate student and retired customer segments for potential targeting opportunities.
- Evaluate the cost-effectiveness of repeated customer contacts before changing contact strategies.
- Consider previous campaign outcomes as a useful segmentation signal, while accounting for missing information.
- Validate recommendations with additional campaign data or controlled experiments.

## Project Notebook
[View the Python analysis notebook](bank_marketing_analysis.ipynb)

## Data Source
UCI Machine Learning Repository: [Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing).
