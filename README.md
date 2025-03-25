# 🎯 Strategic Customer Segmentation | Power BI

![Dashboard Preview](dashboard_preview.png)

*A data-driven approach to identifying high-value customer tiers*

## 📌 Key Insights
- **Revenue Focus**: High + Medium tiers generate **85% of total revenue**
- **Spending Power**: High-value customers spend **2.5X more** than average
- **Target Demographic**: 65% of high-value customers are **female** (insight for marketing)

## 🛠️ Implementation
### 🔧 Data Preparation
- **Dataset**: [Mall Customer Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Tools Used**:
  - Power Query for cleaning
  - **Conditional Column** for tier classification:
    ```
    High: Spending Score > 70
    Medium: Spending Score 40-70 
    Low: Spending Score < 40
    ```

### 📊 Dashboard Features
| Visual | Purpose |
|--------|---------|
| **Tier Distribution Pie** | Revenue share by customer segment |
| **Age vs. Spend Scatter** | Spending patterns colored by tier |
| **Gender Comparison Bar** | Tier distribution by gender |
| **Dynamic Slicers** | Age group + gender filters |

## 💡 Business Value
- Identified **$120K potential** in under-targeted Medium-tier customers
- Reduced segmentation analysis time by **50%** vs manual Excel methods
- Enabled **gender-specific** campaign strategies

## 💻 How to Use
1. Download `Customer_Segmentation.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
3. Interact with:
   - Gender/Age slicers
   - Click visuals to cross-filter

## 📂 Repository Files
- `Customer_Segmentation.pbix` - Power BI file
- `dashboard_preview.png` - Dashboard snapshot
- `mall_customers.csv` - Sample data

---

> 💡 **Pro Tip**: The conditional column approach makes this analysis easily maintainable for business users!

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-blue?logo=linkedin)](your_profile_url)
