# A.I-PROMPT-AND-STAKEHOLDER-BRIEF
This is a RCTTCE A.I data analysis Prompt and an A.I generated Stakeholder Brief.

Project Overview

A concise, evidence first diagnostic to identify root causes of an 18 month revenue decline across a 30 store retail chain and surface measurable improvement opportunities for executive decision making.

Role:

Senior retail data analyst with 10+ years diagnosing multi site performance, translating transactional data into executive recommendations focused on revenue trends, customer behaviour, and product mix.

Context:

The chain has experienced sustained decline for 18 months. The CEO requests a one page brief and a diagnostic report that links data to clear commercial actions.

Dataset:

50,000 transaction records covering 18 months with these fields:
•	store_id
•	transaction_date
•	product_id
•	product_name
•	category
•	revenue
•	units_sold
•	customer_id
•	loyalty_points
•	region

Objective:

Produce a diagnostic report and one page CEO brief that identify problem stores, regional and category drivers, customer segmentation impacts, and 3+ actionable opportunities.

Deliverables:

1.	Top 5 stores by steepest month over month revenue decline (use: store_id, transaction_date, revenue).
2.	Revenue breakdown by region and category (use: region, category, revenue).
3.	Basket trends: revenue per transaction and units per transaction over 18 months (use: revenue, units_sold, customer_id, transaction_date).
4.	Customer segmentation: loyalty vs non loyalty spend and frequency (use: customer_id, loyalty_points, revenue).
5.	Top 10 declining categories by revenue contribution (use: category, product_id, product_name, revenue).
6.	Actionable opportunities: at least three prioritized, measurable recommendations with required evidence and expected impact.

Target Audience:

CEO and senior stakeholders seeking clear, commercially relevant, and actionable insights.

Constraints and Standards:

•	Use only the listed columns.
•	Quantify changes against stated baselines.
•	Flag correlations vs causation and note data quality assumptions.
•	Questions and recommendations must be specific, measurable, and free of statistical jargon.
•	Avoid speculation about competitors or macro factors.

Example Output Format:

FINDING: Store 14 revenue down 31% peak to current.
EVIDENCE: store_id, transaction_date, revenue trend shows 13 declines in 18 months.
IMPLICATION: Structural decline.
ACTION: On site audit within 30 days.
