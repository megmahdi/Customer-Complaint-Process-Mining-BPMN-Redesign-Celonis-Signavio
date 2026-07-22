# Customer-Complaint-Process-Mining-BPMN-Redesign-Celonis-Signavio

Process Mining with **Celonis** | BPMN 2.0 Modeling with **SAP Signavio**

## Overview

This project analyzes a customer complaint handling process using the **BPI Challenge 2016** event log. The objective was to discover the existing process, identify operational issues through process mining, and redesign the workflow using **BPMN 2.0** and process redesign heuristics.

The project was completed as part of my Master's coursework in **Business Process Management** at WU Vienna.

## Tools

- Celonis Process Mining
- SAP Signavio
- BPMN 2.0
- Microsoft Excel

## What I Did

- Imported the BPI Challenge 2016 event log into Celonis.
- Analyzed the process using Process Explorer, Variant Explorer, and Case Explorer.
- Identified major process issues based on the event log.
- Redesigned the process in SAP Signavio using BPMN 2.0.
- Applied process redesign heuristics to improve process efficiency.

## Key Findings

- High process variability due to many unique process variants.
- Limited end-to-end process visibility because complaint cases contained only one recorded activity.
- Fragmented complaint handling leading to duplicate work and inconsistent case management.

## Process Improvements

The redesigned BPMN model focused on:

- Standardizing complaint handling.
- Improving end-to-end case visibility.
- Reducing rework by keeping customer interactions within a single complaint case.

## Repository Contents

```
README.md
DatasetInfo.md
BPI2016_Complaints.csv
Report: Customer Complaint Process Mining & BPMN Redesign.pdf
images/
├── process_explorer_1.png
├── process_explorer_2.png
├── variant_explorer.png
├── case_explorer.png
├── fragmented_case_handling.png
└── bpmn_redesign.jpg
```




## Process Mining Visualizations

The following screenshots highlight key stages of the analysis performed in **Celonis Process Mining** and the final workflow redesign created in **SAP Signavio**.

### Process Explorer

The Process Explorer revealed a highly parallel and weakly structured complaint handling process, indicating inconsistent execution across complaint cases.

![Process Explorer](images/process_explorer_1.png)

---

### Variant Explorer

The Variant Explorer showed a large number of process variants with low coverage per variant, suggesting limited process standardization.

![Variant Explorer](images/variant_explorer.png)

---

### Case Explorer

The Case Explorer highlighted the lack of end-to-end process visibility, making throughput times and waiting periods unobservable.

![Case Explorer](images/case_explorer.png)

---

### Fragmented Case Handling

Analysis of complaint records suggested fragmented case handling, where repeated customer interactions were recorded as separate complaint cases rather than being managed within a single process instance.

![Fragmented Case Handling](images/fragmented_case_handling.png)

---

### BPMN Redesign

Based on the findings from the process mining analysis, the complaint handling process was redesigned in **SAP Signavio** using **BPMN 2.0** to improve standardization, visibility, and process efficiency.

![BPMN Redesign](images/bpmn_redesign.jpg)


