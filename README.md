# A/B Test Analysis: Impact of Larger Food Images on Conversion Rates

## 📌 Project Overview
This project analyzes an **A/B test conducted by a UK-based foodtech company** to evaluate the impact of **larger food images on restaurant menu cards** on **user experience and conversion rates**. The goal is to determine if increasing image size helps users make quicker purchasing decisions and improves order completion rates.


##📽️ Presentation Link
For a detailed walkthrough of the analysis, check out the presentation video: [Watch Here](https://www.loom.com/share/c055638c780b45e583651c6d144450a7?sid=cf872606-7ec4-41ed-992a-8edebc93e9ee)

## 📊 Experiment Details
- **Location**: London, UK
- **Test Duration**: November 25 – November 30, 2024
- **User Groups**:
  - **Control Group**: Saw the **original smaller images**.
  - **Test Group**: Saw **larger food images**.
- **Dataset**: Contains user interaction events, including restaurant visits, order placements, completed orders, and drop-offs.

## 🔍 Key Analysis & Findings
### **1️⃣ Conversion Rate Analysis**
- **User-Based Conversion Rate**
  - Control Group: **38.2%**
  - Test Group: **39.6%** (+1.4% increase)
- **Session-Based Conversion Rate**
  - Control Group: **24.6%**
  - Test Group: **25.8%** (+1.2% increase)
- **Key Insight**: The Test Group showed a higher conversion rate, but the increase was modest.

### **2️⃣ Statistical Significance Testing**
- **Entry to Shop → Order Paid**: ❌ **NOT statistically significant** (p-value = 0.479)
- **Entry to Shop → Successful Order**: ✅ **Statistically significant** (p-value = 0.0000177)
- **Key Insight**: Larger images **did not significantly increase order placements** but **did improve order completion rates** by reducing cancellations and refunds.

### **3️⃣ Drop-Off Rate Analysis**
- **Drop-Off at Entry to Shop**
  - Android: **57.05% (Control) vs. 57.56% (Test)**
  - iOS: **53.38% (Control) vs. 52.96% (Test)**
- **Drop-Off After Order Placement**
  - Android: **19.10% (Control) vs. 13.65% (Test)**
  - iOS: **19.36% (Control) vs. 13.66% (Test)**
- **Key Insight**: The Test Group had a **lower drop-off rate after placing an order**, meaning **larger images increased purchase confidence**.

### **4️⃣ Order Volume by Time of Day**
- **Highest order volume occurred in the evening (5 PM - 5 AM)**.
- **Afternoon performed better than morning**.
- **Key Insight**: Users order most in the evening, so promotions should be focused on high-volume time slots.

### **5️⃣ Platform-Based Conversion Analysis**
- **Android Conversion Rate**:  
  - Control: **37.18%**  
  - Test: **38.25%** (+1.07% increase)  
- **iOS Conversion Rate**:  
  - Control: **40.59%**  
  - Test: **42.84%** (+2.25% increase)  
- **Key Insight**: iOS users **responded better to larger images**, suggesting that visuals influence their purchasing decisions more.

### **6️⃣ Black Friday Influence on Results**
- **The test was conducted during Black Friday week**, which may have artificially increased conversion rates.
- **Key Recommendation**: Conduct a follow-up test outside of promotional periods to validate the findings.

## ✅ Business Recommendations
### **1. Implement Larger Images with Additional Enhancements**
- Keep **larger images** but also **improve restaurant descriptions, search filters, and highlight bestsellers** to drive conversions.

### **2. Address Drop-Off at the "Entry to Shop" Stage**
- Improve **restaurant layout, customer reviews, and estimated delivery times**.

### **3. Optimize for iOS Users**
- Conduct **UX testing on iOS** to identify friction points and improve navigation.

### **4. Leverage High-Converting Time Slots**
- **Run evening and afternoon promotions** (6 PM - 9 PM deals).
- Offer **late-night incentives** to increase orders.

### **5. Rerun the Experiment Outside of Black Friday**
- A follow-up test will ensure the results were not overly influenced by seasonal promotions.

## 📂 Technologies Used
- **Python (Pandas, NumPy, SciPy)** for data wrangling and statistical analysis.
- **SQL** for querying and data extraction.
- **Matplotlib, Plotly** for visualization.
- **Chi-Square Test** for statistical validation.

## 📌 Conclusion
While **larger images improved order completion rates and confidence**, they **did not significantly increase order placements**. To **maximize conversion improvements**, the company should **enhance restaurant discovery, optimize iOS UX, and refine time-based promotions**. A follow-up test outside of **Black Friday** is recommended to validate these findings.

