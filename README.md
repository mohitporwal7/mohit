# Analytics Portfolio — Mohit

Product analytics · Experimentation · Behavioral intelligence

6+ years across B2B SaaS, gaming, healthcare, and AI products. This portfolio contains case studies, SQL patterns, Power BI reports, and Python analyses from real problems I've worked on — churn prevention, monetization, activation, and retention.

---

## Case studies

### [Customer health scoring — Mindtickle](./customer-health-scoring/)

Built a churn-prevention engine for a B2B SaaS platform serving enterprise sales teams.

- Designed a Bronze / Silver / Gold data architecture on Snowflake + Airflow
- Pulled behavioral signals from Mixpanel into a composite health score
- Flagged enterprise accounts at churn risk 60+ days before renewal
- Delivered via Power BI to CS and account management teams
- **Outcome:** $1M+ in enterprise ARR protected

**Stack:** Snowflake · Airflow · Mixpanel · Power BI · SQL

---

### [Pricing A/B test — MoonFrog (Teen Patti Gold)](./pricing-ab-test/)

Ran a full-stack pricing experiment on a 7M MAU mobile gaming platform.

- Designed the experiment hypothesis, variant structure, and success metrics
- Segmented by player cohort — active payers vs lapsed payers vs non-payers
- Measured revenue per user, conversion rate, and downstream retention
- Caught an unintended fraud signal: black market chip prices rose during the test period
- **Outcome:** 7% monthly revenue uplift · 17% lapsed payer reactivation

**Stack:** SQL · Python · Mixpanel · Excel

---

## SQL

Annotated queries covering patterns I use regularly in product analytics.

```
sql/
├── retention/          — N-day and cohort retention
├── funnel-analysis/    — Conversion drop-off, time-to-convert
├── window-functions/   — Running totals, rank, lag/lead patterns
└── churn-signals/      — Behavioral flags and health scoring logic
```

[Browse SQL →](./sql/)

---

## Power BI

Report designs and DAX patterns from production dashboards.

```
power-bi/
├── health-score-dashboard/   — CS team view, account risk tiering
├── revenue-analytics/        — MRR, ARR, expansion / contraction
└── funnel-report/            — Activation and onboarding tracking
```

[Browse Power BI →](./power-bi/)

---

## Python

Analytical notebooks covering experimentation and cohort work.

```
python/
├── ab-test-calculator/     — Two-proportion z-test, power analysis
├── cohort-retention/       — Retention curves, heatmaps
└── eda-templates/          — Product data exploration starter kits
```

[Browse Python →](./python/)

---

## Stack

`SQL` `Python` `Power BI` `Snowflake` `Airflow` `Mixpanel` `dbt` `Pandas` `A/B Testing`

---

## About

I'm a Lead Product Analyst open to roles in product analytics, data analytics, and analytics engineering. Based in Gurugram, India.

[LinkedIn](https://www.linkedin.com/in/mohitporwal77/) · [Email](mohitporwal77@gmail.com)
