# Project Management Dashboard

![Project Management Dashboard](Performance Dashboard/Image_Performance/P_Dashboard.png)

**Your all-in-one Power BI project tracker – simple, smart, and live!** 🌟  

Track **53 projects** and **163 tasks** with real-time insights on **cost**, **progress**, **timelines**, and **team performance**. No more messy spreadsheets — just clear visuals to help you make fast, smart decisions.

Perfect for **project managers**, **teams**, and **leaders** who want to stay on time, on budget, and in control.

---

## Data Model – Clean & Powerful (Star Schema) 🏗️

![Data Model View](Performance%20Dashboard/Image_Performance/Model_View.png)

Built on a **robust star schema** for speed and accuracy:

### Fact Tables
- `Fact_Project` – Core project data (budget, dates, status)
- `Fact_BudgetAnalysis` – Cost vs budget tracking
- `Fact_MonthlyExpense` – Monthly spend trends

### Dimension Tables
- `Dim_Assignees` – Team members & roles
- `Dim_Location` – Project sites (USA map ready)
- `Dim_ProjectType` – Residential, Infrastructure, etc.
- `Dim_Task` – All 163 tasks with status
- `Dim_TaskStatus`, `Dim_ProjectStatus`, `Dim_Priority`
- `Dim_Calendar` – Time intelligence (monthly trends)

> **20+ DAX measures** power progress %, budget health, overdue flags, and more.

---

## Why This Dashboard Works So Well 🚀

- **Live updates**: Data refreshed **November 7, 2025, 8:27 AM**
- **See risks fast**: Overbudget? Delayed? One glance tells you
- **Drill down easy**: Click any project or manager
- **Mobile ready**: Clean layout works on any screen
- **Smart design**: Purple accents, white space, intuitive flow

---

## Key Insights Right Now 🔑

All money values in **thousands (K)** | Updated **Nov 7, 2025**

| Highlight                  | Details                                      | Action Needed                                      |
|----------------------------|----------------------------------------------|----------------------------------------------------|
| **Total Budget**           | **$10,469K**                                 | Solid funding — but 83% already used!              |
| **Total Spent**            | **$8,733K**                                  | Fast burn rate — efficiency or risk?               |
| **Budget Remaining**       | **$1,736K**                                  | Only 17% left — monitor closely                    |
| **Average Progress**       | **75%**                                      | Good pace — push to finish strong                  |
| **Biggest Over Budget**    | **P037 - Skylink Metro**: **$342K over** (105.1%) | **Urgent review** — top cost overrun               |
| **Most Delayed**           | **P017 - Urban Trade Hub**: 552 days late    | Re-scope or add resources now                      |
| **Top Performer**          | **Bilal Ibrahim**: 92% progress, 1 overdue   | Recognize & learn from! 🏆                         |
| **Burnout Alert**          | **Hakima Amrani**: 5 overdue, 61% avg        | **Support needed** — 7 pending tasks               |
| **Overdue Tasks**          | **22 total** (mostly foundation & landscaping) | Prioritize to unblock progress                     |

---

## 4 Powerful Pages to Explore

### 1. **Home** – Your Daily Command Center
![Home Dashboard](Performance%20Dashboard/Image_Performance/P_Dashboard.png)

- Big KPIs: 53 projects, $8.7M spent, 75% progress
- Donut charts: Status & priority
- USA map: Hot spots (Texas leads!)
- Mini manager cards with overdue & progress

> **Quick Win**: 30% projects **not started** — start them today!

---

### 2. **Cost Analysis** – Follow the Money
![Cost Analysis](Performance%20Dashboard/Image_Performance/Cost_Analysis.png)

- Monthly trend: Budget vs actual spend
- Budget by type: **Residential ($2.1M)**, **Commercial ($2.1M)**
- Overbudget table: **Skylink Metro leads at 105%**

> **Insight**: Infrastructure & Residential both at **83% used** — balanced but tight!

---

### 3. **Project Timeline** – Gantt-Style View
![Project Timeline](Performance%20Dashboard/Image_Performance/Project%20Timeline.png)

- Color-coded bars: Completed, In Progress, Not Started, Overdue
- See task owners: **Omar Karim** & **Adil Sami** juggling multiple
- Search & filter by project or task

> **Bottleneck Alert**: Foundation & electrical phases = most delays

---

### 4. **Project Manager** – Team Performance Hub
![Manager Insights](Performance%20Dashboard/Image_Performance/P_Manager.png)

| Manager | Projects | Overdue | Budget Used | Progress |
|--------|----------|---------|-------------|----------|
| Teresa Kralova | 7 | 0 | **89%** | 85% |
| Siti Afiqah | 6 | 1 | 85% | 79% |
| 
