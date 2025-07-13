# Customer Segmentation using SQL + RFM Analysis

This project uses real transactional data to segment customers using the RFM (Recency, Frequency, Monetary) model and basic SQL skills — helping businesses understand customer behavior and take smarter marketing actions.

---

## Objectives

- Clean and prepare transaction data
- Use **SQL** to calculate Recency, Frequency, and Monetary values
- Score customers on RFM scale (1–5)
- Segment customers into actionable groups: Champions, Loyal, At Risk, etc.
- Visualize the distribution of customer segments

---

## Dataset

- Dataset: Online Retail II  
- Columns used: `CustomerID`, `InvoiceDate`, `InvoiceNo`, `Quantity`, `Price`
- Cleaned using Python (missing values, non-positive amounts removed)

---

## Tools Used

- **SQL**: For RFM calculations directly in the database
- **Python (Pandas + Matplotlib)**: For RFM scoring and segment tagging
- **Jupyter Notebook**: For analysis and documentation

---

## Key Segments Created

- **Champions** – High spenders, frequent, recent
- **Loyal** – Frequent buyers
- **At Risk** – Haven’t purchased in a while
- **Hibernating** – Inactive, low value
- **New Customers** – Recent but not yet active

---

##  Sample Output

![Bar chart showing customer segments](link-to-your-bar-chart-image-if-you-upload-it)

---

## How to Run

1. Clone the repository
2. Open the Jupyter notebook
3. Install dependencies: `pandas`, `matplotlib`, `sqlite3`, `ipython-sql`
4. Run all cells

---

##  Output

- Final customer segmentation saved as:  
  `rfm_segmented_customers.csv`

---

## 📢 Author

**Masruj Islam**  
BSc Digital Business & Innovation, Tokyo International University  


