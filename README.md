# Hi, I'm Somesh Zanwar

**Data Science Master's Student @ UT Arlington | Data Analytics | Analytics Engineering | AI/Data Governance**

I build analytics and governance systems that help teams answer two questions more reliably:

1. **Can we trust this data?**
2. **Should this workflow, agent, or decision system be allowed to use it?**

My work sits at the intersection of data quality, analytics engineering, decision intelligence, and applied AI governance. I focus on building projects that do more than produce dashboards, they validate data, explain failures, support decisions, and create audit-ready workflows.

---

## Current Focus

- Data quality monitoring and governance-ready analytics systems
- dbt + PostgreSQL transformation pipelines
- Agent governance patterns for trustworthy AI workflows
- Product analytics, experimentation, and metric diagnosis
- Business intelligence dashboards that connect data to decisions

---

## Featured Projects

### Data Quality-Aware Agent Governance

A two-layer governance prototype that combines agent authorization with dataset trust checks.

Most agent governance systems ask: **is this agent allowed to act?**  
This project adds a second question: **is the target dataset trustworthy right now?**

If an agent is authorized but the dataset is stale, failing validation tests, or below a quality threshold, the action is blocked and logged.

**What it demonstrates:**

- Agent identity checks
- Policy-based authorization
- Dataset freshness and quality validation
- Unified governance decision logs
- A practical pattern for connecting data governance with agent governance

**Tech:** Python, Microsoft Agent Governance Toolkit concepts, YAML policies, JSON audit logs, pytest

[View Repository](https://github.com/SomeshZanwar/Data-Quality-Aware-Agent-Governance)

---

### AI Data Governance Platform

An end-to-end analytics reliability system for monitoring dataset quality, detecting incidents, scoring dataset health, and explaining governance failures.

This platform treats datasets like production systems. Instead of discovering bad data after it reaches dashboards, the system runs quality rules, tracks failures, creates incidents, and generates governance-ready reporting layers.

**What it demonstrates:**

- PostgreSQL-based governance metadata layer
- dbt transformation and analytics models
- Python rule engine for automated data quality checks
- Dataset health scoring
- Incident detection and AI-assisted explanations
- Power BI governance monitoring dashboard

**Tech:** PostgreSQL, dbt, Python, SQL, Power BI, OpenAI API

[View Repository](https://github.com/SomeshZanwar/AI-Data-Governance-Platform)

---

### Metric Decomposition Engine

An automated metric investigation system that explains why a metric changed.

Instead of manually slicing dashboards when a KPI moves, this engine decomposes metric change across dimensions, ranks root contributors, and generates a plain-English incident report.

Example problem:

> DAU dropped 12% on Monday — why?

**What it demonstrates:**

- Metric change analysis
- Dimensional drilldowns
- Root-cause contribution ranking
- Automated stakeholder-ready reports
- Product analytics workflow design

**Tech:** Python, PostgreSQL, pandas, SQLAlchemy, Streamlit, Jinja2

[View Repository](https://github.com/SomeshZanwar/Metric-Decomposition-Engine)

---

### Decision Intelligence Experimentation Platform

A production-style A/B testing and experimentation system that connects statistical analysis to product decisions.

Most experiment projects stop at p-values and charts. This project goes further by producing decision logic, segment-level insights, and rollout recommendations.

**What it demonstrates:**

- Experiment simulation
- dbt-modeled analytics layer
- Conversion and revenue metric analysis
- Statistical testing
- Segment-level insight generation
- Product rollout recommendations

**Tech:** Python, PostgreSQL, dbt, SQL, Streamlit, pandas, NumPy, SciPy

[View Repository](https://github.com/SomeshZanwar/Decision-Intelligence-Experimentation-Platform)

---

## Additional Analytics & ML Projects

### Retail Operations KPI & QA Dashboard

Built a BI and analytics engineering project using Instacart-style retail data, PostgreSQL star schema modeling, SQL QA checks, and Power BI reporting.

**Focus areas:** KPI reporting, SQL quality checks, star schema design, Power BI dashboarding

[View Repository](https://github.com/SomeshZanwar/Retail-Ops-KPI-Dashboard)

---

### Retail Sales & Inventory Optimization Analytics

End-to-end retail analytics project using real transaction data to analyze sales performance, demand patterns, ABC classification, and inventory recommendations.

**Focus areas:** SQL, Python, Streamlit, inventory analytics, revenue analysis

[View Repository](https://github.com/SomeshZanwar/Retail-Sales-Inventory-Analytics)

---

### Customer Churn Prediction with Explainability

Machine learning pipeline for telecom churn prediction using XGBoost and SHAP explainability.

**Result:** ROC-AUC 0.84  
**Focus areas:** supervised ML, churn modeling, SHAP explanations, business retention strategy

[View Repository](https://github.com/SomeshZanwar/Customer-Churn-Prediction-Explainability)

---

### Olympic Performance Analytics Dashboard

Interactive Streamlit dashboard exploring 120+ years of Olympic history with KPI summaries, medal analysis, country trends, and athlete-level performance insights.

**Focus areas:** Python, Streamlit, pandas, Plotly, interactive analytics

[View Repository](https://github.com/SomeshZanwar/Olympic-Performance-Dashboard)

---

## Technical Stack

**Data & Analytics:** SQL, Python, pandas, NumPy  
**Analytics Engineering:** PostgreSQL, dbt, data modeling, ETL pipelines, data quality checks  
**BI & Visualization:** Power BI, Streamlit, Tableau, Plotly  
**Machine Learning:** scikit-learn, XGBoost, SHAP, statistical testing  
**Governance:** data quality rules, metadata layers, audit logs, policy checks, dataset health scoring  
**Tools:** Git, GitHub, Docker, Jupyter, pytest

---

## What I Bring

- I can turn raw data into reliable analytics layers.
- I can build dashboards backed by tested and modeled data, not fragile one-off queries.
- I can connect analysis to business decisions, not just charts.
- I can think about governance at both the dataset level and the AI-agent/workflow level.
- I can explain technical systems clearly to non-technical stakeholders.

---

## Career Direction

I'm actively looking for opportunities in:

- Data Analyst
- Business Intelligence Analyst
- Product Analyst
- Analytics Engineer
- Data Governance Analyst
- AI Governance / Responsible AI Analyst

My strongest fit is with teams that care about reliable data, measurable decisions, and trustworthy AI-enabled workflows.

---

## Connect

- LinkedIn: https://www.linkedin.com/in/someshzanwar
- Portfolio: https://someshzanwar.github.io/
- Email: someshzanwar345@gmail.com

---

**I build systems that make data usable, trustworthy, and decision-ready.**
