# 📞 Flipkart Customer Support Analysis

An Excel-based data analytics project focused on evaluating the performance of Flipkart’s customer service operations. The goal is to identify key pain points in customer support that affect customer satisfaction and retention, using customer call data and key service metrics.

---

### 🎯 **Project Objective**

- To analyze customer call data and assess various aspects of customer service performance to determine if and how it impacts customer retention.
- To identify specific issues within customer service operations that may be affecting customer satisfaction and retention rates.

---

### 👥 **User Journey**

1. The customer visits Flipkart to purchase a product.
2. The customer experiences an issue related to the order or platform.
3. The customer contacts Flipkart’s support team via available channels (chat, call, email).
4. Customer support aims to resolve the issue while focusing on:
   - Reducing response time  
   - Ensuring first-contact resolution  
   - Improving sentiment score and CSAT  

---

### 🛠️ **Tools Used**

- Microsoft Excel  
- Pivot Tables  
- Charts (Bar, Line, Pie)  
- IF, TEXT, MID, LEFT, RIGHT Excel functions  
- Conditional Formatting  

---

### 📌 **KPIs Tracked**

- **CSAT Score:** Measures how satisfied customers are with the support they receive.  
- **Sentiment Score:** Reflects customer sentiment in feedback on service quality.  
- **% Responses within SLA:** Percentage of support responses handled within the defined Service Level Agreement (SLA) time limits.  
- **Issue Resolution Time:** The average time taken to fully resolve an issue.  
- **First Contact Resolution (%):** The proportion of issues resolved during the first support interaction.  

---

### 🧹 **Data Cleaning and Processing**

1. **Data Import:**  
   - The raw CSV dataset was imported into Excel for analysis.

2. **Handling Missing Values:**  
   - **CSAT Scores:** Many entries had missing CSAT scores. These were retained to analyze patterns in interactions that didn't receive a score.  
   - **Other Columns (e.g., Customer Name, Gender, City, State):** Missing values in these fields were minimal and non-critical. No imputation was performed, but gaps were documented.

3. **Removing Duplicates:**  
   - The dataset was scanned for duplicate entries. None were found, ensuring clean and unique data records.

4. **Standardizing Data Formats:**  
   - **Call Timestamp:** This was formatted consistently using Excel's `TEXT`, `RIGHT`, `LEFT`, and `MID` functions to extract date and time.
   - **Call Duration:** Standardized into minutes and converted to numeric format for analysis.

5. **Data Processing:**  
   - **Sentiment Score:** Extracted using Excel’s `IF` function to generate a numerical sentiment score for trend analysis.  
   - **Call Day:** Derived from the timestamp to analyze performance and behavior across weekdays.

---

### 📊 **Charts & Visualizations**

1. **CSAT Score Distribution**  
   _Chart Type: Bar Chart_  
   > Shows overall satisfaction levels and highlights trends over time.

2. **Sentiment Score Analysis**  
   _Chart Type: Line Chart_  
   > Tracks average sentiment across different weeks/months.

3. **SLA Compliance Rate**  
   _Chart Type: Pie or Donut Chart_  
   > Indicates percentage of queries resolved within SLA targets.

4. **Resolution Time by Query Type**  
   _Chart Type: Column Chart_  
   > Helps identify which types of issues take the longest to resolve.

5. **First Contact Resolution Rate**  
   _Chart Type: Stacked Bar Chart_  
   > Compares one-contact resolution across different categories or teams.

---

### 🔍 **Key Insights**

- A significant number of queries are resolved within SLA, but resolution time varies by issue type.
- Higher sentiment scores correlate strongly with first-contact resolution.
- Some customer service teams consistently perform better in CSAT due to lower resolution times.
- Products with delivery or refund issues see lower CSAT and sentiment scores.

---

### 💡 **Recommendations**

- Invest in automation or better triaging for common issues to reduce resolution time.
- Offer additional training to teams with below-average first-contact resolution.
- Use customer sentiment feedback to personalize follow-ups and improve experience.
- Monitor SLA breaches closely to predict potential drops in CSAT.
- Create a CSAT-linked performance incentive to boost service quality.

---

### 🗂️ **File Structure**
├── 📊 dashboard.png # Final dashboard screenshot
├── 📁 Excel file
├── 📄 README.md # Project overview and documentation

---


