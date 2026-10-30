
# Landing Page A/B Testing & Conversion Analysis

## Python | Statistical Hypothesis Testing | Product Analytics

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels  
**Project type:** A/B Testing & Experiment Analysis  
**Period:** January 2026  
**Context:** TripleTen Data Analytics Bootcamp

---

## 01. Project Overview

This project evaluates the performance of two landing-page variants using Python and statistical hypothesis testing.

The objective is to determine whether Version B delivers stronger conversion performance than Version A and investigate differences in customer spending and user segments.

The analysis translates experimental results into evidence-based commercial recommendations.

## 02. Business Questions

1. Which landing-page version achieves a higher conversion rate?
2. Is the conversion difference statistically significant?
3. Does average spending differ between converted users?
4. Are traffic source and user type associated with conversion?
5. What commercial decision is supported by the results?

## 03. Experiment Results

### Conversion Performance

| Metric | Version A | Version B |
|---|---:|---:|
| Conversions | 2,512 | 3,194 |
| Conversion Rate | 12.6% | 16.0% |

**Key finding:** Version B achieved approximately 3.4 percentage points higher conversion than Version A.

The conversion-rate difference was statistically significant (chi-square test, p < 0.001).

### Customer Spending

The analysis also examined spending among converted users.

| Metric | Version A | Version B |
|---|---:|---:|
| Average Spending | $61.09 | $68.75 |

A Welch t-test identified a statistically significant difference in average spending (p < 0.001).

These findings suggest that Version B performed more strongly on both observed conversion and average spending among converted users.

## 04. Additional Statistical Analysis

The project also investigates relationships between conversion outcomes and user characteristics.

- **Traffic source:** Statistically significant association with conversion (p = 0.034).
- **User type:** No statistically significant association detected (p = 0.474).

These tests identify associations; they do not independently establish causality.

## 05. Commercial Recommendations

Based on the observed results:

1. Consider Version B as the preferred candidate for deployment, subject to validation of experiment design and data quality.
2. Evaluate the impact on overall revenue per visitor, not conversion rate alone.
3. Investigate differences in performance across acquisition channels.
4. Monitor post-deployment performance to confirm whether the observed improvements persist.

## 06. Analytical Methodology

The analysis uses:

- Data exploration and validation with Pandas
- Descriptive statistics and visualisation
- Conversion-rate calculations
- Chi-square hypothesis testing
- Welch's t-test for average spending
- Analysis of traffic source and user type

Statistical significance is interpreted alongside commercial relevance and methodological limitations.

## 07. Limitations

The project was developed in an educational environment using a dataset supplied for analytical training.

Statistically significant results do not automatically guarantee equivalent outcomes in a production environment.

Any deployment recommendation should consider randomisation, sample balance, experiment integrity, and business impact.

## 08. Project Files

- `landing_page_ab_test_analysis.ipynb` — Python analysis and statistical tests
- `requirements.txt` — Python dependencies

The dataset is not included in this public repository.

## 09. About the Analyst

Victoria López Vázquez

Commercial merchandising professional transitioning into Data Analytics and Business Intelligence, combining commercial strategy, statistical analysis, and data visualisation.

[View my Data Analytics Portfolio](https://vichovska.github.io/)

---

*Portfolio project developed as part of the TripleTen Data Analytics Bootcamp.*
