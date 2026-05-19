<div align="center">

  <!-- Gradient Banner -->
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:4F46E5,50:7C3AED,100:EC4899&height=160&section=header&text=🚀%20RavenStack%20SaaS%20Intelligence&fontSize=38&fontColor=ffffff&animation=fadeIn&desc=Subscription%20·%20Revenue%20·%20Churn%20·%20Retention&descSize=16&descAlignY=75" />

  <!-- Typing Subtitle -->
  <p>
    <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=16&duration=2800&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=500+Accounts+%7C+5000+Subscriptions+%7C+25000+Events;End-to-End+SaaS+Growth+%26+Churn+Intelligence;Python+%7C+SQL+%7C+Power+BI+Full+Workflow;Cohort+Analysis+%7C+MRR+%7C+Revenue+Forecasting" />
  </p>

  <!-- Tech Stack Badges -->
  <div align="center">

  ![POWERBI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=Power%2520BI&logoColor=black)
  ![POSTGRESQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
  ![PYTHON](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![PANDAS](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![NUMPY](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
  ![MATPLOTLIB](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
  ![SEABORN](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
  ![JUPYTER](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

  </div>

  <!-- Divider -->
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />

</div>


This end-to-end SaaS analytics project delivers deep revenue and churn intelligence for **RavenStack** — a fictional AI-powered collaboration platform. Using real-world analytics workflows across Python, SQL, and Power BI, the project uncovers the behavioral, revenue, and support signals that drive customer churn, retention, and growth, enabling data-driven decisions across the full subscription lifecycle.

---

## 📌 Project Overview

SaaS businesses rely on recurring revenue, retention, and customer lifecycle performance to grow sustainably.  
This project analyses a multi-table subscription dataset to answer questions such as:

- Which plans, industries, and countries drive the most revenue?
- How does customer signup growth evolve over time?
- Where is churn concentrated across customer segments?
- How much recurring revenue is exposed to churn?
- Which conversion, downgrade, reactivation, and cohort patterns matter for business decisions?
- How can dashboard-ready KPIs support executive monitoring of SaaS performance?

The analysis is structured to replicate real-world **revenue intelligence, retention analytics, and subscription business reporting** used by product, finance, GTM, and business operations teams.

---

## 🎯 Business Objective

The goal of this project is to transform raw SaaS subscription data into a clear analytical view of:

- **Revenue performance** — MRR, ARR, plan-level revenue, market contribution
- **Customer growth** — signups, trial-to-paid conversion, funnel performance
- **Churn risk** — churn patterns, churn reasons, revenue exposure
- **Retention analytics** — monthly cohorts, active subscriber trends, reactivation signals
- **Operational intelligence** — support experience, feature usage, downgrade/upgrades
- **Executive reporting** — interactive Power BI dashboards for leadership decisions

---

## 📊 Dataset Overview

This project uses a **synthetic multi-table SaaS dataset** designed to reflect a realistic subscription business environment.  
It contains **customer profiles, subscription lifecycles, feature usage activity, support interactions, and churn events**, enabling both commercial and behavioural analysis.

### 📁 Data Tables

| Dataset | Rows | Purpose |
|---|---:|---|
| `ravenstack_accounts.csv` | **500** | Customer accounts, industry, country, signup channel, seats, plan tier, churn flag |
| `ravenstack_subscriptions.csv` | **5,000** | Subscription lifecycle, MRR, ARR, upgrade/downgrade flags, trial status, auto-renewal |
| `ravenstack_feature_usage.csv` | **25,000** | Daily product usage, feature engagement, duration, error counts, beta-feature usage |
| `ravenstack_supports_ticket.csv` | **2,000** | Support tickets, resolution time, response speed, CSAT, escalation indicators |
| `ravenstack_churn_events.csv` | **600** | Churn dates, churn reasons, refund behaviour, reactivation indicators |

### 🧠 Why this dataset is valuable

The dataset supports analysis across the **full SaaS customer lifecycle**:

- Acquisition → Signup and referral source
- Conversion → Trial to paid
- Monetisation → MRR / ARR / plan revenue
- Engagement → Product feature usage
- Experience → Support interactions and satisfaction
- Retention → Churn, reactivation, and cohort trends

---

## 📁 Repository Structure

```text
Saas-Subscription-Revenue-Churn-Intelligence/
│
├── Buisness_Questions/
│   ├── Buisness Problem and Deliverables.pdf
│   └── README.md
│
├── Presentation_Ravenstack/
│   ├── RavenStack-SaaS-Subscription-Analysis _Presentationpdf.pdf
│   └── README.md
│
├── Project_Architecture/
│   ├── Project architecture .jpg
│   └── README.md
│
├── Project_Report/
│   └── README.md
│
├── Ravenstack.csv_data/
│   ├── ravenstack_accounts.csv
│   ├── ravenstack_subscriptions.csv
│   ├── ravenstack_feature_usage.csv
│   ├── ravenstack_supports_ticket.csv
│   ├── ravenstack_churn_events.csv
│   └── README.md
│
├── notebooks/
│   ├── Ravensstack.ipynb
│   └── README.md
│
├── sql_queries/
│   ├── raven_stack_sql_insights.sql
│   └── README.md
│
├── powerbi/
│   ├── Saas subscription Power bi report.pbix
│   ├── Executive overview .jpg
│   ├── Growth ,funnel analysis.jpg
│   ├── churn,retention and cohort analysis.jpg
│   └── README.md
│
└── README.md
```

---

## 🔁 End-to-End Analytics Workflow

<div align="center">

```text
Business Problem Definition
          ↓
Multi-Table Dataset Understanding
          ↓
Python Data Cleaning & Exploratory Analysis
          ↓
Subscription KPI Engineering
          ↓
PostgreSQL Business Analysis & Cohort Queries
          ↓
Power BI Executive Dashboards
          ↓
Revenue, Churn & Retention Recommendations
```

</div>

---




# 🧹 1. Python Data Preparation & Exploratory Analysis

The Jupyter notebook performs the analytical foundation of the project by:

- Loading and validating **5 relational SaaS datasets**
- Converting date fields into analysis-ready formats
- Preserving valid nulls such as active subscriptions without an `end_date`
- Handling zero-MRR records that may represent trials, free plans, discounts, or delayed billing
- Creating business-friendly logic for subscription status
- Retaining missing satisfaction scores where customer feedback was not provided
- Exploring customer, subscription, revenue, support, usage, and churn trends

### ✔ Important analytical treatment

Rather than deleting records with `null end_date` or `zero MRR`, the workflow preserves them because they can represent meaningful SaaS states such as:

- Active ongoing subscriptions
- Trial users
- Free or discounted plans
- Unbilled or delayed billing periods

This makes the analysis more realistic and avoids artificially inflating churn or undercounting active users.

---

# 🗄️ 2. SQL Business Analysis using PostgreSQL

The SQL layer converts the cleaned relational data into decision-ready business insights.

### 🔍 Key Business Questions Solved

#### 💰 Revenue Intelligence
- Total and average **MRR** by plan tier
- Revenue contribution by **industry**, **country**, and **referral source**
- High-value subscription segments and plan economics

#### 🔄 Funnel & Conversion
- Trial-to-paid conversion funnel
- Signup and acquisition patterns
- Revenue generated during early customer lifecycle windows

#### 📉 Churn & Retention
- Churn rate by plan tier
- Monthly signup cohorts with churn at **30 / 60 / 90 days**
- Active account retention trends month over month
- Churn reason distribution and reactivation behaviour

#### 📈 Subscription Lifecycle
- Upgrade and downgrade patterns
- Revenue movement linked to plan changes
- Auto-renewal and active subscription signals

### 🧾 Sample SQL Query — Trial-to-Paid Conversion Funnel

```sql
WITH trial_accounts AS (
    SELECT account_id
    FROM accounts
    WHERE is_trial = TRUE
),
paid_conversions AS (
    SELECT DISTINCT t.account_id
    FROM trial_accounts t
    JOIN subscriptions s
        ON t.account_id = s.account_id
    WHERE s.mrr_amount > 0
)
SELECT
    COUNT(DISTINCT t.account_id) AS total_trial_accounts,
    COUNT(DISTINCT p.account_id) AS converted_paid_accounts,
    ROUND(
        COUNT(DISTINCT p.account_id)::NUMERIC
        / COUNT(DISTINCT t.account_id) * 100,
        2
    ) AS conversion_rate_percentage
FROM trial_accounts t
LEFT JOIN paid_conversions p
    ON t.account_id = p.account_id;
```

---

# 📊 3. Power BI Dashboard

The Power BI report transforms the analysis into a stakeholder-friendly executive view of **growth, revenue, churn, retention, and cohort behaviour**.

## Dashboard Pages

### 1️⃣ Executive Overview
A high-level view of:
- Revenue performance
- Customer base composition
- Subscription distribution
- Plan and market contribution

<div align="center">

<img src="powerbi/Executive%20overview%20.jpg" width="860" alt="Executive Overview Power BI Dashboard">

</div>

---

### 2️⃣ Growth & Funnel Analysis
Designed to explore:
- Signup growth
- Trial-to-paid movement
- Acquisition channels
- Revenue and conversion performance

<div align="center">

<img src="powerbi/Growth%20,funnel%20analysis.jpg" width="860" alt="Growth and Funnel Analysis Power BI Dashboard">

</div>

---

### 3️⃣ Churn, Retention & Cohort Analysis
Focused on:
- Churn patterns
- Retention trends
- Cohort behaviour
- Customer lifecycle risks

<div align="center">

<img src="powerbi/churn,retention%20and%20cohort%20analysis.jpg" width="860" alt="Churn Retention and Cohort Analysis Power BI Dashboard">

</div>

---

## 🚀 Dashboard Access

<div align="center">

  <p>
    <a href="powerbi/Saas%20subscription%20Power%20bi%20report.pbix" target="_blank">
      📥 Download Power BI Dashboard File
    </a>
  </p>

  <p>
    <a href="powerbi/Executive%20overview%20.jpg" target="_blank">
      🖼️ View Dashboard Preview
    </a>
  </p>

</div>

> **Note:** The repository currently includes the complete Power BI report file and dashboard preview images.  
> A public Power BI / NovyPro live dashboard URL can be added here once published.

---
## 📈 Key Findings & Insights

### 🏆 Revenue
- **Enterprise** accounts generate the highest average MRR despite smaller account volume  
- **FinTech and DevTools** industries contribute disproportionately to total platform revenue  
- Top 5 countries account for ~70% of all MRR — geographic concentration is a revenue risk

### 📉 Churn
- **22% overall churn rate** across the 500-account customer base  
- Top churn reasons: `features` (missing product functionality) > `support` quality > `budget` constraints  
- Accounts that **downgrade before churning** signal an identifiable, preventable revenue loss window  
- A meaningful segment of churned accounts was later **reactivated**, validating win-back investment

### 👥 Cohort & Retention
- Early churn (within 30 days) is elevated in newer cohorts — onboarding experience is a primary risk zone  
- Trial accounts convert at varying rates by cohort month — engagement timing materially affects conversion  
- First-3-month MRR per cohort varies significantly, indicating inconsistent early value delivery across vintages

### 💡 Feature Adoption
- A small core set of features drives the majority of all product usage  
- Beta features show elevated error counts — product quality risk before general availability  
- Session duration varies widely across features — some drive deep engagement, others face rapid abandonment

---

## 💼 5. Business Recommendations

Based on the full analysis, RavenStack could drive measurable improvements in retention and revenue by:

1. **🎯 Prioritize Enterprise retention programs** — highest MRR per account, highest revenue loss if churned  
2. **🚨 Trigger early lifecycle intervention** — low feature usage in the first 30 days is a leading churn signal  
3. **🔁 Build a downgrade early-warning system** — downgrade events reliably precede full churn  
4. **💬 Address `features` as the #1 churn reason** — product gaps are the top driver of departure  
5. **📣 Invest in structured win-back campaigns** — reactivation data proves re-engagement works  
6. **🌍 Diversify geographic revenue concentration** — reduce dependency on top-5 markets  

---

## 🧩 Tools & Technologies

| Category | Technology |
|----------|------------|
| **Data Wrangling** | Python, Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Notebook Environment** | Jupyter Notebook |
| **Database** | PostgreSQL (pgAdmin 4) |
| **SQL Techniques** | CTEs, Window Functions, Aggregations, generate_series |
| **BI Dashboard** | Microsoft Power BI |
| **Version Control** | GitHub |

---

## 📋 Prerequisites

- **Python 3.8+** with `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **PostgreSQL 13+** and pgAdmin 4  
- **Power BI Desktop**  
- **Jupyter Notebook**  

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/dineshbarri/saas-subscription-revenue-churn-intelligence.git
cd saas-subscription-revenue-churn-intelligence
```

---

### 2. Set Up Python Environment

```bash
python -m venv venv && source venv/bin/activate   # Windows: venv\Scripts\activate
pip install pandas numpy matplotlib seaborn jupyter
```

---

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy jupyter
```

---

### 4. Run the Jupyter notebook

```bash
jupyter notebook notebook/saas_revenue_churn_cohort_intelligence_analysis.ipynb
```
> 💡 Update the `file_path` variable in the Setup cell to point to your local `data/` directory before running all cells.
---

### 5. Load Data into PostgreSQL (pgAdmin 4)

- Open **pgAdmin 4** and create a new database named `saas_analysis`  
- Import each CSV via **Right-click on Tables → Import/Export Data** for each of the 5 tables  
- Open `sql/saas_revenue_churn_retention_sql_analysis.sql`  
- Select the `saas_analysis` database and run the script (F5)  

---

### 6. Open the Power BI Dashboard

- Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) if not already installed  
- Open `PowerBi/SaaS Revenue & Churn_Intelligence_Dashboard.pbix`  
- If prompted to refresh data source, point the file path to your local `data/` folder  


---

### 📊 Dataset Source

📎 [RavenStack SaaS Dataset on Kaggle](https://www.kaggle.com/datasets/rivalytics/saas-subscription-and-churn-analytics-dataset) — by River @ Rivalytics

---



### 📈 Business Impact

This project demonstrates how raw SaaS data can be transformed into strategic intelligence:

- **Revenue Intelligence** — identify MRR concentration, risk segments, and growth levers  
- **Churn Early Warning** — behavioral and support signals that precede cancellation  
- **Retention Frameworks** — cohort-based strategies to reduce early and late-stage churn  
- **Product Prioritization** — feature adoption data to align roadmap with usage reality  
- **Executive Dashboards** — shareable Power BI reports ready for leadership communication  

---

### 🔮 Future Enhancements

- Machine learning churn prediction model (Logistic Regression / XGBoost / LightGBM)  
- SHAP-based model interpretability for churn feature importance  
- NLP analysis of `feedback_text` churn responses for unstructured signal extraction  
- Customer health score model combining usage, support, and billing signals  
- Real-time Power BI dashboard with live database refresh  

---

### 🤝 Contributing

Contributions, issues, and feature requests are welcome.  
Feel free to open a pull request or create an issue to suggest improvements.

---

### 💖 Support This Project

If you find this useful, consider supporting my open-source work in Data Analytics, ML & AI automation.  
👉 [GitHub Sponsors](https://github.com/sponsors/dineshbarri) | [PayPal](https://paypal.me/dineshbarri1997)

---

## 👨‍💻 Creator

### Dinesh Barri

#### 📬 Contact Information

- **📧 Email**: [dineshbarri1997@gmail.com](mailto:dineshbarri1997@gmail.com)
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dineshbarri)
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dinesh-barri-7654b010b)

---

## 📄 License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

### ⭐ If you like this project, don't forget to give it a star!
