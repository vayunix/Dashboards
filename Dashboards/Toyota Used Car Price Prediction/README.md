# 3) Toyota Used Car Market Trends and Price Prediction using ML

* **objective:** This dashboard provides a machine learning-driven analysis of used Toyota car prices. It compares actual vs. predicted prices, reveals insights based on fuel type, transmission, engine size, and year, and helps understand how these factors influence pricing. The dashboard supports decision-making for dealers, buyers, and data scientists involved in price modeling and vehicle analytics.

* **Power BI dashboard Image:**

![Toyota Used car_page-0001](https://github.com/user-attachments/assets/a077dff4-6787-4e77-a821-b0086a8389ee)

* **View Google colab link here for machine learning model:** https://colab.research.google.com/drive/1VmfshFrq85IC4AbDAkpv3Qq9nwC6tJ0g?usp=sharing

* **Features:**
   
  * **KPI Metrics:**
     * **Total Models:** Displays the total number of unique Toyota car models available for analysis.
     * **Total Fuel Types:** Shows the diversity of fuel types (Petrol, Diesel, Hybrid, etc.) included in the dataset.
     * **Average Price :** Represents the actual average market price across all Toyota used cars.
     * **Average Predicted Price :** Highlights the average price predicted by the Machine Learning model, offering a benchmark for comparison.

   * **Predicted Price by Year (Line Chart):**
      * Shows ML-predicted total price trends from 2014 to 2019.
      * Peak in 2017 ($24.2M) indicates high-value vehicle demand or better pricing models.
      
   * **Price vs Predicted Price by Car Model (Bar Chart):**
      * Compares actual vs. predicted price for top models like Yaris, Aygo, Auris, C-HR, RAV4.
      * Useful for spotting over/underpriced models.

   * **Predicted Price by Fuel Type(Donut Chart):**
      * Displays how predicted prices are distributed across fuel types (Petrol, Hybrid, Diesel).
      * Useful for understanding how fuel preference impacts predicted value.
   
   * **Predicted Price by Transmission Type(Pie Chart):**
      * Shows predicted price contributions by transmission type (Automatic, Manual, Semi-Auto).
      * Highlights the transmission types most associated with higher predicted prices.

   * **Average of Predicted Price by Engine Size (Scatter Plot):**
      * Higher engine sizes generally associate with higher predicted prices.
      * Helps understand pricing tiers based on engine performance.


   * **Filtering Options:**
      * **Fuel Type Filter:** Lets users narrow down analysis based on fuel type.
      * **Transmission Filter:** Allows selection of transmission category for focused insights.

   
   * **Refresh Function:**
      * **Refresh Button:** Updates the dashboard visuals to reflect the latest selections or changes in the data.


* **Usage:**
   * **Price Prediction Validation:**
     * Compare actual prices to ML-predicted prices for each model, identifying potential over- or under-valuations.

   * **Inventory Pricing Strategy:**
     * Helps dealers set competitive pricing based on predicted trends across fuel types, transmission types, and engine size.

   * **Trend Monitoring:**
     * Reveals how predicted prices change over time (by year), aiding in forecasting and resale value estimation.

   * **Model & Feature Impact Analysis:**
     * Understand how different vehicle specs (fuel, transmission, engine size) affect predicted prices.