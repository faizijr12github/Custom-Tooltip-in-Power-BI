# 📊 Custom Tooltip in Power BI — Report Page Tooltip

> *Transforming static KPIs into transparent, explainable insights through interactive Report Page Tooltips.*

---

## 📖 Overview

This project demonstrates the implementation of **Custom Tooltips in Power BI** using **Report Page Tooltips** to enhance data storytelling and improve transparency of complex calculations.

The solution transforms a simple KPI into an **interactive experience** by revealing the complete calculation logic behind the metric — helping users better understand and trust the data.

---

## 🎯 Objectives

- ✅ Implement Report Page Tooltips in Power BI
- ✅ Improve data transparency and explainability
- ✅ Enhance user experience with contextual, on-demand insights
- ✅ Visualize complex DAX calculations in a simple, intuitive way

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Power BI Desktop** | Report development and design |
| **Report Page Tooltip** | Custom hover-triggered tooltip pages |
| **DAX** | Calculated measures and logic |
| **Data Modeling** | Relationships and schema design |

---

## 🚀 Key Features

### 🔹 1. "Glass Box" Calculation Logic
Instead of displaying only the final KPI value, the tooltip reveals the **full step-by-step breakdown**:

```
Team Members → Working Days → Activity % → Final Output
```

> ➡️ Converts a "black box" metric into a fully transparent, auditable model.

---

### 🔹 2. Weighted Logic Representation
Clearly explains how derived values are calculated, including complex logic such as:

- **Hybrid Staff Calculation** — e.g., `185 × 70%`
- Adjusted totals with visible weighting factors

> ➡️ No more guesswork — users see exactly how numbers are derived.

---

### 🔹 3. Clean & Minimal Dashboard Design
- Main dashboard displays **only the final KPI value** (e.g., `85.84%`)
- Detailed calculation logic is tucked inside the tooltip
- Prevents **information overload** while keeping insights accessible

> ➡️ A clean surface with depth underneath.

---

### 🔹 4. Contextual "On-Hover" Insights
- Tooltip triggered by hovering over an **info icon** `f(x)`
- Provides **just-in-time** explanations at the point of need

> ➡️ Acts as a built-in user guide and training aid.

---

### 🔹 5. Dynamic Calculation Flow
The tooltip is designed like a **visual flowchart**, using operators to represent the logic:

| Operator | Meaning |
|---|---|
| ➕ | Addition |
| ✖️ | Multiplication |
| ➗ | Division |
| `=` | Result |

> ➡️ Makes complex logic easy to follow at a glance.

---

### 🔹 6. Custom Tooltip Page Design
- Dedicated **hidden report page** created for the tooltip
- Page size configured for **optimal popup display**

> ➡️ Ensures a clean, focused, and professional popup experience.

---

### 🔹 7. Data Consistency with Filters
The tooltip **respects all active slicer selections** and works dynamically with filters such as:

- 📅 Response Date
- 📋 Survey Type

> ➡️ Guarantees accurate, real-time calculations in every context.

---

## 📊 Key Insights Delivered

| Insight | Detail |
|---|---|
| ⚠️ **Negative Variance Identified** | Highlighted **–187** remaining working days |
| 📉 **Operational Efficiency Metric** | Applied **80% activity factor** to convert expected hours → actual activity hours |

> ➡️ Enables better operational planning and data-driven decision-making.

---

## 💡 Benefits

| Benefit | Description |
|---|---|
| 🔍 **Data Transparency** | Full calculation logic is visible to end users |
| 🤝 **User Trust** | Builds confidence in reported metrics |
| 📊 **Data Storytelling** | Context-rich insights at every touchpoint |
| 🧠 **DAX Simplification** | Complex logic presented visually |
| ⚡ **On-Demand Insights** | Details available exactly when needed |

---

## 🧠 Key Learnings

- How to create and configure **Report Page Tooltips** in Power BI
- Techniques for explaining complex metrics through **visual storytelling**
- Designing **user-friendly BI reports** that balance detail and simplicity
- Best practices for **balancing depth vs. clarity** in executive dashboards

---

## 📂 Use Cases

This approach is ideal for:

- 📌 Complex KPI dashboards
- 📌 Business reports with calculated or derived metrics
- 📌 Executive dashboards requiring full transparency
- 📌 Onboarding and training users on report logic

---

## 💡 Outcome

- ✅ Built an **interactive and intelligent tooltip system**
- ✅ Transformed static KPIs into **explainable, trustworthy insights**
- ✅ Delivered a **professional and user-friendly** Power BI experience

---

## 📷 Preview

![Custom Tooltip in Power BI](https://github.com/user-attachments/assets/8fbc56e6-40a9-472f-a5f2-97b3bd0e34c7)

*The tooltip reveals the full calculation breakdown on hover — turning a single number into a complete data story.*

---

## 📁 Project Structure

```
📦 custom-tooltip-powerbi
 ┣ 📊 PowerBI_CustomTooltip.pbix       # Main Power BI report file
 ┣ 📷 screenshots/                      # Preview images
 ┗ 📄 README.md                         # Project documentation
```

---

## 🔗 Connect

If you found this project useful or have suggestions, feel free to open an **Issue** or submit a **Pull Request**.
