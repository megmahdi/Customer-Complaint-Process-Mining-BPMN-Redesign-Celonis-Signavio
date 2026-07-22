# Dataset Information

## Dataset

**BPI Challenge 2016 – Customer Complaints**

This dataset originates from the **Business Process Intelligence (BPI) Challenge 2016** and contains customer complaint records from the **Dutch Employee Insurance Agency (UWV)**. It is widely used for process mining education and research to analyze real-world business processes through event log data.

The dataset included in this repository (`BPI2016_Complaints.csv`) was imported into **Celonis Process Mining** for process discovery and analysis, with the findings later used to redesign the process in **SAP Signavio** using **BPMN 2.0**.

---

## Dataset Structure

The dataset consists of **18 attributes** describing customer information, complaint details, communication channels, and complaint classifications.

| Column | Description |
|---------|-------------|
| CustomerID | Unique identifier for each customer. |
| AgeCategory | Customer age group. |
| Gender | Customer gender. |
| Office_U | Internal office identifier (U). |
| Office_W | Internal office identifier (W). |
| ComplaintDossierID | Identifier for the complaint dossier (case). |
| ComplaintID | Unique complaint identifier. |
| ContactDate | Date the complaint was recorded. |
| ContactChannelID | Communication channel used to submit the complaint. |
| ComplaintThemeID | Identifier for the main complaint category. |
| ComplaintSubthemeID | Identifier for the complaint subcategory. |
| ComplaintTopicID | Identifier for the specific complaint topic. |
| ComplaintTheme | Main complaint category. |
| ComplaintSubtheme | Detailed complaint category. |
| ComplaintTopic | Specific complaint topic. |
| ComplaintTheme_EN | English translation of the complaint category. |
| ComplaintSubtheme_EN | English translation of the complaint subcategory. |
| ComplaintTopic_EN | English translation of the complaint topic. |

The complaint classifications cover topics such as payment issues, communication problems, administrative errors, appointments, document processing, and other customer service-related concerns.

---

## Project Usage

This dataset was imported into **Celonis Process Mining** to:

- Discover the existing complaint handling process.
- Analyze process variants and case behavior.
- Identify operational inefficiencies and improvement opportunities.
- Support the redesign of the workflow using **SAP Signavio (BPMN 2.0)**.

---

## Notes

Although the dataset provides detailed customer and complaint information, the event log contains only a single recorded activity for each complaint case. As a result, end-to-end process metrics such as throughput time, waiting time, and bottleneck analysis cannot be fully observed. These limitations were considered when redesigning the complaint handling process.
