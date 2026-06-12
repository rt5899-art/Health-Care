## Healthcare Data Analytics Dashboard

### Project Overview

This project provides a comprehensive, data-driven analysis of healthcare operations, financial performance, and patient demographics. By leveraging data extraction, cleaning, and interactive visualization, the dashboard unifies complex healthcare datasets to uncover trends in billing, patient care distributions, and insurance provider utilization.

### Tools & Technologies

Microsoft Excel: Initial data structuring, verification, and pivot table modeling.

Power BI: Data modeling, DAX calculations, and interactive dashboard design.

#### Dashboard Preview

![image alt](https://github.com/rt5899-art/Health-Care/blob/main/Screenshot%202026-06-12%20134244.png?raw=true)

### Key Business Insights

#### Executive Metrics

* Total Patients Tracked: 56K across various demographics and conditions.

* Financial Scope: Total accumulated billing of $1.42bn with an overall average billing of $25.54K per patient.

* Demographic Baseline: Average patient age stands at 51.54 years, with a balanced gender distribution of 53.06% Male (104 samples) and 46.94% Female (92 samples).

#### Operational & Financial Trends

* Consistent Volume with Recent Drop: Billing trends remained relatively stable from 2020 through late 2023 at around $20M per interval, followed by a sharp decline in early 2024.

* Uniform Condition Distribution: Patient volume is evenly distributed across major medical conditions, each hovering around 9.2K to 9.3K patients (including Arthritis, Diabetes, Hypertension, Obesity, Cancer, and Asthma).

* Insurance Performance: Revenue is evenly spread among major providers, led by Cigna ($0.29bn), Medicare ($0.29bn), Blue Cross ($0.28bn), UnitedHealthcare ($0.28bn), and Aetna ($0.28bn).

* Top Care Providers: Michael Smith ($0.78M), Robert Smith ($0.63M), and John Smith ($0.61M) lead the top 10 doctors by total billing revenue.

### Recommendations

#### Investigate the 2024 Revenue Drop

Insight: The line chart shows a severe drop in the sum of billing amounts moving into 2024.

* Action: Conduct an immediate audit of 2024 data pipelines to check for missing logs, or consult operations to identify potential external market shifts or systemic insurance policy adjustments.

#### Optimize Admission Type Resource Allocation

Insight: Urgent, Elective, and Emergency admissions show near-identical distributions (around 9K to 9.5K patients each) across genders.

* Action: Maintain flexible, non-siloed staffing models across emergency and elective wings since patient volume does not heavily lean toward one specific admission type.

#### Standardize Condition-Based Pricing

Insight: The "Avg Billing Per Condition" sits exceptionally high at $236.24M, while individual condition patient counts remain uniform.

* Action: Review the underlying cost drivers behind specific high-cost procedures within those conditions to ensure standardized pricing agreements with major providers like Blue Cross and Aetna.
