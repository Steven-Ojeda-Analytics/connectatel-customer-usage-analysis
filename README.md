# ConnectaTel Customer Usage Analysis

## 📌 Project Overview
This project presents an end-to-end exploratory data analysis of a telecom customer dataset (ConnectaTel), focusing on understanding customer behavior through usage patterns, segmentation, and outlier detection.  
The objective is to transform raw usage data into actionable business insights that support decision-making, customer segmentation, and product strategy.

---

## 🎯 Objectives
- Clean and validate customer usage data
- Detect and interpret outliers in customer behavior
- Segment customers by **usage intensity** and **age group**
- Identify high-value customer segments
- Translate analytical findings into business recommendations

---

## 📊 Dataset Description
The dataset contains anonymized telecom customer information, including:
- `age`: Customer age
- `cant_mensajes`: Number of messages sent
- `cant_llamadas`: Number of calls made
- `cant_minutos_llamada`: Total call duration (minutes)

---

## 🧪 Analysis Workflow
1. **Data Cleaning**
   - Validation of data types
   - Review of missing and extreme values

2. **Outlier Detection**
   - Visual inspection using boxplots
   - Interpretation of extreme usage patterns
   - Decision to retain outliers when they represent real customer behavior

3. **Customer Segmentation**
   - **Usage-based segmentation**:
     - Low usage
     - Medium usage
     - High usage
   - **Age-based segmentation**:
     - Young
     - Adult
     - Senior

4. **Visualization**
   - Distribution plots for usage variables
   - Count plots for customer segments

5. **Executive Insights**
   - Identification of valuable customer groups
   - Recognition of intensive usage patterns
   - Business-oriented recommendations

---

## 💡 Key Insights
- High-usage customers represent a smaller segment but generate disproportionate value.
- Outliers are not data errors; they reflect intensive and potentially profitable usage behaviors.
- Adult and senior customers tend to concentrate higher call durations.
- Usage-based segmentation provides clearer business value than age alone.

---

## 📈 Business Recommendations
- Design premium plans tailored to high-usage customers
- Offer retention strategies for intensive callers
- Use segmentation to personalize marketing and pricing strategies
- Monitor extreme usage as an early signal for churn or upselling opportunities

---

## ▶️ How to Run the Notebook
1. Open the notebook in **Google Colab**
2. Run all cells sequentially from top to bottom
3. Ensure required libraries (pandas, seaborn, matplotlib) are available

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 👤 Author
**Steven Ojeda**  
Data Analytics & Business Intelligence  
GitHub: https://github.com/Steven-Ojeda-Analytics
