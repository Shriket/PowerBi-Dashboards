# **Purchase Department Analytics Dashboard**

## 🚀 Overview  
The **Purchase Department Analytics Dashboard** provides a **comprehensive view of the entire procurement lifecycle**, helping stakeholders track to optimize purchase activities. **Divided into two key sections – Indent & Purchase Order (PO)** – the dashboard enables real-time monitoring, **reducing manual effort by 90%, cutting purchase cycle time by 15%, and minimizing stock discrepancies by 21%**.   

---------------------------------------------------------------------------------------------------------
![Demo GIF](https://github.com/Shriket/PowerBi-Dashboards/blob/main/Procurement/Purchase%20Dept/Indent.png)
![Demo GIF](https://github.com/Shriket/PowerBi-Dashboards/blob/main/Procurement/Purchase%20Dept/Purchase%20Order%20(PO).png)
---------------------------------------------------------------------------------------------------------


## 🧗‍♂️ **Key Obstacles Faced** 

*   **Indent Data Mismatch:** Data discrepancies existed between the indent dashboard and the erp standard indent reports, raising concerns about data accuracy and reliability.
    *   *Mitigation:* Initiated a reconciliation process to identify and correct the data discrepancies between the dashboard and source reports with erp team.

*   **ERP Calculation Logic Deficiency:** The ERP system lacked transparency in its calculation logic for the procurement dashboard. Specifically, the dashboard provided counts based on indents, but did not adequately account for variations in items sanction statuses within those indents. [3]
    *   *Mitigation:* Collaborated with the ERP team to understand and document the calculation logic. Recommended modifications to incorporate item sanction statuses into the dashboard metrics.

- **Unwanted Item Grouping:** Items were grouped in ways that did not reflect business logic or were inconsistent with established categories. This made it difficult to analyze data trends and identify top-stock level products.
    *   *Mitigation:* Revised the item grouping logic based on business requirements and created new, more appropriate categories. Updated the dashboard to reflect the corrected item groupings.


## 🗣️📝 Reporting & Communication 
- Findings were simultaneously reported to key stakeholders throughout the resolution process.

---

## 🎯 **Key Features & Insights**  

### 📌 **1️⃣ Indent Lifecycle Tracking**  
- **Complete visibility into indent processing** – from creation to approval, rejection, and closure.
- **Drill down to individual item entries** to monitor key purchases and ensure timely approvals.
- **Track indent status counts** (Daily & FY) across Created, Checked, Approved-Pending, Approved-Closed, Rejected, and Closed.
- **Monitor pending indent distribution** across **sites, item groups, and individual items** to avoid procurement delays.
- **Analyze key purchase items** with details such as **sanctioned quantity, indent quantity, unit rates, and action status**.
- **Expedite approvals** for critical purchases, ensuring uninterrupted site operations.

#### **🔹 Business Impact:**  
✅ **Saved 2 months of manual effort annually**, tracking 1,800+ items.  
✅ **Reduced manual reporting by 90%**, improving decision-making.  
✅ **Cut purchase cycle time by 15%**, ensuring quicker procurement.  
✅ **Reduced stock discrepancies by 21%**, leading to optimized inventory and cost savings.  
✅ **Eliminated 2 months spent on report creation annually**, allowing teams to focus on strategic tasks.  

#### **🔍 Key Insights from Indent Tracking:**  
1️⃣ **Why were 25 tons allocated for a 20-ton requirement?** Align procurement with project budgets.  
2️⃣ **Identify the oldest pending indents & newest requests instantly** to prioritize approvals.  
3️⃣ **Approve/reject indents remotely** with live stock balances and consumption insights.  

---------------------------------------------------------------------------------------

### 📌 **2️⃣ Purchase Order (PO) Lifecycle Tracking**  
- **Monitor PO status counts** across Pending, Checked, Approved, Canceled, and Closed.
- **Deep-dive into vendor analytics** – understand total business given to vendors (₹, PO count, item count).
- **Track PO status for each vendor** – Pending, Approved, Closed, or Rejected – for full transparency.
- **One-click access to a vendor’s full FY statement**, including all PO numbers, item details, unit rates, and amounts.

#### **🔹 Business Impact:**  
✅ **Improved vendor negotiations**, leveraging full FY transaction insights.  
✅ **Ensured GRN compliance**, resolving discrepancies in pending PO bills.  
✅ **Optimized procurement expenses** with real-time cost tracking for critical materials (fuel, cement, etc.).  
✅ **Strengthened vendor relationships**, evaluating **benefits such as discounts, gifts, or loyalty advantages**.  

#### **🔍 Key Insights from PO Tracking:**  
1️⃣ **Identify bottlenecks** – e.g., *Material arrived on 15th March – why hasn’t work started?*  
2️⃣ **Track pending GRN entries** – *Why have bills been pending for 4 months after purchase?*  
3️⃣ **Plan procurement expenses** based on real-time consumption trends, aiding cash flow planning.  
4️⃣ **Analyze vendor relations** – *How much business did Vendor X get this year? Were discounts offered?*  
5️⃣ **Identify overpriced vendors** & demand better rates using real-time insights.  
6️⃣ **Leverage procurement volume for benefits** – e.g., *Purchasing multiple tippers – should we receive a corporate benefit?*  

---

## 🛠 **Tech Stack**  
🔹 **Power BI**  
🔹 **Excel**  
🔹 **Nway ERP Data Integration**  
🔹 **Python**  
🔹 **Jenkins**  

---

## 📌 **Conclusion**  
This **Purchase Department Dashboard** has **revolutionized procurement efficiency**, enabling **faster approvals, cost savings, and better vendor management**. By **eliminating manual reporting, optimizing indent and PO tracking, and leveraging real-time analytics**, the purchase team now operates with **enhanced transparency, accuracy, and strategic insights**. 🚀

