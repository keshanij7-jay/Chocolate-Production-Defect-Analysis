# Chocolate Production Defect Analysis

### Excel & Power BI–Based Quality Analytics System

**Final Year Industrial Placement Project | Ceylon Chocolates Ltd. | Production Department**
**Project Period:** September–December 2025 | **Grade:** A+

## OVERVIEW OF THE PROJECT

This project developed a **data-driven production defect analysis and quality monitoring system** for the chocolate manufacturing process at **Ceylon Chocolates Ltd.**

The project integrates **Microsoft Excel, VBA automation, statistical analysis, Lean Six Sigma concepts, and Power BI** to transform production records into meaningful quality insights.

The primary goal was to improve visibility of production defects, identify major sources of damage, monitor production KPIs, and support **data-driven quality improvement and continuous improvement decisions**.

### Business Problem

Production defect information was being recorded during manufacturing, but the available information was not being fully utilized for deeper analysis.

Key challenges included:

* Production data was maintained separately across machines.
* Overall production and defect trends were difficult to identify.
* Recurring defect patterns were not immediately visible.
* Reporting was mainly descriptive.
* Production teams required clearer analytical insights to support improvement decisions.

### Business Question

> **How can production defect data be systematically consolidated, analyzed, and visualized to identify quality problems and support defect reduction?**

### Solution

A structured **Excel + Power BI Quality Analytics System** was developed:

```text
Production Data
       ↓
Data Consolidation
       ↓
VBA Automation
       ↓
Data Preparation
       ↓
Statistical & Quality Analysis
       ↓
Pareto / Trend / KPI Analysis
       ↓
Power BI Dashboard
       ↓
Actionable Production Insights
```

# EXECUTIVE DASHBOARD

The Power BI dashboard provides an interactive overview of production performance and quality indicators.

### Dashboard Capabilities

*  Date-based filtering
*  Machine/section filtering
*  Product/category filtering
*  Total input and output monitoring
*  Damage monitoring
*  Production and damage trends
*  Category-level damage analysis
*  Interactive exploration of production performance

### Dashboard Preview

**Add your Power BI dashboard screenshot here**

The dashboard converts raw production records into a visual decision-support tool, allowing production performance and damage patterns to be explored more efficiently.

# KEY FINDINGS

The analysis provided several useful insights into production quality:

### 1. Packaging-related operations were a major area of concern

The analysis indicated that production damage was particularly associated with **packaging-related operations**, highlighting these areas for further investigation and process improvement.

### 2. Damage patterns varied across production areas

Machine/section-level analysis helped identify differences in damage contribution and provided a basis for prioritizing improvement efforts.

### 3. Pareto analysis supported prioritization

Pareto analysis was used to identify the categories and production areas contributing most significantly to recorded damage.

### 4. KPI monitoring improved visibility

Production input, output, damage, and damage rate were brought together to provide a clearer view of production quality.

### 5. Data analytics supported continuous improvement

The project demonstrated how structured production data combined with **statistical analysis, visualization, and Lean Six Sigma principles** can support data-driven quality improvement.

* **Important:** The project established an analysis and monitoring system. A longer post-implementation study would be required to statistically quantify sustained defect reduction.

# REPORT CONTENTS

The complete project documentation covers:

### 01. Project Proposal

Defines the business problem, objectives, significance, methodology, expected outcomes, and project scope.

### 02. Data Collection

Real production data were collected from the chocolate production environment during:

**01 September 2025 – 15 September 2025**

### 03. Data Consolidation

Production records from multiple machines were consolidated into a centralized Master Sheet.

### 04. Data Preparation & Analysis

The data were structured and analyzed using Excel-based analytical techniques.

### 05. Quality Analysis

The project applied:

* Pareto Analysis
* Trend Analysis
* KPI Analysis
* Machine/section comparison
* Damage-rate analysis
* Lean Six Sigma quality concepts

### 06. Power BI Dashboard

Interactive visualizations were developed for production and quality monitoring.


### 07. Findings & Recommendations

Key production-quality patterns were identified and potential improvement areas were highlighted.

### 08. Limitations & Future Development

The project limitations and opportunities for extending the system into advanced analytics are documented.

# METHODOLOGY

The project followed a structured industrial analytics workflow:

```text
1. Data Collection
        ↓
2. Data Consolidation
        ↓
3. Data Preparation
        ↓
4. Exploratory & Statistical Analysis
        ↓
5. Quality Analysis
        ↓
6. KPI Development
        ↓
7. Power BI Visualization
        ↓
8. Insight Generation
        ↓
9. Improvement Recommendations
```

## Data Structure

The dataset contains production information including:

| Variable          | Description                |
| ----------------- | -------------------------- |
| Date              | Production date            |
| Category          | Chocolate/product category |
| Section / Machine | Production machine         |
| Input (kg)        | Production input quantity  |
| Output (kg)       | Good production output     |
| Damage (kg)       | Recorded production damage |

### Machines / Production Sources

* `KumFuji_Final`
* `SIG_old_Final`
* `Fuji_old_Final`

---

## VBA Data Consolidation

Production records were maintained separately for different machines.

VBA automation was developed to:

1. Access individual machine worksheets.
2. Identify the required production records.
3. Copy and consolidate the records.
4. Create a centralized Master Sheet.
5. Prepare the dataset for further analysis.

This reduced repetitive manual consolidation and improved consistency in the analytical workflow.

---

## Key Performance Indicator

### Damage Rate

[
\text{Damage Rate} =
\frac{\text{Total Damage (kg)}}{\text{Total Input (kg)}} \times 100
]

Additional indicators included:

* Total Input (kg)
* Total Output (kg)
* Total Damage (kg)
* Damage by Machine
* Damage by Category
* Production Trends
* Defect Contribution

---

# TECH STACK

| Technology / Method      | Application                               |
| ------------------------ | ----------------------------------------- |
| **Microsoft Excel**      | Data preparation, analysis & reporting    |
| **VBA**                  | Automated data consolidation              |
| **Power BI**             | Interactive dashboards & visualization    |
| **Statistical Analysis** | Production and defect analysis            |
| **Pareto Analysis**      | Prioritizing major defect contributors    |
| **Trend Analysis**       | Monitoring production/damage patterns     |
| **Lean Six Sigma**       | Quality improvement & root-cause thinking |

---

# PROJECT STRUCTURE

```text
Chocolate-Production-Defect-Analysis/
│
├──  data/
│   └── production_dataset.xlsx
│
├──  excel/
│   ├── MasterSheet/
│   ├── VBA/
│   └── Analysis/
│
├──  powerbi/
│   └── Dashboard/
│
├──  documentation/
│   ├── Project_Proposal.pdf
│   └── Project_Report.pdf
│
├──  images/
│   └── dashboard-preview.png
│
└── README.md
```

**Data Availability:** The dataset used in this project is based on **real production data collected during the industrial placement**. The company has granted permission for the dataset to be shared for academic and portfolio purposes.

# KNOWN LIMITATIONS

The following limitations should be considered when interpreting the analysis:

* **Limited observation period:** The analysis covers production data from **01 September 2025 to 15 September 2025**, limiting the ability to assess long-term and seasonal patterns.

* **Limited explanatory variables:** The dataset primarily contains production quantity and damage information. Additional factors such as detailed machine settings, downtime, environmental conditions, maintenance activities, and operator-level information were not included.

* **Data recording dependency:** The quality of the analysis depends on the accuracy and completeness of production records.

* **Limited scope:** The analysis focused on the machines, production categories, and variables available during the industrial placement period.

* **No predictive modelling:** The completed project focused on descriptive and diagnostic analytics using Excel and Power BI. Machine-learning-based prediction was outside the original project scope.

* **Short-term impact assessment:** The system was designed to support defect reduction and continuous improvement, but a longer post-implementation study would be required to statistically measure its sustained impact on defect rates.

These limitations provide opportunities to extend the system into **advanced statistical process control and predictive quality analytics**.

# FUTURE DEVELOPMENT

Potential extensions of the project include:

*  Python-based automated analysis pipeline
*  Advanced Statistical Process Control (SPC)
*  Machine-learning-based defect prediction
*  Automated anomaly detection
*  Defect cost estimation
*  Integration of machine downtime information
*  Automated data pipelines and dashboard refresh
*  Predictive quality monitoring

The long-term objective would be to evolve the current system from **descriptive/diagnostic analytics toward predictive quality analytics**.

---

# SKILLS DEMONSTRATED

### Data Analytics

* Data preparation
* Exploratory analysis
* KPI development
* Trend analysis
* Pareto analysis
* Data visualization

### Technical

* Microsoft Excel
* VBA automation
* Power BI
* Statistical analysis
* Dashboard development

### Business & Quality

* Manufacturing quality analysis
* Process improvement
* Waste reduction
* Root-cause analysis
* Lean Six Sigma

### Professional

* Working with real industrial production data
* Translating a business problem into an analytical solution
* Communicating analytical findings visually
* Developing a practical decision-support system

---

# PROJECT OUTCOME

The project successfully delivered an **Excel + Power BI production defect analysis system** that provides a structured approach to:

**Consolidate → Analyze → Visualize → Identify → Improve**

The system provides production-quality insights that can support more informed decision-making and continuous improvement.

### Academic Achievement

**Final Year Industrial Placement Project — Grade: A+**

This project represents my **first major industrial data analytics project**, applying mathematical, statistical, analytical, and quality-management concepts to a real-world production environment.

---

# AUTHOR

### K. A. Jayawardana

**BSc (Hons) Applied Sciences — Mathematics**

**Faculty of science**

**University of Peradeniya, Sri Lanka**

**Areas of Interest**

`Data Science` · `Data Analytics` · `Applied Mathematics` · `Statistical Modelling` · `Business Analytics`

---

## Acknowledgement

This project was completed as part of my industrial placement in the **Production Department of Ceylon Chocolates Ltd.**

I acknowledge the support and guidance provided during the industrial placement and the permission granted to use the production dataset for academic and portfolio purposes.
