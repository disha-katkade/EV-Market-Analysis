# EV Market Segmentation Analysis⚡
The Indian Electric Vehicle (EV) market is growing rapidly, but adoption varies significantly across different vehicle categories. This project focuses on segmenting the EV market based on vehicle type using data analysis, visualization, time-series trends, and machine learning techniques.
The goal is to help EV manufacturers and stakeholders make data-driven strategic decisions regarding production, investment, and market expansion.

## 🎯Objectives
- Analyze EV adoption trends across different vehicle types
- Perform market segmentation using statistical and ML techniques
- Identify mature, high-growth, and emerging EV segments
- Provide actionable business recommendations for EV companies

## 📊 Datasets Used
- EV sales data (year-wise, vehicle-type-wise)
- State-wise EV adoption data (for geographic segmentation)

#### Key Features:
- Vehicle Type / Category
- State
- Year-wise EV sales (2015–2024)
  
#### Data Sources: 
Kaggle EV datasets and Government-based EV registration data (VAHAN/MoRTH derived)

**link**
- https://drive.google.com/file/d/1pUaj35XKjQ3LFL33bDpLrSkxXUpd9wCD/view?usp=sharing 
- https://drive.google.com/file/d/12OSGo2GAl46JCy2j1mZDFF-Qq7Qr_4sW/view?usp=sharing

## Data Preprocessing
- Converted wide year-wise data into long (tidy) format
- Aggregated EV sales by vehicle type and geography
- Engineered new features:
    - Total Sales
    - Average Annual Sales
    - Growth Rate

## 📈 Exploratory Data Analysis (EDA)
The following analyses and visualizations were performed:
- Market Share (%) by Vehicle Type
- Heatmap (Vehicle Type vs Year) for trend analysis
- State-wise EV adoption by vehicle type (Geographic Segmentation)

These visualizations helped identify demand patterns, stability, and growth behavior across segments.

## 🕒 Time-Series Analysis
- Analyzed EV adoption trends over multiple years
- Identified policy-driven growth phases
- Compared adoption timing across vehicle types
- This analysis is descriptive, not predictive.

## 🤖 Machine Learning Segmentation
Model Used:
- **K-Means Clustering (Unsupervised Learning)**

Features for Clustering:
- Total EV Sales
- Average Annual Sales
- Growth Rate

Outcome:
Vehicle types were grouped into:
- Mature segments
- High-growth segments
- Emerging / niche segments

## 🔍 Key Insights
- EV two-wheelers dominate the market due to affordability and urban usage
- Passenger EVs show strong future growth potential
- Commercial EVs are emerging but infrastructure-dependent
- EV adoption is highly uneven across states

## 💡 Business Recommendations
- Scale production in high-demand vehicle segments
- Invest in R&D for high-growth segments
- Use fleet-based and policy-driven approaches for commercial EVs
- Align product launches with state-level EV policies
  
## 📂 Project Structure

EV-Market-Segmentation/
- `datasets/`
   - `ev_sales_by_makers_and_cat_15-24.csv`
   - `India_vehicle_sales_yearly.xlsx - Sheet1.csv`
- `Market_Segmentation_on_EV.ipynb`
- `visuals/`
  - `market_share.png`
  - `heatmap.png`
  - `clustering.png`
  - `growth_trend.png`
  - `statewise_vehicle_adoption.png`
- `EV Market Segmentation Report.pdf`
- `README.md`

📌 This project demonstrates that the EV market is not uniform and requires vehicle-type-specific and region-specific strategies. Combining data analysis with machine learning enables better decision-making for EV manufacturers and policymakers.
