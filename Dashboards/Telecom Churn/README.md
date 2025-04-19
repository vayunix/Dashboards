# 2) Telecom Churn Analysis using Machine learning model

* **objective:** This Telecom Churn Analysis Dashboard leverages machine learning to predict customer churn and uncover key factors influencing it. Using classification models, it identifies high-risk customers, enabling telecom companies to take proactive retention actions. The dashboard combines data insights and ML predictions in an interactive visual format to support smarter decision-making.

* **Power BI dashboaed Image:**

![Telecom-churn analysis Dashboard_page-0001](https://github.com/user-attachments/assets/2839c7cf-6d10-498e-8ee9-f3ea53ca5784)

* **View Google colab link here for machine learning model:** https://colab.research.google.com/drive/1zgOnC3U_26AbM7MwoZZ7RSQ02V7nm4zA?usp=sharing

* **Features:**
   * **Key Performance Indicators (KPIs):**
      * **Total Customers:** Displays the count of all customers in the dataset.

      * **Churn Count:** Total number of customers who have discontinued services.

      * **Total Revenue:** Aggregated total charges from all customers.

      * **Churn Categories & Reasons:** Summary of categorized churn reasons for strategic analysis.

      * **City and Internet Coverage:** Number of unique cities and internet types in the data.


  * **Churn Reason Breakdown (Table Matrix):**
      * Displays the top 10 reasons customers chose to leave (e.g., network issues, pricing dissatisfaction).

      * Enables strategic focus on the most critical customer pain points.


  * **Churn by Grouped Category (Bar Chart):**
      * Groups churn reasons into broad categories like Price, Competitor, Support, and Internet Issues.

      * Helps in identifying the major business areas affecting customer satisfaction.

  * **Churn by Gender (Donut Chart):**
      * Compares churn rate across genders to uncover potential demographic-specific trends.
      * Supports gender-sensitive customer experience improvements.


  * **Revenue by Internet Type (Pie Chart):**
      * Shows total revenue contribution across DSL, Fiber Optic, and No Internet service types.
      * Aids in understanding which services drive higher revenue and which are underperforming.

  * **Churn by City (Column Chart):**
      * Ranks cities based on customer churn volume.
      * Useful for geographically targeted churn-reduction strategies.

  * **Filtering Options:**
      * **Offer Type Filter:** Drill down based on promotional plans used.
      * **Payment Method Filter:** Filter churn metrics by the customer's preferred payment mode.


  * **Refresh Functionality:**
      *  **Refresh Button:** Instantly updates all visualizations based on the latest filter selections.

* **Power BI Prediction dashboard Image:**

![Telecom-churn analysis Dashboard_page-0002](https://github.com/user-attachments/assets/e13a0586-0f87-4339-b3c9-fb4a8546fc54)

* **Features:**
    * **Confusion Matrix Breakdown (Table + Text Insight):**
      * Displays actual vs predicted churn outcomes by the ML model.
      * **Highlights:**
        * 381 customers correctly predicted as churned.
        * 1,394 customers correctly predicted as not churned.
        * 92.20% accuracy achieved using a 50% prediction threshold.

    * **Churn Probability Distribution (Column Chart):**
      * Shows how many customers fall into each predicted churn probability bin (e.g., 50–59%, 90–100%).

      * Helps identify how confident the model is in its predictions.


    * **Tenure vs Total Charges (Scatter Plot):**
      * Reveals the relationship between how long a customer has stayed and their total billing.
      * Shows a strong positive correlation — longer tenure leads to higher total charges.



 * **Usage:**
    * **Business Stakeholders:**
      * **Understand Why Customers Leave:** Leverage churn reason analytics to make informed business decisions.
      * **Revenue Impact Evaluation:** Identify how churn is affecting the bottom line across different service segments.
      * **Plan Targeted Retention Campaigns:** Use ML-based predictions to target at-risk customers before they churn.


    * **Data Analysts & Scientists:**
      * **Model Evaluation:** Monitor churn predictions and align with business KPIs.
      * **Drill-Down Exploration:** Use filters to segment data and uncover hidden churn trends.
      * **Feature Insights:** Gain understanding of what drives churn using top predictive factors.


    * **Marketing & CX Teams:**
      * **Tailored Messaging:** Understand churn categories to personalize customer communication.
      * **Customer Segmentation:** Segment audience by churn likelihood, region, or demographics for focused campaigns.