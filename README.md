# 🚧 Capital Project Dashboard

## 📌 Overview

The **Capital Project Management Dashboard** is an end-to-end Power BI solution designed to monitor, analyze, and optimize capital project execution. The dashboard provides stakeholders with a centralized view of project budgets, costs, profitability, task progress, resource allocation, project status, and timeline tracking.

Built using a robust **Star Schema Data Model**, advanced **DAX measures**, **Row-Level Security (RLS)**, and custom **SVG-based KPI indicators**, the solution enables project managers and executives to make data-driven decisions throughout the project lifecycle.

---

## 📷 Dashboard Preview

### Executive Overview

![Overview Dashboard](assets/dashboard-overview.png)

### Task Timeline

![Task Timeline](assets/task-timeline.png)

---

## 🎯 Business Problem

Organizations managing multiple capital projects often struggle with:

* Budget overruns
* Schedule delays
* Limited project visibility
* Resource allocation challenges
* Tracking project profitability

This dashboard addresses these challenges through centralized project monitoring and analytics.

---

## 📊 Key Features

### Executive Overview Dashboard

#### KPI Monitoring

* Total Projects
* Total Tasks
* Total Cost
* Budget Utilization %
* Task Completion %

#### Financial Analysis

* Budget vs Cost Trends
* Monthly Profit Analysis
* Budget Utilization Monitoring

#### Project Tracking

* Project Status Distribution
* Task Priority Analysis
* Progress Monitoring
* Project Type Analysis

#### Geographic Analysis

* Project and Task Distribution by Location

#### Project Manager Performance

* Budget Management
* Cost Tracking
* Profit Contribution
* Task Completion Monitoring

---

### Task Timeline Dashboard

Interactive Gantt-style visualization featuring:

* Project Hierarchy
* Task Progress Tracking
* Start and End Dates
* Project Manager Assignments
* Status Monitoring
* Timeline Analysis
* Delay Identification

---

## 🏗️ Data Model Architecture

This solution follows a **Star Schema** design for improved scalability and performance.

### Fact Tables

* FactProjects
* FactTasks
* FactBudget
* FactCost

### Dimension Tables

* DimDate
* DimProject
* DimProjectManager
* DimLocation
* DimProjectStatus
* DimTaskPriority
* DimTaskStatus
* DimProjectType

### Star Schema Benefits

* Improved Query Performance
* Simplified Relationships
* Better DAX Efficiency
* Easier Maintenance
* Scalable Architecture

---

## 🔒 Row-Level Security (RLS)

Implemented **Dynamic Row-Level Security (RLS)** to ensure secure access to project information.

### Security Roles

#### Project Manager

Access only assigned projects.

#### Department Head

Access projects within their department.

#### Executive Team

Full access to all project data.

### Benefits

* Secure Reporting
* Role-Based Access
* Improved Data Governance

---

## ⚡ Advanced Power BI Concepts Used

### Data Modeling

* Star Schema Design
* One-to-Many Relationships
* Date Dimension Modeling

### DAX Measures

* Budget Utilization %
* Profit Calculation
* Task Completion %
* Cost Variance Analysis
* Dynamic KPI Metrics
* Time Intelligence Functions

### Power Query

* Data Cleaning
* Data Transformation
* Data Validation
* Query Optimization

### Advanced Features

* Row-Level Security (RLS)
* Interactive Drill-Through
* Dynamic Filtering
* Cross-Highlighting
* Bookmarks & Navigation
* Custom Tooltips

---

## 🎨 SVG-Based Custom Visuals

Custom SVG visuals were used to create dynamic KPI indicators and progress bars.

### SVG Applications

* Budget Utilization Indicators
* Task Completion Bars
* Performance Tracking KPIs
* Progress Visualizations

### Advantages

* Lightweight Rendering
* Dynamic Formatting
* Enhanced User Experience
* Better Visual Consistency

---

## 📈 Business Insights

The dashboard helps stakeholders answer:

* Which projects are over budget?
* Which projects are most profitable?
* What percentage of tasks are completed?
* Which project managers are performing best?
* Where are project delays occurring?
* Which project types consume the highest budget?

---

## 🛠️ Tools & Technologies

| Technology       | Purpose               |
| ---------------- | --------------------- |
| Power BI Desktop | Dashboard Development |
| Power Query      | Data Transformation   |
| DAX              | Business Calculations |
| SVG              | Custom Visual Design  |
| Star Schema      | Data Modeling         |
| RLS              | Data Security         |
| Bing Maps        | Geographical Analysis |

---

## 🚀 Performance Optimization

The dashboard was optimized using:

* Star Schema Modeling
* Efficient Relationships
* Measure-Based Calculations
* Query Folding
* Reduced Cardinality
* Optimized DAX Patterns

---

## ⭐ Project Highlights

* End-to-End Power BI Dashboard
* Star Schema Data Model
* Dynamic Row-Level Security (RLS)
* Advanced DAX Calculations
* Custom SVG Visualizations
* Interactive Gantt Timeline
* Financial & Operational Analytics
* Executive Reporting Dashboard

---

<img width="1197" height="750" alt="image" src="https://github.com/user-attachments/assets/f7f4163f-9102-4688-8151-cd948072cef7" />

<img width="1206" height="747" alt="image" src="https://github.com/user-attachments/assets/89a25832-cc69-4254-bb43-afb959280522" />



If you found this project useful, consider giving it a ⭐ on GitHub.
