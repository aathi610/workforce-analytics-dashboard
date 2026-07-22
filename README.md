Workforce & Compensation Analytics Dashboard

An end-to-end Power BI dashboard built to answer a simple question with real data behind it: is this workforce growing sustainably, is pay equitable across roles, and are there retention risks hiding in the numbers before they become a problem?

The Problem

Workforce data — headcount, salary, tenure, leave balances — usually sits scattered across HR systems without a single view. That makes it hard to catch things early: a role that's underpaid relative to its market band, a pay gap by gender, or a group of employees quietly accumulating unused leave that often signals disengagement. None of that shows up until someone builds the view that surfaces it.

What I Built

Built the dashboard end-to-end across two pages, from raw data to interactive reporting:

Cleaned and transformed raw employee data using Power Query
Engineered DAX measures including Cumulative Headcount, Gender Pay Gap, and a leave-balance flag to identify employees over the 20-day threshold
Built KPI cards tracking total headcount, average salary, average leave balance, and count of employees with a high leave balance
Designed a Workforce Overview page — headcount and average salary by job title, gender split, and cumulative headcount growth over time
Designed a Pay & Demographics page — headcount by age band and gender, a full salary breakdown table (avg/min/max by job title), and a scatter plot of salary against qualification level
Key Insights
Analyzed 161 employees across 10 job titles, with an org-wide average salary of $54K
Product Manager is the highest-paid role (~$83K average, up to $85K), while Packaging Associate is the lowest (~$33K average, $28.9K–$36.2K range) — a $50K spread between the top and bottom roles
Packaging Associate is also the largest single role by headcount (22 people), followed by Production Operator (20) and Sales Representative (18)
Gender split is nearly even organization-wide — 54.7% male (88) vs. 45.3% female (73)
Flagged a retention-risk segment: 29 employees (18% of the workforce) hold leave balances over 20 days — a group worth a proactive check-in rather than waiting for attrition data to confirm the problem
Headcount has grown steadily and cumulatively since 2018, with the sharpest climb in more recent years
Age distribution clusters around the early-30s band for both genders, suggesting a relatively young, still-maturing workforce
Salary scales visibly with qualification — Bachelor's and Master's degree holders cluster in higher salary bands than Diploma and High School holders, which is useful context when reviewing pay bands by education requirement
Dashboard Pages

Workforce Overview — KPI cards (headcount, avg salary, avg leave balance, high-leave-balance count), headcount and salary by job title, headcount by gender, and cumulative headcount growth by join date

Pay & Demographics — headcount by age band and gender, full salary breakdown table by job title, and salary vs. qualification scatter plot

Tech Stack

Power BI · DAX · Power Query

<img width="1320" height="746" alt="Screenshot 2026-07-22 095141" src="https://github.com/user-attachments/assets/f57d4896-8276-4e7b-be20-cb29a4cb1b3f" />


Pay & Demographics — headcount by age and gender, salary breakdown table by job title, salary vs. qualification analysis
<img width="1312" height="736" alt="Screenshot 2026-07-22 095119" src="https://github.com/user-attachments/assets/e4403e1d-f144-46da-a0cf-d3abd0341356" />
