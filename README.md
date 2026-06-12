# My Data Analyst Portfolio

## Currently Building
(https://github.com/Flaviusben/customer-base-audit) — CLV analytics that validates its own assumptions.

Unlike naive text-to-SQL utilities or cookie-cutter analytics dashboards that blindly fit models to invalid data, this system encodes **Judgment-as-Code**. It acts as an automated methodology gate—interrogating data anomalies, checking structural assumptions, and catching model violations (such as the frequency-spend correlation on academic benchmarks) before generating executive insights.

**What I've Done:**
- **Ingestion Gate & Fuzzy Mapping:** Fuzzy-matches messy, unvetted transaction CSV headers to canonical RFM matrices.
- **Contractual Auto-Detection:** Interrogates purchase cadence and price variance to auto-detect business models, executing a hard-refuse path if contractual (subscription) data tries to enter a non-contractual (BG/NBD) pipeline.
- **Probabilistic CLV & Segmentation Scoring:** Fits BG/NBD and Gamma-Gamma models to output 12-month value forecasts, P(alive) scores, and Stobachoff concentration metrics.
- **Executive Synthesis:** Generates a boardroom-ready HTML brief that maps out a 4-quadrant strategic asset framework while programmatically embedding methodology warnings in the footer.

---

### 📝 Projects
### **Projecting Romania's Electricity Prices: An Analysis of NECP Scenarios & Renewable Energy Impact** - as part of my Bachelor's Thesis
🔗 **[View Electricity Prices Project](projects/REI-Impact-and-Electricity-Prices.html)**

#### 🔍 **Key Insights:**
- **Historical Price Drivers Identified:** Developed a robust log-linear OLS model (2015-2022 data) with Newey-West HAC standard errors, confirming EU ETS carbon costs and fossil fuel production levels significantly increased historical electricity prices, while wind and hydro generation had a statistically significant price-depressing effect (merit-order).
- **Scenario Projections (WAM vs. WEM):** Utilized the validated historical model to project average monthly electricity prices for Romania under the NECP’s 'With Existing Measures' (WEM) and 'With Additional Measures' (WAM) scenarios for 2025 and 2030.
- **WAM Shows Significant Price Advantage:** Projections indicate the WAM scenario consistently yields lower average electricity prices compared to WEM, with the difference widening to approximately €20.1/MWh by 2030.
- **Wind Power as Key Differentiator:** WAM’s projected price advantage is predominantly attributable to its significantly higher assumed deployment of wind power.

### **Machine Learning: Sentiment Analysis and Topic Modelling with Latent Dirichlet Allocation (LDA)**
🔗 **[View Sentiment Analysis Project](projects/Sentiment-Analysis---Topic-Modelling.html)**

*Explored customer sentiment and feedback trends using sentiment analysis and topic modeling techniques in R. The main goal was to uncover key themes in customer reviews and analyze their impact on products satisfaction and sales.*

#### 🔍 **Key Insights:**  
- **Sentiment Analysis:** Used `tidytext` with **NRC** and **Bing** lexicons to classify reviews as positive/negative.  
- **Bigram & Trigram Analysis:** Extracted common word pairings to reveal sentiment-driving phrases.  
- **Topic Modeling (LDA):** Identified hidden themes in customer feedback (e.g., **technical issues, delivery concerns, product satisfaction**).  
- **Predictive Modeling:** Developed a customer satisfaction model by integrating **review sentiment, ratings, and product feedback**. (in propgress) 

### **Analyzing the average sea level change since 1880 and predicting sea level until 2050 using R.**
🔗 **[View Sea-Level-Rise Project](projects/Sea-Level-Rise.html)**
#### **Same Project using Python**
🔗 **[View Sea-Level-Rise Project](projects/Sea_Level_Rise.html)**

### **Building a Dashboard in Excel**
📊 [Download the Excel Dashboard](projects/Excel_Project_Dashboard.xlsx)

  *Explored bike sales per region and customers*
  
### **Building a Dashboard in Power BI**
📊 [The Dashboard Link](projects/Power_BI_Survey_Dashboard.pbix)

  *Used basic data modelling and visualizaion to create a breakdown of Data Professionals' salary*

## 📬 Contact Me  
📩 Email: benfulness24@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/flaviusben)  
🔗 [GitHub](https://github.com/Flaviusben)  
