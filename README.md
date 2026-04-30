# Bank_Analytics
Interactive Power BI dashboard analyzing bank loan data — tracking loan amounts, payment status, revolving balances by grade/subgrade, and borrower profiles across time, geography, and home ownership type.


📊 Overview

This project presents a Bank Loan Analysis Dashboard built in Power BI that enables financial analysts, risk teams, and business stakeholders to explore and monitor loan portfolio performance. The dashboard provides a 360° view of loan disbursements, repayments, borrower verification status, and revolving credit balances — all filterable by year, month, state, loan status, grade, and sub-grade.

🔢 Key Metrics (KPIs)

MetricValue  

Total Loan Amount      446M

Total Payment Received     482.67M

Total Loan Count     40K

Average Loan Amount      11.22K


📈 Visualizations Included


1. Total Loan Amount by Year

Bar chart showing yearly growth in loan disbursements
Trend visible from near-zero in early years up to 0.26bn in the most recent year, indicating rapid portfolio expansion

2. Total Revolving Balance by Grade

Line + area chart across grades G → A
Grade B carries the highest revolving balance (161M), followed by A (115M) and C (110M)
Useful for assessing credit concentration risk

3. Total Revolving Balance by Sub-Grade

Granular breakdown across sub-grades (B3, B5, B4, A5, A4, C1, C2, B1, C3, A3, D2, C4, D3, C5, A2, D4)
Top sub-grades: B3 and B5 each at ~40M
Helps identify which sub-segments carry the most revolving exposure

4. Total Payment by Verification Status

Donut chart split across three categories:

✅ Verified: 219.89M (45.5%)
🔵 Not Verified: 153M (31%)
🟠 Source Verified: 109.27M (22.64%)

Highlights the share of loans lacking full income verification

5. Loan Status by Month

Horizontal bar chart for months February through October
Volume ramps from 2.4K (Feb/Jan) to 3.9K (October)
Shows seasonal origination trends useful for capacity planning

6. Last Payment by Home Ownership

Bar chart across: RENT, MORTGAGE, OWN, OTHER
RENT: 18.8K | MORTGAGE: 17.6K | OWN: 3.1K | OTHER: 0.1K
Renters and mortgage holders dominate the borrower base


🛠️ Tools & Technologies

Power BI Desktop — Dashboard design and interactivity

DAX — Calculated measures (Sum, Count, Average, etc.)

Power Query (M) — Data transformation and cleaning

Dataset — Bank loan records (CSV/Excel source)


💡 Key Insights

Loan volume has grown significantly year-over-year, with the latest year accounting for the largest share (0.26bn).

Grade B borrowers hold the highest revolving balances, suggesting mid-risk borrowers are driving the most credit utilization.

Over 31% of loans are unverified, which could signal elevated default risk in that segment.

Loan originations peak later in the year (September–October), possibly tied to seasonal financial needs.

Renters and mortgage holders make up the vast majority of borrowers compared to outright homeowners.


Dashboard:

PowerBI:
![preview]()

