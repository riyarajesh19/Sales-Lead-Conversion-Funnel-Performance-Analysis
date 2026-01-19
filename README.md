📊 **Sales Lead Conversion & Funnel Performance Analysis | Tool : Power BI**

📌 Project Overview

This project analyzes the end-to-end sales lead lifecycle to understand how leads progress through the funnel, identify conversion drivers, uncover drop-off reasons, and evaluate sales team performance.
Using Power BI, raw CSV datasets were transformed into an interactive, insight-driven dashboard that supports data-driven decision-making.

🎯 Project Objectives

Analyze lead movement across funnel stages

Measure the impact of demo engagement on conversions

Identify key drop-off stages and reasons

Evaluate sales manager performance

Provide actionable insights to improve conversion rates

📂 Dataset Overview

The project uses five interconnected CSV datasets, linked using a common key lead_id.

Leads Basic Details – Demographics and lead source information

Leads Demo Watched Details – Demo engagement and watch percentage

Leads Interaction Details – Funnel stages of each lead

Leads Reasons for No Interest – Reasons for lead drop-offs

Sales Managers Assigned Leads Details – Sales team assignments and hierarchy

Together, these datasets enable end-to-end funnel analysis.

🧹 Data Cleaning Steps

Fixed date format issues using locale-based conversion

Handled missing values in demo watch percentage

Removed blank and invalid drop-off reason entries

Cleaned and standardized text fields

Renamed columns for clarity and business understanding

Checked for duplicates and data integrity

🔧 Data Preprocessing Steps

Normalized drop-off reasons into a single column

Created Age Groups for demographic analysis

Grouped demo watch percentages into engagement buckets

Built mapping tables to maintain correct funnel and bucket order

Designed a star-schema data model

Created Senior → Junior Sales Manager hierarchy

Developed reusable DAX measures for KPIs

🧮 Key DAX Measures Used

Total Leads

Converted Leads

Conversion Rate %

Funnel Leakage %

Drop-off Count

Conversion Rate Gap

Demo Engagement Buckets

Sales Manager Conversion %

Sales Manager Rank

Age Group Segmentation

📊 Dashboard Highlights

Lead Conversion Funnel – Visualizes stage-wise lead progression

Demo Engagement Analysis – Shows impact of demo completion on conversion

Drop-off Analysis – Identifies where and why leads are lost

Sales Performance Analysis – Compares conversion efficiency across managers

Executive KPIs – High-level summary for quick decision-making

🔍 Key Insights

Leads with high demo engagement (>75%) convert significantly better

Maximum funnel leakage occurs at the consideration stage

Pricing concerns and offline learning preference are top drop-off reasons

Some lead sources generate volume but lower quality conversions

Sales manager performance varies even with similar lead volumes

🚀 Recommendations

Improve demo completion through reminders or shorter demos

Address pricing concerns early with clear communication or EMI options

Focus marketing spend on high-quality lead sources

Strengthen follow-ups during the consideration stage

Replicate best practices from top-performing sales managers

🛠 Tools & Technologies

Power BI

Power Query

DAX

Data Modeling

Funnel & KPI Analysis

Data Visualization

📌 Conclusion

This project demonstrates how structured data cleaning, preprocessing, and advanced DAX can transform raw sales data into meaningful insights. The dashboard provides a clear understanding of lead behavior, conversion drivers, and sales performance, enabling data-driven business decisions.
