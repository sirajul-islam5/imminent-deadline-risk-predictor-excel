# ⏳ Imminent Deadline Risk Predictor — Excel Project

An Excel tool that automatically flags which tasks or projects are at risk of missing their deadlines — based on how much work remains versus how many days are left. Built entirely using core Excel formulas and conditional formatting, with no macros or external add-ins.

---

## 📌 Project Overview

When managing dozens or hundreds of tasks at once, it's easy to lose track of which ones are quietly heading toward a missed deadline. This project solves that problem by calculating a **Risk of Missing Deadline (%)** score for every task — instantly flagging it as Low, Medium, or High Risk based on its actual pace of completion.

The dataset simulates 124 real-world tasks across software development, IT operations, security, design, and business functions — giving the tool a realistic, cross-functional feel rather than a single-domain demo.

---

## 🖼️ Imminent Deadline Risk Predictor Preview

![Predictor Preview](risk-predictor-preview.png)

---

## 📊 Summary Metrics

| Metric | Value |
|--------|-------|
| Total Projects Tracked | 124 |
| High Risk Projects | 48 |
| Medium Risk Projects | 49 |
| Low Risk Projects | 27 |

---

## 🧮 How the Risk Score Works

Each task is evaluated using four core data points:

| Column | Description |
|--------|-------------|
| Tasks Completed | Number of subtasks finished so far |
| Total Tasks | Total subtasks required to finish the project |
| Days Left | Remaining days before the deadline |
| % Work Remaining | Percentage of total work not yet completed |
| Risk of Missing Deadline (%) | Calculated pace-based risk score |
| Risk Level | Auto-categorized as Low / Medium / High Risk |

**The logic in plain terms:**
The tool compares how much work is left against how much time is left. If the remaining work can't realistically be finished at the current pace within the remaining days, the risk score rises above 100% — signaling the deadline is very likely to be missed.

**Risk Level Categories:**
- 🟢 **Low Risk** — Risk score well under 100%, task is on pace   
- 🟡 **Medium Risk** — Risk score approaching or slightly over 100%   
- 🔴 **High Risk** — Risk score significantly above 100%, deadline is highly likely to be missed at current pace   

---

## 🔍 Sample Data Snapshot

| Task Name | Tasks Completed | Total Tasks | Days Left | % Work Remaining | Risk (%) | Risk Level |
|-----------|-----------------|-------------|-----------|-------------------|----------|------------|
| E-Commerce Payment Gateway | 4 | 10 | 3 | 60% | 200% | High Risk |
| API Gateway Overhaul | 5 | 9 | 6 | 44% | 74% | Medium Risk |
| Auth0 Integration | 9 | 10 | 2 | 10% | 50% | Low Risk |
| iOS Push Notifications | 6 | 8 | 1 | 25% | 250% | High Risk |
| Cloud Backup Automation | 10 | 10 | 3 | 0% | 0% | Low Risk |
| Zendesk Macro Clean-up | 3 | 7 | 1 | 57% | 571% | High Risk |
| SOC2 Compliance Check | 4 | 8 | 1 | 50% | 500% | High Risk |

> The dataset spans 124 tasks in total — covering engineering,
> security, design, and operations workstreams.

---

## 🛠️ Excel Skills & Features Used

| Feature | Purpose |
|---------|---------|
| Formula-Based Risk Calculation | Converts task pace into a single risk percentage |
| Conditional Formatting | Color-codes rows by risk level (red/yellow/green) |
| Summary KPI Cells | Live counts of High, Medium, and Low risk projects |
| Percentage Formatting | Displays work remaining and risk as clean percentages |
| Table Formatting | Bold header row with alternating row shading for readability |

---

## 💡 Key Learnings

- How to translate a real project-management problem into a single, automatically calculated risk metric   
- Building a percentage-based formula that scales meaningfully beyond 100% to clearly signal high-risk outliers   
- Using conditional formatting to make risk instantly visible without needing to read every row   
- Designing a dataset broad enough (124 tasks across multiple departments) to feel like a realistic portfolio tracker rather than a toy example   

---

## 🚀 How to Use

1. Download the `Imminent_Deadline_Risk_Predictor.xlsx` file   
2. Open it in Microsoft Excel   
3. Add a new task row with Tasks Completed, Total Tasks, and Days Left   
4. The % Work Remaining, Risk %, and Risk Level columns will calculate and color-code automatically   
5. Use the summary cells at the top to get an instant portfolio-wide risk overview   

---

## 👤 Author

**Md. Sirajul Islam**   
📎 [linkedin.com/in/md-sirajul-islam57](https://linkedin.com/in/md-sirajul-islam57)   
🐙 [github.com/sirajul-islam5](https://github.com/sirajul-islam5)   

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).   

---

> *This is a self-made mini project created for learning purpose.* 
