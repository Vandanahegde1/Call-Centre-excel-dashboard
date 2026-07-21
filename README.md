# Call Centre Dashboard (Excel)

## Business Problem
Call centre managers need visibility into which representatives, call durations, and days of the week are associated with stronger or weaker customer satisfaction, so they can decide where coaching, staffing, or process changes would actually move the needle. This dashboard analyzes a full year of call centre activity to surface those patterns — and to test whether the common assumption that "shorter calls make happier customers" actually holds up.

This project was built for learning purposes using concepts from Chandoo's Excel Data Analysis series.

## Dataset
- **Size:** 1,000 call records across 2023 (full calendar year)
- **Scope:** 5 representatives, 15 unique customers
- **Key variables:** call duration, representative, date of call, purchase amount, satisfaction rating, day of week, duration bucket, customer demographics (gender, age, city)

## Tools & Technologies
- Microsoft Excel — Pivot Tables, Pivot Charts, Conditional Formatting, Slicers/Filters, dashboard design

## Key Questions Answered
1. Does call duration affect customer satisfaction?
2. Which representatives have the strongest satisfaction and purchase outcomes?
3. Are there day-of-week patterns in call volume or satisfaction?
4. Does a higher purchase amount correlate with higher satisfaction?

## Key Findings
- **Call duration has virtually no relationship with satisfaction** (correlation ≈ 0.01). Calls under 10 minutes averaged the same satisfaction (3.93) as calls over 2 hours (3.88) — the assumption that shorter calls make happier customers doesn't hold in this data.
- **Purchase amount also shows no meaningful correlation with satisfaction** (≈ 0.004), suggesting satisfaction isn't simply a function of how much a customer spent.
- **Overall average satisfaction sits at 3.89 out of 5** across all 1,000 calls, with an average call duration of ~90 minutes and average purchase amount of ~$97.
- **Representative R01 leads on satisfaction (3.92 avg)** despite not having the highest call volume, while R03 has the lowest average satisfaction (3.86) despite handling 207 calls — a relatively tight spread across reps rather than one standout or one clear underperformer.
- **Wednesday and Sunday post the highest average satisfaction (3.94)**, while Monday is the lowest (3.75) — a modest but consistent dip at the start of the week.

## Business Recommendations
1. **Don't treat call duration as a satisfaction lever.** Since duration shows no real correlation with satisfaction, initiatives aimed purely at shortening calls are unlikely to move customer experience scores — investigate call quality and resolution instead.
2. **Look into R03's Monday performance specifically** as a starting point for coaching, since it sits at the intersection of the lowest-satisfaction rep and the lowest-satisfaction day.
3. **Investigate what's actually driving the small satisfaction gap between reps** (R01 vs. R03) — since it isn't duration or purchase amount, factors like call resolution or communication style are more likely candidates worth reviewing directly.

## Dashboard / Visualisations
An interactive Excel dashboard with:
- KPI tracking (total calls, average satisfaction, average duration, average purchase amount)
- Representative performance comparison
- Call volume and satisfaction by day of week
- Customer satisfaction analysis by duration bucket
- Slicers and filters for interactive exploration

[Screenshot of dashboard]

## A Note on Methodology
It would have been easy to assume shorter calls drive higher satisfaction and build the dashboard around confirming that. Testing it directly against the data — and finding essentially no correlation — was a more honest result, and points toward call quality and resolution as more likely drivers of satisfaction than raw call length.
