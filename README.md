# training-analytics-powerbi-dashboard

3-page Power BI dashboard analyzing training effectiveness, 
retention and tenure patterns across 1,04,707 employees 
in a dealer network.

📊 Project Overview

This dashboard answers three core business questions for the HR and training team:


Does training actually improve retention?
Does higher certification level lead to longer tenure?
Is training happening at the right time in an employee's career?


🗂️ Dataset

MetricValueTotal employee records1,04,707Dealerships1,128Zones12Regions56Certification levelsL0, L1, L2, L2+, L3Data span4+ years

The dataset includes employee joining dates, attrition dates, training dates per certification level, scores, designation, function (Sales/Service), and zone/region hierarchy.

📄 Dashboard Pages

Page 1 — Training Impact Overview


Total, trained, and untrained employee counts with training rate %
Trained vs untrained average tenure comparison
Trained vs untrained retention rate (donut visualization)
Interactive filters: Zone, Designation, Function


Page 2 — Training Level Effectiveness


Average tenure by certification level (L1 to L3) benchmarked against a combined Untrained + L0 baseline
Retention % progression across levels
Employee count distribution by level — highlighting the training pipeline bottleneck


Page 3 — Tenure Before vs After Training


Average time elapsed before an employee receives first (L1) training
Average tenure after training, segmented by level
Zone-wise training completion rate ranking


🔍 Key Insights


Only 21.9% of the workforce has ever received formal training
Trained employees stay 2× longer than untrained employees
L3-certified employees show 96.8% retention — nearly 6× the untrained baseline
Employees wait an average of 15.6 months after joining before receiving their first training — a critical delay that limits training's impact on retention
Significant pipeline drop-off: thousands of employees reach L1, but very few progress to L3


🛠️ Tools & Techniques


Power BI Desktop — report building and visualization
Power Query (M language) — data cleaning, date parsing, custom column creation
DAX — calculated measures for tenure, retention %, and level-wise benchmarking
Data modeling — handling inconsistent date formats, missing/dirty data, and serial date conversions.

📁 Files


Training_Analytics_Dashboard.pbix — full interactive Power BI report
dashboard_screenshots/ — PNG exports of all 3 pages


🙏 Acknowledgment

This project was built under the guidance of an industry mentor with real-world HR analytics experience. The dataset was provided in a modified/anonymized form for learning purposes.
