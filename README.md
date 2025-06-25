#  Superstore Sales Analysis  (Identified Profit - Loss Pattern)
**Tools Used: Excel | Python | Power BI**

---

##  Business Context

Retailers often have vast amounts of sales data, but it's difficult to pinpoint what’s truly driving profit — or causing losses.

This project dives into Superstore's historical sales data to uncover:
- Which customer segments and regions are profitable or in loss
- How discounts impact profit
- Which product categories are major contributors to losses

The ultimate goal: **enable smarter pricing, discounting, and product decisions.**

---

##  Problem Statement

 “How can we identify and reduce sales losses by analyzing customer segments, product categories, and regional sales patterns?”

---

##  Project Objectives

1. Explore sales data to uncover trends, patterns, and outliers  
2. Identify products, discounts, and regions that drive losses  
3. Build an interactive Power BI dashboard for decision-makers  
4. Provide actionable recommendations to boost profitability

---

##  Key EDA Insights (Excel + Python)

|  Insight             | Description |
|  South region       | Highest concentration of loss-making orders |
|  Tables & Bookcases | Contribute over 30% of total losses |
|  Discounts >30%     | Often result in negative average profit |
|  Corporate Segment  | More profitable than Consumer customers |

---

##  Loss Driver Analysis

Performed deeper filtering and grouping on rows with `Profit < 0`.  
Key techniques:
- Excel pivot tables to segment by Sub-Category and Region  
- Python `groupby()` to isolate discount impact  
- Visualized **Discount vs. Profit** trends

---

##  Power BI Dashboard Highlights

Designed an interactive dashboard summarizing business performance.

** Visuals Included:**
- KPI Cards: Total Sales, Total Profit, Order Count, Loss Order Count
- Slicers: Region and Segment
- Bar Chart: Profit by Category
- Line Chart: Discount vs. Average Profit
- Table: Top 10 loss-making orders

** Preview Screenshot:**  

---

##  Tools & Technologies

- **Excel**: Data cleaning, filtering, pivot insights  
- **Python**: EDA with `pandas`, `matplotlib`  
- **Power BI**: Dashboard creation & DAX measures  
- **GitHub**: Version control & documentation

---


---

##  Business Recommendations

| # | Recommendation                       | Justification |
| 1 | **Cap Discounts at 20–25%**          | Prevent margin erosion on high-discount orders |
| 2 | **Audit Tables & Bookcases**         | These are frequent loss-making categories |
| 3 | **Focus on Corporate Clients**       | They deliver higher profitability |
| 4 | **Improve South/Central Strategies** | These regions have the most losses despite decent sales |

---

##  How to Run This Project

- Open `.pbix` file in Power BI Desktop to explore dashboard  
- Review Excel pivots in `Day3_LossAnalysis_Superstore.xlsx`  
- Use Jupyter or VS Code to run Python notebooks for EDA

---

## Author

**Parul Dhami**  
Aspiring Data Scientist | Skilled in Power BI, Python, Excel, and SQL  | Data Analyst
 [dhamiparul1@gmail.com]  
GitHub: [https://github.com/Amodni007]
LinkedInhttps://www.linkedin.com/in/paruldhami/: 

---


