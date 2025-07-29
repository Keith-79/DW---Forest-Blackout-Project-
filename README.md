# ⚡ Forecast Blackout – Data Warehouse Project

> Predicting power outages in California using weather and outage data.

## 🔧 Tech Stack
- **Airflow** for DAG orchestration (ETL, ELT, Forecast)
- **dbt** for transformations in Snowflake
- **Python** for scripts and forecasting
- **Tableau** for dashboards

## 📁 Project Structure
├── ETL/ # ETL Airflow DAGs

├── ELT/ # ELT DAG + dbt models

├── Forecast/ # Weather forecast DAG

├── Tableau_exports/ # Dashboards and images

├── docker-compose.yaml

📊 Dashboards
See Tableau_exports/ for visual insights (outage trends, forecasts, etc.).

🔍 Features
✅ Airflow DAGs for ETL and forecasting

✅ dbt for Snowflake transformations

✅ Weather API ingestion & 3-day forecasts

✅ Counterfactual explanations

✅ Tableau visualization integration

🌱 Future Improvements

Integrate real-time outage data using webhooks or streaming.

Expand dashboard interactivity with parameterized filters.

Model evaluation metrics integration in dashboard.

📌 Authors
Group 4 – Data Warehouse, Spring 2025

---

👤 **Contributor Note – Keith Gonsalves**

This fork was created to showcase my individual contributions to the Forecast Blackout – Data Warehouse Project.  
I actively contributed to:

- Developing and maintaining ETL pipelines using Apache Airflow  
- Engineering dbt models for Snowflake transformation layers  
- Designing Tableau dashboards to visualize power outage risks and trends  
- Integrating weather forecast APIs and enabling 3-day ahead predictions  
- Collaborating on counterfactual logic for model interpretation

For the original group repository, visit: [puks0618/DW-Project](https://github.com/puks0618/DW-Project)

