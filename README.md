# Customer Segmentation & Personality Analysis Using RFM Modeling

## 📋Overview
The core objective of this project is to perform a comprehensive **Customer Personality Analysis** to help a retail business intimately understand its consumer base. By analyzing historical purchasing behaviors, demographic attributes, and engagement channels, this project builds data-driven customer profiles.

Instead of exhausting marketing budgets on generic, blanket campaigns across the entire database, this analysis empowers the business to target specific high-yield segments, modify product offerings to match distinct behavioral preferences, and maximize marketing ROI.


## 📈 Executive Dashboard Preview
The analysis was executed and visualized using Power BI. Below is the primary analytical interface:

*Place your dashboard screenshot here to make your repository stand out!*
### Key Performance Indicators (KPIs)
* **Total Revenue Generated (Spent):** $1.36M
* **Total Active Customer Base:** 2,000 unique customers
* **Total Purchase Volume:** 33K transactions
* **Average Customer Income:** $51.68K
  

## 🧠 Analytical Framework: RFM & Demographics
Customers were segmented using an **RFM (Recency, Frequency, Monetary)** architecture combined with complex demographic attributes (Age Bins, Marital Status, Education Levels) to map behavioral trends across channels.

### 👥 Defined Customer Profile Groups

#### 1. At-Risk / Lost Segment (Mass Retention Target)
* **Profile:** This represents the single largest consumer cluster (approaching ~1,000 customers). They have high historical spend/frequency but have gone cold recently.
* **Demographics:** Highly concentrated in the middle-age categories (Ages 40–60), predominantly married with higher education degrees (Graduation/Master).
* **Actionable Strategy:** Deploy automated email win-back sequences. Offer targeted promotional discounts tailored toward categories they historically frequented to incentivize immediate reactivation.

#### 2. Potential Loyalists & New Customers (The Growth Engine)
* **Profile:** Recent buyers displaying low-to-moderate purchase frequency but high active discovery traits.
* **Demographics:** Lean younger (Ages 20–40) with a notable presence of single individuals and consumers with basic/2n Cycle education.
* **Behavior:** Highest digital foot traffic via web visits and web-based buying channels over traditional catalog options.
* **Actionable Strategy:** Optimize digital onboarding journeys. Run targeted social/web cross-selling campaigns focused on auxiliary product lines (e.g., Sweet and Gold items) to scale their Average Order Value (AOV).

#### 3. Champions & Loyal Customers (The High-Value Core)
* **Profile:** High recency, high frequency, and high monetary contributions. This elite group generates a heavily disproportionate share of the total $1.36M revenue.
* **Demographics:** Markedly older consumer segment (Ages 50–80+). This correlates with scatter plot trends showing a dense upward trajectory of high-spending outliers aged 75–85.
* **Behavior:** Major consumers of premium categories specifically **Wines** and **Meats**. They favor offline transactional touchpoints, showing strong metrics in Store Purchases and Catalog Purchases.
* **Actionable Strategy:** Roll out closed-loop premium loyalty or VIP rewards systems. Lean heavily on high-touch offline marketing channels (such as physical catalog drop-offs or priority in-store events).



## 🔍 Core Insights Captured

* **Product Category Dominance:** Wine and Meat stand out as the undisputed primary revenue drivers across every single age demographic over 30. Fruits, Sweets, and Fish products maintain highly niche positions.
* **The Digital Browse-to-Buy Loop:** While older demographics exhibit peak physical in-store purchasing numbers, their digital footprint remains remarkably high. This implies heavy digital pre-browsing behavior before finishing a sale offline.
* **Peak Purchasing Demographic:** The 40–60 age bracket functions as the primary economic engine for the business, leading engagement across store, web, and catalog channels alike.



## 🛠️ Technical Stack & Tools Used
* **Power BI Desktop:** End-to-end data modeling, DAX measure creations, and interactive visualization building.
* **Power Query:** Applied data transformations, structural data cleaning, conditional column creation, and custom age binning.
* **RFM Architecture:** Clustered grouping logic to isolate behavior profiles.



## 📂 Repository Contents
* `Customer_Segmentation_Report.pbix` — The complete interactive Power BI Dashboard file.
* `marketing_campaign.xlsx` — Folder containing the foundational raw datasets.


