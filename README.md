# Mortgage Loan Pipeline Risk & Prioritization Dashboard

## Live Dashboard
Tableau Public: https://public.tableau.com/views/MortgageLoanPipelineRiskPrioritizationDashboard/Dashboard1

![Dashboard](images/dashboard.png)

---

## Overview
This project provides an operational view of a mortgage loan pipeline, designed to help underwriting teams identify risk, prioritize work, and manage loan flow across stages.

---

## Business Objective
Provide a clear, actionable view of pipeline risk and prioritization to support underwriting decision-making and workflow management.

---

## Key Insights
- Aging Pipeline Loans represent the largest share of workload across the pipeline  
- LE Past Due loans, while smaller in volume, represent the highest operational risk  
- Urgency is driven more by compliance timing (disclosures) than total loan volume  
- Bottlenecks can be identified by concentration of loans within specific stages  

---

## Dashboard Features
- Pipeline heatmap by stage and priority tier  
- Identification of urgency drivers (e.g., past due disclosures, aging loans)  
- Actionable loan-level queue for prioritization  
- KPI tracking urgent loans (High + Critical)  

---

## Tools Used
- SQL (MySQL)  
- Tableau Public

---

## Version 2: Pipeline Bottleneck Analysis Extension

### Objective

Investigate whether Medium-tier loan aging reflected a true operational bottleneck or normal late-stage pipeline accumulation.

### Key Findings

- Medium-tier loans initially appeared to represent the primary bottleneck due to higher aging and loan volume.
- Stage-level analysis showed aging was concentrated in Clear to Close and Closing Scheduled stages.
- Findings suggested much of the accumulation reflected normal late-stage progression near completion rather than operational delay.

### Analytical Insight

Deeper drill-down analysis changed the original interpretation of the pipeline data. While Medium-tier loans appeared operationally problematic at a surface level, stage-level analysis indicated that much of the aging occurred near the end of the loan lifecycle, suggesting normal pipeline accumulation rather than a true workflow bottleneck.

### Skills Demonstrated

- SQL aggregation and drill-down analysis
- Tableau dashboard storytelling
- Operational workflow analysis
- Analytical interpretation and refinement
- Business process investigation

### Tableau Public

[View the Pipeline Bottleneck Analysis Extension on Tableau Public](https://public.tableau.com/views/PipelineBottleneckAnalysisExtensionStudy/PipelineBottleneckAnalysis)

### Dashboard Screenshot

![Pipeline Bottleneck Analysis Extension](images/pipeline_bottleneck_analysis_v2.png)

