# ⚙️ Applying AI for Equipment Logs

## 🧭 Overview
**Applying AI for Equipment Logs** is a Microsoft Power Automate project designed to automate the extraction and analysis of data from structured equipment log sheets uploaded to SharePoint. The extracted data is then stored in Excel and visualized through a Power BI dashboard embedded within the **Quattrofy** web application. This project supports decision-making on equipment maintenance vs. replacement by identifying service costs over time.

---

## 💡 Idea & Concept
The purpose of this project is to eliminate manual entry and improve reporting accuracy for equipment maintenance logs. By leveraging AI Builder in Power Platform, structured documents (equipment logs) are analyzed, and key service and cost data are extracted to support business intelligence efforts.

This initiative was built as part of Quattro Constructors’ digital transformation strategy to better monitor asset health and reduce long-term operational costs.

---

## ✨ Features & Functionality
- **AI-Driven Data Extraction** from structured PDF equipment logs
- **Trigger-based Automation** using SharePoint folder upload
- **Field Mapping via AI Model** for:
  - Vendor name
  - Date of service
  - Table of services provided
  - Type of service
  - Individual and total costs
- **Data Storage** in Excel for processing and archiving
- **Power BI Dashboard** to:
  - Visualize service cost trends
  - Compare equipment maintenance expenses
  - Evaluate cost-effectiveness of continued servicing vs. replacement

---

## ⚙️ Tech Stack

| Tool / Technology       | Description                                     |
|-------------------------|-------------------------------------------------|
| ![Power Automate](https://img.shields.io/badge/Power%20Automate-0089D6?logo=Microsoft%20Power%20Automate&logoColor=white&style=for-the-badge) | Workflow automation |
| ![AI Builder](https://img.shields.io/badge/AI%20Builder-742774?logo=microsoft&logoColor=white&style=for-the-badge) | Custom model to read structured documents |
| ![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?logo=microsoft&logoColor=white&style=for-the-badge) | Trigger file uploads and store logs |
| ![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white&style=for-the-badge) | Store extracted data |
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black&style=for-the-badge) | Dashboard for visualizing service costs |
| ![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white&style=for-the-badge) | Data structure in flows |
| ![Quattrofy](https://img.shields.io/badge/Quattrofy-App-integration-blue?style=for-the-badge) | Internal web app embedding Power BI dashboard |

---

## 🧑‍💻 My Role & Contributions
- Designed and trained the AI Builder model for document structure
- Built Microsoft Flow to trigger on SharePoint upload and extract AI data
- Mapped fields from document to Excel rows
- Built and embedded Power BI dashboard into Quattrofy web app
- Optimized flow for scale and cross-project use

---

## 📊 Results
- Enabled near real-time visibility of equipment service costs
- Reduced manual entry errors
- Helped stakeholders make data-driven decisions about asset lifecycle
- Enhanced Quattrofy's ability to centralize analytics for operations

---

## 🔍 Related Projects
- [Quattrofy](#)
- [Microsoft Flow PO Requests (AI)](#)
- [Quattrofy API](#)
