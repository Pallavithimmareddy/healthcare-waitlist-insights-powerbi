# healthcare-waitlist-insights-powerbi
# 🏥 Healthcare Waitlist Insights Dashboard (Power BI)

## 1️⃣ Project Title / Headline

**🏥 Healthcare Waitlist Insights Dashboard**  
An interactive Power BI dashboard designed to analyze hospital waitlist data across multiple specialties, case types, and age profiles — using **DAX**, **bookmarks**, and **tooltips** to enable intuitive, data-driven healthcare management.

---

## 2️⃣ Short Description / Purpose

The **Healthcare Waitlist Insights Dashboard** provides actionable insights into patient backlog trends.  
It helps healthcare administrators, analysts, and policy planners monitor and optimize patient wait times by analyzing **total waitlists, age groups, case types, and specialties** through interactive visualizations.

---

## 3️⃣ 🧰 Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization and dashboard creation platform.  
- ⚙️ **Power Query** – Used for data cleaning, transformation, and merging healthcare datasets.  
- 🧮 **DAX (Data Analysis Expressions)** – Created dynamic KPIs, YOY growth rates, and calculated measures.  
- 🧭 **Bookmarks & Navigation Buttons** – For smooth multi-page transitions (Summary, Detail, Drilldown).  
- 💬 **Custom Tooltips** – Display deeper context (e.g., patient distribution, specialty trends) on hover.  
- 🧱 **Data Modeling** – Star schema with fact table (Waitlist Data) and dimension tables (Date, Specialty, Case Type).  
- 💾 **File Format** – `.pbix` for the dashboard and `.png` images for previews.  

---

## 4️⃣ 📊 Data Source

**Source:** Simulated healthcare waitlist dataset (inspired by NHS open data & public healthcare analytics samples).  

The data includes:

- Monthly patient counts on waiting lists  
- Breakdown by **case type** (Outpatient, Day Case, Inpatient)  
- Specialty details (ENT, Orthopaedics, Dermatology, Surgery, etc.)  
- Age profile of patients  
- Date ranges from **2018 – 2021**  

Each record captures the number of patients in a specific specialty, categorized by age group and time band.

---

## 5️⃣ 🌟 Features / Highlights

### • Business Problem
Hospitals face increasing patient backlogs post-pandemic, making it difficult to prioritize treatments and resources effectively.  
Administrators need a real-time visual system to track **wait times**, **case severity**, and **specialty bottlenecks**.

---

### • Goal of the Dashboard
To build a Power BI dashboard that:

- Enables **executives** to monitor total and YOY changes in patient waitlists.  
- Helps **department heads** analyze performance by specialty and case type.  
- Allows **policy teams** to identify long-term trends and improve resource allocation.

---

### • Walkthrough of Key Visuals

| Section | Visual Type | Description |
|----------|--------------|-------------|
| **Header Cards** | KPI Tiles | Shows current month vs. previous year waitlist counts (709K vs. 640K). |
| **Waitlist Bifurcation** | Donut Chart | Displays the share of Outpatient, Day Case, and Inpatient cases. |
| **Waitlist Analysis (Age Band vs. Time)** | Clustered Bar Chart | Compares waiting times across different patient age groups. |
| **Top 5 Specialties** | Horizontal Bar Chart | Highlights top medical areas by patient volume. |
| **Monthly Trends Analysis** | Line Chart | Shows YOY comparison for case types (Day Case vs. Outpatient). |
| **Bookmarks Navigation** | Buttons | Lets users switch between Summary, Detail, and Drill Down pages. |
| **Tooltips** | Popup Pages | Provide additional data when hovering over visuals for deeper insights. |

---

### • Business Impact & Insights

- 🏥 **Operational Efficiency:** Quickly identifies which case types or specialties cause major delays.  
- 🧭 **Strategic Planning:** Hospitals can forecast resources based on backlog trends.  
- 💹 **Performance Tracking:** Administrators can evaluate YOY performance and growth.  
- 👨‍⚕️ **Data Transparency:** Encourages data-driven healthcare decisions and patient-focused strategies.

---

## 6️⃣ 🖼️ Screenshots / Demos

### Dashboard Preview
<p align="center">
  <img src="reports/Dashboard.png" alt="Healthcare Waitlist Dashboard" width="850"/>
</p>

### Additional Pages
<p align="center">
  <img src="reports/Summary_Page.png" alt="Summary Page" width="420"/> &nbsp;
  <img src="reports/Detail_Page.png" alt="Detail Page" width="420"/>
</p>

### Interactive Features
<p align="center">
  <img src="reports/Tooltip_View.png" alt="Tooltip View" width="420"/> &nbsp;
  <img src="reports/Navigation_Bookmarks.png" alt="Bookmark Navigation" width="420"/>
</p>

---

## 7️⃣ 🧩 Folder Structure


