# Hi, I'm Dani 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-jane-garcia)  [![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:danij4ne@gmail.com)

---

## About me

---

My name is Dani, a developer based in Barcelona, Spain, building my career in Data Engineering.

I'm passionate about turning raw, messy data into reliable and well-structured data systems. I learn through hands-on, production-oriented projects, focusing not only on making things work, but on making them maintainable, reproducible, and scalable.

I'm constantly learning, building, and pushing myself to become a better engineer.

---



## Projects

---



### 🛍️ [retail-weather-etl](https://github.com/Danij4ne/retail-weather-etl)

---

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)![DuckDB](https://img.shields.io/badge/DuckDB-FFF100?style=flat-square&logo=duckdb&logoColor=black)![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)![Pandera](https://img.shields.io/badge/Pandera-2E8B57?style=flat-square)![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Business:** Retail analytics focused on understanding how weather affects sales by city and product category.

**Architecture:** Local-first ETL with a Medallion architecture (raw → silver → gold), rejected sales for audit, full-refresh processing, and a star schema + analytical mart.

**Analytics:** Units sold, orders, net revenue, average ticket, temperature, precipitation, rain/temp buckets, and price coverage.

**Diagrams:**

<table>
  <tr>
    <td align="center" width="25%">
      <img src="assets/retail-weather-etl/architecture.png" alt="Flow" width="200">
      <br>
      <sub>Flow</sub>
    </td>
    <td align="center" width="25%">
      <img src="assets/retail-weather-etl/data_layers.png" alt="Layers" width="200">
      <br>
      <sub>Layers</sub>
    </td>
    <td align="center" width="25%">
      <img src="assets/retail-weather-etl/local_execution_flow.png" alt="Local" width="200">
      <br>
      <sub>Local</sub>
    </td>
    <td align="center" width="25%">
      <img src="assets/retail-weather-etl/airflow_orchestrated_flow.png" alt="Airflow" width="200">
      <br>
      <sub>Airflow</sub>
    </td>
  </tr>
</table>

---



### 📈 [saas-revenue-elt](https://github.com/Danij4ne/saas-revenue-elt) 

---

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)![DBT](https://img.shields.io/badge/DBT-FF694B?style=flat-square&logo=dbt&logoColor=white)![GCS](https://img.shields.io/badge/GCS-4285F4?style=flat-square&logo=googlecloudstorage&logoColor=white)![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Business:** SaaS subscription revenue analytics focused on revenue movements and customer retention.

**Architecture:** Append-only raw loads; dbt staging views → intermediate tables → analytical marts, with intermediate and marts rebuilt on full refresh.

**Analytics:** MRR, ARR, ARPU, MRR movements, logo churn, monetary churn, and 12-month NRR.

**Diagrams:**

<table>
  <tr>
    <td align="center" width="25%">
      <img src="assets/saas-revenue-elt/data_flow.png" alt="Flow" width="200">
      <br>
      <sub>Flow</sub>
    </td>
    <td align="center" width="25%">
      <img src="assets/saas-revenue-elt/data_layer.png" alt="Layers" width="200">
      <br>
      <sub>Layers</sub>
    </td>
    <td align="center" width="25%">
      <img src="assets/saas-revenue-elt/commit_to_deploy.png" alt="Deploy" width="200">
      <br>
      <sub>Deploy</sub>
    </td>
    <td align="center" width="25%">
      <img src="assets/saas-revenue-elt/gcp_infrastructure.png" alt="Infra" width="200">
      <br>
      <sub>Infra</sub>
    </td>
  </tr>
</table>