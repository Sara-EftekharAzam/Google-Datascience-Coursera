# Automatidata Project Proposal  
**Project Title:** Predicting New York City Taxi Fares Using Regression Models  
**Prepared by:** Sara Eftekhar Azam  
**Date:** November 2025  
**Organization:** Automatidata  
**Project Manager:** Deshawn Washington  

---

## **1. Project Overview**

Automatidata has been contracted by the New York City Taxi and Limousine Commission (TLC) to develop a **predictive regression model** that estimates taxi fares prior to the start of each trip. The model will use trip distance, time of day, and other influential factors (such as pickup location, weather, and passenger count) to predict fare amounts.  

The goal is to **enhance transparency and fairness** in fare estimation for riders and drivers, while providing the TLC with analytical insights into patterns affecting fare variability.

---

## **2. Project Objectives**

- Build a **regression model** capable of predicting taxi fares with high accuracy.  
- Identify and analyze the **key factors** that influence taxi fares in New York City.  
- Develop visualizations to communicate fare trends and model results.  
- Provide **data-driven recommendations** to TLC to support decision-making around fare structure and policy.  
- Ensure all work aligns with the **PACE** data workflow: *Plan, Analyze, Construct, Execute.*

---

## **3. PACE Strategy Alignment**

| Task | PACE Stage | Description |
|------|-------------|-------------|
| Establish structure for project workflow | **Plan** | Define project roles, milestones, deliverables, and communication plan. |
| Write project proposal | **Plan** | Develop this proposal outlining objectives, workflow, and milestones. |
| Compile summary information about the data | **Analyze** | Collect metadata (data size, schema, variable types, missing values). |
| Begin exploring the data | **Analyze** | Conduct exploratory data analysis (EDA) to identify trends and anomalies. |
| Data exploration and cleaning | **Plan**, **Analyze** | Identify and handle missing values, duplicates, outliers, and errors. |
| Compute descriptive statistics | **Analyze** | Summarize data (mean, median, standard deviation, correlations). |
| Visualization building | **Analyze**, **Construct** | Develop graphs to identify trends, correlations, and distributions. |
| Conduct hypothesis testing | **Analyze**, **Construct** | Test relationships (e.g., between distance, time, and fare). |
| Build a regression model | **Analyze**, **Construct** | Train and validate a regression model to predict fares. |
| Evaluate the model | **Execute** | Assess model accuracy using MAE, RMSE, and R² metrics. |
| Build a machine learning model (if applicable) | **Construct** | Compare regression results with machine learning models (e.g., Random Forest). |
| Communicate final insights with stakeholders | **Execute** | Present final report, visualizations, and actionable insights. |

---

## **4. Data Description**

**Data Source:** New York City Taxi & Limousine Commission (TLC) public dataset.  
**Data Content:** Records of taxi trips including:  
- Pickup and drop-off timestamps  
- Trip distance (miles)  
- Pickup and drop-off locations (boroughs, coordinates)  
- Payment type (cash, credit, etc.)  
- Fare amount and surcharges  
- Passenger count  

**Data Volume:** Millions of records collected monthly.  
**Data Quality Considerations:**  
- Potential missing or incorrect entries in trip duration and fare fields  
- Need for filtering extreme outliers (e.g., unrealistic trip distances or fares)  
- Conversion of timestamps into useful features (hour of day, day of week)

---

## **5. Key Questions**

1. What are the most influential variables affecting taxi fares?  
2. How does trip distance and time of day correlate with fare amount?  
3. Can weather or location patterns improve the predictive accuracy?  
4. How can fare estimation improve passenger trust and TLC operations?  

---

## **6. Tools and Technologies**

- **Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)** – data analysis and modeling  
- **Jupyter Notebooks** – exploratory analysis and documentation  
- **SQL / BigQuery** – querying and managing large datasets  
- **Power BI / Tableau** – creating interactive dashboards  
- **GitHub** – version control and team collaboration  

---

## **7. Project Milestones**

| Milestone | Description | Deliverables | Estimated Completion |
|------------|-------------|---------------|-----------------------|
| **1. Planning** | Define objectives, roles, and workflow | PACE strategy document, project proposal | Week 1 |
| **2. Data Acquisition & Exploration** | Gather and inspect TLC dataset | Data summary report, initial EDA notebook | Week 2 |
| **3. Data Cleaning & Preprocessing** | Handle missing data and outliers | Clean dataset, feature engineering report | Week 3 |
| **4. Descriptive Analysis & Visualization** | Summarize and visualize data | EDA report with visualizations | Week 4 |
| **5. Model Development** | Train and validate regression models | Model notebook, metrics summary | Week 5 |
| **6. Evaluation & Optimization** | Test performance and fine-tune | Evaluation report | Week 6 |
| **7. Communication & Delivery** | Present findings and insights | Final presentation, dashboard, report | Week 7 |

---

## **8. Stakeholders and Responsibilities**

| Stakeholder | Role | Responsibilities |
|--------------|------|------------------|
| **Deshawn Washington** | Data Analysis Manager | Oversees project and approves deliverables |
| **Jesse Rivera** | Senior Data Scientist | Guides modeling and validation process |
| **[Your Name]** | Data Analyst | Conducts data exploration, modeling, and reporting |
| **TLC Representatives** | Client Stakeholders | Define requirements, review insights, and approve final outcomes |

---

## **9. Expected Outcomes**

- A **validated regression model** capable of predicting taxi fares before rides.  
- A **dashboard** that visualizes fare patterns across time, geography, and trip characteristics.  
- Actionable insights that help the TLC improve fare transparency and driver efficiency.  
- Recommendations for future data collection and predictive analytics initiatives.  

---

## **10. Evaluation Metrics**

| Metric | Purpose |
|--------|----------|
| **Mean Absolute Error (MAE)** | Measure average prediction error |
| **Root Mean Squared Error (RMSE)** | Penalize larger errors |
| **R² Score** | Assess model explanatory power |
| **Visual Comparison (Actual vs. Predicted)** | Evaluate real-world performance visually |

---

## **11. Communication Plan**

- **Weekly Updates:** Internal progress reports shared with Deshawn and Jesse.  
- **Midpoint Review:** Present preliminary model and findings.  
- **Final Presentation:** Deliver comprehensive results, visualizations, and recommendations to TLC leadership.  

Communication channels include **Slack** for daily coordination, **Google Docs** for document sharing, and **Zoom** for meetings.

---

## **12. Conclusion**

This proposal outlines a complete plan to develop a robust, interpretable regression model for NYC taxi fare prediction. By adhering to the **PACE workflow**, Automatidata will ensure a structured, efficient, and high-quality project execution. The outcome will not only support TLC’s operational goals but also serve as a benchmark for future predictive analytics projects.

